---
layout: "single"
title: "Research and Publications"
read_time: false
comments: false
share: false
author_profile: true
classes: wide
---
## 2020
<div class="research-item">
    <p style="float: left;"><img src="/assets/images/bnn_review.png" height="200px" width="200px" border="10px"></p>
  <small>
      Ethan Goan and Clinton Fookes. Bayesian Neural Networks: An Introduction and Survey.  Case Studies in Applied Bayesian Data Science: CIRM Jean-Morlet Chair, Springer, 2020.<br>
    <br>
    <input type="button" value="arXiv" onclick="location.href = 'https://arxiv.org/abs/2006.12024v1'">
    <input type="button" value="paper" onclick="location.href = 'https://link.springer.com/chapter/10.1007/978-3-030-42553-1_3'">
    <input type="button" value="bibtex" onclick="toggle_visibility('bibtex_bnn_review')">
  </small>
  <div id="bibtex_bnn_review" style="display:none;">
    <small><div class="highlighter-rouge"><pre class="highlight">
        <code>@incollection{goan2020bayesian,
        title={Bayesian Neural Networks: An Introduction and Survey},
        author={Goan, Ethan and Fookes, Clinton},
        booktitle={Case Studies in Applied Bayesian Data Science},
        pages={45--87},
        year={2020},
        publisher={Springer}
        }
          </code>
        </pre>
      </div>
    </small>
  </div>
</div>


<div class="research-item">
  <p style="float: left;"><img src="/assets/images/mammography.png" height="200px" width="200px" border="10px"></p>
    <small>
    Thomas Schaffter, Diana SM Buist, Christoph I Lee, Yaroslav Nikulin, Dezső Ribli, Yuanfang Guan, William Lotter, Zequn Jie, Hao Du, Sijia Wang, Jiashi Feng, etal.
    <br>
        Evaluation of Combined Artificial Intelligence and Radiologist Assessment to Interpret Screening Mammograms, JAMA Network Open. 2020
    <br>
    <input type="button" value="paper" onclick="location.href = 'https://jamanetwork.com/journals/jamanetworkopen/article-abstract/2761795'">
    <input type="button" value="DREAM Challange" onclick="location.href = 'https://www.synapse.org/#!Synapse:syn4224222'">
    <input type="button" value="bibtex" onclick="toggle_visibility('bibtex_dream_mammography')">
  </small>
  <div id="bibtex_dream_mammography" style="display:none;">
    <small><div class="highlighter-rouge"><pre class="highlight">
          <code>
              @article{10.1001/jamanetworkopen.2020.0265,
                  author = {Schaffter, Thomas and Buist, Diana S. M. and Lee, Christoph I. and Nikulin, Yaroslav and Ribli, Dezső and Guan, Yuanfang and Lotter, William and Jie, Zequn and Du, Hao and Wang, Sijia and Feng, Jiashi and Feng, Mengling and Kim, Hyo-Eun and Albiol, Francisco and Albiol, Alberto and Morrell, Stephen and Wojna, Zbigniew and Ahsen, Mehmet Eren and Asif, Umar and Jimeno Yepes, Antonio and Yohanandan, Shivanthan and Rabinovici-Cohen, Simona and Yi, Darvin and Hoff, Bruce and Yu, Thomas and Chaibub Neto, Elias and Rubin, Daniel L. and Lindholm, Peter and Margolies, Laurie R. and McBride, Russell Bailey and Rothstein, Joseph H. and Sieh, Weiva and Ben-Ari, Rami and Harrer, Stefan and Trister, Andrew and Friend, Stephen and Norman, Thea and Sahiner, Berkman and Strand, Fredrik and Guinney, Justin and Stolovitzky, Gustavo and and the DM DREAM Consortium},
                  title = "{Evaluation of Combined Artificial Intelligence and Radiologist Assessment to Interpret Screening Mammograms}",
                  journal = {JAMA Network Open},
                  volume = {3},
                  number = {3},
                  pages = {e200265-e200265},
                  year = {2020},
                  month = {03},
                  abstract = "{Mammography screening currently relies on subjective human interpretation. Artificial intelligence (AI) advances could be used to increase mammography screening accuracy by reducing missed cancers and false positives.To evaluate whether AI can overcome human mammography interpretation limitations with a rigorous, unbiased evaluation of machine learning algorithms.In this diagnostic accuracy study conducted between September 2016 and November 2017, an international, crowdsourced challenge was hosted to foster AI algorithm development focused on interpreting screening mammography. More than 1100 participants comprising 126 teams from 44 countries participated. Analysis began November 18, 2016.Algorithms used images alone (challenge 1) or combined images, previous examinations (if available), and clinical and demographic risk factor data (challenge 2) and output a score that translated to cancer yes/no within 12 months. Algorithm accuracy for breast cancer detection was evaluated using area under the curve and algorithm specificity compared with radiologists’ specificity with radiologists’ sensitivity set at 85.9\\% (United States) and 83.9\\% (Sweden). An ensemble method aggregating top-performing AI algorithms and radiologists’ recall assessment was developed and evaluated.Overall, 144 231 screening mammograms from 85 580 US women (952 cancer positive ≤12 months from screening) were used for algorithm training and validation. A second independent validation cohort included 166 578 examinations from 68 008 Swedish women (780 cancer positive). The top-performing algorithm achieved an area under the curve of 0.858 (United States) and 0.903 (Sweden) and 66.2\\% (United States) and 81.2\\% (Sweden) specificity at the radiologists’ sensitivity, lower than community-practice radiologists’ specificity of 90.5\\% (United States) and 98.5\\% (Sweden). Combining top-performing algorithms and US radiologist assessments resulted in a higher area under the curve of 0.942 and achieved a significantly improved specificity (92.0\\%) at the same sensitivity.While no single AI algorithm outperformed radiologists, an ensemble of AI algorithms combined with radiologist assessment in a single-reader screening environment improved overall accuracy. This study underscores the potential of using machine learning methods for enhancing mammography screening interpretation.}",
                  issn = {2574-3805},
                  doi = {10.1001/jamanetworkopen.2020.0265},
                  url = {https://doi.org/10.1001/jamanetworkopen.2020.0265},
                  eprint = {https://jamanetwork.com/journals/jamanetworkopen/articlepdf/2761795/schaffter\_2020\_oi\_200024.pdf},
              }
    </code>
        </pre>
      </div>
    </small>
  </div>
</div>



<div class="research-item">
  <p style="float: left;"><img src="/assets/images/parkinsons.png" height="200px" width="200px" border="10px"></p>
  <small>
    S. K. Sieberts, J. Schaff, M. Duda, B. Á. Pataki, M. Sun, P. Snyder, J.-F. Daneault,
    F. Parisi, G. Costante, U. Rubin, P. Banda, Y. Chae, E. C. Neto, R. Dorsey, Z. Aydın,
    A. Chen, L. L. Elo, C. Espino, E. Glaab, E. Goan, F. N. Golabchi, Y. Görmez, M. K.
    Jaakkola, J. Jonnagaddala, R. Klén, D. Li, C. McDaniel, D. Perrin, N. M. Rad, E. Rainaldi,
    S. Sapienza, P. Schwab, N. Shokhirev, M. S. Venäläinen, G. Vergara-Diaz, Y. Zhang, ,
    Y. Wang, Y. Guan, D. Brunner, P. Bonato, L. M. Mangravite, and L. Omberg
    <br>
    Crowd-sourcing digital health measures to predict parkinson’s disease severity: the parkinson’s
    disease digital biomarker dream challenge, bioRXiv, 2020
    <br>
    <input type="button" value="paper" onclick="location.href = 'https://www.biorxiv.org/content/10.1101/2020.01.13.904722v1'">
    <input type="button" value="DREAM Challange" onclick="location.href = 'https://www.synapse.org/#!Synapse:syn8717496/wiki/422884'">
    <input type="button" value="bibtex" onclick="toggle_visibility('bibtex_dream_parkinsons')">
  </small>
  <div id="bibtex_dream_parkinsons" style="display:none;">
    <small><div class="highlighter-rouge"><pre class="highlight">
          <code>
@article {Sieberts2020.01.13.904722,
author = {Sieberts, Solveig K. and Schaff, Jennifer and Duda, Marlena and Pataki, B{\'a}lint {\'A}rmin and Sun, Ming and Snyder, Phil and Daneault, Jean-Francois and Parisi, Federico and Costante, Gianluca and Rubin, Udi and Banda, Peter and Chae, Yooree and Neto, Elias Chaibub and Dorsey, Ray and Ayd{\i}n, Zafer and Chen, Aipeng and Elo, Laura L. and Espino, Carlos and Glaab, Enrico and Goan, Ethan and Golabchi, Fatemeh Noushin and G{\"o}rmez, Yasin and Jaakkola, Maria K. and Jonnagaddala, Jitendra and Kl{\'e}n, Riku and Li, Dongmei and McDaniel, Christian and Perrin, Dimitri and Rad, Nastaran Mohammadian and Rainaldi, Erin and Sapienza, Stefano and Schwab, Patrick and Shokhirev, Nikolai and Ven{\"a}l{\"a}inen, Mikko S. and Vergara-Diaz, Gloria and Zhang, Yuqian and , and Wang, Yuanjia and Guan, Yuanfang and Brunner, Daniela and Bonato, Paolo and Mangravite, Lara M. and Omberg, Larsson},
editor = {, and Abrami, Avner and Adhikary, Aditya and Agurto, Carla and Bhalla, Sherry and Bilgin, Halil and Caggiano, Vittorio and Cheng, Jun and Deng, Eden and Gan, Qiwei and Girsa, Rajan and Han, Zhi and Heisig, Stephen and Huang, Kun and Jahandideh, Samad and Kopp, Wolfgang and Kurz, Christoph F. and Lichtner, Gregor and Norel, Raquel and Raghava, G.P.S and Sethi, Tavpritesh and Shawen, Nicholas and Tripathi, Vaibhav and Tsai, Matthew and Wang, Tongxin and Wu, Yi and Zhang, Jie and Zhang, Xinyu},
title = {Crowdsourcing digital health measures to predict Parkinson{\textquoteright}s disease severity: the Parkinson{\textquoteright}s Disease Digital Biomarker DREAM Challenge},
elocation-id = {2020.01.13.904722},
year = {2020},
doi = {10.1101/2020.01.13.904722},
publisher = {Cold Spring Harbor Laboratory},
URL = {https://www.biorxiv.org/content/early/2020/01/16/2020.01.13.904722},
eprint = {https://www.biorxiv.org/content/early/2020/01/16/2020.01.13.904722.full.pdf},
journal = {bioRxiv}
}
          </code>
        </pre>
      </div>
    </small>
  </div>
</div>


## Prior Research
Research conducted prior to starting my PhD.

<div class="research-item">
  <p style="float: left;"><img src="/assets/images/hyperspec_plant.png" height="200px" width="200px" border="10px"></p>
  <small>
    Peyman Moghadam, Daniel Ward, Ethan Goan, Srimal Jayawardena, Pavan Sikka, Emili Hernandez. Plant disease detection using hyperspectral imaging.  DICTA. 2017.<br>
    <br>
    <input type="button" value="paper" onclick="location.href = 'https://ieeexplore.ieee.org/abstract/document/8227476'">
    <input type="button" value="bibtex" onclick="toggle_visibility('bibtex_hyperspec_plant')">
  </small>
  <div id="bibtex_hyperspec_plant" style="display:none;">
    <small><div class="highlighter-rouge"><pre class="highlight">
          <code>@inproceedings{moghadam2017plant,
            title={Plant disease detection using hyperspectral imaging},
            author={Moghadam, Peyman and Ward, Daniel and Goan, Ethan and Jayawardena, Srimal and Sikka, Pavan and Hernandez, Emili},
            booktitle={2017 International Conference on Digital Image Computing: Techniques and Applications (DICTA)},
            pages={1--8},
            year={2017},
            organization={IEEE}
            }
          </code>
        </pre>
      </div>
    </small>
  </div>
</div>

<div class="research-item">
  <p style="float: left;"><img src="/assets/images/hyperspec.png" height="200px" width="200px" border="10px"></p>
  <small>
    Reza Arablouie, Ethan Goan, Stephen Gensemer, Brano Kusy. Fast and robust pushbroom hyperspectral imaging via DMD-based scanning.  Novel Optical Systems Design and Optimization XIX. 2016.<br>
    <br>
    <input type="button" value="paper + presentation" onclick="location.href = 'https://www.spiedigitallibrary.org/conference-proceedings-of-spie/9948/99480A/Fast-and-robust-pushbroom-hyperspectral-imaging-via-DMD-based-scanning/10.1117/12.2239107.full?casa_token=lrKFa_KYiJMAAAAA%3apI0t3RPNfHF0ah0qztk3_z5uz5h7PBQdkyocg20nRTxfTVqgC3QSItpCV-eqGE5riHY-fhNMKA'">
    <input type="button" value="arXiv" onclick="location.href = 'https://arxiv.org/abs/1608.00361'">
    <input type="button" value="bibtex" onclick="toggle_visibility('bibtex_hyperspec_cam')">
  </small>
  <div id="bibtex_hyperspec_cam" style="display:none;">
    <small><div class="highlighter-rouge"><pre class="highlight">
          <code>@inproceedings{arablouei2016fast,
            title={Fast and robust pushbroom hyperspectral imaging via DMD-based scanning},
            author={Arablouei, Reza and Goan, Ethan and Gensemer, Stephen and Kusy, Branislav},
            booktitle={Novel Optical Systems Design and Optimization XIX},
            volume={9948},
            pages={99480A},
            year={2016},
            organization={International Society for Optics and Photonics}
            }
          </code>
        </pre>
      </div>
    </small>
  </div>
</div>



<!-- research item style -->
<style>
  .research-item {
     margin-top: 1.5cm;
     margin-bottom: 1.5cm;
  }
</style>



<!-- script to toggle visibility -->
<script type="text/javascript">
   function toggle_visibility(block_id) {
       var e = document.getElementById(block_id);
       if(e.style.display == 'block')
          e.style.display = 'none';
       else
          e.style.display = 'block';
   }
</script>
