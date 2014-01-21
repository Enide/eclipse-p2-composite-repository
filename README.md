# eclipse-p2-composite-repository

Eclipse p2 composite repositories allow you to combine several p2 repositories (aka Eclipse update site)
into 1 virtual repository, that can be hosted anywhere including local folder.

*Enide repository* will try to collect all useful Eclipse plugins around the world.
(I guess performance maybe low due to different and many network delays.)

Update p2 repository URL: `https://raw.github.com/Enide/eclipse-p2-composite-repository/master/`

[How to use](http://marketplace.eclipse.org/updatesite/help?url=https://raw.github.com/Enide/eclipse-p2-composite-repository/master/)

Great thanks to [oberlies](http://stackoverflow.com/users/1523648/oberlies)
 for his [answer](http://stackoverflow.com/questions/20951842/combine-aggregate-eclipse-p2-repositories-extendable-p2-repository)

Some googled links:

- http://help.eclipse.org/kepler/index.jsp?topic=%2Forg.eclipse.platform.doc.isv%2Fguide%2Fp2_composite_repositories.htm
- http://wiki.eclipse.org/Equinox/p2/Composite_Repositories_%28new%29
- http://blog.vogella.com/2010/04/06/eclipse-p2-composite-repository/

## Warning

What you loose? Usually when you find plugin on Marketplace or via web search, you can read about the plugin, how to use,
where to submit bug, news etc. When you have 100+ plugin in one update site, you are likely to miss something.
So the best usage would be for those who already know the plugins, just need quicker way to install all favorites.

Authors should add Eclipse Help with info about plugin, how to use, etc. Have you been in a situation, 
when you need a plugin you have used before,
but you don't remember it's name (It is maybe installed in this Eclipse or other, but there is no way to check quickly.)


<p><a href="http://with-eclipse.github.io/" target="_blank"><img alt="with-Eclipse logo" src="http://with-eclipse.github.io/with-eclipse-1.jpg" /></a></p>
				
<p><i>Hosted by</i><br>
<a href="https://github.com/Nodeclipse">
  <img src="https://github.com/github/media/raw/master/logos/github_logo_social_coding_outlined.png" style="border: 0" alt="github.com" height="39" width="88">
</a></p>
