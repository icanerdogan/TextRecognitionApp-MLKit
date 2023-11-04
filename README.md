<h1> Text Recognition App </h1>

<p>Unleash the power of text within images like never before with [Your App Name], the ultimate Image Text Analyzer and Copy Tool! Say goodbye to manual typing and tedious data entry—our advanced AI-driven technology transforms any photo into editable and copyable text with just a tap. Whether it's a snapshot from your camera or an image from your gallery, our app makes digitizing text a breeze! </p>

<a href="https://play.google.com/store/apps/details?id=com.ibrahimcanerdogan.textrecognitionapp"><img width="90" height="90" src="https://img.icons8.com/?size=512&id=L1ws9zn2uD01&format=png"/></a>

<h4><a href="https://medium.com/@ibrahimcanerdogan/text-recognition-app-with-mlkit-android-7d0b29f522cd" target="_blank"> MEDIUM </a></h4>

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

<h2> LICENSE </h2>

````
MIT License

Copyright (c) 2023 İbrahim Can Erdoğan

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
