# SugarCane

This section presents the classification results for diseased sugarcane leaves. Based on the number of experiments conducted, we observe that the performance metrics do not follow a normal distribution, as verified by quantile-quantile (QQ) plots comparing the distribution of metrics for each model across the training, validation, and test sets. Additionally, tables summarize the metrics results for all models across all data sets, using the median as a measure of central tendency and the interquartile range (IQR) as a measure of dispersion.

## Table of contents.
1. [QQPLOTS](#qqplot-normalidad)
    1. [Accuracy](#ACCURACY%20FOTO)
    2. [Micro avg precision](#MICRO%20PRECISION)
    3. [Micro avg recall](#MICRO%20RECALL)
    4. [Micro avg f1](#MICRO%20F1)
    5. [Macro avg precision](#MACRO%20PRECISION)
    3. [Macro avg recall](#MACRO%20RECALL)
    4. [Macro avg f1](#MACRO%20F1)
2. [TABLES](#tablas)
    1. [Accuracy](#ACCURACY)
    2. [Micro avg precision](#MI%20PRECISION)
    3. [Micro avg recall](#MI%20RECALL)
    4. [Micro avg f1](#MI%20F1)
    5. [Macro avg precision](#MA%20PRECISION)
    3. [Macro avg recall](#MA%20RECALL)
    4. [Macro avg f1](#MA%20F1)

##  QQ plot Normality

### Accuracy <a name="ACCURACY FOTO"></a>
![qqplots](QQPLOT%20MODELS/Accuracy.png)

### Micro Avg Precision <a name="MICRO PRECISION"></a>
![qqplots](QQPLOT%20MODELS/Micro%20avg%20precision.png)

### Micro Avg Recall <a name="MICRO RECALL"></a>
![qqplots](QQPLOT%20MODELS/Micro%20avg%20recall.png)

### Micro Avg F1 <a name="MICRO F1"></a>
![qqplots](QQPLOT%20MODELS/Micro%20avg%20f1.png)

### Macro Avg Precision <a name="MACRO PRECISION"></a>
![qqplots](QQPLOT%20MODELS/Macro%20avg%20precision.png)

### Macro Avg Recall <a name="MACRO RECALL"></a>
![qqplots](QQPLOT%20MODELS/Macro%20avg%20recall.png)

### Macro Avg F1 <a name="MACRO F1"></a>
![qqplots](QQPLOT%20MODELS/Macro%20avg%20f1.png)

## Tables

### Accuracy <a name="ACCURACY"></a>
<table>
  <thead>
  <tr>
    <th colspan="7">Accuracy</th>
  </tr>
   <tr>
    <td rowspan="2"><b>Models</b></td>
    <td colspan="2"><b>Training set</b></td>
    <td colspan="2"><b>Validation set</b></td>
    <td colspan="2"><b>Test set</b></td>
  </tr>
  <tr>
    <td>&#x0078;&#x0303;</td>
    <td>IQR</td>
    <td>&#x0078;&#x0303;</td>
    <td>IQR</td>
    <td>&#x0078;&#x0303;</td>
    <td>IQR</td>
  </tr>
</thead>
<tbody>
    <tr>
        <td>1</td>
        <td>0.9965</td>
        <td>0.0052</td>
        <td>0.9792</td>
        <td>0.0096</td>
        <td>0.9773</td>
        <td>0.0100 </td>
    </tr>
    <tr>
        <td>2</td>
        <td>0.9723</td>
        <td>0.0280</td>
        <td>0.9500</td>
        <td>0.0317</td>
        <td>0.9447</td>
        <td>0.0333 </td>
    </tr>
    <tr>
        <td>3</td>
        <td>0.8779</td>
        <td>0.1480</td>
        <td>0.8500</td>
        <td>0.1313</td>
        <td>0.8447</td>
        <td>0.1397 </td>
    </tr>
    <tr>
        <td>4</td>
        <td>0.9608</td>
        <td>0.0310</td>
        <td>0.9125</td>
        <td>0.0296</td>
        <td>0.9120</td>
        <td>0.0253 </td>
    </tr>
    <tr>
        <td>5</td>
        <td>0.9044</td>
        <td>0.0533</td>
        <td>0.8775</td>
        <td>0.0575</td>
        <td>0.8760</td>
        <td>0.0567 </td>
    </tr>
    <tr>
        <td>6</td>
        <td>0.8858</td>
        <td>0.1024</td>
        <td>0.8508</td>
        <td>0.0938</td>
        <td>0.8527</td>
        <td>0.1013 </td>
    </tr>
</tbody>
</table>

### Micro Avg Precision <a name="MI PRECISION"></a>
<table>
  <thead>
  <tr>
    <th colspan="7">Micro Avg Precision</th>
  </tr>
   <tr>
    <td rowspan="2"><b>Models</b></td>
    <td colspan="2"><b>Training set</b></td>
    <td colspan="2"><b>Validation set</b></td>
    <td colspan="2"><b>Test set</b></td>
  </tr>
  <tr>
    <td>&#x0078;&#x0303;</td>
    <td>IQR</td>
    <td>&#x0078;&#x0303;</td>
    <td>IQR</td>
    <td>&#x0078;&#x0303;</td>
    <td>IQR</td>
  </tr>
</thead>
<tbody>
<tr>
        <td>1</td>
        <td>0.9965</td>
        <td>0.0052</td>
        <td>0.9792</td>
        <td>0.0096</td>
        <td>0.9773</td>
        <td>0.0100 </td>
    </tr>
    <tr>
        <td>2</td>
        <td>0.9723</td>
        <td>0.0280</td>
        <td>0.9500</td>
        <td>0.0317</td>
        <td>0.9447</td>
        <td>0.0333 </td>
    </tr>
    <tr>
        <td>3</td>
        <td>0.8779</td>
        <td>0.1480</td>
        <td>0.8500</td>
        <td>0.1313</td>
        <td>0.8447</td>
        <td>0.1397 </td>
    </tr>
    <tr>
        <td>4</td>
        <td>0.9608</td>
        <td>0.0310</td>
        <td>0.9125</td>
        <td>0.0296</td>
        <td>0.9120</td>
        <td>0.0253 </td>
    </tr>
    <tr>
        <td>5</td>
        <td>0.9044</td>
        <td>0.0533</td>
        <td>0.8775</td>
        <td>0.0575</td>
        <td>0.8760</td>
        <td>0.0567 </td>
    </tr>
    <tr>
        <td>6</td>
        <td>0.8858</td>
        <td>0.1024</td>
        <td>0.8508</td>
        <td>0.0938</td>
        <td>0.8527</td>
        <td>0.1013 </td>
    </tr>
</tbody>
</table>

### Micro Avg Recall <a name="MI RECALL"></a>
<table>
  <thead>
  <tr>
    <th colspan="7">Micro Avg Recall</th>
  </tr>
   <tr>
    <td rowspan="2"><b>Models</b></td>
    <td colspan="2"><b>Training set</b></td>
    <td colspan="2"><b>Validation set</b></td>
    <td colspan="2"><b>Test set</b></td>
  </tr>
  <tr>
    <td>&#x0078;&#x0303;</td>
    <td>IQR</td>
    <td>&#x0078;&#x0303;</td>
    <td>IQR</td>
    <td>&#x0078;&#x0303;</td>
    <td>IQR</td>
  </tr>
</thead>
<tbody>
<tr>
        <td>1</td>
        <td>0.9965</td>
        <td>0.0052</td>
        <td>0.9792</td>
        <td>0.0096</td>
        <td>0.9773</td>
        <td>0.0100 </td>
    </tr>
    <tr>
        <td>2</td>
        <td>0.9723</td>
        <td>0.0280</td>
        <td>0.9500</td>
        <td>0.0317</td>
        <td>0.9447</td>
        <td>0.0333 </td>
    </tr>
    <tr>
        <td>3</td>
        <td>0.8779</td>
        <td>0.1480</td>
        <td>0.8500</td>
        <td>0.1313</td>
        <td>0.8447</td>
        <td>0.1397 </td>
    </tr>
    <tr>
        <td>4</td>
        <td>0.9608</td>
        <td>0.0310</td>
        <td>0.9125</td>
        <td>0.0296</td>
        <td>0.9120</td>
        <td>0.0253 </td>
    </tr>
    <tr>
        <td>5</td>
        <td>0.9044</td>
        <td>0.0533</td>
        <td>0.8775</td>
        <td>0.0575</td>
        <td>0.8760</td>
        <td>0.0567 </td>
    </tr>
    <tr>
        <td>6</td>
        <td>0.8858</td>
        <td>0.1024</td>
        <td>0.8508</td>
        <td>0.0938</td>
        <td>0.8527</td>
        <td>0.1013 </td>
    </tr>
</tbody>
</table>

### Micro Avg F1 <a name="MI F1"></a>
<table>
  <thead>
  <tr>
    <th colspan="7">Micro Avg F1</th>
  </tr>
   <tr>
    <td rowspan="2"><b>Models</b></td>
    <td colspan="2"><b>Training set</b></td>
    <td colspan="2"><b>Validation set</b></td>
    <td colspan="2"><b>Test set</b></td>
  </tr>
  <tr>
    <td>&#x0078;&#x0303;</td>
    <td>IQR</td>
    <td>&#x0078;&#x0303;</td>
    <td>IQR</td>
    <td>&#x0078;&#x0303;</td>
    <td>IQR</td>
  </tr>
</thead>
<tbody>
<tr>
        <td>1</td>
        <td>0.9965</td>
        <td>0.0052</td>
        <td>0.9792</td>
        <td>0.0096</td>
        <td>0.9773</td>
        <td>0.0100 </td>
    </tr>
    <tr>
        <td>2</td>
        <td>0.9723</td>
        <td>0.0280</td>
        <td>0.9500</td>
        <td>0.0317</td>
        <td>0.9447</td>
        <td>0.0333 </td>
    </tr>
    <tr>
        <td>3</td>
        <td>0.8779</td>
        <td>0.1480</td>
        <td>0.8500</td>
        <td>0.1313</td>
        <td>0.8447</td>
        <td>0.1397 </td>
    </tr>
    <tr>
        <td>4</td>
        <td>0.9608</td>
        <td>0.0310</td>
        <td>0.9125</td>
        <td>0.0296</td>
        <td>0.9120</td>
        <td>0.0253 </td>
    </tr>
    <tr>
        <td>5</td>
        <td>0.9044</td>
        <td>0.0533</td>
        <td>0.8775</td>
        <td>0.0575</td>
        <td>0.8760</td>
        <td>0.0567 </td>
    </tr>
    <tr>
        <td>6</td>
        <td>0.8858</td>
        <td>0.1024</td>
        <td>0.8508</td>
        <td>0.0938</td>
        <td>0.8527</td>
        <td>0.1013 </td>
    </tr>
</tbody>
</table>

### Macro Avg Precision <a name="MA PRECISION"></a>
<table>
  <thead>
  <tr>
    <th colspan="7">Macro Avg Precision</th>
  </tr>
   <tr>
    <td rowspan="2"><b>Models</b></td>
    <td colspan="2"><b>Training set</b></td>
    <td colspan="2"><b>Validation set</b></td>
    <td colspan="2"><b>Test set</b></td>
  </tr>
  <tr>
    <td>&#x0078;&#x0303;</td>
    <td>IQR</td>
    <td>&#x0078;&#x0303;</td>
    <td>IQR</td>
    <td>&#x0078;&#x0303;</td>
    <td>IQR</td>
  </tr>
</thead>
<tbody>
    <tr>
        <td>1</td>
        <td>0.9965</td>
        <td>0.0050</td>
        <td>0.9796</td>
        <td>0.0087</td>
        <td>0.9780</td>
        <td>0.0087 </td>
    </tr>
    <tr>
        <td>2</td>
        <td>0.9733</td>
        <td>0.0247</td>
        <td>0.9525</td>
        <td>0.0288</td>
        <td>0.9477</td>
        <td>0.0275 </td>
    </tr>
    <tr>
        <td>3</td>
        <td>0.8955</td>
        <td>0.1156</td>
        <td>0.8682</td>
        <td>0.1034</td>
        <td>0.8621</td>
        <td>0.1079 </td>
    </tr>
    <tr>
        <td>4</td>
        <td>0.9624</td>
        <td>0.0278</td>
        <td>0.9159</td>
        <td>0.0282</td>
        <td>0.9159</td>
        <td>0.0239 </td>
    </tr>
    <tr>
        <td>5</td>
        <td>0.9126</td>
        <td>0.0403</td>
        <td>0.8918</td>
        <td>0.0405</td>
        <td>0.8891</td>
        <td>0.0386 </td>
    </tr>
    <tr>
        <td>6</td>
        <td>0.8964</td>
        <td>0.0720</td>
        <td>0.8672</td>
        <td>0.0574</td>
        <td>0.8656</td>
        <td>0.0632 </td>
    </tr>
</tbody>
</table>

### Macro Avg Recall <a name="MA RECALL"></a>
<table>
  <thead>
  <tr>
    <th colspan="7">Macro Avg Recall</th>
  </tr>
   <tr>
    <td rowspan="2"><b>Models</b></td>
    <td colspan="2"><b>Training set</b></td>
    <td colspan="2"><b>Validation set</b></td>
    <td colspan="2"><b>Test set</b></td>
  </tr>
  <tr>
    <td>&#x0078;&#x0303;</td>
    <td>IQR</td>
    <td>&#x0078;&#x0303;</td>
    <td>IQR</td>
    <td>&#x0078;&#x0303;</td>
    <td>IQR</td>
  </tr>
</thead>
<tbody>
    <tr>
        <td>1</td>
        <td>0.9965</td>
        <td>0.0052</td>
        <td>0.9792</td>
        <td>0.0096</td>
        <td>0.9773</td>
        <td>0.0100 </td>
    </tr>
    <tr>
        <td>2</td>
        <td>0.9723</td>
        <td>0.0280</td>
        <td>0.9500</td>
        <td>0.0317</td>
        <td>0.9447</td>
        <td>0.0333 </td>
    </tr>
    <tr>
        <td>3</td>
        <td>0.8779</td>
        <td>0.1480</td>
        <td>0.8500</td>
        <td>0.1313</td>
        <td>0.8447</td>
        <td>0.1397 </td>
    </tr>
    <tr>
        <td>4</td>
        <td>0.9608</td>
        <td>0.0310</td>
        <td>0.9125</td>
        <td>0.0296</td>
        <td>0.9120</td>
        <td>0.0253 </td>
    </tr>
    <tr>
        <td>5</td>
        <td>0.9044</td>
        <td>0.0533</td>
        <td>0.8775</td>
        <td>0.0575</td>
        <td>0.8760</td>
        <td>0.0567 </td>
    </tr>
    <tr>
        <td>6</td>
        <td>0.8858</td>
        <td>0.1024</td>
        <td>0.8508</td>
        <td>0.0938</td>
        <td>0.8527</td>
        <td>0.1013 </td>
    </tr>
</tbody>
</table>

### Macro Avg F1 <a name="MA F1"></a>
<table>
  <thead>
  <tr>
    <th colspan="7">Macro Avg F1</th>
  </tr>
   <tr>
    <td rowspan="2"><b>Models</b></td>
    <td colspan="2"><b>Training set</b></td>
    <td colspan="2"><b>Validation set</b></td>
    <td colspan="2"><b>Test set</b></td>
  </tr>
  <tr>
    <td>&#x0078;&#x0303;</td>
    <td>IQR</td>
    <td>&#x0078;&#x0303;</td>
    <td>IQR</td>
    <td>&#x0078;&#x0303;</td>
    <td>IQR</td>
  </tr>
</thead>
<tbody>
   <tr>
        <td>1</td>
        <td>0.9965</td>
        <td>0.0052</td>
        <td>0.9792</td>
        <td>0.0095</td>
        <td>0.9773</td>
        <td>0.0099 </td>
    </tr>
    <tr>
        <td>2</td>
        <td>0.9724</td>
        <td>0.0284</td>
        <td>0.9500</td>
        <td>0.0319</td>
        <td>0.9443</td>
        <td>0.0333 </td>
    </tr>
    <tr>
        <td>3</td>
        <td>0.8783</td>
        <td>0.1498</td>
        <td>0.8492</td>
        <td>0.1359</td>
        <td>0.8459</td>
        <td>0.1414 </td>
    </tr>
    <tr>
        <td>4</td>
        <td>0.9608</td>
        <td>0.0306</td>
        <td>0.9130</td>
        <td>0.0292</td>
        <td>0.9116</td>
        <td>0.0256 </td>
    </tr>
    <tr>
        <td>5</td>
        <td>0.9043</td>
        <td>0.0541</td>
        <td>0.8771</td>
        <td>0.0576</td>
        <td>0.8756</td>
        <td>0.0576 </td>
    </tr>
    <tr>
        <td>6</td>
        <td>0.8858</td>
        <td>0.1104</td>
        <td>0.8496</td>
        <td>0.1006</td>
        <td>0.8486</td>
        <td>0.1004 </td>
    </tr>
</tbody>
</table>
