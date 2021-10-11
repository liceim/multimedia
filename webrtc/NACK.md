NACK (Negative Acknowledgement)

NACK stands for Negative Acknowledgement. It is one of the error resiliency mechanisms in WebRTC.

NACK is a way for the receiving end to indicate it hasn’t received a specific packet.

A NACK message is sent over RTCP to the sender of the media, which in turn needs to decide if it will retransmit the lost packet based on its availability in its cache and its estimate to the usefulness of the retransmission (will it be possible to use it once received).

https://webrtcglossary.com/nack/
