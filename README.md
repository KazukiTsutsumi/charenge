# charenge
<html>
<head>
  <meta charset="utf-8">
  <link rel="stylesheet"type="text/css"href="a.css">
  <script type="text/javascript" src="http://code.jquery.com/jquery-2.1.4.min.js"></script>
  <script type="text/javascript" src="https://www.google.com/jsapi"></script>

  <script type="text/javascript" src="script.js"></script>

  <script type="text/javascript">
  google.load("feeds", "1");
  function initialize() {
    var feedurl = "http://news.livedoor.com/topics/rss/top.xml";
    var feed = new google.feeds.Feed(feedurl);
    feed.setNumEntries(10);
    feed.load(function (result){
      if (!result.error){
        for (var i = 0; i < result.feed.entries.length; i++) {
          var entry = result.feed.entries[i];
          var title = '<p><h1><a href="' + entry.link + '">' + entry.title + '</a></h1></p>';
          var conte = '<p>' + entry.contentSnippet + '</p>';
          var dates = '<p>' + entry.publishedDate + '</p>';
          $('#feed1').append('<div class="post"><p>' + title + conte + dates + '</p></div>');
          $('#feed1').append('<hr>');

        }
      }
    });
  }
  google.setOnLoadCallback(initialize);

</script>

<script type="text/javascript">
  google.load("feeds", "1");
  function initialize() {
  var feedurl = "http://news.livedoor.com/topics/rss/int.xml";
  var feed = new google.feeds.Feed(feedurl);
  feed.setNumEntries(10);
  feed.load(function (result){
    if (!result.error){
      for (var i = 0; i < result.feed.entries.length; i++) {
        var entry = result.feed.entries[i];
        var title = '<p><h1><a href="' + entry.link + '">' + entry.title + '</a></h1></p>';
        var conte = '<p>' + entry.contentSnippet + '</p>';
        var dates = '<p>' + entry.publishedDate + '</p>';
        $('#feed3').append('<div class="post"><p>' + title + conte + dates + '</p></div>');
        $('#feed3').append('<hr>');
      }
    }
  });
  }
  google.setOnLoadCallback(initialize);

  </script>
  <script type="text/javascript">
  google.load("feeds", "1");
  function initialize() {
  var feedurl = "http://news.livedoor.com/topics/rss/dom.xml";
  var feed = new google.feeds.Feed(feedurl);
  feed.setNumEntries(10);
  feed.load(function (result){
    if (!result.error){
      for (var i = 0; i < result.feed.entries.length; i++) {
        var entry = result.feed.entries[i];
        var title = '<p><h1><a href="' + entry.link + '">' + entry.title + '</a></h1></p>';
        var conte = '<p>' + entry.contentSnippet + '</p>';
        var dates = '<p>' + entry.publishedDate + '</p>';
        $('#feed2').append('<div class="post"><p>' + title + conte + dates + '</p></div>');
        $('#feed2').append('<hr>');
      }
    }
  });
  }
  google.setOnLoadCallback(initialize);
  </script>
  <script type="text/javascript">
  google.load("feeds", "1");
  function initialize() {
  var feedurl = "http://news.livedoor.com/topics/rss/eco.xml";
  var feed = new google.feeds.Feed(feedurl);
  feed.setNumEntries(10);
  feed.load(function (result){
    if (!result.error){
      for (var i = 0; i < result.feed.entries.length; i++) {
        var entry = result.feed.entries[i];
        var title = '<p><h1><a href="' + entry.link + '">' + entry.title + '</a></h1></p>';
        var conte = '<p>' + entry.contentSnippet + '</p>';
        var dates = '<p>' + entry.publishedDate + '</p>';
        $('#feed4').append('<div class="post"><p>' + title + conte + dates + '</p></div>');
        $('#feed4').append('<hr>');
      }
    }
  });
  }
  google.setOnLoadCallback(initialize);
  </script>
  <script type="text/javascript">
  google.load("feeds", "1");
  function initialize() {
  var feedurl = "http://news.livedoor.com/topics/rss/ent.xml";
  var feed = new google.feeds.Feed(feedurl);
  feed.setNumEntries(10);
  feed.load(function (result){
    if (!result.error){
      for (var i = 0; i < result.feed.entries.length; i++) {
        var entry = result.feed.entries[i];
        var title = '<p><h1><a href="' + entry.link + '">' + entry.title + '</a></h1></p>';
        var conte = '<p>' + entry.contentSnippet + '</p>';
        var dates = '<p>' + entry.publishedDate + '</p>';
        $('#feed5').append('<div class="post"><p>' + title + conte + dates + '</p></div>');
        $('#feed5').append('<hr>');
      }
    }
  });
  }
  google.setOnLoadCallback(initialize);
  </script>
  <script type="text/javascript">
  google.load("feeds", "1");
  function initialize() {
  var feedurl = "http://news.livedoor.com/topics/rss/spo.xml";
  var feed = new google.feeds.Feed(feedurl);
  feed.setNumEntries(10);
  feed.load(function (result){
    if (!result.error){
      for (var i = 0; i < result.feed.entries.length; i++) {
        var entry = result.feed.entries[i];
        var title = '<p><h1><a href="' + entry.link + '">' + entry.title + '</a></h1></p>';
        var conte = '<p>' + entry.contentSnippet + '</p>';
        var dates = '<p>' + entry.publishedDate + '</p>';
        $('#feed6').append('<div class="post"><p>' + title + conte + dates + '</p></div>');
        $('#feed6').append('<hr>');
      }
    }
  });
  }
  google.setOnLoadCallback(initialize);
  </script>
  <script type="text/javascript">
  google.load("feeds", "1");
  function initialize() {
  var feedurl = "http://news.livedoor.com/rss/summary/52.xml";
  var feed = new google.feeds.Feed(feedurl);
  feed.setNumEntries(10);
  feed.load(function (result){
    if (!result.error){
      for (var i = 0; i < result.feed.entries.length; i++) {
        var entry = result.feed.entries[i];
        var title = '<p><h1><a href="' + entry.link + '">' + entry.title + '</a></h1></p>';
        var conte = '<p>' + entry.contentSnippet + '</p>';
        var dates = '<p>' + entry.publishedDate + '</p>';
        $('#feed7').append('<div class="post"><p>' + title + conte + dates + '</p></div>');
        $('#feed7').append('<hr>');
      }
    }
  });
  }
  google.setOnLoadCallback(initialize);
  </script>
  <script type="text/javascript">
  google.load("feeds", "1");
  function initialize() {
  var feedurl = "http://news.livedoor.com/rss/summary/52.xml";
  var feed = new google.feeds.Feed(feedurl);
  feed.setNumEntries(10);
  feed.load(function (result){
    if (!result.error){
      for (var i = 0; i < result.feed.entries.length; i++) {
        var entry = result.feed.entries[i];
        var title = '<p><h1><a href="' + entry.link + '">' + entry.title + '</a></h1></p>';
        var conte = '<p>' + entry.contentSnippet + '</p>';
        var dates = '<p>' + entry.publishedDate + '</p>';
        $('#feed8').append('<div class="post"><p>' + title + conte + dates + '</p></div>');
        $('#feed8').append('<hr>');
      }
    }
  });
  }
  google.setOnLoadCallback(initialize);
  </script>
  <script type="text/javascript">
  google.load("feeds", "1");
  function initialize() {
  var feedurl = "http://news.livedoor.com/topics/rss/love.xml";
  var feed = new google.feeds.Feed(feedurl);
  feed.setNumEntries(10);
  feed.load(function (result){
    if (!result.error){
      for (var i = 0; i < result.feed.entries.length; i++) {
        var entry = result.feed.entries[i];
        var title = '<p><h1><a href="' + entry.link + '">' + entry.title + '</a></h1></p>';
        var conte = '<p>' + entry.contentSnippet + '</p>';
        var dates = '<p>' + entry.publishedDate + '</p>';
        $('#feed9').append('<div class="post"><p>' + title + conte + dates + '</p></div>');
        $('#feed9').append('<hr>');
      }
    }
  });
  }
  google.setOnLoadCallback(initialize);
  </script>
  <script type="text/javascript">
  google.load("feeds", "1");
  function initialize() {
  var feedurl = "http://news.livedoor.com/topics/rss/trend.xml";
  var feed = new google.feeds.Feed(feedurl);
  feed.setNumEntries(10);
  feed.load(function (result){
    if (!result.error){
      for (var i = 0; i < result.feed.entries.length; i++) {
        var entry = result.feed.entries[i];
        var title = '<p><h1><a href="' + entry.link + '">' + entry.title + '</a></h1></p>';
        var conte = '<p>' + entry.contentSnippet + '</p>';
        var dates = '<p>' + entry.publishedDate + '</p>';
        $('#feed10').append('<div class="post"><p>' + title + conte + dates + '</p></div>');
        $('#feed10').append('<hr>');
      }
    }
  });
  }
  google.setOnLoadCallback(initialize);
  </script>
</head>
<body>
<div id="site-box">

<div id="a-box">
  <p>
    <img id="s" src="newsimg.png">
  </p>
</div>

<div id="b-box">
    <nav class="tabbox">
      <li>
        <span  class="tab1"  onclick="ChangeTab('tab1'); return false;">
          主要
        </span>
      </li>
      <li >
        <span onclick="ChangeTab('tab2'); return false;">
          国内
        </span>
      </li>
      <li>
        <span class="tab3" onclick="ChangeTab('tab3'); return false;">
          海外
        </span>
      </li>
      <li>
        <span class="tab4" onclick="ChangeTab('tab4'); return false;">
          IT経済
        </span>
      </li>
      <li>
        <span class="tab5" onclick="ChangeTab('tab5'); return false;">
          芸能
        </span>
        </li>
      <li>
        <span class="tab6" onclick="ChangeTab('tab6'); return false;">
          スポーツ
        </span>
      </li>
      <li>
        <span class="tab7" onclick="ChangeTab('tab7'); return false;">
          映画
        </span>
      </li>
      <li>
        <span class="tab8" onclick="ChangeTab('tab8'); return false;">
          グルメ
        </span>
      </li>
      <li>
        <span class="tab9" onclick="ChangeTab('tab9'); return false;">
          女子
        </span>
      </li>
      <li>
        <span class="tab10" onclick="ChangeTab('tab10'); return false;">
          トレンド
        </span>
      </li>
    </nav>
</div>


<article id="c-box">
    <div id="tab1">
        <p id="feed1"></p>
    </div>
    <div id="tab2" >
        <p id="feed2" ></p>
    </div>
    <div id="tab3" >
        <p id="feed3"></p>
    </div>
    <div id="tab4" >
        <p id="feed4" ></p>
    </div>
    <div id="tab5">
        <p id="feed5"></p>
    </div>
    <div id="tab6">
        <p id="feed6"></p>
    </div>
    <div id="tab7" >
        <p id="feed7"></p>
    </div>
    <div id="tab8" >
        <p id="feed8"></p>
    </div>
    <div id="tab9" >
        <p id="feed9"></p>
    </div>
    <div id="tab10" >
        <p id="feed10"></p>
    </div>
</article>



<div id="d-box">
  <div id="kanrenkijibox"></div></div>

</div>

</body>
</html>
