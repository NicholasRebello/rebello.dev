---
# the default layout is 'page'
icon: fas fa-graduation-cap
order: 2
---

<style>
.image-container {
    width: 30%; /* Set the desired width for each column */
    box-sizing: border-box;
    float: left;
    text-align: center;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    margin: 0 1% 20px 1%; /* Add margin to separate columns */
}

.image-container img {
    width: 100%;
    height: auto;
    max-width: 100%;
    max-height: 100%;
}

.image-container p {
    margin: 10px 0 0;
}

@media (max-width: 768px) {
    .image-container {
    width: 45%; /* Adjust for two columns on smaller screens */
    }
}

@media (max-width: 480px) {
    .image-container {
    width: 100%; /* Full width for one column on even smaller screens */
    }
}
</style>


<div class="image-container">
  <img src="{{ site.baseurl }}/assets/img/certifications/pjpt.png" alt="PJPT">
  <p>Earned: 03-DEC-23</p>
  <p>Expires: Never</p>
</div>

<div class="image-container">
  <img src="{{ site.baseurl }}/assets/img/certifications/gwapt.png" alt="GWAPT">
  <p>Earned: 14-OCT-23</p>
  <p>Expires: 31-OCT-23</p>
</div>

<div class="image-container">
  <img src="{{ site.baseurl }}/assets/img/certifications/gcih.png" alt="GCIH">
  <p>Earned: 06-AUG-23</p>
  <p>Expires: 31-AUG-27</p>
</div>

<div class="image-container">
  <img src="{{ site.baseurl }}/assets/img/certifications/gsec.png" alt="GSEC">
  <p>Earned: 07-MAY-23</p>
  <p>Expires: 31-MAY-27</p>
</div>

<div class="image-container">
  <img src="{{ site.baseurl }}/assets/img/certifications/securityplus.png" alt="Security+">
  <p>Earned: 15-FEB-23</p>
  <p>Expires: 15-FEB-26</p>
</div>

<div class="image-container">
  <img src="{{ site.baseurl }}/assets/img/certifications/networkplus.png" alt="Network+">
  <p>Earned: 17-JUL-23</p>
  <p>Expires: 15-FEB-26</p>
</div>