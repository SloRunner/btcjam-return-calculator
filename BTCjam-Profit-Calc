// ==UserScript==
// @name        BTCjam Profit
// @namespace   www.slo-runner.ws.gy
// @description BTCjam profit calculator
// @include     *btcjam.com*
// @version     1.0
// @owner       Slo_Runner (https://www.facebook.com/slo.runner.samp)
// @grant       none
// ==/UserScript==

//Copyright (C) 2014  Aleš Kalan (Slo_Runner)
//##############################LICENSE#################################
//# This program is free software; you can redistribute it and/or
//# modify it under the terms of the GNU General Public License
//# as published by the Free Software Foundation; either version 2
//# of the License, or (at your option) any later version.
//# This program is distributed in the hope that it will be useful,
//# but WITHOUT ANY WARRANTY; without even the implied warranty of
//# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
//# GNU General Public License for more details.
//######################################################################


window.donate = function () {
var para = document.createElement("div");
var node = "<h4>Thanks for using Simple return calculator if you want to donate you can send some bitcoins to this address: <a href='bitcoin:14KYVGkXPszaWSrrPv293bhEQuqPR1X552'>14KYVGkXPszaWSrrPv293bhEQuqPR1X552</a> Thanks for your support :)</h4>";
para.innerHTML = node;
    para.setAttribute('style', 'text-align:center;position:fixed;display:block;color:#00FF00;box-shadow:0pt 1px 0pt rgba(0,0,0,0.1);font-weight:bold;border-radius:3px;border:1px solid rgba(200,200,50,0.2);padding:5px;background-color:#000000');
var element = document.getElementById("fb-root");
element.appendChild(para);
};

window.calc = function () {
    var invest = document.getElementById('invest') .value;
    var percentage = document.getElementById('percent') .value;
    var percents = (percentage / 100) * invest;
    var total = parseFloat(percents) + parseFloat(invest);
    document.getElementById('result') .value = total.toFixed(8);
};
var askformsg = "<div><span class='img sp_38ydyu sx_004ff3'></span><a href='https://www.facebook.com/slo.runner.samp' target='_blank' style='position:absolute;padding-left:3px;font-size:11px;color:#00FF00;'>Simple return calculator by Slo_Runner</a></div></br><br>";
askformsg += "<div><input id='invest' placeholder='Invest amount'></input><br><input id='percent' placeholder='Rate'></input><br><fieldset><legend><center>Result</center></legend><input id='result' placeholder='Total amount earned'></input></fieldset></div>";
askformsg += "<div><center><button class='btn btn-gold' onclick='window.calc()'>Calculate</button><button class='btn btn-primary' onclick='window.donate()'>Donations</button></center></div>";
var Popupset = document.createElement('div');
Popupset.setAttribute('style', 'position:fixed;left:0%;margin-left:50px;bottom:50px;z-index:9999;font-size:11px;font-family:tahoma;color:#3B5998;box-shadow:0pt 1px 0pt rgba(0,0,0,0.1);font-weight:bold;border-radius:3px;border:1px solid rgba(200,200,50,0.2);padding:5px;background-color:#4276A3');
Popupset.innerHTML = askformsg;
document.body.appendChild(Popupset);
