<?xml version="1.0" encoding="utf-8" ?>
<!-- Copyright (C) 2014 The CyanogenMod Project
     Licensed under the Apache License, Version 2.0 (the "License");
     you may not use this file except in compliance with the License.
     You may obtain a copy of the License at
          http://www.apache.org/licenses/LICENSE-2.0
     Unless required by applicable law or agreed to in writing, software
     distributed under the License is distributed on an "AS IS" BASIS,
     WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
     See the License for the specific language governing permissions and
     limitations under the License.
-->

<Included>
    <Decoders>

        <!--  ffmpeg audio codecs -->
        <MediaCodec name="OMX.ffmpeg.aac.decoder"    type="audio/mp4a-latm" />
        <MediaCodec name="OMX.ffmpeg.wma.decoder"    type="audio/x-ms-wma" />
        <MediaCodec name="OMX.ffmpeg.ra.decoder"     type="audio/vnd.rn-realaudio" />
        <MediaCodec name="OMX.ffmpeg.flac.decoder"   type="audio/flac" />
        <MediaCodec name="OMX.ffmpeg.mp2.decoder"    type="audio/mpeg-L2" />
        <MediaCodec name="OMX.ffmpeg.ac3.decoder"    type="audio/ac3" />
        <MediaCodec name="OMX.ffmpeg.ape.decoder"    type="audio/x-ape" />
        <MediaCodec name="OMX.ffmpeg.dts.decoder"    type="audio/vnd.dts" />
        <MediaCodec name="OMX.ffmpeg.atrial.decoder" type="audio/ffmpeg" />

        <!--  ffmpeg video codecs -->
        <MediaCodec name="OMX.ffmpeg.mpeg2.decoder"  type="video/mpeg2"/>
        <MediaCodec name="OMX.ffmpeg.wmv.decoder"    type="video/x-ms-wmv"/>
        <MediaCodec name="OMX.ffmpeg.rv.decoder"     type="video/vnd.rn-realvideo"/>
        <MediaCodec name="OMX.ffmpeg.flv1.decoder"   type="video/x-flv"/>
        <MediaCodec name="OMX.ffmpeg.vtrial.decoder" type="video/ffmpeg" />
    </Decoders>
</Included>
