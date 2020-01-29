# Offensive-Responses-Dataset 
offensive responses from chinese chat records 
### Statistical characteristics of the offensive response dataset: 
<img src="images/Capture.PNG" width = "330" height = "200" div align=center />
(a) The number of positive and negative samples in the dataset.
<br /><br /><br />
<img src="images/Capture2.PNG" width = "330" height = "200" div align=center />
(b) The proportions of three categories of offensive responses.
<br /><br /><br />



If a response is offensive, then it is further annotated according to the following categories of offensive responses:
**Offensive words:** There are explicit profane words in the response sentence. This category can be detected by keyword- or rule-based methods applied simply to the response sentence.
<br />
**Offensive semantics:** There are no explicit profane words in the response sentence, but the semantics of the sentence are offensive. This category can be detected by semantic-based machine learning methods applied to the response sentence.
<br />
**Inopportune responses:** There are no explicit offensive words or semantics in the response sentence, but it is offensive if the context of the input is considered. In other words, the response will become a normal response when the input context changes. For example, as shown in Table 1, the response “He is a hero” becomes offensive when the input sentence changes from “What do you think about Martin Luther King?” to “What do you think of Hitler?”.
<br />

<img src="images/Capture4.PNG" width = "380" height = "230" div align=center />
<br />

<img src="images/Capture3.PNG" width = "380" height = "230" div align=center />
<br />


