# X-Modalities-Fusion-using-Contrastive-Learning-for-Image-Retrieval
Source Code of X-Modalities Fusion using Contrastive Learning for Image Retrieval Framework
Image search with requisite modification through text holds promise for daily uses, including online shopping and surfing on the internet. The objective is to use a query image and text to find images that not only match the query image but also include specified modifications as described in the text input. This presents two key challenges. Firstly, the challenge lies in the misalignment between two completely different modalities i.e vision and text. Secondly, there is a need to make targeted modifications to specific attributes of the query image in accordance with textual descriptions. These challenges are notably intricate as they require a collaborative comprehension of both image and text modalities. This paper introduces a two-stage framework that utilizes features extracted by Constrastive Language-Image Pre-trained (CLIP) model. Initially, CLIP encoders are aligned by combining visual and textual features through element-wise summation. Subsequently, relational network is trained sequentially aimed to seamlessly combined features from both modalities. Thereby integrating bimodal information and generating unified features. These jointly learned features are then utilized for retrieval purposes. Contrastive learning is employed consistently in the training of both stages. The suggested framework is evaluated using two real-world fashion domain datasets namely Fashion-200K and Fashion-IQ. Accordingly, results showed that it performed better than baseline frameworks used for comparative analysis.
