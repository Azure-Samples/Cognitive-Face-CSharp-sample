## Microsoft Cognitive Services - Face Service Tutorial Sample Changelog

# 1.0.2 (2018-07-02)

*Features*

* Updated to target [Microsoft.Azure.CognitiveServices.Vision.Face 1.0.2-preview](https://www.nuget.org/packages/Microsoft.Azure.CognitiveServices.Vision.Face/1.0.2-preview) client library.

*Bug Fixes*

* none

*Breaking Changes*

* IFaceServiceClient -> IFaceAPI
* Face[] -> IList&lt;DetectedFace&gt;
* IEnumerable&lt;FaceAttributeType&gt; -> IList&lt;FaceAttributeType&gt;
* IFaceServiceClient.DetectAsync -> IFaceAPI.DetectWithStreamAsync
* FaceAPIException -> APIErrorException
* EmotionScores -> Emotion
* HairColor[] -> IList&lt;HairColor&gt;

<a name="x.y.z"></a>
# 1.3.0 (2018-07-01)

*Features*

* Port of sample code from [Getting Started with Face API in C# Tutorial](https://docs.microsoft.com/en-us/azure/cognitive-services/face/tutorials/faceapiincsharptutorial#fullsource).
* Targets [Microsoft.ProjectOxford.Face 1.3.0](https://www.nuget.org/packages/Microsoft.ProjectOxford.Face/) client library (works with v1.4.0).

*Bug Fixes*

* Set `resizeFactor` to 1 for images that don't contain `dpi` info.
