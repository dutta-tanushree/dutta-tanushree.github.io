##  Publications and Preprints
### 2024

#### [CLR-Face: Conditional Latent Refinement for Blind Face Restoration Using Score-Based Diffusion Models (IJCAI24)](https://arxiv.org/pdf/2402.06106.pdf)

**Maitreya Suin** and Rama Chellappa.

<table>
<colgroup>
<col width="25%" />
<col width="85%" />
</colgroup>
<tbody>
<tr>
<td markdown="span"><img src="https://github.com/maitreyasuin/maitreyasuin.github.io/blob/master/images/ijcai.png?raw=true" width="182" height="102"></td>
<td markdown="span"> Generating fine-grained facial details faithful to inputs remains a challenging problem. Most existing methods produce either overly smooth outputs or alter the identity as they attempt to balance between generation and reconstruction. This may be attributed to the typical trade-off between quality and resolution in the latent space. We introduce a diffusion-based-prior inside a VQGAN architecture that focuses on learning the distribution over uncorrupted latent embeddings. We iteratively recover the clean embedding conditioning on the degraded counterpart. To ensure the reverse diffusion trajectory does not deviate from the underlying identity, we train a separate Identity Recovery Network and use its output to constrain the diffusion process. </td>
</tr>
</tbody>
</table>
