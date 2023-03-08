<h1> Text Recognition App </h1>

<p> The ML Kit Text Recognition API can recognize text in any Latin-based character set. It can also be used to automate data-entry tasks such as processing credit cards, receipts, and business cards. </p>

<h2> Key capabilities </h2>
<ul>
<li>Recognize text across Latin-based languages Supports recognizing text using Latin script</li>
<li>Analyze structure of text Supports detection of words/elements, lines and paragraphs</li>
<li>Identify language of text Identifies the language of the recognized text</li>
<li>Small application footprint On Android, the API is offered as an unbundled library through Google Play Services</li>
<li>Real-time recognition Can recognize text in real-time on a wide range of devices</li>
</ul>

<h2> Text structure </h2>
<p>The Text Recognizer segments text into blocks, lines, elements and symbols. Roughly speaking:</p>
<ul>
<li>a Block is a contiguous set of text lines, such as a paragraph or column</li>
<li>a Line is a contiguous set of words on the same axis, and</li>
<li>an Element is a contiguous set of alphanumeric characters ("word") on the same axis in most Latin languages, or a word in others</li>
<li>an Symbol is a single alphanumeric character on the same axis in most Latin languages, or a character in others</li>
</ul>

<p> The image below highlights examples of each of these in descending order. The first highlighted block, in cyan, is a Block of text. The second set of highlighted blocks, in blue, are Lines of text. Finally, the third set of highlighted blocks, in dark blue, are Words. </p>

<img src="https://developers.google.com/static/ml-kit/vision/text-recognition/images/text-structure.png">

<p> For all detected blocks, lines, elements and symbols, the API returns the bounding boxes, corner points, rotation information, confidence score, recognized languages and recognized text. </p>

<h2> Text Recognition App Preview </h2>

App        |  Main Screen
:-------------------------:|:-------------------------:
![](https://github.com/icanerdogan/TextRecognitionApp-MLKit/blob/master/documents/TextRecognition.gif?raw=true)  |  ![](https://raw.githubusercontent.com/icanerdogan/TextRecognitionApp-MLKit/master/documents/MainActivity.png)
