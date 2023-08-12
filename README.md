
**This is the official Pytorch implemenation of "Invariant Training on Joint Hard samples for Few-shot 3D Shape Recognition".**


We tackle the data scarcity challenge in few-shot point cloud recognition of 3D objects by using a joint prediction
from a conventional 3D model and a well-trained 2D model. Surprisingly, such an ensemble, though seems trivial, has
hardly been shown effective in recent 2D-3D models. We find out the crux is the less effective training for the “joint
hard samples”, which have high confidence prediction on different wrong labels, implying that the 2D and 3D models
do not collaborate well. To this end, our proposed invariant training strategy, called INVJOINT, does not only emphasize the training more on the hard samples, but also seeks
the invariance between the conflicting 2D and 3D ambiguous predictions. INVJOINT can learn more collaborative 2D and 3D representations for better ensemble. Extensive
experiments on 3D shape classification with widely adopted ModelNet10/40, ScanObjectNN and Toys4K, and shape retrieval with ShapeNet-Core validate the superiority of our INVJOINT.

<div align="center">
  <img src="figure1.png">
</div>




*I've recently been busy preparing my submissions for ICLR as well as expanding the paper's content ( point cloud detection and part segementation; pretraining for zero-shot ) for journal publication.* 

The arxiv version of this paper will be available in August. The code will be open-sourced later this year. 

If you are interested in invariant training or pretrained model ensembling, please feel free to contact me (*xuanyucver@gmail.com*)




