# <p> CLESSR-VC: Contrastive Learning Enhanced Self-Supervised Representation for One-shot Voice Conversion

# ABSTRACT
<p align="justify"> One-shot voice conversion (VC) is getting more and more attention because it is closer to practical applications. This paper proposes a CLESSR-VC model, which enhances pre-trained self-supervised representations through contrastive learning for one-shot VC. First, SSL features from the 23rd layer of the pre-trained WavLM are adopted as the input to the content encoder. Then, contrastive learning combined with the pitch-shifting-based augmentation method is applied to disentangle content information from SSL features. Second, SSL features from the 9th layer of the pre-trained WavLM and mel-spectrograms are adopted to extract SSL speaker embedding and mel speaker embedding, respectively. Then, AM-Softmax and cross-architecture contrastive learning are applied to obtain the fused speaker embedding that helps improve speech quality and speaker similarity. Both objective and subjective evaluation results confirm that the proposed VC model has outstanding performance and few trainable parameters.</p>

The following is the overall model architecture.
<div align="center">
  <img src="images/CLESSR-VC.jpg" width="80%">
  <p>Fig.1: The overall architecture of the proposed model.</p>
</div>

# DEMO
For the converted samples, you can visit [the demo page](https://superman-valencia.github.io/CLESSR-VC-Demo/).