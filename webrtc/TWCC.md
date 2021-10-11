TWCC (Transport Wide Congestion Control)

Also known as transport-cc.

TWCC stands for Transport Wide Congestion Control. It is used as a sender-side bandwidth estimation technique in WebRTC.

TWCC is operated under the following concept:

Receiver of the media calculates the intra-packet delays and reports it back to the sender of the media
The sender then calculates the estimated bitrate based on that information
TWCC is considered a better algorithm for bandwidth estimation by many, and is also the algorithm that Google is focusing and investing in more time and effort. The main reason for this is that the actual estimation implementation is reliant on only the sender, and in media servers such as an SFU that means better control over the algorithm.

The draft for TWCC implementation can be found in draft-holmer-rmcat-transport-wide-cc-extensions-01. The support for TWCC is negotiated in the Offer/Answer SDP Exchange.

https://webrtcglossary.com/transport-cc/
