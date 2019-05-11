# AI Based Super Resolution

Image super-resolution (SR) is a computer vision task in-
volving reconstruction of high-resolution (HR) images given
a low-resolution (LR) image as input. It is highly challenging
and has many practical applications, such as medical image

processing [22], satellite imaging [6], facial image enhance-
ment [17], [18] and compressed image improvement [16].

Over the past decade, many SR techniques have been
developed using deep learning. Among those, generative

adversarial networks (GAN) [4] and very deep convolu-
tional networks (VDSR) [7] have shown promising results

in terms of HR image quality and computational speed. In
this paper, we propose two approaches based on these two
algorithms: VDSR-ResNeXt, which is a deep multi-branch
convolutional network inspired by VDSR and ResNeXt; and
SRCGAN, which is a conditional GAN that explicitly passes
class labels as input to the GAN. The two methods were
implemented on common SR benchmark datasets for both
quantitative and qualitative assessment.</p>