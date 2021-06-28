# surgical-workflow-data-sets

Description
-----------
List of surgical tool datasets organised by task. A list of data repositories is also displayed at the bottom. Please open an issue if you see a relevant open dataset which is missing or if you find inacurate information.

Tool classification
-------------------

<table align="center">
  <tr>
    <td align="center">Dataset</td> <td align="center">Brief description</td> <td align="center">Images</td> <td align="center">Procedures</td> <td align="center">Paper</td>
  </tr>
  
  <!-- Cholec80 -->
  <tr>
    <td align="center">
      <a href="http://camma.u-strasbg.fr/datasets">Cholec80</a>
    </td>
    <td align="center">
      80 videos of cholecystectomy surgeries performed by 13 surgeons. The videos are captured at 25 fps. The dataset is labeled with the phase (at 25 fps) and tool presence annotations (at 1 fps). A tool is defind as present in an image if at least half of the tool tip is visible.
    </td>
    <td align="center">86K</td>
    <td align="center">80</td>
    <td align="center">
      <a href="https://arxiv.org/abs/1602.03012">Twinanda et al. 2016</a>
    </td>
  </tr>
  
  <!-- CATARACTS -->
  <tr>
    <td align="center">
      <a href="https://ieee-dataport.org/open-access/cataracts">CATARACTS</a>
    </td>
    <td align="center">
      This dataset consists of 50 cataract surgery. It was annotated for two main tasks: surgical tool presence detection and surgical activity recognition. It was divided into two sets (train, test) for the surgical tool presence detection task and 3 sets (train, dev, test) for the activity recognition task.
    </td>
    <td align="center">900K</td>
    <td align="center">50</td>
    <td align="center">
      <a href="https://www.sciencedirect.com/science/article/abs/pii/S136184151830865X">Al Hajj et al. 2019</a>
    </td>
  </tr>
  
</table>

Tool segmentation
-----------------
<table align="center">
  <tr>
    <td align="center">Dataset</td> <td align="center">Brief description</td> <td align="center">Images</td> <td align="center">Procedures</td> <td align="center">Paper</td>
  </tr>
  
  <!-- RMIT -->
  <tr>
    <td align="center">
      <a href="https://sites.google.com/site/sznitr/code-and-datasets">RMIT</a>
    </td>
    <td align="center">
      This dataset consists of three image sequences during retinal microsurgery. For each image sequence, the instrument position and size has been hand annotated.
    </td>
    <td align="center">1.5K</td>
    <td align="center">4</td>
    <td align="center">
      <a href="https://link.springer.com/chapter/10.1007/978-3-642-33418-4_70">Sznitman et a. 2012</a>
    </td>
  </tr>
  
  <!-- InstrumentCrowd -->
  <tr>
    <td align="center">
      <a href="https://opencas.webarchiv.kit.edu/?q=InstrumentCrowd">InstrumentCrowd</a>
    </td>
    <td align="center">
      The training data was generated from a total of 6 surgical procedures, three from laparoscopic adrenalectomies and three from laparoscopic pancreatic resections. From each surgery, 20 images containing one or several medical instruments were extracted, yielding 120 images in total.
    </td>
    <td align="center">120</td>
    <td align="center">6</td>
    <td align="center">
      <a href="https://link.springer.com/chapter/10.1007%2F978-3-319-10470-6_55">Maier-Hein et al. 2014</a>
    </td>
  </tr>
  
  <!-- NeuroSurgicalTools -->
  <tr>
    <td align="center">
      <a href="https://medicis.univ-rennes1.fr/software#neurosurgicaltools_dataset">NeuroSurgicalTools</a>
    </td>
    <td align="center">
      Consists of 2476 monocular images (1221 for training and 1255 for testing) coming from in vivo neurosurgeries. The resolution of the images varies from 612×460 to 1920×1080. 
    </td>
    <td align="center">2.5K</td>
    <td align="center">14</td>
    <td align="center">
      <a href="https://ieeexplore.ieee.org/document/7138629">Bouget et al. 2015</a>
    </td>
  </tr>
  
  <!-- EndoVis2015 -->
  <tr>
    <td align="center">
      <a href="https://opencas.webarchiv.kit.edu/?q=node/30">EndoVis2015</a>
    </td>
    <td align="center">
      40 2D in-vivo images from 4 laparoscopic colorectal surgeries. Each pixel is labelled as either background, shaft and manipulator (~160 2D images and annotations in total). 4x 45-second 2D images sequences of at least one Large Needle Driver instrument in an ex-vivo setup. Each pixel is labelled as either backgroud, shaft, head or clasper. 
    </td>
    <td align="center">9K</td>
    <td align="center">8</td>
    <td align="center">
      N/A
    </td>
  </tr>
  
  <!-- EndoVis2017 -->
  <tr>
    <td align="center">
      <a href="https://endovissub2017-roboticinstrumentsegmentation.grand-challenge.org">EndoVis2017</a>
    </td>
    <td align="center">
      8x 225-frame robotic surgical videos, captured at 2 Hz, with manually labelled different tool parts and types. The testing set contains 8x 75-frame videos and 2x 300-frame videos.
    </td>
    <td align="center">1.8K</td>
    <td align="center">8</td>
    <td align="center">
      <a href="https://arxiv.org/pdf/1902.06426.pdf">Allan et al. 2019</a>
    </td>
  </tr>
  
  <!-- EndoVis2018 -->
  <tr>
    <td align="center">
      <a href="https://endovissub2018-roboticscenesegmentation.grand-challenge.org">EndoVis2018</a>
    </td>
    <td align="center">
      Training dataset is made up of 16 robotic nephrectomy procedures recorded using da Vinci Xi systems in porcine labs (subsampled to 2fps). Sequences with little or no motion are manually removed to leave 149 frames per procedure. Video frames are 1280x1024 and we provide the left and right eye camera image as well as the stereo camera calibration parameters. Labels are only provided for the left image. 
    </td>
    <td align="center">2.4K</td>
    <td align="center">16</td>
    <td align="center">
      <a href="https://arxiv.org/abs/2001.11190">Allan et al. 2020</a>
    </td>
  </tr>
  
  <!-- ROBUST-MIS 2019 -->
  <tr>
    <td align="center">
      <a href="https://www.synapse.org/#!Synapse:syn20575265">ROBUST-MIS2019</a>
    </td>
    <td align="center">
      Procedures in rectal resection and proctocolectomy. A training case encompasses a 10 second video snippet in form of 250 endoscopic image frames and a reference annotation for the last frame. In the annotated frame a “0” indicates the absence of a medical instrument and numbers “1”, “2“, ... represent different instances of medical instruments.
    </td>
    <td align="center">10K</td>
    <td align="center">30</td>
    <td align="center">
      <a href="https://arxiv.org/abs/2003.10299">Ross et al. 2020</a>
    </td>
  </tr>
  
  <!-- Kvasir-Instrument -->
  <tr>
    <td align="center">
      <a href="https://datasets.simula.no/kvasir-instrument/">Kvasir-Instrument</a><br>
    </td>
    <td align="center">
      The Kvasir-Instrument dataset consists of consists of 590 annotated frames comprising of GI procedure tools such as snares, balloons, biopsy forceps, etc. The resolution of the image in the dataset varies from 720x576 to 1280x1024. 
    </td>
    <td align="center">590</td>
    <td align="center">N/A</td>
    <td align="center">
      <a href="https://link.springer.com/chapter/10.1007/978-3-030-67835-7_19">Jha et al. 2020</a>
    </td>
  </tr>
  
  <!-- CholecSeg8k -->
  <tr>
    <td align="center">
      <a href="https://www.kaggle.com/newslab/cholecseg8k">CholecSeg8k</a>
    </td>
    <td align="center">
      This dataset contains 8080 laparoscopic cholecystectomy image frames extracted and annotated from 17 video clips in Cholec80.
    </td>
    <td align="center">8K</td>
    <td align="center">17</td>
    <td align="center">
      <a href="https://arxiv.org/pdf/2012.12453.pdf">Hong et al. 2020</a>
    </td>
  </tr>
  
  <!-- RoboTool -->
  <tr>
    <td align="center">
      <a href="https://www.synapse.org/#!Synapse:syn22427422">RoboTool</a>
    </td>
    <td align="center">
      514 images extracted from the videos of 20 freely available robotic surgical procedures and annotated for binary tool-background segmentation.
    </td>
    <td align="center">514</td>
    <td align="center">20</td>
    <td align="center">
      <a href="https://arxiv.org/abs/2102.09528">Garcia-Peraza-Herrera et al. 2021</a>
    </td>
  </tr>
  
</table>

Tool-tissue action detection
----------------------------

<table align="center">
  <tr>
    <td align="center">Dataset</td> <td align="center">Brief description</td> <td align="center">Images</td> <td align="center">Procedures</td> <td align="center">Paper</td>
  </tr>
  
  <!-- CholecT50 -->
  <tr>
    <td align="center">
      <a href="https://cholectriplet2021.grand-challenge.org/">CholecT50</a>
    </td>
    <td align="center">
      Every frame is annotated with labels from the triplet: instrument, verb and target.
    </td>
    <td align="center">N/A</td>
    <td align="center">N/A</td>
    <td align="center">
      N/A
    </td>
  </tr>
  
  <!-- SARAS-MESAD2021 -->
  <tr>
    <td align="center">
      <a href="https://saras-mesad.grand-challenge.org">SARAS-MESAD2021</a>
    </td>
    <td align="center">
      Dataset contains monocular digital recordings from da Vinci Xi robotic system. Two sub-datasets: MESAD-Real and MESAD-Phantom. MESAD-Real represents the prostatectomy procedures recorded on human patients. It contains four sessions of complete prostatectomy procedure performed by expert surgeons on real patients. MESAD-Phantom is also designed for surgeon action detection during prostatectomy, but is composed of videos captured during procedures on phantoms used for the training of surgeons. MESAD-Real comprises 21 action classes and MESAD-Phantom contemplates a smaller list of 14 action classes. Both the datasets share 11 action classes.
    </td>
    <td align="center">N/A</td>
    <td align="center">4</td>
    <td align="center">
      N/A
    </td>
  </tr>
  
</table>

Skill assessment and workflow recognition
-----------------------------------------

<table align="center">
  <tr>
    <td align="center">Dataset</td> <td align="center">Brief description</td> <td align="center">Images</td> <td align="center">Procedures</td> <td align="center">Paper</td>
  </tr>
  
  <!-- JIGSAWS -->
  <tr>
    <td align="center">
      <a href="https://cirl.lcsr.jhu.edu/research/hmm/datasets/jigsaws_release/">JIGSAWS</a>
    </td>
    <td align="center">
      The JIGSAWS dataset consists of three components: kinematic data (Cartesian positions, orientations, velocities, angular velocities and gripper angle describing the motion of the manipulators), video data (stereo video captured from the endoscopic camera), and manual annotations of gestures (atomic surgical activity segment labels) and skill (global rating score using modified objective structured assessments of technical skills).
    </td>
    <td align="center">N/A</td>
    <td align="center">N/A</td>
    <td align="center">
      <a href="https://cirl.lcsr.jhu.edu/wp-content/uploads/2015/11/JIGSAWS.pdf">Gao et al. 2014</a>
    </td>
  </tr>
  
  <!-- Cataract-101 -->
  <tr>
    <td align="center">
      <a href="https://zenodo.org/record/1220951#.YK_TxmZKg7Y">Cataract-101</a>
    </td>
    <td align="center">
      This dataset contains 101 videos of cataract surgeries annotated with two kinds of information: Anonymous ID and experience level of operating surgeon, and starting points of quasi-standardized operation phases in videos.
    </td>
    <td align="center">1.3M</td>
    <td align="center">101</td>
    <td align="center">
      <a href="https://dl.acm.org/doi/10.1145/3204949.3208137">Schoeffmann et al. 2018</a>
    </td>
  </tr>
  
  <!-- HeiCo -->
  <tr>
    <td align="center">
      <a href="https://www.synapse.org/#!Synapse:syn21903917/wiki/601992">HeiCo</a>
    </td>
    <td align="center">
      The data set contains of data from the ROBUST-MIS 2019 challenge and the Surgical Workflow Challenges from EndoVis 2017 and 2018.
    </td>
    <td align="center">10K</td>
    <td align="center">30</td>
    <td align="center">
      <a href="https://arxiv.org/abs/2005.03501">Maier-Hein et al. 2020</a>
    </td>
  </tr>
  
  <!-- MISAW -->
  <tr>
    <td align="center">
      <a href="https://www.synapse.org/#!Synapse:syn21776936/wiki/601700">MISAW</a>
    </td>
    <td align="center">
      The data-set contains 27 micro-anastomosis training sequences and is composed of the following information: stereoscopic video, kinematic data, workflow annotation at 3 levels of granularity (phases, steps, and activities).
    </td>
    <td align="center">N/A</td>
    <td align="center">27</td>
    <td align="center">
      <a href="https://arxiv.org/abs/2103.13111">Huaulmé et al. 2021</a>
    </td>
  </tr>
  
  <!-- PETRAW -->
  <tr>
    <td align="center">
      <a href="https://www.synapse.org/#!Synapse:syn25147789/wiki/608848">PETRAW</a>
    </td>
    <td align="center">
      Dataset for online automatic recognition of surgical workflow by using both kinematic and stereoscopic video information on a micro-anastomosis training task.
    </td>
    <td align="center">N/A</td>
    <td align="center">100</td>
    <td align="center">
      N/A
    </td>
  </tr>
  
</table>

Image-to-image translation
--------------------------
<table align="center">
  <tr>
    <td align="center">Dataset</td> <td align="center">Brief description</td> <td align="center">Paper</td>
  </tr>
  
  <!-- Laparoscopic Image to Image Translation -->
  <tr>
    <td align="center">
      <a href="http://opencas.dkfz.de/image2image/">Laparoscopic Image to Image Translation</a>
    </td>
    <td align="center">
      Synthetic images in a 3D environemnt roughly resembling laparoscopic liver surgery scenes. A group of Generative Adversarial Networks (GAN) is trained to translate these images to look like real laparoscopic images. After the training process, the translated images along with their labels can be used as training data for a certain target task.
    </td>
    <td align="center">
      <a href="https://arxiv.org/abs/1907.02882">Pfeiffer et al. 2019</a>
    </td>
  </tr>
</table>

Repositories holding multiple datasets
--------------------------------------
* https://endovis.grand-challenge.org
* https://opencas.webarchiv.kit.edu
* http://camma.u-strasbg.fr/datasets
* http://hamlyn.doc.ic.ac.uk/vision
* https://sites.google.com/site/sznitr/code-and-datasets
* https://datasets.simula.no/index.html
