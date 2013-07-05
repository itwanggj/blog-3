AUDIO AND VIDEO


The Web is about more than text and information, it is also a medium for expressing artistic creativity, data visualization, and optimizing the presentation of information for different audiences with different needs and expectations. Like graphics, the use of video and audio on Web sites enhances the experience for users, and W3C has several different and complementary technologies that work together with HTML, SVG and scripting to provide the creators of Web pages and Web Applications with the tools they need to deliver the best possible representation of their content.

current status：
+ SMIL
+ Media Access
+ Timed Text
+ SVG
+ HTML
+ Web Real Time Communication
+ Audio
+ Web and TV

What are Audio and Video?

The terms audio and video commonly refers to the time-based media storage format for sound/music and moving pictures information. Audio and video digital recording, also referred as audio and video codecs, can be uncompressed, lossless compressed, or lossy compressed depending on the desired quality and use cases.

Audio codecs can usually contain one audio channel (mono), two audio channels (stereo), or more channels (e.g. "5.1" surround). For example, human voice is recorded using one channel while music uses in general two or more channels. The quality will vary depending on the bitrate, ie the number of bits used per unit of playback time.

Video codecs will contain a sequence of frames, ie still pictures and, for compressed formats, movements between those pictures. Quality will vary depending on the number of frames per second, color space, resolution, etc.

Media storage formats will contain audio codec streams, video codec streams, captions, and meta information. It combine them to provide the audio or the video, with alternative or enhanced materials. In general a video will have one video codec stream, one or more alternative audio codec streams, and may have captions and meta information.

What is Audio and Video Used For?

Audio and video are used for enhancing the experience with Web pages (e.g. audio background) to serving music, family videos, presentations, etc. The Web content accessibility guidelines recommend to always provide alternatives for time-based media, such as captions, descriptions, or sign language.

What is SMIL?

SMIL is the Synchronized Multimedia Integration Language, an XML-based language for describing interactive multimedia presentations. It combines audio, video, hypertext, images in time and space, allowing visual transitions in between.

What is Timed Text?

Timed Text is an XML-based language to timed text media for the purpose of interchange among authoring systems. It may also be used directly as a distribution format, thus suitable for captioning or video description.

What are Media Fragments?

Media fragments provide for a media-format independent, standard means of addressing media fragments, in time and space, on the Web using identifiers (URL, URI, IRI).

What are Media Annotations?

Media annotations provide ways to describe media resources, using a common set of properties. Those annotations help convey information that can then be reused in search engines or tagging systems.

Examples

Here are some examples of SMIL, SVG, and HTML respectively with video content:

	<smil xmlns="http://www.w3.org/ns/SMIL">
		<body>
			<par>
				<video src="http://www.example.org/MyVideo" fill="freeze"/>
				<text src="http://www.example.org/MyCaption" fill="freeze" />
			</par>   
		</body>
	</smil>

	<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
		<g>
			<video xlink:href="http://www.example.org/MyVideo" x="0" y="0" width="360" height="240" />
		</g>
	</svg>

	<!DOCTYPE html>
	<html>
		<head>
			<title>My Video</title>
		</head>
		<body>   
			<video src="http://www.example.org/MyVideo" width="360" height="240">
		</body>   
	</html>

Learn More

...Explanation...