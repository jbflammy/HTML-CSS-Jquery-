<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8" />
<title>Sponsor</title>
<script type="text/javascript" src="js/jquery.js"></script>
<script type="text/javascript">
$(document).ready(function () {  
	$('#nav_sponsor li').hover(
		function () {
			//show its submenu
			$('ul', this).stop().slideDown(10);
    }, 
		function () {
			//hide its submenu
			$('ul', this).stop().slideUp(10);			
		}
	);
});
	</script>
<style type="text/css">
@import url("css/reset.css");
@import url("css/style.css");
@import url(http://fonts.googleapis.com/css?family=Capriola);
@import url(http://fonts.googleapis.com/css?family=McLaren);
@import url(http://fonts.googleapis.com/css?family=Niconne);
</style>
</head>
<div id="main_content">
	<div id="logo_sponsor">
    </div><!--logo-->
	<div id="banner_sponsor">
    </div><!--banner-->
	 <div id="nav_sponsor">
        		<ul id="na_sponsor">
            		<li class="parent_menu"><a href="#">HOME</a></li>
                	<li class="parent_menu"><a href="#">PROJECTS</a></li>
                	<li class="parent_menu"><a href="#" class="selected">JOIN></a>
                    	<ul>
                        	<li class="sub_menu"><a href="#">MODEL/TALENT</a></li>
                            <li class="sub_menu"><a href="#">BUSINESS TO BUSINESS</a></li>
                            <li class="sub_menu"><a href="#">INDUSTRY PROFESSIONALS</a></li>
                       </ul></li>
                    <li class="parent_menu"><a href="#">CONTESTS</a></li>
                    <li class="parent_menu"><a href="#" class="selected">BENEFITS ></a>
                    	<ul>
                        	<li class="sub_menu"><a href="#">FOR MODEL/TALENT</a></li>
                            <li class="sub_menu"><a href="#">FOR BUSINESSES</a></li>
                            <li class="sub_menu"><a href="#">FOR INDUSTRY PROF</a></li>
                       </ul></li>
                       
                	<li class="parent_menu"><a href="#">CONTACT</a></li>
           		</ul>
        	</div><!--nav-->
    <div id="content_sponsor">
    	<div id="sponsor_banner">
        </div><!--sponsor_banner-->
        <div id="upper_content_sponsor">
        	<div id="mid_content">
        		<div id="left_mid_content">
            		<div id="left_mid_header">
                    	<p>BE A SPONSOR</p>
                	</div><!--left_mid_header-->
                	<div id="left_mid_para">
                		<p>LOREM IPSUM DOLOR SIT AMETLOREM IPSUM DOLOR SIT AMETLOREM IPSUM DOLOR SIT AMETLOREM IPSUM DOLOR SIT AMET
                        	LOREM IPSUM DOLOR SIT AMETLOREM IPSUM DOLOR SIT AMET</p>
                	</div><!--left_mid_para-->
            	</div><!--left mid content-->
            	<div id="right_mid_content">
            		<div id="right_mid_header">
                    	<p>BE SPONSORED</p>
                	</div><!--right_mid_header-->
                		<div id="right_mid_para">
                			<p>LOREM IPSUM DOLOR SIT AMETLOREM IPSUM DOLOR SIT AMETLOREM IPSUM DOLOR SIT AMETLOREM IPSUM DOLOR SIT AMET
                        	LOREM IPSUM DOLOR SIT AMETLOREM IPSUM DOLOR SIT AMET.</p>
                		</div><!--right_mid_para-->
            	</div><!--right mid content-->
            </div><!--mid_content-->
         	<div id="button_sponsor">
         		<div id="join_button_left">
                	<ul>
                		<li><a href="#">JOIN</a></li>
                 	</ul>   
            	</div><!--join button left-->
            	<div id="join_button_right">
                	<ul>
                		<li><a href="#">JOIN</a></li>
                 	</ul>
            	</div><!--join button right-->
        	</div><!--button sponsor-->
        </div><!--upper content-->
        <div id="downer_content_sponsor">
        	<p class="quote">"We can do no great things, only small things with great love."</p>
            <p class="author">Mother Terasa</p>
        </div><!--downer_content_sponsor-->
    </div><!--content_sponsor-->
    <div id="footer">
        	<div id="social_network">
        	<ul>
            	<li><a href="#" class="twitter"><span>Twitter</span></a></li>
                <li><a href="#" class="youtube"><span>Youtube</span></a></li>
                <li><a href="#" class="facebook"><span>Facebook</span></a></li>
            </ul>
            </div><!--social_network-->
            <div id="copy_right">
            	<p>Copyright 2012 &copy; MTS</p>
            </div><!--copy_right-->
       </div><!--footer-->
</div><!--wrapper-->
</body>
</html>
