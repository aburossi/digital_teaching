---
{"dg-publish":true,"permalink":"/10-tag-1/30-merkblaetter/podcast-reihe/sucht/","noteIcon":""}
---


https://raw.githubusercontent.com/bbk-bbw/audio/main/podcast/filename.mp3

<audio controls> <source src="https://github.com/bbk-bbw/audio/raw/refs/heads/main/podcast/BBK_MB_Sucht.mp3" type="audio/mpeg"> Your browser does not support the audio element. </audio>

<audio controls>
  <source src="https://github.com/bbk-bbw/audio/raw/refs/heads/main/podcast/BBK_MB_Sucht.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>

<audio controls>
    <source src="https://raw.githubusercontent.com/bbk-bbw/audio/main/podcast/BBK_MB_Sucht.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
</audio>


![[raw.githubusercontent.com/bbk-bbw/audio/main/podcast/BBK_MB_Sucht.mp3\|raw.githubusercontent.com/bbk-bbw/audio/main/podcast/BBK_MB_Sucht.mp3]]]



![[merkblatt-207-rassismus.pdf]]

const audioFiles = [
    "BBK MB Mobbing.mp3",
    "Another File Name.mp3",
    // Add more file names here
];

const container = document.getElementById('audio-container');

audioFiles.forEach(fileName => {
    const audio = document.createElement('audio');
    audio.controls = true;
    // Encode the file name and construct the full URL
    audio.src = `https://raw.githubusercontent.com/bbk-bbw/audio/main/podcast/${encodeURIComponent(fileName)}`;
    container.appendChild(audio);
});
