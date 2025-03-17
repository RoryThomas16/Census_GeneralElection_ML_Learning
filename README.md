# Machine Learning Practice | 2021 Census - 2024 General Election Predictor

<!-- Credit to: https://github.com/othneildrew/Best-README-Template/blob/main/README.md for the Template <3 -->
<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

This is a personal repo for me to practice machine learning work. The impetus for this was just the thought "what could I gleam from the 2021 Census data?":
* Could I guess the population of LGBT+ people in an area?
* Could I guess how the average age of an area?
* Could I guess how a constituency voted, based on the census data?
The latter question was the most interesting to me.

So I set to work doing so obtaining all the census data:
* Bulk Data: https://www.nomisweb.co.uk/sources/census_2021_bulk
* Census Map: https://www.ons.gov.uk/census/maps/

So I set to work doing so obtaining all the general election data:
* https://commonslibrary.parliament.uk/research-briefings/cbp-10009/

And finally, the maps between the geography codes:
* https://geoportal.statistics.gov.uk/datasets/5968b5b2c0f14dd29ba277beaae6dec3_0/explore
* https://geoportal.statistics.gov.uk/datasets/098360c460dd41beacbdfad83bc4fea2_0/explore
* https://geoportal.statistics.gov.uk/datasets/0d62b50d90d14b8d8b2ccf9f770b5751_0/explore 


<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With
The code is predominantly built in Python; primarily Jupyter Notebooks.
The Notebook has been run with the following libraries:
* Python [= 3.11.11]
* Pandas
* Scikit-Learn
* Numpy
* XGBoost
* Seaborn
* Matplotlib
* Imblearn

<p align="right">(<a href="#readme-top">back to top</a>)</p>

