Welcome to **FRCSyn**, the **Face Recognition Challenge in the Era of Synthetic Data** organized at **WACV 2024**. 

<p align="center"><img src="https://wacv2024.thecvf.com/wp-content/uploads/2023/04/WACV-Logo_2024-1024x263.png" style="width:35%;height:auto;"></p>

<p align="center"><img src="/assets/images/intraclass.jpg" style="width:75%;height:auto;"></p>

To promote and advance the use of synthetic data for face recognition, we organize the **Face Recognition Challenge in the Era of Synthetic Data (FRCSyn)**. This challenge intends to **explore the application of synthetic data to the field of face recognition** in order to find solutions to the current limitations existed in the technology, for example, in terms of **privacy concerns** associated with real data, **bias in demographic groups** (e.g., ethnicity and gender), and **lack of performance in challenging conditions** such as large age gaps between enrolment and testing, pose variations, occlusions etc.

This challenge intends to provide an in-depth analysis of the following research questions:

- What are the limits of face recognition technology trained only with synthetic data?
- Can the use of synthetic data be beneficial to reduce the current limitations existed in face recognition technology?

FRCSyn challenge will analyze **improvements achieved using synthetic data** and the state-of-the-art face recognition technology in **realistic scenarios**, providing valuable contributions to advance the field.

### Tasks

**The FRCSyn challenge focuses on the two following challenges** existed in
current face recognition technology:

- **Task 1**: synthetic data for **demographic bias mitigation**.
- **Task 2**: synthetic data for **overall performance improvement** (e.g., age, pose, expression, occlusion, demographic groups, etc.).
  
**Within each task, there are two sub-tasks that propose alternative approaches for
training face recognition technology**: one exclusively with synthetic data and the other with a possible combination of real and synthetic data.

### Synthetic Datasets

In the FRCSyn Challenge, **we will provide participants with our synthetic datasets after registration in the challenge**. They are based on our two recent approaches:

**DCFace**: a novel framework entirely based on Diffusion models, composed of i) a sampling stage for the generation of synthetic identities X<sub>ID</sub>, and ii) a mixing stage for the generation of images X<sub>ID,sty</sub> with the same identities X<sub>ID</sub> from the sampling stage and the style selected from a “style bank” of images <sub>Xsty</sub>. 

[Reference](https://openaccess.thecvf.com/content/CVPR2023/html/Kim_DCFace_Synthetic_Face_Generation_With_Dual_Condition_Diffusion_Model_CVPR_2023_paper.html) M. Kim, F. Liu, A. Jain and X. Liu, “DCFace: Synthetic Face Generation with Dual Condition Diffusion Model”, in *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition*, 2023. 

**GANDiffFace**: a novel framework based on GANs and Diffusion models that provides fully-synthetic face recognition datasets with the desired properties of human face realism, controllable demographic distributions, and realistic intra-class variations. **Best Paper Award at AMFG @ ICCV 2023.**

[Reference](https://arxiv.org/abs/2305.19962) P. Melzi, C. Rathgeb, R. Tolosana, R. Vera-Rodriguez, D. Lawatsch, F. Domin, M. Schaubert, “GANDiffFace: Controllable Generation of Synthetic Datasets for Face Recognition with Realistic Variations”, in *Proceedings of the IEEE/CVF International Conference on Computer Vision Workshops*, 2023. 

### Registration

**The platform used in FRCSyn Challenge is CodaLab. Participants need to register to take part in the challenge**. Please, follow the instructions:

1. Fill up [this form](https://docs.google.com/forms/d/e/1FAIpQLSf8U80MRf5gk5c0QbGxF76TshaxmThVymeHWXUocSyXRkSiMA/viewform?usp=pp_url) including your information.
2. Sign up in [CodaLab](https://codalab.lisn.upsaclay.fr/competitions/15485) using **the same email** introduced in step 1).
3. Join in [CodaLab](https://codalab.lisn.upsaclay.fr/competitions/15485) the [FRCSyn Challenge](https://frcsyn.github.io/). Just click in the "Participate" tab for the registration.
4. We will give you access once we check everything is correct.
5. You will receive an email with all the instructions to kickstart FRCSyn, including links to download datasets, experimental protocol, and an example of submission file.

### Paper

The **best teams** of each sub-task will be invited to **contribute as co-authors in the summary paper of the FRCSyn challenge**. This paper will be **published in the proceedings of the WACV 2024 conference**. In addition, **top performers will be invited to present their methods at the workshop. This presentation can be virtual**.

### News

- **10 Oct 2023** Deadline extended to 30 October
- **13 Sep 2023** FRCSyn Challenge starts
- **10 Sep 2023** Website is live!

### Important Dates

- **13 Sep 2023** FRCSyn starts
- **30 Oct 2023** FRCSyn ends
- **2 Nov 2023** Announcement of winning teams
- **19 Nov 2023** Paper submission with results of the challenge 

### Schedule

TBD

### Keynote Speakers

TBD

### Organizers

<table>
  <tr>
    <td width="33%">
      <div>
        <p align="center"><img src="/assets/images/Melzi.jpg" style="width:70%;height:auto;"></p>
        <p align="center"><a href="https://scholar.google.com/citations?user=iGAKK84AAAAJ&hl=it&oi=ao">Pietro Melzi</a></p>
        <p align="center">Universidad Autonoma de Madrid, Spain</p>
      </div>
    </td>
    <td width="33%">
      <div>
        <p align="center"><img src="/assets/images/Kim.jpg" style="width:70%;height:auto;"></p>
        <p align="center"><a href="https://mckim.dev/">Minchul Kim</a></p>
        <p align="center">Michigan State University, US</p>
      </div>
    </td>
    <td width="33%">
      <div>
        <p align="center"><img src="/assets/images/Tolosana.jpg" style="width:70%;height:auto;"></p>
        <p align="center"><a href="https://rubentolosana.github.io/">Ruben Tolosana</a></p>
        <p align="center">Universidad Autonoma de Madrid, Spain</p>
      </div>
    </td>
  </tr>

  <tr>
    <td>
      <div>
        <p align="center"><img src="/assets/images/Rathgeb.jpg" style="width:70%;height:auto;"></p>
        <p align="center"><a href="https://scholar.google.com/citations?user=_itMaUcAAAAJ&hl=it&oi=ao">Christian Rathgeb</a></p>
        <p align="center">Hochschule Darmstadt, Germany</p>
      </div>
    </td>
    <td>
      <div>
        <p align="center"><img src="/assets/images/Vera.jpg" style="width:70%;height:auto;"></p>
        <p align="center"><a href="https://scholar.google.com/citations?user=KYMQ0tsAAAAJ&hl=it&oi=ao">Ruben Vera-Rodriguez</a></p>
        <p align="center">Universidad Autonoma de Madrid, Spain</p>
      </div>
    </td>
    <td>
      <div>
        <p align="center"><img src="/assets/images/Morales.jpg" style="width:70%;height:auto;"></p>
        <p align="center"><a href="https://aythami.me/">Aythami Morales</a></p>
        <p align="center">Universidad Autonoma de Madrid, Spain</p>
      </div>
    </td>
  </tr>

  <tr>
    <td>
      <div>
        <p align="center"><img src="/assets/images/Liu.jpg" style="width:70%;height:auto;"></p>
        <p align="center"><a href="https://www.cse.msu.edu/~liuxm/index2.html">Xiaoming Liu</a></p>
        <p align="center">Michigan State University, US</p>
      </div>
    </td>
    <td>
      <div>
        <p align="center"><img src="/assets/images/Fierrez.jpg" style="width:70%;height:auto;"></p>
        <p align="center"><a href="http://biometrics.eps.uam.es/fierrez/index.php">Julian Fierrez</a></p>
        <p align="center">Universidad Autonoma de Madrid, Spain</p>
      </div>
    </td>
    <td>
      <div>
        <p align="center"><img src="/assets/images/Ortega.png" style="width:70%;height:auto;"></p>
        <p align="center"><a href="https://scholar.google.com/citations?user=LwiecBYAAAAJ&hl=en">Javier Ortega-Garcia</a></p>
        <p align="center">Universidad Autonoma de Madrid, Spain</p>
      </div>
    </td>
  </tr>
</table>

### Fundings

<table>
  <tr>
    <td width="50%">
      <div>
        <p align="center"><img src="/assets/images/comunidad.png" style="width:70%;height:auto;"></p>
      </div>
    </td>
    <td width="50%">
      <div>
        <p align="center"><img src="/assets/images/gobierno.png" style="width:70%;height:auto;"></p>
      </div>
    </td>
  </tr>

  <tr>
    <td width="50%">
      <div>
        <p align="center"><img src="/assets/images/european.png" style="width:70%;height:auto;"></p>
      </div>
    </td>
    <td width="50%">
      <div>
        <p align="center"><img src="/assets/images/trespass.png" style="width:70%;height:auto;"></p>
      </div>
    </td>
  </tr>

</table>
