# MedVidClassification
This task was a part of the [Shared Task on Medical Video Question Answering](https://medvidqa.github.io/).

Consider a medical question, “How to place a tourniquet in case of fingertip avulsions? ”, the textual answer to this question will be hard to understand and act upon without visual aid. In order to provide visual aid, first, we need to identify the relevant video, which is medical and instructional in nature. Once we find a relevant video, it is often the case that the entire video can not be considered as the answer to the given question. Instead, we want to refer to a particular temporal segment, or moment, from the video, where the answer is being shown or the explanation is illustrated in the video. We believe medical videos may provide the best possible answers to many first aid, medical emergency, and medical education questions.


      [![IMAGE](https://img.youtube.com/vi/OaSovqEimyA/0.jpg)]("https://www.youtube.com/embed/OaSovqEimyA" image)



<table style="width:100%">
<thead>
  <tr>
    <th> 

</th>
    <th>
      [![IMAGE](https://img.youtube.com/vi/YqHv_8rKkeE/0.jpg)]("https://www.youtube.com/embed/YqHv_8rKkeE")
    </th>
    <th>
     [![IMAGE](https://img.youtube.com/vi/hE63VMlLyB8/0.jpg)]("https://www.youtube.com/embed/hE63VMlLyB8")
    </th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="text-align:center;"><strong>Medical Instructional</strong></td>
    <td style="text-align:center;"><strong>Medical Non-Instructional</strong></td>
    <td style="text-align:center;"><strong>Non-medical</strong></td>
  </tr>
</tbody>
</table>

## Categories
- <b>Medical Instructional</b>: An instructional medical video for non-professionals should clearly demonstrate a medical procedure providing enough details to reproduce the procedure and achieve the desired results without prior training. The accompanying narrative should be to the point and should clearly describe the steps in the visual content. Suppose a valid medical or health-related question is aligned with an instructional medical video. In that case, it should explain/answer the medical question with a demonstration or should be a tutorial/educational video where someone (e.g., a doctor or a medical professional) demonstrates a procedure related to the medical question or should be a how-to video about the medical or health-related question.

- <b>Medical Non-instructional</b>: A medical video on a discussion of medical-related topics without any visual answer to any medical or health-related question.

- <b>Non-medical</b>: A video can be categorized as non-medical if the video is neither medical instructional nor medical non-instructional.
       
