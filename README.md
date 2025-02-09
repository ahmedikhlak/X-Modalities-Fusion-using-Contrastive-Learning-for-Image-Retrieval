Image search with desired modification through text query holds promise for daily
uses, including online shopping and surfing on the internet. The goal is to utilize set
of integrated features of both the visual and corresponding textual query to retrieve
images that align with the original image while incorporating the modifications detailed
in the provided text description. This presents three key challenges. Firstly, the chal-
lenge lies in itself i.e; the misalignment between two completely different modalities of
vision and text. Secondly, there is a need to make targeted modifications to specific
attributes of the query image in accordance with textual descriptions. Another chal-
lenge arises when absence of contextual understanding is faced due in-appropriate
structure or conceptual understanding of textual query. These challenges are notably
intricate as they require a collaborative comprehension of both image and text modal-
ities. This paper introduces a two stage framework that utilizes features extracted by
Constrastive Language-Image Pre-trained (CLIP) model. Initially, CLIP encoders are
aligned by combining visual and textual features through element-wise summation.
The contextual understanding of the query is supplemented by introducing a Knowl-
edge Embedded stream (KES) in the proposed framework. KES is utilized to integrate
concepts into the textual query by leveraging the global features of the reference im-
age. Subsequently, relational network is trained sequentially aimed to seamlessly
combine features from both modalities. Thereby integrating bimodal information and
generating unified features. These jointly learned features are then utilized for retrieval
purposes. Contrastive learning is employed consistently in the training of both stages.
The proposed framework has been evaluated using two real-world fashion domain
datasets, Fashion-200K and Fashion-IQ, as well as the CIRR dataset, which consists
of real-life images. Accordingly, results showed that it performed better than baseline
frameworks used for comparative analysis.
