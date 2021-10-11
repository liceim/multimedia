REMB (Receiver Estimated Maximum Bitrate)

REMB stands for Receiver Estimated Maximum Bitrate. It is a RTCP message used to provide bandwidth estimation in order to avoid creating congestion in the network.

This RTCP message includes a field to convey the total estimated available bitrate on the path to the receiving side of this RTP session (in mantissa + exponent format). Even if it is defined as the total available bitrate, the sender typically uses it to configure the maximum bitrate of the video encoding.

In addition to be used from an endpoint to notify the available bandwidth in the network, it has also been used by media servers to limit the amount of bitrate the sender is allowed to send.

To provide a better estimation, REMB is usually used in combination with the abs-send-time header extension because providing accurate timing information is critical for the accuracy of the REMB value calculation.

This RTCP message defined in draft-alvestrand-rmcat-remb-03 was never fully standardized but is supported by all the WebRTC browser implementations, although in case of Chrome it is deprecated in favor of the new sender side bandwidth estimation based on RTCP Transport Feedback messages. The support for this message is negotiated in the Offer/Answer SDP Exchange.

Tags:Network


https://webrtcglossary.com/remb/
