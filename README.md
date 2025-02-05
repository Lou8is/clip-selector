# clip-selector

Load all needed twitch clips in the clip page and retrieve their data using those lines in your browser CLI. Note that this uses CSS classes subject to change over time so you may need to adapt it.


var clips = document.querySelectorAll("div.ivrFkx");

var titles = [];document.querySelectorAll("div.ivrFkx h3").forEach(function (currentValue, currentIndex, listObj) { titles[currentIndex]=currentValue.innerHTML })

var links = [];document.querySelectorAll("div.ivrFkx a.htMMdJ").forEach(function (currentValue, currentIndex, listObj) { links[currentIndex]=currentValue.href })

var duration = [];document.querySelectorAll("div.ivrFkx div.jHpjIV div.jRUNHm").forEach(function (currentValue, currentIndex, listObj) { duration[currentIndex]=currentValue.innerHTML })

var vues = [];document.querySelectorAll("div.ivrFkx div.kdSYzp div.jRUNHm").forEach(function (currentValue, currentIndex, listObj) { dates[currentIndex]=currentValue.innerHTML })

var dates = [];document.querySelectorAll("div.ivrFkx div.hYDQKO div.jRUNHm").forEach(function (currentValue, currentIndex, listObj) { dates[currentIndex]=currentValue.innerHTML })

var createdby = [];document.querySelectorAll("div.ivrFkx div.hgouXh :nth-child(2) > a").forEach(function (currentValue, currentIndex, listObj) { createdby[currentIndex]=currentValue.innerHTML })
