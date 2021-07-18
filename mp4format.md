mp4或称MPEG-4 Part 14，是一种多媒体容器格式，扩展名为.mp4.

MP4文件由许多box组成，每个box包含不同的信息， 这些box以树形结构的方式组织。以下是主要box的简要说明：
https://upload-images.jianshu.io/upload_images/8744338-ba0b0b5e95c10e7b.png

根节点之下，主要包含三个节点：ftyp、moov、mdat。
ftyp：文件类型。描述遵从的规范的版本。
moov box：媒体的metadata信息。
mdat：具体的媒体数据。
说明：在 mp4 中默认写入字节序是 Big-Endian的。

