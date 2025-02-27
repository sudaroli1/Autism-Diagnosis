# Autism-Diagnosis

Early identification of autism in the younger generation is essential, as it can lead to significant improvements in their overall quality of life. This work focuses specifically on the analysis of stereotypical behaviors through video-based methods, which can provide valuable insights into the characteristics and frequencies of these behaviors.

Currently, many activity recognition tasks rely on supervised learning approaches that necessitate extensive labeled datasets. However, collecting such large volumes of labeled data is often impractical due to the wide variety of stereotypical behaviors associated with autism. This challenge can impede the effectiveness of traditional methods, underscoring the need for alternative strategies.

To address this limitation, we propose a self-supervised learning strategy that utilizes unlabelled video samples of typical behaviors alongside a smaller set of labeled autism videos. This approach features three carefully designed proxy tasks that guide the model in enhancing its learning and recognition capabilities. By employing these proxy tasks, the model can effectively capture patterns and features that indicate both normal and abnormal behaviors.

During the inference phase, the model generates pseudo-labels for the unlabelled samples, facilitating the detection and classification of atypical behaviors or anomalies. This process is crucial for the early identification of potential signs of autism, allowing for timely intervention and support.

Furthermore, our model incorporates a repeated behavior detection proxy, which specifically focuses on recognizing recurring behaviors in video footage. This feature is particularly beneficial, as it enables a more accurate identification of abnormal behaviors that may indicate autism.

Overall, this self-supervised approach not only addresses the challenges stemming from the lack of extensive labeled data but also enhances the model’s ability to distinguish between typical and atypical behaviors in a comprehensive manner.
