# MatrixNTFScan

## Overview


Below shows the rarity and count of all the publicly known attributes for Niftys Matrix NFTs.  

There are two jupyter notebooks with one what scrapes the Nifty Matrix site and pulls the attributes per NTF then writes it out to a file.  The second then aggregates the files together into a dataframe then displays count and percentages

Please note this is a work in progress and I will update the attribute files periodically based on changes I see in on Nifty's site.  Also, this site is for informational purposes only.

My daughter and I are excited about 2022 and what this Matrix NFT journey will entail so hence the reason to discover this information 

Lastly, if you find this information useful then buy me a coffee @ vinceherrin.eth or like my matrix nft's here https://niftys.com/vinceherrin

Thanks for reading this and I hope this information is useful 

Rarity ranking calculation article [Ranking Rarity: Understanding Rarity Calculation Methods](https://raritytools.medium.com/ranking-rarity-understanding-rarity-calculation-methods-86ceaeb9b98c).


# Metrics

Please note that I'm using two different methods for calculating rarity with one using rarity-tools link above and the other is multiplication method 
</br>
</br>
## Addition Method:
</br>
Rarity Score for a Trait Value = 1 / (Number of Items with that Trait Value / Total Number of Items in Collection)

The total Rarity Score for an NFT is the sum of the Rarity Score of all of it’s trait values.
</br>
</br>
## Multiplication Method:
</br>
Rarity Score for a Trait Value = √√ (1 / (Number of Items with that Trait Value / Total Number of Items in Collection))
</br>
</br>


</br>

 # Contract: base (ckw5j7pqf0011g4731pvaj6gm)</br>
## Updated on 2022-01-23</br>
- [Sorted by Nifty ID using addition method](./data/ckw5j7pqf0011g4731pvaj6gm/full_a_sorted_niftyID.html) </br>
 - [Sorted by Ranking ID using addition method](./data/ckw5j7pqf0011g4731pvaj6gm/full_a_sorted_rankingID.html) </br>
 - [Sorted by Nifty ID using multiplication method](./data/ckw5j7pqf0011g4731pvaj6gm/full_m_sorted_niftyID.html) </br>
 - [Sorted by Ranking ID using multiplication method](./data/ckw5j7pqf0011g4731pvaj6gm/full_m_sorted_rankingID.html) </br>
 </br>

 ### Top 25 (rarity using addition)
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th style="min-width: 80px;">rankingID</th>
      <th style="min-width: 80px;">niftyID</th>
      <th style="min-width: 80px;">aRarity</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>11621</td>
      <td>1223.22</td>
    </tr>
    <tr>
      <td>2</td>
      <td>29795</td>
      <td>740.93</td>
    </tr>
    <tr>
      <td>3</td>
      <td>63467</td>
      <td>717.45</td>
    </tr>
    <tr>
      <td>4</td>
      <td>86373</td>
      <td>708.79</td>
    </tr>
    <tr>
      <td>5</td>
      <td>53836</td>
      <td>703.82</td>
    </tr>
    <tr>
      <td>6</td>
      <td>49110</td>
      <td>702.57</td>
    </tr>
    <tr>
      <td>7</td>
      <td>83101</td>
      <td>701.80</td>
    </tr>
    <tr>
      <td>8</td>
      <td>68770</td>
      <td>700.24</td>
    </tr>
    <tr>
      <td>9</td>
      <td>5135</td>
      <td>697.20</td>
    </tr>
    <tr>
      <td>10</td>
      <td>22889</td>
      <td>693.35</td>
    </tr>
    <tr>
      <td>11</td>
      <td>2942</td>
      <td>692.80</td>
    </tr>
    <tr>
      <td>12</td>
      <td>93728</td>
      <td>692.19</td>
    </tr>
    <tr>
      <td>13</td>
      <td>38379</td>
      <td>692.09</td>
    </tr>
    <tr>
      <td>14</td>
      <td>63775</td>
      <td>691.57</td>
    </tr>
    <tr>
      <td>15</td>
      <td>750</td>
      <td>690.34</td>
    </tr>
    <tr>
      <td>16</td>
      <td>17313</td>
      <td>569.48</td>
    </tr>
    <tr>
      <td>17</td>
      <td>81747</td>
      <td>558.55</td>
    </tr>
    <tr>
      <td>18</td>
      <td>47263</td>
      <td>543.14</td>
    </tr>
    <tr>
      <td>19</td>
      <td>39591</td>
      <td>533.73</td>
    </tr>
    <tr>
      <td>20</td>
      <td>62311</td>
      <td>528.43</td>
    </tr>
    <tr>
      <td>21</td>
      <td>44625</td>
      <td>528.06</td>
    </tr>
    <tr>
      <td>22</td>
      <td>37120</td>
      <td>527.77</td>
    </tr>
    <tr>
      <td>23</td>
      <td>52344</td>
      <td>527.69</td>
    </tr>
    <tr>
      <td>24</td>
      <td>59977</td>
      <td>527.54</td>
    </tr>
    <tr>
      <td>25</td>
      <td>74825</td>
      <td>527.28</td>
    </tr>
  </tbody>
</table></br>

### Bottom 25 (rarity using addition)

Please notice the reverse order  <table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th style="min-width: 80px;">rankingID</th>
      <th style="min-width: 80px;">niftyID</th>
      <th style="min-width: 80px;">aRarity</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>97619</td>
      <td>15504</td>
      <td>3.11</td>
    </tr>
    <tr>
      <td>97618</td>
      <td>29479</td>
      <td>3.15</td>
    </tr>
    <tr>
      <td>97617</td>
      <td>70646</td>
      <td>3.16</td>
    </tr>
    <tr>
      <td>97616</td>
      <td>88333</td>
      <td>3.19</td>
    </tr>
    <tr>
      <td>97615</td>
      <td>23442</td>
      <td>3.24</td>
    </tr>
    <tr>
      <td>97614</td>
      <td>471</td>
      <td>3.32</td>
    </tr>
    <tr>
      <td>97613</td>
      <td>12840</td>
      <td>3.32</td>
    </tr>
    <tr>
      <td>97612</td>
      <td>1189</td>
      <td>3.32</td>
    </tr>
    <tr>
      <td>97611</td>
      <td>31021</td>
      <td>3.33</td>
    </tr>
    <tr>
      <td>97610</td>
      <td>69174</td>
      <td>3.35</td>
    </tr>
    <tr>
      <td>97609</td>
      <td>22942</td>
      <td>3.39</td>
    </tr>
    <tr>
      <td>97608</td>
      <td>67863</td>
      <td>3.39</td>
    </tr>
    <tr>
      <td>97607</td>
      <td>57198</td>
      <td>3.40</td>
    </tr>
    <tr>
      <td>97606</td>
      <td>12197</td>
      <td>3.40</td>
    </tr>
    <tr>
      <td>97605</td>
      <td>94080</td>
      <td>3.41</td>
    </tr>
    <tr>
      <td>97604</td>
      <td>94640</td>
      <td>3.46</td>
    </tr>
    <tr>
      <td>97603</td>
      <td>17248</td>
      <td>3.46</td>
    </tr>
    <tr>
      <td>97602</td>
      <td>2654</td>
      <td>3.47</td>
    </tr>
    <tr>
      <td>97601</td>
      <td>53827</td>
      <td>3.48</td>
    </tr>
    <tr>
      <td>97600</td>
      <td>30386</td>
      <td>3.49</td>
    </tr>
    <tr>
      <td>97599</td>
      <td>84020</td>
      <td>3.50</td>
    </tr>
    <tr>
      <td>97598</td>
      <td>16765</td>
      <td>3.51</td>
    </tr>
    <tr>
      <td>97597</td>
      <td>89747</td>
      <td>3.53</td>
    </tr>
    <tr>
      <td>97596</td>
      <td>59463</td>
      <td>3.55</td>
    </tr>
    <tr>
      <td>97595</td>
      <td>38555</td>
      <td>3.56</td>
    </tr>
  </tbody>
</table></br>  </br>

 ### Top 25 (rarity using multiplication)
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th style="min-width: 80px;">rankingID</th>
      <th style="min-width: 80px;">niftyID</th>
      <th style="min-width: 80px;">mRarity</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>11621</td>
      <td>52.40</td>
    </tr>
    <tr>
      <td>2</td>
      <td>81747</td>
      <td>14.31</td>
    </tr>
    <tr>
      <td>3</td>
      <td>47263</td>
      <td>8.95</td>
    </tr>
    <tr>
      <td>4</td>
      <td>63467</td>
      <td>8.79</td>
    </tr>
    <tr>
      <td>5</td>
      <td>39591</td>
      <td>8.37</td>
    </tr>
    <tr>
      <td>6</td>
      <td>29795</td>
      <td>7.45</td>
    </tr>
    <tr>
      <td>7</td>
      <td>83101</td>
      <td>7.40</td>
    </tr>
    <tr>
      <td>8</td>
      <td>53836</td>
      <td>7.00</td>
    </tr>
    <tr>
      <td>9</td>
      <td>68770</td>
      <td>6.35</td>
    </tr>
    <tr>
      <td>10</td>
      <td>7732</td>
      <td>5.99</td>
    </tr>
    <tr>
      <td>11</td>
      <td>44625</td>
      <td>5.56</td>
    </tr>
    <tr>
      <td>12</td>
      <td>86373</td>
      <td>5.38</td>
    </tr>
    <tr>
      <td>13</td>
      <td>74825</td>
      <td>5.12</td>
    </tr>
    <tr>
      <td>14</td>
      <td>17313</td>
      <td>5.07</td>
    </tr>
    <tr>
      <td>15</td>
      <td>48223</td>
      <td>4.86</td>
    </tr>
    <tr>
      <td>16</td>
      <td>73014</td>
      <td>4.84</td>
    </tr>
    <tr>
      <td>17</td>
      <td>49110</td>
      <td>4.73</td>
    </tr>
    <tr>
      <td>18</td>
      <td>26019</td>
      <td>4.45</td>
    </tr>
    <tr>
      <td>19</td>
      <td>10200</td>
      <td>4.45</td>
    </tr>
    <tr>
      <td>20</td>
      <td>1367</td>
      <td>4.40</td>
    </tr>
    <tr>
      <td>21</td>
      <td>52344</td>
      <td>4.12</td>
    </tr>
    <tr>
      <td>22</td>
      <td>55033</td>
      <td>4.02</td>
    </tr>
    <tr>
      <td>23</td>
      <td>63775</td>
      <td>3.99</td>
    </tr>
    <tr>
      <td>24</td>
      <td>86692</td>
      <td>3.97</td>
    </tr>
    <tr>
      <td>25</td>
      <td>14982</td>
      <td>3.82</td>
    </tr>
  </tbody>
</table></br>

### Bottom 25 (rarity using multiplication)

Please notice the reverse order  <table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th style="min-width: 80px;">rankingID</th>
      <th style="min-width: 80px;">niftyID</th>
      <th style="min-width: 80px;">mRarity</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>97619</td>
      <td>80225</td>
      <td>0.23</td>
    </tr>
    <tr>
      <td>97618</td>
      <td>70407</td>
      <td>0.23</td>
    </tr>
    <tr>
      <td>97617</td>
      <td>50100</td>
      <td>0.25</td>
    </tr>
    <tr>
      <td>97616</td>
      <td>79571</td>
      <td>0.25</td>
    </tr>
    <tr>
      <td>97615</td>
      <td>86171</td>
      <td>0.25</td>
    </tr>
    <tr>
      <td>97614</td>
      <td>74475</td>
      <td>0.26</td>
    </tr>
    <tr>
      <td>97613</td>
      <td>21352</td>
      <td>0.26</td>
    </tr>
    <tr>
      <td>97612</td>
      <td>68900</td>
      <td>0.26</td>
    </tr>
    <tr>
      <td>97611</td>
      <td>32076</td>
      <td>0.26</td>
    </tr>
    <tr>
      <td>97610</td>
      <td>60396</td>
      <td>0.26</td>
    </tr>
    <tr>
      <td>97609</td>
      <td>73026</td>
      <td>0.26</td>
    </tr>
    <tr>
      <td>97608</td>
      <td>2847</td>
      <td>0.26</td>
    </tr>
    <tr>
      <td>97607</td>
      <td>34239</td>
      <td>0.26</td>
    </tr>
    <tr>
      <td>97606</td>
      <td>3151</td>
      <td>0.26</td>
    </tr>
    <tr>
      <td>97605</td>
      <td>11635</td>
      <td>0.26</td>
    </tr>
    <tr>
      <td>97604</td>
      <td>96302</td>
      <td>0.26</td>
    </tr>
    <tr>
      <td>97603</td>
      <td>6160</td>
      <td>0.26</td>
    </tr>
    <tr>
      <td>97602</td>
      <td>89145</td>
      <td>0.26</td>
    </tr>
    <tr>
      <td>97601</td>
      <td>44073</td>
      <td>0.27</td>
    </tr>
    <tr>
      <td>97600</td>
      <td>20144</td>
      <td>0.27</td>
    </tr>
    <tr>
      <td>97599</td>
      <td>38057</td>
      <td>0.27</td>
    </tr>
    <tr>
      <td>97598</td>
      <td>73450</td>
      <td>0.27</td>
    </tr>
    <tr>
      <td>97597</td>
      <td>36438</td>
      <td>0.27</td>
    </tr>
    <tr>
      <td>97596</td>
      <td>78555</td>
      <td>0.27</td>
    </tr>
    <tr>
      <td>97595</td>
      <td>36450</td>
      <td>0.27</td>
    </tr>
  </tbody>
</table></br>  </br>

 # Contract: matrix-red-contract</br>
## Updated on 2022-01-23</br>
- [Sorted by Nifty ID using addition method](./data/matrix-red-contract/full_a_sorted_niftyID.html) </br>
 - [Sorted by Ranking ID using addition method](./data/matrix-red-contract/full_a_sorted_rankingID.html) </br>
 - [Sorted by Nifty ID using multiplication method](./data/matrix-red-contract/full_m_sorted_niftyID.html) </br>
 - [Sorted by Ranking ID using multiplication method](./data/matrix-red-contract/full_m_sorted_rankingID.html) </br>
 </br>

 ### Top 25 (rarity using addition)
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th style="min-width: 80px;">rankingID</th>
      <th style="min-width: 80px;">niftyID</th>
      <th style="min-width: 80px;">aRarity</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>5090</td>
      <td>10800.54</td>
    </tr>
    <tr>
      <td>2</td>
      <td>96220</td>
      <td>10798.65</td>
    </tr>
    <tr>
      <td>3</td>
      <td>81743</td>
      <td>10730.83</td>
    </tr>
    <tr>
      <td>4</td>
      <td>41904</td>
      <td>10725.47</td>
    </tr>
    <tr>
      <td>5</td>
      <td>52958</td>
      <td>10717.62</td>
    </tr>
    <tr>
      <td>6</td>
      <td>84328</td>
      <td>10707.18</td>
    </tr>
    <tr>
      <td>7</td>
      <td>61440</td>
      <td>10693.90</td>
    </tr>
    <tr>
      <td>8</td>
      <td>51080</td>
      <td>10690.63</td>
    </tr>
    <tr>
      <td>9</td>
      <td>86889</td>
      <td>10689.20</td>
    </tr>
    <tr>
      <td>10</td>
      <td>86839</td>
      <td>10676.32</td>
    </tr>
    <tr>
      <td>11</td>
      <td>72688</td>
      <td>10673.99</td>
    </tr>
    <tr>
      <td>12</td>
      <td>88042</td>
      <td>10650.99</td>
    </tr>
    <tr>
      <td>13</td>
      <td>51216</td>
      <td>10649.42</td>
    </tr>
    <tr>
      <td>14</td>
      <td>74323</td>
      <td>10640.39</td>
    </tr>
    <tr>
      <td>15</td>
      <td>12530</td>
      <td>10639.77</td>
    </tr>
    <tr>
      <td>16</td>
      <td>31653</td>
      <td>10636.24</td>
    </tr>
    <tr>
      <td>17</td>
      <td>41240</td>
      <td>10629.12</td>
    </tr>
    <tr>
      <td>18</td>
      <td>89892</td>
      <td>10623.39</td>
    </tr>
    <tr>
      <td>19</td>
      <td>80020</td>
      <td>10621.80</td>
    </tr>
    <tr>
      <td>20</td>
      <td>61378</td>
      <td>10614.74</td>
    </tr>
    <tr>
      <td>21</td>
      <td>39160</td>
      <td>10610.43</td>
    </tr>
    <tr>
      <td>22</td>
      <td>69853</td>
      <td>10602.73</td>
    </tr>
    <tr>
      <td>23</td>
      <td>1373</td>
      <td>10602.64</td>
    </tr>
    <tr>
      <td>24</td>
      <td>81243</td>
      <td>10601.14</td>
    </tr>
    <tr>
      <td>25</td>
      <td>18763</td>
      <td>10599.15</td>
    </tr>
  </tbody>
</table></br>

### Bottom 25 (rarity using addition)

Please notice the reverse order  <table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th style="min-width: 80px;">rankingID</th>
      <th style="min-width: 80px;">niftyID</th>
      <th style="min-width: 80px;">aRarity</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>40779</td>
      <td>133</td>
      <td>33.44</td>
    </tr>
    <tr>
      <td>40778</td>
      <td>11569</td>
      <td>33.70</td>
    </tr>
    <tr>
      <td>40777</td>
      <td>24874</td>
      <td>35.77</td>
    </tr>
    <tr>
      <td>40776</td>
      <td>21376</td>
      <td>37.22</td>
    </tr>
    <tr>
      <td>40775</td>
      <td>87275</td>
      <td>37.37</td>
    </tr>
    <tr>
      <td>40774</td>
      <td>51412</td>
      <td>37.61</td>
    </tr>
    <tr>
      <td>40773</td>
      <td>80475</td>
      <td>37.76</td>
    </tr>
    <tr>
      <td>40772</td>
      <td>55061</td>
      <td>38.25</td>
    </tr>
    <tr>
      <td>40771</td>
      <td>96113</td>
      <td>38.27</td>
    </tr>
    <tr>
      <td>40770</td>
      <td>77362</td>
      <td>38.27</td>
    </tr>
    <tr>
      <td>40769</td>
      <td>83276</td>
      <td>38.54</td>
    </tr>
    <tr>
      <td>40768</td>
      <td>90304</td>
      <td>39.17</td>
    </tr>
    <tr>
      <td>40767</td>
      <td>4367</td>
      <td>39.23</td>
    </tr>
    <tr>
      <td>40766</td>
      <td>57932</td>
      <td>39.29</td>
    </tr>
    <tr>
      <td>40765</td>
      <td>20534</td>
      <td>39.29</td>
    </tr>
    <tr>
      <td>40764</td>
      <td>65129</td>
      <td>39.51</td>
    </tr>
    <tr>
      <td>40763</td>
      <td>86248</td>
      <td>39.61</td>
    </tr>
    <tr>
      <td>40762</td>
      <td>31178</td>
      <td>39.88</td>
    </tr>
    <tr>
      <td>40761</td>
      <td>47364</td>
      <td>39.93</td>
    </tr>
    <tr>
      <td>40760</td>
      <td>27989</td>
      <td>40.86</td>
    </tr>
    <tr>
      <td>40759</td>
      <td>67644</td>
      <td>41.12</td>
    </tr>
    <tr>
      <td>40758</td>
      <td>7959</td>
      <td>41.31</td>
    </tr>
    <tr>
      <td>40757</td>
      <td>11909</td>
      <td>41.40</td>
    </tr>
    <tr>
      <td>40756</td>
      <td>48954</td>
      <td>41.44</td>
    </tr>
    <tr>
      <td>40755</td>
      <td>11216</td>
      <td>41.52</td>
    </tr>
  </tbody>
</table></br>  </br>

 ### Top 25 (rarity using multiplication)
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th style="min-width: 80px;">rankingID</th>
      <th style="min-width: 80px;">niftyID</th>
      <th style="min-width: 80px;">mRarity</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>71216</td>
      <td>492234.57</td>
    </tr>
    <tr>
      <td>2</td>
      <td>19706</td>
      <td>273102.95</td>
    </tr>
    <tr>
      <td>3</td>
      <td>88736</td>
      <td>210568.47</td>
    </tr>
    <tr>
      <td>4</td>
      <td>12012</td>
      <td>145673.71</td>
    </tr>
    <tr>
      <td>5</td>
      <td>21728</td>
      <td>135754.43</td>
    </tr>
    <tr>
      <td>6</td>
      <td>12682</td>
      <td>132229.64</td>
    </tr>
    <tr>
      <td>7</td>
      <td>48088</td>
      <td>112938.30</td>
    </tr>
    <tr>
      <td>8</td>
      <td>11092</td>
      <td>93521.87</td>
    </tr>
    <tr>
      <td>9</td>
      <td>54604</td>
      <td>78848.61</td>
    </tr>
    <tr>
      <td>10</td>
      <td>66091</td>
      <td>64336.68</td>
    </tr>
    <tr>
      <td>11</td>
      <td>34221</td>
      <td>63928.83</td>
    </tr>
    <tr>
      <td>12</td>
      <td>73288</td>
      <td>56943.59</td>
    </tr>
    <tr>
      <td>13</td>
      <td>41685</td>
      <td>56710.42</td>
    </tr>
    <tr>
      <td>14</td>
      <td>86400</td>
      <td>56092.67</td>
    </tr>
    <tr>
      <td>15</td>
      <td>65611</td>
      <td>56005.65</td>
    </tr>
    <tr>
      <td>16</td>
      <td>66344</td>
      <td>52914.51</td>
    </tr>
    <tr>
      <td>17</td>
      <td>506</td>
      <td>50544.26</td>
    </tr>
    <tr>
      <td>18</td>
      <td>69107</td>
      <td>47295.44</td>
    </tr>
    <tr>
      <td>19</td>
      <td>43625</td>
      <td>46749.43</td>
    </tr>
    <tr>
      <td>20</td>
      <td>66661</td>
      <td>46425.01</td>
    </tr>
    <tr>
      <td>21</td>
      <td>81249</td>
      <td>46182.62</td>
    </tr>
    <tr>
      <td>22</td>
      <td>63363</td>
      <td>45905.25</td>
    </tr>
    <tr>
      <td>23</td>
      <td>75064</td>
      <td>43765.84</td>
    </tr>
    <tr>
      <td>24</td>
      <td>43562</td>
      <td>43693.48</td>
    </tr>
    <tr>
      <td>25</td>
      <td>71947</td>
      <td>43359.86</td>
    </tr>
  </tbody>
</table></br>

### Bottom 25 (rarity using multiplication)

Please notice the reverse order  <table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th style="min-width: 80px;">rankingID</th>
      <th style="min-width: 80px;">niftyID</th>
      <th style="min-width: 80px;">mRarity</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>40779</td>
      <td>21376</td>
      <td>0.93</td>
    </tr>
    <tr>
      <td>40778</td>
      <td>11569</td>
      <td>0.97</td>
    </tr>
    <tr>
      <td>40777</td>
      <td>133</td>
      <td>1.06</td>
    </tr>
    <tr>
      <td>40776</td>
      <td>27989</td>
      <td>1.08</td>
    </tr>
    <tr>
      <td>40775</td>
      <td>87275</td>
      <td>1.09</td>
    </tr>
    <tr>
      <td>40774</td>
      <td>96113</td>
      <td>1.18</td>
    </tr>
    <tr>
      <td>40773</td>
      <td>83460</td>
      <td>1.19</td>
    </tr>
    <tr>
      <td>40772</td>
      <td>80475</td>
      <td>1.23</td>
    </tr>
    <tr>
      <td>40771</td>
      <td>24874</td>
      <td>1.28</td>
    </tr>
    <tr>
      <td>40770</td>
      <td>40952</td>
      <td>1.32</td>
    </tr>
    <tr>
      <td>40769</td>
      <td>28851</td>
      <td>1.32</td>
    </tr>
    <tr>
      <td>40768</td>
      <td>57932</td>
      <td>1.39</td>
    </tr>
    <tr>
      <td>40767</td>
      <td>20534</td>
      <td>1.40</td>
    </tr>
    <tr>
      <td>40766</td>
      <td>438</td>
      <td>1.40</td>
    </tr>
    <tr>
      <td>40765</td>
      <td>20320</td>
      <td>1.45</td>
    </tr>
    <tr>
      <td>40764</td>
      <td>77362</td>
      <td>1.46</td>
    </tr>
    <tr>
      <td>40763</td>
      <td>79071</td>
      <td>1.46</td>
    </tr>
    <tr>
      <td>40762</td>
      <td>37222</td>
      <td>1.47</td>
    </tr>
    <tr>
      <td>40761</td>
      <td>44695</td>
      <td>1.48</td>
    </tr>
    <tr>
      <td>40760</td>
      <td>48006</td>
      <td>1.50</td>
    </tr>
    <tr>
      <td>40759</td>
      <td>79469</td>
      <td>1.53</td>
    </tr>
    <tr>
      <td>40758</td>
      <td>17343</td>
      <td>1.53</td>
    </tr>
    <tr>
      <td>40757</td>
      <td>73327</td>
      <td>1.55</td>
    </tr>
    <tr>
      <td>40756</td>
      <td>83276</td>
      <td>1.56</td>
    </tr>
    <tr>
      <td>40755</td>
      <td>55061</td>
      <td>1.64</td>
    </tr>
  </tbody>
</table></br>  </br>

 # Contract: matrix-blue-contract</br>
## Updated on 2022-01-23</br>
- [Sorted by Nifty ID using addition method](./data/matrix-blue-contract/full_a_sorted_niftyID.html) </br>
 - [Sorted by Ranking ID using addition method](./data/matrix-blue-contract/full_a_sorted_rankingID.html) </br>
 - [Sorted by Nifty ID using multiplication method](./data/matrix-blue-contract/full_m_sorted_niftyID.html) </br>
 - [Sorted by Ranking ID using multiplication method](./data/matrix-blue-contract/full_m_sorted_rankingID.html) </br>
 </br>

 ### Top 25 (rarity using addition)
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th style="min-width: 80px;">rankingID</th>
      <th style="min-width: 80px;">niftyID</th>
      <th style="min-width: 80px;">aRarity</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>47036</td>
      <td>21885.63</td>
    </tr>
    <tr>
      <td>2</td>
      <td>55898</td>
      <td>16087.96</td>
    </tr>
    <tr>
      <td>3</td>
      <td>55194</td>
      <td>16013.67</td>
    </tr>
    <tr>
      <td>4</td>
      <td>13009</td>
      <td>12828.34</td>
    </tr>
    <tr>
      <td>5</td>
      <td>71381</td>
      <td>10977.52</td>
    </tr>
    <tr>
      <td>6</td>
      <td>27567</td>
      <td>10918.57</td>
    </tr>
    <tr>
      <td>7</td>
      <td>79979</td>
      <td>10795.71</td>
    </tr>
    <tr>
      <td>8</td>
      <td>13626</td>
      <td>7684.61</td>
    </tr>
    <tr>
      <td>9</td>
      <td>76582</td>
      <td>7268.52</td>
    </tr>
    <tr>
      <td>10</td>
      <td>45395</td>
      <td>7239.03</td>
    </tr>
    <tr>
      <td>11</td>
      <td>11621</td>
      <td>5513.61</td>
    </tr>
    <tr>
      <td>12</td>
      <td>7510</td>
      <td>4611.70</td>
    </tr>
    <tr>
      <td>13</td>
      <td>68164</td>
      <td>4576.09</td>
    </tr>
    <tr>
      <td>14</td>
      <td>74966</td>
      <td>4527.06</td>
    </tr>
    <tr>
      <td>15</td>
      <td>8779</td>
      <td>4412.25</td>
    </tr>
    <tr>
      <td>16</td>
      <td>47495</td>
      <td>4411.57</td>
    </tr>
    <tr>
      <td>17</td>
      <td>71447</td>
      <td>4371.73</td>
    </tr>
    <tr>
      <td>18</td>
      <td>55079</td>
      <td>4035.50</td>
    </tr>
    <tr>
      <td>19</td>
      <td>60553</td>
      <td>3859.93</td>
    </tr>
    <tr>
      <td>20</td>
      <td>92345</td>
      <td>3721.82</td>
    </tr>
    <tr>
      <td>21</td>
      <td>33754</td>
      <td>3705.34</td>
    </tr>
    <tr>
      <td>22</td>
      <td>62291</td>
      <td>3687.88</td>
    </tr>
    <tr>
      <td>23</td>
      <td>59354</td>
      <td>3652.02</td>
    </tr>
    <tr>
      <td>24</td>
      <td>83101</td>
      <td>3335.25</td>
    </tr>
    <tr>
      <td>25</td>
      <td>77787</td>
      <td>3124.21</td>
    </tr>
  </tbody>
</table></br>

### Bottom 25 (rarity using addition)

Please notice the reverse order  <table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th style="min-width: 80px;">rankingID</th>
      <th style="min-width: 80px;">niftyID</th>
      <th style="min-width: 80px;">aRarity</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>10499</td>
      <td>55147</td>
      <td>126.27</td>
    </tr>
    <tr>
      <td>10498</td>
      <td>9710</td>
      <td>131.53</td>
    </tr>
    <tr>
      <td>10497</td>
      <td>67484</td>
      <td>138.44</td>
    </tr>
    <tr>
      <td>10496</td>
      <td>57833</td>
      <td>139.57</td>
    </tr>
    <tr>
      <td>10495</td>
      <td>3854</td>
      <td>142.27</td>
    </tr>
    <tr>
      <td>10494</td>
      <td>31010</td>
      <td>144.74</td>
    </tr>
    <tr>
      <td>10493</td>
      <td>89282</td>
      <td>145.13</td>
    </tr>
    <tr>
      <td>10492</td>
      <td>37366</td>
      <td>145.40</td>
    </tr>
    <tr>
      <td>10491</td>
      <td>71129</td>
      <td>147.10</td>
    </tr>
    <tr>
      <td>10490</td>
      <td>74676</td>
      <td>147.43</td>
    </tr>
    <tr>
      <td>10489</td>
      <td>72078</td>
      <td>147.78</td>
    </tr>
    <tr>
      <td>10488</td>
      <td>9525</td>
      <td>148.16</td>
    </tr>
    <tr>
      <td>10487</td>
      <td>69477</td>
      <td>148.90</td>
    </tr>
    <tr>
      <td>10486</td>
      <td>31223</td>
      <td>148.99</td>
    </tr>
    <tr>
      <td>10485</td>
      <td>44241</td>
      <td>150.44</td>
    </tr>
    <tr>
      <td>10484</td>
      <td>74923</td>
      <td>151.43</td>
    </tr>
    <tr>
      <td>10483</td>
      <td>84109</td>
      <td>151.77</td>
    </tr>
    <tr>
      <td>10482</td>
      <td>3057</td>
      <td>152.23</td>
    </tr>
    <tr>
      <td>10481</td>
      <td>40873</td>
      <td>152.25</td>
    </tr>
    <tr>
      <td>10480</td>
      <td>84016</td>
      <td>152.27</td>
    </tr>
    <tr>
      <td>10479</td>
      <td>76584</td>
      <td>152.28</td>
    </tr>
    <tr>
      <td>10478</td>
      <td>62728</td>
      <td>152.30</td>
    </tr>
    <tr>
      <td>10477</td>
      <td>78351</td>
      <td>152.45</td>
    </tr>
    <tr>
      <td>10476</td>
      <td>56633</td>
      <td>152.64</td>
    </tr>
    <tr>
      <td>10475</td>
      <td>18412</td>
      <td>152.84</td>
    </tr>
  </tbody>
</table></br>  </br>

 ### Top 25 (rarity using multiplication)
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th style="min-width: 80px;">rankingID</th>
      <th style="min-width: 80px;">niftyID</th>
      <th style="min-width: 80px;">mRarity</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>17601</td>
      <td>58679197.10</td>
    </tr>
    <tr>
      <td>2</td>
      <td>47036</td>
      <td>47793907.47</td>
    </tr>
    <tr>
      <td>3</td>
      <td>21677</td>
      <td>42155949.75</td>
    </tr>
    <tr>
      <td>4</td>
      <td>55898</td>
      <td>21254946.90</td>
    </tr>
    <tr>
      <td>5</td>
      <td>9260</td>
      <td>20209640.31</td>
    </tr>
    <tr>
      <td>6</td>
      <td>90190</td>
      <td>18587014.45</td>
    </tr>
    <tr>
      <td>7</td>
      <td>32839</td>
      <td>16397978.02</td>
    </tr>
    <tr>
      <td>8</td>
      <td>1319</td>
      <td>16047829.15</td>
    </tr>
    <tr>
      <td>9</td>
      <td>21133</td>
      <td>11430020.23</td>
    </tr>
    <tr>
      <td>10</td>
      <td>1884</td>
      <td>11414043.20</td>
    </tr>
    <tr>
      <td>11</td>
      <td>77787</td>
      <td>11070706.26</td>
    </tr>
    <tr>
      <td>12</td>
      <td>16294</td>
      <td>10828664.11</td>
    </tr>
    <tr>
      <td>13</td>
      <td>79308</td>
      <td>10570553.17</td>
    </tr>
    <tr>
      <td>14</td>
      <td>21454</td>
      <td>10543351.57</td>
    </tr>
    <tr>
      <td>15</td>
      <td>71381</td>
      <td>10410283.85</td>
    </tr>
    <tr>
      <td>16</td>
      <td>17085</td>
      <td>10048131.93</td>
    </tr>
    <tr>
      <td>17</td>
      <td>95783</td>
      <td>9756820.23</td>
    </tr>
    <tr>
      <td>18</td>
      <td>95331</td>
      <td>9648288.58</td>
    </tr>
    <tr>
      <td>19</td>
      <td>21218</td>
      <td>9511706.83</td>
    </tr>
    <tr>
      <td>20</td>
      <td>66967</td>
      <td>9300305.32</td>
    </tr>
    <tr>
      <td>21</td>
      <td>60553</td>
      <td>9298972.61</td>
    </tr>
    <tr>
      <td>22</td>
      <td>92398</td>
      <td>9155730.04</td>
    </tr>
    <tr>
      <td>23</td>
      <td>3651</td>
      <td>8987508.04</td>
    </tr>
    <tr>
      <td>24</td>
      <td>48839</td>
      <td>8367831.65</td>
    </tr>
    <tr>
      <td>25</td>
      <td>18717</td>
      <td>8077794.94</td>
    </tr>
  </tbody>
</table></br>

### Bottom 25 (rarity using multiplication)

Please notice the reverse order  <table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th style="min-width: 80px;">rankingID</th>
      <th style="min-width: 80px;">niftyID</th>
      <th style="min-width: 80px;">mRarity</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>10499</td>
      <td>57833</td>
      <td>3137.23</td>
    </tr>
    <tr>
      <td>10498</td>
      <td>55147</td>
      <td>3482.30</td>
    </tr>
    <tr>
      <td>10497</td>
      <td>9710</td>
      <td>4227.43</td>
    </tr>
    <tr>
      <td>10496</td>
      <td>18412</td>
      <td>4281.96</td>
    </tr>
    <tr>
      <td>10495</td>
      <td>3434</td>
      <td>4592.56</td>
    </tr>
    <tr>
      <td>10494</td>
      <td>23916</td>
      <td>4664.80</td>
    </tr>
    <tr>
      <td>10493</td>
      <td>67484</td>
      <td>4871.06</td>
    </tr>
    <tr>
      <td>10492</td>
      <td>44241</td>
      <td>5097.70</td>
    </tr>
    <tr>
      <td>10491</td>
      <td>33173</td>
      <td>5150.71</td>
    </tr>
    <tr>
      <td>10490</td>
      <td>12216</td>
      <td>5154.91</td>
    </tr>
    <tr>
      <td>10489</td>
      <td>71389</td>
      <td>5179.78</td>
    </tr>
    <tr>
      <td>10488</td>
      <td>87903</td>
      <td>5183.94</td>
    </tr>
    <tr>
      <td>10487</td>
      <td>20700</td>
      <td>5291.03</td>
    </tr>
    <tr>
      <td>10486</td>
      <td>37366</td>
      <td>5516.68</td>
    </tr>
    <tr>
      <td>10485</td>
      <td>31010</td>
      <td>5708.33</td>
    </tr>
    <tr>
      <td>10484</td>
      <td>6524</td>
      <td>5923.46</td>
    </tr>
    <tr>
      <td>10483</td>
      <td>75314</td>
      <td>5979.52</td>
    </tr>
    <tr>
      <td>10482</td>
      <td>5220</td>
      <td>6035.91</td>
    </tr>
    <tr>
      <td>10481</td>
      <td>2654</td>
      <td>6061.52</td>
    </tr>
    <tr>
      <td>10480</td>
      <td>67896</td>
      <td>6256.41</td>
    </tr>
    <tr>
      <td>10479</td>
      <td>26654</td>
      <td>6419.13</td>
    </tr>
    <tr>
      <td>10478</td>
      <td>70405</td>
      <td>6442.27</td>
    </tr>
    <tr>
      <td>10477</td>
      <td>9525</td>
      <td>6442.30</td>
    </tr>
    <tr>
      <td>10476</td>
      <td>43507</td>
      <td>6466.21</td>
    </tr>
    <tr>
      <td>10475</td>
      <td>78605</td>
      <td>6551.20</td>
    </tr>
  </tbody>
</table></br>  