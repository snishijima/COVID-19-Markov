# COVID-19-Markov
This is a simple COVID-19 Markov Model that can be used to predict and analyze the COVID-19 pandemic trend. 
Used only three states Active, Recovery, and Death. 
Probabilities used from India-2020 <i>These probabilities can be replaced with current rates.</i>
<p></p>
Markov Cohort Models explicitly models the passage of time over a series of discrete-time periods with mutually exclusive states that an individual can occupy over time (e.g. Active, Recovery, or Death). 
Each state has an associated health-related quality of life and cost value, which will help to evaluate the quality-adjusted life years (QALYs) and cost-effectiveness of decisions. 
The Markov property is the assumption that each transition state probability is independent of an individual’s history (stochastic/memoryless). Markov chain, a Markov process, accounts for time-dependent transition. 
<p></p>
The recommendation for further modeling is to use Microsimulation Models, which uses mutually exclusive and collectively exhaustive health states. 
Each individual can be in one health state at any given cycle with specific transition probabilities and transitions depends on the individual’s past transitions and characteristics. <i>However, there would be difficulty in obtaining information relating to individual's health state (HIPAA). </i>
<p></p>
<table class="tg">
<thead>
  <tr>
    <th class="tg-0pky"></th>
    <th class="tg-0pky">Active</th>
    <th class="tg-0pky">Recovery</th>
    <th class="tg-0pky">Death</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0pky">Active</td>
    <td class="tg-0pky">0.933</td>
    <td class="tg-0pky">0.0484</td>
    <td class="tg-0pky">0.0186</td>
  </tr>
  <tr>
    <td class="tg-0pky">Recovery</td>
    <td class="tg-0pky">0.6628</td>
    <td class="tg-0pky">0.2791</td>
    <td class="tg-0pky">0.0581</td>
  </tr>
  <tr>
    <td class="tg-0pky">Death</td>
    <td class="tg-0pky">0.4681</td>
    <td class="tg-0pky">0.1064</td>
    <td class="tg-0pky">0.4255</td>
  </tr>
</tbody>
</table>
<p></p> <i> **Rows Future State & Columns Current State** </i>
<p></p>
Conclusion from this Markov Chain is the probability of starting at an "Active" state and ending at "Recovery" state is 5.57%. This data was based on the India COVID-19 2020 peak.
<p></p>
Language: Python
<p></p>
<i>Last Updated: 8/20/20</i>
