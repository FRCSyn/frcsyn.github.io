Welcome to **[FRCSyn](https://codalab.lisn.upsaclay.fr/competitions/15485)**, the **Face Recognition Challenge in the Era of Synthetic Data** organized at **WACV 2024**. 

**The summary paper of the FRCSyn Challenge is available [here](https://arxiv.org/abs/2311.10476).**

<p align="center"><img src="https://wacv2024.thecvf.com/wp-content/uploads/2023/09/WACV-Logo_2024-1024x243.png" style="width:35%;height:auto;"></p>

<p align="center"><img src="/assets/images/intraclass.jpg" style="width:75%;height:auto;"></p>

To promote and advance the use of synthetic data for face recognition, we organize the **Face Recognition Challenge in the Era of Synthetic Data (FRCSyn)**. This challenge intends to **explore the application of synthetic data to the field of face recognition** in order to find solutions to the current limitations existed in the technology, for example, in terms of **privacy concerns** associated with real data, **bias in demographic groups** (e.g., ethnicity and gender), and **lack of performance in challenging conditions** such as large age gaps between enrolment and testing, pose variations, occlusions etc.

This challenge intends to provide an in-depth analysis of the following research questions:

- What are the limits of face recognition technology trained only with synthetic data?
- Can the use of synthetic data be beneficial to reduce the current limitations existed in face recognition technology?

FRCSyn challenge will analyze **improvements achieved using synthetic data** and the state-of-the-art face recognition technology in **realistic scenarios**, providing valuable contributions to advance the field.

### News

- **30 Nov 2023** <a href="#schedule">Schedule for the Workshop is available</a>  
- **20 Nov 2023** [Summary paper available on arxiv](https://arxiv.org/abs/2311.10476)
- **30 Oct 2023** FRCSyn Challenge ends
- **10 Oct 2023** Deadline extended to 30 October
- **13 Sep 2023** FRCSyn Challenge starts
- **10 Sep 2023** Website is live!

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

### Important Dates

- **13 Sep 2023** FRCSyn starts
- **30 Oct 2023** FRCSyn ends
- **2 Nov 2023** Announcement of winning teams
- **19 Nov 2023** Paper submission with results of the challenge
- **8 Jan 2024** FRCSyn Workshop at WACV 2024

### FRCSyn at WACV 2024: Results

To determine the winners of sub-tasks 1.1 and 1.2 we consider Trade-off Accuracy, defined as the difference between the average and standard deviation of accuracy across demographic groups. To determine the winners of sub-tasks 2.1 and 2.2 we consider the average of verification accuracy across datasets.

<p align="center"><strong>Task 1.1 - synthetic data for bias mitigation</strong>strong></p>
<table>
<thead>
  <tr>
    <th rowspan="2">#</th>
    <th rowspan="2">User</th>
    <th rowspan="2">Entries</th>
    <th rowspan="2">Date of Last Entry</th>
    <th rowspan="2">Team Name</th>
    <th rowspan="2">Trade-off Accuracy (AVG - STD) [%] </th>
    <th rowspan="2">AVG Accuracy [%] </th>
    <th rowspan="2">STD Accuracy [%] </th>
    <th rowspan="2">FNMR@ FMR=1% </th>
    <th rowspan="2">Gap to Real [%] </th>
  </tr>
  <tr>
  </tr>
</thead>
<tbody>
  <tr>
    <td>1</td>
    <td>lens</td>
    <td>44</td>
    <td>10/30/23</td>
    <td>LENS</td>
    <td>92.25 (1)</td>
    <td>93.54 (1)</td>
    <td>1.28 (3)</td>
    <td>15.25 (2)</td>
    <td>-0.74 (7)</td>
  </tr>
  <tr>
    <td>2</td>
    <td>anjith2006</td>
    <td>15</td>
    <td>10/30/23</td>
    <td>Idiap</td>
    <td>91.88 (2)</td>
    <td>93.41 (2)</td>
    <td>1.53 (4)</td>
    <td>13.97 (1)</td>
    <td>-3.80 (4)</td>
  </tr>
  <tr>
    <td>3</td>
    <td>bjgbiesseck</td>
    <td>14</td>
    <td>10/30/23</td>
    <td>BOVIFOCR-UFPR</td>
    <td>90.51 (3)</td>
    <td>92.35 (3)</td>
    <td>1.84 (5)</td>
    <td>16.35 (3)</td>
    <td>4.23 (9)</td>
  </tr>
  <tr>
    <td>4</td>
    <td>ckoutlis</td>
    <td>20</td>
    <td>10/27/23</td>
    <td>MeVer Lab</td>
    <td>87.51 (4)</td>
    <td>89.62 (4)</td>
    <td>2.11 (6)</td>
    <td>32.57 (5)</td>
    <td>5.68 (10)</td>
  </tr>
  <tr>
    <td>5</td>
    <td>asanchez</td>
    <td>6</td>
    <td>10/30/23</td>
    <td>Aphi</td>
    <td>82.24 (5)</td>
    <td>86.01 (5)</td>
    <td>3.77 (10)</td>
    <td>23.80 (4)</td>
    <td>0.84 (8)</td>
  </tr>
</tbody>
</table>

<p align="center"><strong>Task 1.2 - mixed data for bias mitigation</strong>strong></p>
<table>
<thead>
  <tr>
    <th rowspan="2">#</th>
    <th rowspan="2">User</th>
    <th rowspan="2">Entries</th>
    <th rowspan="2">Date of Last Entry</th>
    <th rowspan="2">Team Name</th>
    <th rowspan="2">Trade-off Accuracy (AVG - STD) [%] </th>
    <th rowspan="2">AVG Accuracy [%] </th>
    <th rowspan="2">STD Accuracy [%] </th>
    <th rowspan="2">FNMR@ FMR=1% </th>
    <th rowspan="2">Gap to Real [%] </th>
  </tr>
  <tr>
  </tr>
</thead>
<tbody>
  <tr>
    <td>1</td>
    <td>zhaoweisong</td>
    <td>68</td>
    <td>10/30/23</td>
    <td>CBSR</td>
    <td>95.25 (1)</td>
    <td>96.45 (1)</td>
    <td>1.20 (3)</td>
    <td>8.68 (4)</td>
    <td>-2.10 (5)</td>
  </tr>
  <tr>
    <td>2</td>
    <td>lens</td>
    <td>44</td>
    <td>10/30/23</td>
    <td>LENS</td>
    <td>95.24 (2)</td>
    <td>96.35 (2)</td>
    <td>1.11 (1)</td>
    <td>6.35 (2)</td>
    <td>-5.67 (4)</td>
  </tr>
  <tr>
    <td>3</td>
    <td>ckoutlis</td>
    <td>20</td>
    <td>10/27/23</td>
    <td>MeVer Lab</td>
    <td>93.87 (3)</td>
    <td>95.44 (3)</td>
    <td>1.56 (4)</td>
    <td>9.50 (5)</td>
    <td>-0.78 (6)</td>
  </tr>
  <tr>
    <td>4</td>
    <td>bjgbiesseck</td>
    <td>14</td>
    <td>10/30/23</td>
    <td>BOVIFOCR-UFPR</td>
    <td>93.15 (4)</td>
    <td>95.04 (4)</td>
    <td>1.89 (5)</td>
    <td>10.00 (6)</td>
    <td>1.28 (9)</td>
  </tr>
  <tr>
    <td>5</td>
    <td>atzoriandrea</td>
    <td>8</td>
    <td>10/30/23</td>
    <td>UNICA-FRAUNHOFER IGD</td>
    <td>91.03 (5)</td>
    <td>94.06 (5)</td>
    <td>3.03 (6)</td>
    <td>6.85 (3)</td>
    <td>-10.62 (2)</td>
  </tr>
  <tr>
    <td>6</td>
    <td>anjith2006</td>
    <td>15</td>
    <td>10/30/23</td>
    <td>Idiap</td>
    <td>87.22 (6)</td>
    <td>91.54 (6)</td>
    <td>4.32 (8)</td>
    <td>5.50 (1)</td>
    <td>-0.65 (7)</td>
  </tr>
</tbody>
</table>

<p align="center"><strong>Task 2.1 - syn. data for performance improvement</strong>strong></p>
<table>
<thead>
  <tr>
    <th rowspan="2">#</th>
    <th rowspan="2">User</th>
    <th rowspan="2">Entries</th>
    <th rowspan="2">Date of Last Entry</th>
    <th rowspan="2">Team Name</th>
    <th rowspan="2">AVG Accuracy [%] </th>
    <th rowspan="2">FNMR@ FMR=1% </th>
    <th rowspan="2">Gap to Real [%] </th>
  </tr>
  <tr>
  </tr>
</thead>
<tbody>
  <tr>
    <td>1</td>
    <td>bjgbiesseck</td>
    <td>14</td>
    <td>10/30/23</td>
    <td>BOVIFOCR-UFPR</td>
    <td>90.50 (1)</td>
    <td>20.83 (1)</td>
    <td>2.66 (3)</td>
  </tr>
  <tr>
    <td>2</td>
    <td>lens</td>
    <td>44</td>
    <td>10/30/23</td>
    <td>LENS</td>
    <td>88.18 (2)</td>
    <td>33.25 (3)</td>
    <td>3.75 (5)</td>
  </tr>
  <tr>
    <td>3</td>
    <td>anjith2006</td>
    <td>15</td>
    <td>10/30/23</td>
    <td>Idiap</td>
    <td>86.39 (3)</td>
    <td>30.73 (2)</td>
    <td>6.39 (6)</td>
  </tr>
  <tr>
    <td>4</td>
    <td>nicolo.didomenico</td>
    <td>5</td>
    <td>10/29/23</td>
    <td>BioLab</td>
    <td>83.93 (4)</td>
    <td>49.51 (5)</td>
    <td>6.88 (7)</td>
  </tr>
  <tr>
    <td>5</td>
    <td>ckoutlis</td>
    <td>20</td>
    <td>10/27/23</td>
    <td>MeVer Lab</td>
    <td>83.45 (5)</td>
    <td>50.05 (6)</td>
    <td>3.20 (4)</td>
  </tr>
  <tr>
    <td>6</td>
    <td>asanchez</td>
    <td>6</td>
    <td>10/30/23</td>
    <td>Aphi</td>
    <td>80.53 (6)</td>
    <td>46.09 (4)</td>
    <td>9.12 (8)</td>
  </tr>
</tbody>
</table>

<p align="center"><strong>Task 2.2 - mixed data for performance improvement</strong>strong></p>
<table>
<thead>
  <tr>
    <th rowspan="2">#</th>
    <th rowspan="2">User</th>
    <th rowspan="2">Entries</th>
    <th rowspan="2">Date of Last Entry</th>
    <th rowspan="2">Team Name</th>
    <th rowspan="2">AVG Accuracy [%] </th>
    <th rowspan="2">FNMR@ FMR=1% </th>
    <th rowspan="2">Gap to Real [%] </th>
  </tr>
  <tr>
  </tr>
</thead>
<tbody>
  <tr>
    <td>1</td>
    <td>zhaoweisong</td>
    <td>68</td>
    <td>10/30/23</td>
    <td>CBSR</td>
    <td>94.95 (1)</td>
    <td>10.82 (1)</td>
    <td>-3.69 (3)</td>
  </tr>
  <tr>
    <td>2</td>
    <td>lens</td>
    <td>44</td>
    <td>10/30/23</td>
    <td>LENS</td>
    <td>92.40 (2)</td>
    <td>17.67 (4)</td>
    <td>-1.63 (4)</td>
  </tr>
  <tr>
    <td>3</td>
    <td>anjith2006</td>
    <td>15</td>
    <td>10/30/23</td>
    <td>Idiap</td>
    <td>91.74 (3)</td>
    <td>23.27 (5)</td>
    <td>0.00 (7)</td>
  </tr>
  <tr>
    <td>4</td>
    <td>bjgbiesseck</td>
    <td>14</td>
    <td>10/30/23</td>
    <td>BOVIFOCR-UFPR</td>
    <td>91.34 (4)</td>
    <td>16.51 (2)</td>
    <td>1.77 (8)</td>
  </tr>
  <tr>
    <td>5</td>
    <td>ckoutlis</td>
    <td>20</td>
    <td>10/27/23</td>
    <td>MeVer Lab</td>
    <td>87.60 (5)</td>
    <td>17.10 (3)</td>
    <td>-1.57 (5)</td>
  </tr>
  <tr>
    <td>6</td>
    <td>atzoriandrea</td>
    <td>8</td>
    <td>10/30/23</td>
    <td>UNICA-FRAUNHOFER IGD</td>
    <td>84.86 (6)</td>
    <td>39.35 (6)</td>
    <td>-27.43 (1)</td>
  </tr>
</tbody>
</table>

### FRCSyn at WACV 2024: Top Teams

**CBSR** <br>
Weisong Zhao, Xiangyu Zhu, Zheyu Yan, Xiao-Yu Zhang, Jinlin Wu, Zhen Lei<br>
IIE, CAS, China; School of Cyber Security, UCAS, China; MAIS, CASIA, China; School of Artificial Intelligence, UCAS, China; CAIR, HKISI, CAS, China<br>

**LENS**<br>
Suvidha Tripathi, Mahak Kothari, Md Haider Zama, Debayan Deb<br>
LENS, Inc., US<br>

**BOVIFOCR-UFPR**<br>
Bernardo Biesseck, Pedro Vidal, Roger Granada, Guilherme Fickel, Gustavo Führ, David Menotti<br>
Federal University of Parana, Curitiba, PR, Brazil; Federal Institute of Mato Grosso, Pontes e Lacerda, Brazil; unico - idTech, Brazil<br>

**Idiap**<br>
Alexander Unnervik, Anjith George, Christophe Ecabert, Hatef Otroshi Shahreza, Parsa Rahimi, Sébastien Marcel<br>
Idiap Research Institute, Switzerland; Ecole Polytechnique Fédérale de Lausanne, Switzerland; Universite de Lausanne, Switzerland<br>

**MeVer**<br>
Ioannis Sarridis, Christos Koutlis, Georgia Baltsou, Symeon Papadopoulos, Christos Diou<br>
Centre for Research and Technology Hellas, Greece; Harokopio University of Athens, Greece<br>

**BioLab**<br>
Nicolò Di Domenico, Guido Borghi, Lorenzo Pellegrini<br>
University of Bologna, Cesena Campus, Italy<br>

**Aphi**<br>
Enrique Mas-Candela, Ángela Sánchez-Pérez<br>
Facephi, Spain<br>

**UNICA-FRAUNHOFER IGD**<br>
Andrea Atzori, Fadi Boutros, Naser Damer, Gianni Fenu, Mirko Marras<br>
University of Cagliari, Italy; Fraunhofer IGD, Germany; TU Darmstadt, Germany<br>


### Schedule
<div id="schedule">Destination</div>
<table>
<thead>
  <tr>
    <th>Time (HST) </th>
    <th>Duration </th>
    <th>Activity </th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>8:20 – 8:30 </td>
    <td>10 mins </td>
    <td>Introduction </td>
  </tr>
  <tr>
    <td>8:30 – 9:15 </td>
    <td>45 min </td>
    <td>Keynote 1: <a href="https://luminohope.org/">Koki Nagano</a> </td>
  </tr>
  <tr>
    <td>9:15 – 10:00 </td>
    <td>45 min </td>
    <td>Keynote 2: <a href="https://www.cs.cmu.edu/~ftorre/">Fernando De la Torre</a> </td>
  </tr>
  <tr>
    <td>10:00 – 10:15 </td>
    <td>15 min </td>
    <td>1st Break </td>
  </tr>
  <tr>
    <td>10:15 – 10:35 </td>
    <td>20 min </td>
    <td>FRCSyn Challenge </td>
  </tr>
  <tr>
    <td>10:35 – 11:10 </td>
    <td>35 min </td>
    <td>Top-ranked Teams (5) </td>
  </tr>
  <tr>
    <td>11:10 – 11:25 </td>
    <td>15 min </td>
    <td>Notable Teams (3) </td>
  </tr>
  <tr>
    <td>11:25 – 11:45 </td>
    <td>20 min </td>
    <td>FRCSyn Challenge: Q&amp;A </td>
  </tr>
  <tr>
    <td>11:45 – 12:00 </td>
    <td>15 min </td>
    <td>2nd Break </td>
  </tr>
  <tr>
    <td>12:00 – 12:45 </td>
    <td>45 min </td>
    <td>Keynote 3: <a href="https://cvlab.cse.msu.edu/">Xiaoming Liu</a> </td>
  </tr>
  <tr>
    <td>12:45 – 12:55 </td>
    <td>10 min </td>
    <td>Closing Notes </td>
  </tr>
</tbody>
</table>

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
