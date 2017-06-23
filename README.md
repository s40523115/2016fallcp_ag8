# 2016fallcp_ag8


<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<title>reveal.js – The HTML Presentation Framework</title>

<meta name="description" content="A framework for easily creating beautiful presentations using HTML">
<meta name="author" content="Hakim El Hattab">

<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">

<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">

<link rel="stylesheet" href="https://cad-lab.github.io/cadlab_data/reveal/css/reveal.css">
<link rel="stylesheet" href="https://cad-lab.github.io/cadlab_data/reveal/css/theme/black.css" id="theme">

<!-- Theme used for syntax highlighting of code -->
<link rel="stylesheet" href="https://cad-lab.github.io/cadlab_data/reveal/lib/css/zenburn.css">

<!-- Printing and PDF exports -->
<script>
    var link = document.createElement( 'link' );
    link.rel = 'stylesheet';
    link.type = 'text/css';
    link.href = window.location.search.match( /print-pdf/gi ) ? 'https://cad-lab.github.io/cadlab_data/reveal/css/print/pdf.css' : 'https://cad-lab.github.io/cadlab_data/reveal/css/print/paper.css';
    document.getElementsByTagName( 'head' )[0].appendChild( link );
</script>

<!--[if lt IE 9]>
<script src="https://cad-lab.github.io/cadlab_data/reveal/lib/js/html5shiv.js"></script>
<![endif]-->
	
</head>

<body>
<div class="reveal">
<!-- Any section element inside of this container is displayed as a slide -->
<div class="slides">
        <section>
            <h1>第八組 </h1>
		<h1>40523115內容管理簡報</h1>
            <h3>Hello World</h3>
            <p>
                <small>
                 by 第八組
			</small>
                
			</p>
           
        </section>
        	
        <section>
            <h2>前言</h2>機械設計
	機械設計是一種表達 機=精巧配置的互動元件 械=特定功能 社=表達  計=許多思考與討論 做虛實整合界資料管理
		
            
           <p align=left><font size="4">軟體配置管理s（Software Configuration Management,SCM)</font><br>
	<font size="3">對每個項目變更進行管理控制，並維護不同項目之間的版本關聯，以使軟體在開發過程中任一時間的內容都可以被追溯。</font>

  <p>分散式版本控制（Distributed Revision control）  </p>
  <p><font size="3"><p align=left>藉此能在倉儲管理的過程中，確保由不同人所編輯的同一檔案都能得到同步。而且可不必在相同的網路系統下工作。  </p></font>
		  <p> 內容管理系統（Content Management System,CMS）
 </p>
		  <p align=left>指在一個合作模式下，用於管理工作流程的一套制度。該系統可應用於手工操作中，也可以應用到電腦或網路裡。此系統可將相關內容集中儲存並具有群組管理、版本控制等功能。版本控制是內容管理系統的一個主要優勢。
 <p>
 
        </section>


        					
        <!-- Example of nested vertical slides -->
        <section>

            <section>
                    <h2>什麼是CMSimpfly? 什麼是Fossil?</h2>
                    <p align=left>CMSimpfly是一個內容管理系統，它不需要資料庫即可運作。
	所有的資料都存在2個檔案裡面－ content.html（內容）和pagedata.php（頁面相關的數據）
</p>
                   <p align=left>
                   Fossil(軟體) :是一個分散式版本控制系統、缺陷跟蹤管理系統或被用來在軟體開發中使用的wiki軟體伺服器，資料不會因停電或系統崩潰而損失，因為它使用SQLite資料庫。

                    </p>
                    <br>
                   
            </section>
            
          
        </section>

        						
        <section>
            <h2>CMSimpfly特色</h2>
            <p>
           <p align=left> CMSimpfly是由CMSimple的開發分支CMSimply演變而來，而CMSimple由Python 3 和CherryPy程式語言寫成的

可以在網站中建立很多子目錄，正所謂“子網站”。而且每個子網站可以是不同的語言。
      </p>
        </section>
<section>
	<h2>什麼是OpenSSL驗證?</h2>
<p align=left>在電腦網路上，OpenSSL是一個開放原始碼的軟體函式庫套件，應用程式可以使用這個套件來進行安全通訊，避免竊聽，同時確認另一端連線者的身分。這個套件廣泛被應用在網際網路的網頁伺服器上。
	
	</section>
 <script src="https://cad-lab.github.io/cadlab_data/reveal/lib/js/head.min.js"></script>
        <script src="https://cad-lab.github.io/cadlab_data/reveal/js/reveal.js"></script>
        <script>
                // More info https://github.com/hakimel/reveal.js#configuration
                Reveal.initialize({
                    controls: true,
                    progress: true,
                    history: true,
                    center: true,
        
                    transition: 'slide', // none/fade/slide/convex/concave/zoom
        
                    // More info https://github.com/hakimel/reveal.js#dependencies
                    dependencies: [
                        { src: 'https://cad-lab.github.io/cadlab_data/reveal/lib/js/classList.js', condition: function() { return !document.body.classList; } },
                        { src: 'https://cad-lab.github.io/cadlab_data/reveal/plugin/markdown/marked.js', condition: function() { return !!document.querySelector( '[data-markdown]' ); } },
                        { src: 'https://cad-lab.github.io/cadlab_data/reveal/plugin/markdown/markdown.js', condition: function() { return !!document.querySelector( '[data-markdown]' ); } },
                        { src: 'https://cad-lab.github.io/cadlab_data/reveal/plugin/highlight/highlight.js', async: true, callback: function() { hljs.initHighlightingOnLoad(); } },
                        { src: 'https://cad-lab.github.io/cadlab_data/reveal/plugin/zoom-js/zoom.js', async: true },
                        { src: 'https://cad-lab.github.io/cadlab_data/reveal/plugin/notes/notes.js', async: true }
                    ]
                });
        </script>
        			
</div>

</div>

</body>
</html>
