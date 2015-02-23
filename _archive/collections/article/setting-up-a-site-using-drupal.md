---

title: Setting up a site using Drupal
published: true
date: 2007-10-05
---

These are the things that I need to do in order to set up a new site.
<ol>
	<li>create the directory in the SVN repository on the server.</li>
	<li>edit the httpd.conf file locally to set up the virtual host, <em>located at /etc/httpd/</em>.</li>
	<li>edit the local hosts file<em> located at /etc/hosts</em>.</li>
	<li>copy an instance in the standard drupal files in to the place where the working copy is going to be kept in my case <em>/Volumes/Local_Work/svn/*siteroot*</em>.</li>
	<li>go to the alias that you have set up in the hosts file which should match the alias that you set up in the httpd.conf file.</li>
	<li>you should see the drupal page telling you that it cant access the database.</li>
	<li>open your MySQL GUI create a new database.</li>
	<li>change the permissions on the settings file to 777 (just for the time being) in the drupal site. <em>located at /sites/default/</em></li>
	<li>go back to your browser and refresh the page you should now see a page asking you to set up the database.</li>
	<li>change the database to the same name as the one you set up in step 7.</li>
	<li>you then have to log in to the drupal site (normally this is when I create the admin user and password if it's local I just use a crap password but don't forget to change it later once its semi live).</li>
	<li>thats it you should now be able to customise the site.</li>
</ol>
