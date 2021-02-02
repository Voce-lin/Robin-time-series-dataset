# Robin-time-series-dataset
Time series anomaly detection dataset from an anonymous commercial bank
Data Format：
<table>
  <tbody><tr>
    <th>timestamp</th>
    <th>value</th>
    <th>label</th>
    </tr>
  <tr>
    <td>2020/6/27  0:00:00</td>
    <td>14.1</td>
    <td>0</td>
    </tr>
  <tr>
    <td>2020/6/27  0:05:00</td>
    <td>8.5</td>
    <td>0</td>
    </tr>
  <tr>
    <td>...</td>
    <td>...</td>
    <td>...</td>
    </tr>
  <tr>
    <td>...</td>
    <td>...</td>
    <td>...</td>
    </tr>
  <tr>
    <td>...</td>
    <td>...</td>
    <td>...</td>
    </tr>
  </tbody></table>
We've labeled out the true anomalies, where label=1 means this point is abnormal.
