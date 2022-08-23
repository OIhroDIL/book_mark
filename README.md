<!doctype html>
<html>
 
<head>
	<link rel="stylesheet" href="tree_fontello/css/fontello.css">
	<style>
	.tree{
	  color:#393939;
	}
	.tree, .tree ul{
	  list-style: none;
	  padding-left:17px;
	}
	.tree *:before{
	  width:17px;
	  height:17px;
	  display:inline-block;
	}
	.tree label{
	  cursor: pointer;
	}
	.tree label:before{
	  content:'\f256';
	  font-family: fontello;
	}
	.tree a{
	  text-decoration: none;
	  color:#393939;
	}
	.tree a:before{
	  content:'\e800';
	  font-family: fontello;
	}
	.tree input[type="checkbox"] {
	display: none;
	}
	.tree input[type="checkbox"]:checked~ul {
	  display: none;
	}
	.tree input[type="checkbox"]:checked+label:before{
	  content:'\f255';
	  font-family: fontello;
	}
	</style>
</head>
 
<body>
	<h1> PORTAL </h1>  
	
	<h3><a href="https://www.naver.com/" target = "_blank"> NAVER </a></h3>
	<form method="get" action="http://search.naver.com/search.naver">
		NAVER SEARCH <input name="query">
		<input type="submit" value="SEARCH">
	</form></br>
	<hr>

	<h3><a href="https://www.google.com/" target = "_blank"> GOOGLE </a></h3>
	<form method="get" action="https://www.google.com/search">
		GOOGLE SEARCH <input name="query">
		<input type="submit" value="SEARCH">
	</form>
	</form></br>
	<hr>

	<h3><a href="https://www.daum.net//" target = "_blank"> DAUM </a></h3>
	<form method="get" action="https://search.daum.net/search">
		DAUM SEARCH <input name="q">
		<input type="submit" value="SEARCH">
	</form></br>
	<hr>

	<h3><a href="https://www.youtube.com//" target = "_blank"> YOUTUBE </a></h3>
	<form method="get" action="https://www.youtube.com/results">
		YOUTUBE SEARCH <input name="search_query">
		<input type="submit" value="SEARCH">
	</form></br>
	<hr>

	<h1>FAVORITES</h1>  
	
	  <ul class="tree">
	    <li>
	      <input type="checkbox" id="root1" checked>
	      <label for="root1">NAVER</label>
	      <ul>
	        <li><a href="https://www.naver.com/" target = "_blank"> NAVER </a></li>
	        <li><a href="https://new.land.naver.com/complexes?ms=37.3851785,126.9516421,17&a=APT&b=A1&e=RETAIL" target = "_blank"> NAVER MAP </a></li>
	        <li><a href="https://map.naver.com/v5/?c=14132178.2130329,4493223.5117517,16,0,0,0,dh" target = "_blank"> NAVER LAND </a></li>
	        <li><a href="https://papago.naver.com/" target = "_blank"> PAPAGO</a></li>
	     	<li><a href="https://comic.naver.com/index.nhn" target = "_blank"> NAVER WEBTOON </a></li>
   
	      </ul>
	    </li>
	  </ul>

	  <ul class="tree">
	    <li>
	      <input type="checkbox" id="root2" checked>
	      <label for="root2">DAUM</label>
	      <ul>
	        <li><a href="https://www.daum.net//" target = "_blank"> DAUM </a></li>
	        <li><a href="https://finance.daum.net" target = "_blank"> DAUM STOCK </a></li>
	        <li><a href="http://webtoon.daum.net" target = "_blank"> DAUM WEBTOON </a></li>
	      </ul>
	    </li>
	  </ul>

	<ul class="tree">
	<li>
	  <input type="checkbox" id="root3" checked>
	  <label for="root3">GOOGLE</label>
	  <ul>
	    <li><a href="https://www.google.co.kr/webhp?hl=ko" target = "_blank"> GOOGLE </a></li>
	    <li><a href="https://www.google.co.kr/imghp?hl=ko" target = "_blank">  GOOGLE IMAGE SEARCH </a></li>
	    <li><a href="https://mail.google.com/mail/u/0/#inbox" target = "_blank"> G MAIL </a></li>
	    <li><a href="https://translate.google.co.kr/?hl=ko&tab=TT" target = "_blank"> GOOGLE TRANSLATE  </a></li>
    	<li><a href="https://keep.google.com/u/0/#home" target = "_blank"> GOOGLE KEEP </a></li>
	  </ul>
	</li>
	</ul>

	<ul class="tree">
	<li>
	  <input type="checkbox" id="root4" checked>
	  <label for="root4">STOCK MARKET</label>
	  <ul>
	    <li><a href="https://kr.investing.com" target = "_blank"> INVASTE </a></li>
	    <li><a href="https://www.finviz.com/map.ashx?t=sec_all" target = "_blank"> FINVIZ </a></li>
	    <li><a href="https://finance.daum.net" target = "_blank"> DAUM STOCK </a></li>
	  </ul>
	</li>
	</ul>

	<ul class="tree">
	<li>
	  <input type="checkbox" id="root5" checked>
	  <label for="root5"> ENTER </label>
	  <ul>
  	    <li><a href="https://www.netflix.com/browse" target = "_blank"> NETFLIX </a></li>
	    <li><a href="http://103.204.13.68:8901/bbs/board.php?bo_table=ctoon&is=&sord=&type=&page=23" target = "_blank"> 11</a></li>
                <li><a href="https://manatoki141.net" target = "_blank"> 마나토끼</a></li>
	    <li><a href="https://jusoshow.me" target = "_blank"> 쇼미주소 </a></li>

		<li><a href="https://post.naver.com/my.nhn?memberNo=954004&navigationType=push" target = "_blank"> 전원속의 내집 </a></li>
		<li>
          <input type="checkbox" id="node1">
          <label for="node1">CAMERA</label>
          <ul>
			<li><a href="http://www.slrclub.com/" target = "_blank"> SLR CLUB </a></li>
          </ul>
        </li>
	    
	  </ul>
	</li>
	</ul>

	<ul class="tree">
	<li>
	  <input type="checkbox" id="root6" checked>
	  <label for="root6">YOUTUBE</label>
	  <ul>
	    <li><a href="https://www.youtube.com/channel/UCZ1TnBS8k1swzD1LR3S9B6w/videos" target = "_blank"> 모두의 부동산 </a></li>
	    <li><a href="https://www.youtube.com/channel/UCYYqb06Ym3aeubtHFwA4ECg/videos" target = "_blank"> 안협소 </a></li>

	  </ul>
	</li>
	</ul>

	<ul class="tree">
	<li>
	  <input type="checkbox" id="root7" checked>
	  <label for="root7"> 부동산 </label>
	  <ul>
	    <li><a href="https://new.land.naver.com/complexes?ms=37.3876896,126.9495516,16&a=APT:ABYG:JGC&e=RETAIL" target = "_blank"> 네이버 부동산 </a></li>
	    <li><a href="https://hogangnono.com/apt/5q885/0" target = "_blank"> 호갱노노 </a></li>
	    <li><a href="https://www.valueupmap.com" target = "_blank"> 벨류맵</a></li>
	    <li><a href="https://www.disco.re" target = "_blank"> 디스코 </a></li>
	    <li><a href="https://www.applyhome.co.kr/co/coa/selectMainView.do" target = "_blank"> 청약홈 </a></li>
	  </ul>
	</li>
	</ul>

	<ul class="tree">
	<li>
	  <input type="checkbox" id="root8" checked>
	  <label for="root8">CLOUD</label>
	  <ul>
	    <li><a href="http://chaieunhome.synology.me:5000/" target = "_blank"> 채은홈 </a></li>
	    <li><a href="http://optologics.quickconnect.to/" target = "_blank"> 옵토로직스 </a></li>
	  </ul>
	</li>	
	</ul>

	<ul class="tree">
	<li>
	  <input type="checkbox" id="root9" checked>
	  <label for="root9"> 옵토로직스 </label>
	  <ul>
	  	<li><a href="http://www.optologics.com/kr/" target = "_blank"> 옵토로지 </a></li>
	    <li><a href="http://a5261.ajpark.kr/" target = "_blank"> 주차 </a></li>
	    <li><a href="https://office.hiworks.com/optologics.com/home/office" target = "_blank"> 하이웍스 </a></li>
	  </ul>
	</li>	
	</ul>

	<ul class="tree">
	<li>
	  <input type="checkbox" id="root10" checked>
	  <label for="root10"> 쇼핑 </label>
	  <ul>
	  	<li><a href="https://www.11st.co.kr/main" target = "_blank"> 11번가 </a></li>
	    <li><a href="http://www.danawa.com/" target = "_blank"> 다나와 </a></li>
		<li><a href="https://www.daangn.com" target = "_blank"> 당근 마켓 </a></li>
	    
	  </ul>
	</li>	
	</ul>








	
<!--
 <ul class="tree">
    <li>
      <input type="checkbox" id="root2">
      <label for="root2">DAUM</label>
      <ul>
        <li><a href="https://www.naver.com/"> ���� </a></li>
        <li><a href="https://new.land.naver.com/complexes?ms=37.3851785,126.9516421,17&a=APT&b=A1&e=RETAIL"> ���̹��ε��� </a></li>
        <li>
          <input type="checkbox" id="node4">
          <label for="node4">node3</label>
          <ul>
            <li><a href="https://opentutorials.org">node31</a></li>
            <li><a href="https://opentutorials.org">node32</a></li>
            <li><a href="https://opentutorials.org">node33</a></li>
          </ul>
        </li>
      </ul>
    </li>
  </ul>

 -->
</body>
 
</html>
