---
Title: "multi-lingual"
date: 2019-07-15 15:40:40 -0400
categories: xinapse TTS
-
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Audio samples from "Building a mixed-lingual neural TTS system with only monolingual data"</title>
  <style>
    body {
      margin: 0;
      padding: 10px 1px;
      background: #fff;
      color: #111;
      font-size: 15px;
      font-family: sans-serif;
      font-weight: 400;
      line-height: 1.8;
      overflow-x: hidden;
      -webkit-font-smoothing: antialiased;
    }

    audio {
      width: 250px;
      margin-right: 10px;
    }

    .sample {
      font-size: 0.9em;
      font-style: italic;
      border: 1px solid #ddd;
      padding: 1em;
      margin-bottom: 1em;
    }

    caption {
      text-align: left;
      font-size: 1.0em;
      font-weight: bold;
    }
  </style>
</head>

<br><h2>본 샘플들은 연구용입니다.</h2>
<hr>
<h2 align="left">1. Speaker embedding at differen position</h3>
<div style="height: 420px">
<table align="left">
      <h3 align="left">Mandarin Samples</h3>
      <caption align="left">(1). 这儿夏天雨水很多，可是秋天很少雨。</caption>
      <tr>      
        <td align="center" width=400>Speaker embedding at encoder (SE-ENC)</td>
        <td align="center" width=500>Speaker embedding at decoder (SE-DEC)</td>
      </tr>   
      <tr>
          <td align="center" width=400><audio src="samples/SE-ENC/cn/000527.wav" controls=""></audio></td>
          <td align="center" width=400><audio src="samples/SE-DEC/cn/000527.wav" controls=""></audio></td>
      </tr>
</table>
<table align="left">     
      <caption align="left">(2). 峨眉山今天下雨，不冷，西南风四到五级。</caption>
      <tr>
        <td align="center" width=400>Speaker embedding at encoder (SE-ENC)</td>
        <td align="center" width=500>Speaker embedding at decoder (SE-DEC)</td>
      </tr>
      <tr>
          <td align="center" width=400><audio src="samples/SE-ENC/cn/001576.wav" controls=""></audio></td>
          <td align="center" width=400><audio src="samples/SE-DEC/cn/001576.wav" controls=""></audio></td>
      </tr>      
</table>
<table align="left">     
      <caption align="left">(3). 不过稍微改变了一点儿说法。</caption>
      <tr>
        <td align="center" width=400>Speaker embedding at encoder (SE-ENC)</td>
        <td align="center" width=500>Speaker embedding at decoder (SE-DEC)</td>
      </tr>
      <tr>
          <td align="center" width=400><audio src="samples/SE-ENC/cn/004834.wav" controls=""></audio></td>
          <td align="center" width=400><audio src="samples/SE-DEC/cn/004834.wav" controls=""></audio></td>
      </tr>      
</table>    
</div> 
