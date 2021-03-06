[<img _ngcontent-c2="" src="https://avatars1.githubusercontent.com/u/28770833?s=88&v=4" style="background-color: transparent;">](https://ps3838api.github.io)



# Fair Use
This API is protected by copyright laws and is provided free of charge to our players, partners and affiliates only.

The use of this free resource is subject to our "Fair Use Policy" which is set out below.

When you utilize the API, you are agreeing to this policy. Any breaches of this policy, whether intentional or not, may result in a temporary or permanent suspension of your access without notice at our sole discretion.

# Fair usage

The API is provided to players to facilitate wagering and may not be used for data gathering, scrapping or any other purpose. The API usage must be proportionate to wagering activities as determined on a case by case basis by PS3838.

Unless explicitly agreed in writing by PS3838, the commercial usage of the API will lead to the permanent suspension of your access.

You will not attempt or encourage others to:

- To interfere with, disrupt, or disable any API features;
- Use the API for commercial purposes without a written agreement with PS3838;
Sell, rent, lease, sublicense, redistribute, or syndicate the API to any third party without prior written approval from PS3838.

### The following limitations must be observed per sport:

- Requests made for the /fixtures and /odds operation without the since parameter must be restricted to once every 60 seconds;
- Requests made for the /fixtures and /odds operation with the since parameter must be restricted to once every 5 seconds.

#### Recommended calling rate
<table>
  <tr>
    <th>API</th>
    <th>Recommended API Version</th>
    <th>Recommended Interval</th>
  </tr>
  <tr>
    <td>/sports</td>
    <td>/v3</td>
    <td>Every 60s</td>
  </tr>
  <tr>
    <td>/leagues</td>
    <td>/v3</td>
    <td>Every 60s</td>
  </tr>
  <tr>
    <td>/fixtures</td>
    <td>/v3</td>
    <td><p>Every 5s per sport with since parameter</p><p>Every 60s per sport without since parameter</p></td>
  </tr>
  <tr>
    <td>/fixtures/settled</td>
    <td>/v3</td>
    <td><p>Every 5s per sport with since parameter</p><p>Every 60s per sport without since parameter</p></td>
  </tr>
  <tr>
    <td>/fixtures/special</td>
    <td>/v2</td>
    <td><p>Every 5s per sport with since parameter</p><p>Every 60s per sport without since parameter</p></td>
  </tr>
  <tr>
    <td>/fixtures/special/settled</td>
    <td>/v3</td>
    <td><p>Every 5s per sport with since parameter</p><p>Every 60s per sport without since parameter</p></td>
  </tr>
  <tr>
    <td>/odds</td>
    <td>/v3</td>
    <td><p>Every 5s per sport with since parameter</p><p>Every 60s per sport without since parameter</p></td>
  </tr>
  <tr>
    <td>/odds/parlay</td>
    <td>/v3</td>
    <td><p>Every 5s per sport with since parameter</p><p>Every 60s per sport without since parameter</p></td>
  </tr>
  <tr>
    <td>/odds/special</td>
    <td>/v2</td>
    <td><p>Every 5s per sport with since parameter</p><p>Every 60s per sport without since parameter</p></td>
  </tr>
  <tr>
    <td>/odds/teaser</td>
    <td>/v1</td>
    <td>Every 5s per teaser Id</td>
  </tr>
  <tr>
    <td>/inrunning</td>
    <td>/v2</td>
    <td>Every 2s</td>
  </tr>
  <tr>
    <td>/teaser/groups</td>
    <td>/v1</td>
    <td>Every 60s</td>
  </tr>
  <tr>
    <td>/bets (Get Bet)</td>
    <td>/v3</td>
    <td>Every 2s</td>
  </tr>
  <tr>
    <td>/betting-status</td>
    <td>/v1</td>
    <td>Every 1s</td>
  </tr>
  <tr>
    <td>/cancellationreasons</td>
    <td>/v1</td>
    <td>Every 10min</td>
  </tr>
  <tr>
    <td>/currencies</td>
    <td>/v2</td>
    <td>Every 10min</td>
  </tr>
  <tr>
    <td>/line</td>
    <td>/v2</td>
    <td>On demand</td>
  </tr>
  <tr>
    <td>/line/parlay</td>
    <td>/v2</td>
    <td>On demand</td>
  </tr>
  <tr>
    <td>/line/teaser</td>
    <td>/v1</td>
    <td>On demand</td>
  </tr>
  <tr>
    <td>/line/special</td>
    <td>/v2</td>
    <td>On demand</td>
  </tr>
  <tr>
    <td>/translations</td>
    <td>/v3</td>
    <td>On demand</td>
  </tr>
  <tr>
    <td>/client/balance</td>
    <td>/v1</td>
    <td>On demand</td>
  </tr>
</table>

### Best practice

Please use a delta /fixtures and /odds calls (with the since parameter) calls instead of a snapshot /fixtures and /odds calls (without since parameter).

# Disclaimer
PS3838 is not liable for use of the API for any purpose, the API is provided on an “as is” and “as available” basis, without warranties of any kind, either express or implied, including, without limitation, implied warranties of merchantability, fitness for a particular purpose or non-infringement.
