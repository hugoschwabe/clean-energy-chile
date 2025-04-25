<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->


<!-- ABOUT THE PROJECT -->
## About The Project

<h2>🇨🇱 Scenario Analysis of a 100% Renewable Energy System for Chile (2013)</h2>

<p>This repository contains a university project exploring the feasibility of a fully renewable energy system for Chile in the base year 2013. The analysis is performed using Python in a Jupyter Notebook, leveraging the open-source <strong>PyPSA</strong> package for power system modeling.</p>

<h3>📊 What the Project Does</h3>

<p>The project performs a multi-step analysis using real-world datasets (included in the <code>data/</code> folder), aiming to estimate the technical and economic potential of wind and solar power in Chile. The key steps are:</p>

<ol>
  <li><strong>Land Eligibility Analysis</strong><br>
      Filters regions based on land cover classes to identify suitable areas for renewable installations.
  </li>
  <li><strong>Capacity Factor Time Series Calculation</strong><br>
      Derives wind and solar capacity factors using point-in-time wind speed and solar radiation data.
  </li>
  <li><strong>Building the PyPSA Model</strong><br>
      Constructs an energy model incorporating:
      <ul>
        <li>Renewable generation potential</li>
        <li>Existing power plant data</li>
        <li>Historical electricity demand</li>
        <li>Simplified regional power transmission</li>
      </ul>
  </li>
  <li><strong>System Optimization</strong><br>
      Runs a cost-minimizing optimization to:
      <ul>
        <li>Simulate hourly generation</li>
        <li>Determine required battery and hydrogen storage capacities</li>
      </ul>
  </li>
  <li><strong>Results & Insights</strong><br>
      Interprets the optimized system design and discusses trade-offs, limitations, and future potential for renewables in Chile.
  </li>
</ol>



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these steps.



### Prerequisites

* For this notebook to execute a list of python packages need to be installed. A requirements-file is provided.
  ```sh
  pip install requirements.txt
  ```



### Installation

* Clone the repository
   ```sh
   git clone https://github.com/hugoschwabe/clean-energy-chile.git
   ```
* or
	```sh
   git clone git@github.com:hugoschwabe/clean-energy-chile.git
   ```


<!-- LICENSE -->
## License

Distributed under the MIT license. See `LICENSE` for more information.




<!-- CONTACT -->
## Contact

Hugo Schwabe - [LinkedIn](https://linkedin.com/in/hugo-schwabe-1a57a7360) - schwabehugo@gmail.com

Project Link: [https://github.com/hugoschwabe/clean-energy-chile](https://github.com/hugoschwabe/clean-energy-chile)
