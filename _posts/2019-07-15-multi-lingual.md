---
Title: "multi-lingual"
date: 2019-07-15 15:40:40 -0400
categories: xinapse TTS
---
<head>
  <style>
    body {
      margin: 0;
      padding: 10px 1px;
      background: #fff;
      color: #111;
      font-size: 15px;
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
<h3>본 샘플들은 연구용입니다.</h3>
<hr>
<h3 align="left">1. Original language</h3>
  1-1. Eng<br>
   Text: We present a multispeaker, multilingual text-to-speech synthesis model based on Tacotron.
<table>
  <caption align="left">
  <tr>      
    <td align="center">Baseline </td>
    <td align="center">Advanced </td>
  </tr>
  <tr>
    <td align="center"><audio src="/audio_samples/LJ_Baseline_Eng.wav" controls=""></audio></td>
    <td align="center"><audio src="/audio_samples/LJ_New_Eng.wav" controls=""></audio></td>
  </tr>
</table>
  1-2. Kor
    Text: 제가 이번에 국내 최고 수준의 인공지능 스타트업 자이냅스를 방문했는데요?
<table>
  <tr>      
    <td align="center">Baseline </td>
    <td align="center">Advanced </td>
  </tr>
  <tr>
    <td align="center"><audio src="/audio_samples/KSS_Baseline_Kor.wav" controls=""></audio></td>
    <td align="center"><audio src="/audio_samples/KSS_New_Kor.wav" controls=""></audio></td>
  </tr>
</table>
<h3 align="left">2. Transfer language</h3>
  2-1. Eng to Kor
    Text: 제가 이번에 국내 최고 수준의 인공지능 스타트업 자이냅스를 방문했는데요?
<table>
  <tr>      
    <td align="center">Baseline </td>
    <td align="center">Advanced </td>
  </tr>
  <tr>
    <td align="center"><audio src="/audio_samples/LJ_Baseline_Kor.wav" controls=""></audio></td>
    <td align="center"><audio src="/audio_samples/LJ_New_Kor.wav" controls=""></audio></td>
  </tr>
</table>
<table align="left">
  2-2. Kor to Eng
    Text: We present a multispeaker, multilingual text-to-speech synthesis model based on Tacotron.
  <tr>      
    <td align="center">Baseline </td>
    <td align="center">Advanced </td>
  </tr>
  <tr>
    <td align="center"><audio src="/audio_samples/KSS_Baseline_Eng.wav" controls=""></audio></td>
    <td align="center"><audio src="/audio_samples/KSS_New_Eng.wav" controls=""></audio></td>
  </tr>
</table>
