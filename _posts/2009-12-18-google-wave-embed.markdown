---
layout: post
title: 'Google Wave Embed'
---
I was playing with <a href="http://wave.google.com">Google Wave</a> tonight. I am curious to see how I can use it. I keep thinking about using Google Wave as a <a class="zem_slink" title="Content management system" rel="wikipedia" href="http://en.wikipedia.org/wiki/Content_management_system">content management system</a> (CMS).<p></p>
I am starting with the basics. First I started a new wave and filled it with some dummy content.
<p style="text-align: center;"><img class="aligncenter" title="Google Wave CMS Editor" src="http://kinlane-productions.s3.amazonaws.com/google-wave_embed/Wave-CMS-Editor.jpg" alt="" width="536" height="238" /><p></p>
Then using the <a href="http://code.google.com/apis/wave/embed/">Google Wave Embed API</a> I can quickly grab the Wave ID and embed it in a web page using a simple little JavaScript that creates and manipulates a Google Wave Embed Panel.
<blockquote>&lt;script src="embed.js" type="text/javascript"&gt;&lt;/script&gt;
&lt;script type="text/javascript"&gt;
function initialize() {
var wavePanel = new WavePanel('http://wave.google.com/a/wavesandbox.com/');
wavePanel.loadWave('wavesandbox.com!w+Fe5fw2vJA');<p></p>
var conf = new WavePanel.UIConfig();
conf.setBgcolor("#ffffff");
conf.setFont("arial");
conf.setFontSize("10px");
conf.setToolbarEnabled(0);
wavePanel.setUIConfigObject(conf);<p></p>
wavePanel.init(document.getElementById('waveframe'));
wavePanel.setEditMode(0);
}
&lt;/script&gt;</blockquote>
This means I could easily create a dynamic web site that would pull from some sort of dynamic sitemap that has the site outline with corresponding Google Wave ID. The Wave would handle all the user edit permissions.<p></p>
Then using the sitemap you could create some sort of graphical look for the site that built the menu, submenus, and bread crumbs on the fly.<p></p>
You could easily create an administrative tool that would allow a webmaster to create new sections, pages and it would automatically create new waves, and setup user permissions from Google Wave contacts.<p></p>
Right now Google has wave embed limited to the Google Wave Sandbox. So its hard to tell what the public will see.
<p style="text-align: center;"><img class="aligncenter" title="Wave-CMS-Editor-Embed" src="http://kinlane-productions.s3.amazonaws.com/google-wave_embed/Wave-CMS-Editor-Embed.jpg" alt="" width="484" height="202" />
<p style="text-align: left;">This is just one page, however I can see the potential. You can basically crowd source the management of a web site across many different people using Google Wave.
<p style="text-align: left;">I still have some public and user editing isuess on the embed page to figure out. I will also create some sort of web site registry tool that will build the site map and handle organizing all the waves.<p></p>
