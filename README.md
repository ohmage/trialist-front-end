master/bootstrap/                                                                                   000755  000767  000024  00000000000 12200247327 015023  5                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         master/bootstrap/css/                                                                               000755  000767  000024  00000000000 12152167766 015631  5                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         master/bootstrap/img/                                                                               000755  000767  000024  00000000000 12110524611 015571  5                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         master/bootstrap/js/                                                                                000755  000767  000024  00000000000 12110524611 015431  5                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         master/bootstrap/less/                                                                              000755  000767  000024  00000000000 12152167702 015775  5                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         master/bootstrap/less/dropdowns.less                                                                000644  000767  000024  00000233203 12136500402 020675  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                           


<!DOCTYPE html>
<html>
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# githubog: http://ogp.me/ns/fb/githubog#">
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <title>bootstrap/less/dropdowns.less at master · twitter/bootstrap</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub" />
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub" />
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-touch-icon-114.png" />
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-touch-icon-114.png" />
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-touch-icon-144.png" />
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-touch-icon-144.png" />
    <link rel="logo" type="image/svg" href="http://github-media-downloads.s3.amazonaws.com/github-logo.svg" />
    <link rel="xhr-socket" href="/_sockets">
    <meta name="msapplication-TileImage" content="/windows-tile.png">
    <meta name="msapplication-TileColor" content="#ffffff">

    
    
    <link rel="icon" type="image/x-icon" href="/favicon.ico" />

    <meta content="authenticity_token" name="csrf-param" />
<meta content="zXcNFkaalMeTegkIBO2aLckNrTRhcPrRqREcKcwfBlU=" name="csrf-token" />

    <link href="https://a248.e.akamai.net/assets.github.com/assets/github-ba9334f20ce3c230182573735217c391db5f0d28.css" media="all" rel="stylesheet" type="text/css" />
    <link href="https://a248.e.akamai.net/assets.github.com/assets/github2-f0f30526f0f97f3b8305a871ece055ff80f65878.css" media="all" rel="stylesheet" type="text/css" />
    


      <script src="https://a248.e.akamai.net/assets.github.com/assets/frameworks-010d500708696b4ecee44478b5229d626367e844.js" type="text/javascript"></script>
      <script src="https://a248.e.akamai.net/assets.github.com/assets/github-3650b119e8cb8e869962cc12cf15570bac2a8847.js" type="text/javascript"></script>
      
      <meta http-equiv="x-pjax-version" content="93043389b7957fb779950962f0003882">

        <link data-pjax-transient rel='permalink' href='/twitter/bootstrap/blob/37d0a30589e8bd74299b2d857c348d91396563ed/less/dropdowns.less'>
    <meta property="og:title" content="bootstrap"/>
    <meta property="og:type" content="githubog:gitrepository"/>
    <meta property="og:url" content="https://github.com/twitter/bootstrap"/>
    <meta property="og:image" content="https://secure.gravatar.com/avatar/2f4a8254d032a8ec5e4c48d461e54fcc?s=420&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png"/>
    <meta property="og:site_name" content="GitHub"/>
    <meta property="og:description" content="bootstrap - Sleek, intuitive, and powerful front-end framework for faster and easier web development."/>
    <meta property="twitter:card" content="summary"/>
    <meta property="twitter:site" content="@GitHub">
    <meta property="twitter:title" content="twitter/bootstrap"/>

    <meta name="description" content="bootstrap - Sleek, intuitive, and powerful front-end framework for faster and easier web development." />

  <link href="https://github.com/twitter/bootstrap/commits/master.atom" rel="alternate" title="Recent Commits to bootstrap:master" type="application/atom+xml" />

  </head>


  <body class="logged_in page-blob macintosh vis-public env-production  ">
    <div id="wrapper">

      

      
      
      

      <div class="header header-logged-in true">
  <div class="container clearfix">

    <a class="header-logo-blacktocat" href="https://github.com/">
  <span class="mega-icon mega-icon-blacktocat"></span>
</a>

    <div class="divider-vertical"></div>

    
  <a href="/notifications" class="notification-indicator tooltipped downwards" title="You have unread notifications">
    <span class="mail-status unread"></span>
  </a>
  <div class="divider-vertical"></div>


      <div class="command-bar js-command-bar  ">
            <form accept-charset="UTF-8" action="/search" class="command-bar-form" id="top_search_form" method="get">
  <a href="/search/advanced" class="advanced-search-icon tooltipped downwards command-bar-search" id="advanced_search" title="Advanced search"><span class="mini-icon mini-icon-advanced-search "></span></a>

  <input type="text" data-hotkey="/ s" name="q" id="js-command-bar-field" placeholder="Search or type a command" tabindex="1" data-username="jojenki" autocapitalize="off">

  <span class="mini-icon help tooltipped downwards" title="Show command bar help">
    <span class="mini-icon mini-icon-help"></span>
  </span>

  <input type="hidden" name="ref" value="cmdform">

    <input type="hidden" class="js-repository-name-with-owner" value="twitter/bootstrap"/>
    <input type="hidden" class="js-repository-branch" value="master"/>
    <input type="hidden" class="js-repository-tree-sha" value="aa216022c839324948797ba7d75cac577cfbfed0"/>

  <div class="divider-vertical"></div>
</form>
        <ul class="top-nav">
            <li class="explore"><a href="https://github.com/explore">Explore</a></li>
            <li><a href="https://gist.github.com">Gist</a></li>
            <li><a href="/blog">Blog</a></li>
          <li><a href="http://help.github.com">Help</a></li>
        </ul>
      </div>

    

  
    <ul id="user-links">
      <li>
        <a href="https://github.com/jojenki" class="name">
          <img height="20" src="https://secure.gravatar.com/avatar/5f6038d19f287812c9b94ddd1d189d47?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="20" /> jojenki
        </a>
      </li>
      <li>
        <a href="/new" id="new_repo" class="tooltipped downwards" title="Create a new repo">
          <span class="mini-icon mini-icon-create"></span>
        </a>
      </li>
      <li>
        <a href="/settings/profile" id="account_settings"
          class="tooltipped downwards"
          title="Account settings ">
          <span class="mini-icon mini-icon-account-settings"></span>
        </a>
      </li>
      <li>
        <a href="/logout" data-method="post" id="logout" class="tooltipped downwards" title="Sign out">
          <span class="mini-icon mini-icon-logout"></span>
        </a>
      </li>
    </ul>



    
  </div>
</div>

      

      

      


            <div class="site hfeed" itemscope itemtype="http://schema.org/WebPage">
      <div class="hentry">
        
        <div class="pagehead repohead instapaper_ignore readability-menu ">
          <div class="container">
            <div class="title-actions-bar">
              


<ul class="pagehead-actions">


    <li class="subscription">
      <form accept-charset="UTF-8" action="/notifications/subscribe" data-autosubmit="true" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="authenticity_token" type="hidden" value="zXcNFkaalMeTegkIBO2aLckNrTRhcPrRqREcKcwfBlU=" /></div>  <input id="repository_id" name="repository_id" type="hidden" value="2126244" />

    <div class="select-menu js-menu-container js-select-menu">
      <span class="minibutton select-menu-button js-menu-target">
        <span class="js-select-button">
          <span class="mini-icon mini-icon-watching"></span>
          Watch
        </span>
      </span>

      <div class="select-menu-modal-holder js-menu-content">
        <div class="select-menu-modal">
          <div class="select-menu-header">
            <span class="select-menu-title">Notification status</span>
            <span class="mini-icon mini-icon-remove-close js-menu-close"></span>
          </div> <!-- /.select-menu-header -->

          <div class="select-menu-list js-navigation-container">

            <div class="select-menu-item js-navigation-item js-navigation-target selected">
              <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
              <div class="select-menu-item-text">
                <input checked="checked" id="do_included" name="do" type="radio" value="included" />
                <h4>Not watching</h4>
                <span class="description">You only receive notifications for discussions in which you participate or are @mentioned.</span>
                <span class="js-select-button-text hidden-select-button-text">
                  <span class="mini-icon mini-icon-watching"></span>
                  Watch
                </span>
              </div>
            </div> <!-- /.select-menu-item -->

            <div class="select-menu-item js-navigation-item js-navigation-target ">
              <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
              <div class="select-menu-item-text">
                <input id="do_subscribed" name="do" type="radio" value="subscribed" />
                <h4>Watching</h4>
                <span class="description">You receive notifications for all discussions in this repository.</span>
                <span class="js-select-button-text hidden-select-button-text">
                  <span class="mini-icon mini-icon-unwatch"></span>
                  Unwatch
                </span>
              </div>
            </div> <!-- /.select-menu-item -->

            <div class="select-menu-item js-navigation-item js-navigation-target ">
              <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
              <div class="select-menu-item-text">
                <input id="do_ignore" name="do" type="radio" value="ignore" />
                <h4>Ignoring</h4>
                <span class="description">You do not receive any notifications for discussions in this repository.</span>
                <span class="js-select-button-text hidden-select-button-text">
                  <span class="mini-icon mini-icon-mute"></span>
                  Stop ignoring
                </span>
              </div>
            </div> <!-- /.select-menu-item -->

          </div> <!-- /.select-menu-list -->

        </div> <!-- /.select-menu-modal -->
      </div> <!-- /.select-menu-modal-holder -->
    </div> <!-- /.select-menu -->

</form>
    </li>

    <li class="js-toggler-container js-social-container starring-container ">
      <a href="/twitter/bootstrap/unstar" class="minibutton js-toggler-target star-button starred upwards" title="Unstar this repo" data-remote="true" data-method="post" rel="nofollow">
        <span class="mini-icon mini-icon-remove-star"></span>
        <span class="text">Unstar</span>
      </a>
      <a href="/twitter/bootstrap/star" class="minibutton js-toggler-target star-button unstarred upwards" title="Star this repo" data-remote="true" data-method="post" rel="nofollow">
        <span class="mini-icon mini-icon-star"></span>
        <span class="text">Star</span>
      </a>
      <a class="social-count js-social-count" href="/twitter/bootstrap/stargazers">48,271</a>
    </li>

        <li>
          <a href="/twitter/bootstrap/fork_select" class="minibutton js-toggler-target fork-button lighter upwards" title="Fork this repo" rel="facebox nofollow">
            <span class="mini-icon mini-icon-branch-create"></span>
            <span class="text">Fork</span>
          </a>
          <a href="/twitter/bootstrap/network" class="social-count">14,431</a>
        </li>


</ul>

              <h1 itemscope itemtype="http://data-vocabulary.org/Breadcrumb" class="entry-title public">
                <span class="repo-label"><span>public</span></span>
                <span class="mega-icon mega-icon-public-repo"></span>
                <span class="author vcard">
                  <a href="/twitter" class="url fn" itemprop="url" rel="author">
                  <span itemprop="title">twitter</span>
                  </a></span> /
                <strong><a href="/twitter/bootstrap" class="js-current-repository">bootstrap</a></strong>
              </h1>
            </div>

            
  <ul class="tabs">
    <li><a href="/twitter/bootstrap" class="selected" highlight="repo_source repo_downloads repo_commits repo_tags repo_branches">Code</a></li>
    <li><a href="/twitter/bootstrap/network" highlight="repo_network">Network</a></li>
    <li><a href="/twitter/bootstrap/pulls" highlight="repo_pulls">Pull Requests <span class='counter'>76</span></a></li>

      <li><a href="/twitter/bootstrap/issues" highlight="repo_issues">Issues <span class='counter'>175</span></a></li>

      <li><a href="/twitter/bootstrap/wiki" highlight="repo_wiki">Wiki</a></li>


    <li><a href="/twitter/bootstrap/graphs" highlight="repo_graphs repo_contributors">Graphs</a></li>


  </ul>
  
<div class="tabnav">

  <span class="tabnav-right">
    <ul class="tabnav-tabs">
          <li><a href="/twitter/bootstrap/tags" class="tabnav-tab" highlight="repo_tags">Tags <span class="counter ">18</span></a></li>
    </ul>
    
  </span>

  <div class="tabnav-widget scope">


    <div class="select-menu js-menu-container js-select-menu js-branch-menu">
      <a class="minibutton select-menu-button js-menu-target" data-hotkey="w" data-ref="master">
        <span class="mini-icon mini-icon-branch"></span>
        <i>branch:</i>
        <span class="js-select-button">master</span>
      </a>

      <div class="select-menu-modal-holder js-menu-content js-navigation-container">

        <div class="select-menu-modal">
          <div class="select-menu-header">
            <span class="select-menu-title">Switch branches/tags</span>
            <span class="mini-icon mini-icon-remove-close js-menu-close"></span>
          </div> <!-- /.select-menu-header -->

          <div class="select-menu-filters">
            <div class="select-menu-text-filter">
              <input type="text" id="commitish-filter-field" class="js-filterable-field js-navigation-enable" placeholder="Filter branches/tags">
            </div>
            <div class="select-menu-tabs">
              <ul>
                <li class="select-menu-tab">
                  <a href="#" data-tab-filter="branches" class="js-select-menu-tab">Branches</a>
                </li>
                <li class="select-menu-tab">
                  <a href="#" data-tab-filter="tags" class="js-select-menu-tab">Tags</a>
                </li>
              </ul>
            </div><!-- /.select-menu-tabs -->
          </div><!-- /.select-menu-filters -->

          <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket css-truncate" data-tab-filter="branches">

            <div data-filterable-for="commitish-filter-field" data-filterable-type="substring">

                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/3.0.0-wip/less/dropdowns.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="3.0.0-wip" rel="nofollow" title="3.0.0-wip">3.0.0-wip</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/bootjack/less/dropdowns.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="bootjack" rel="nofollow" title="bootjack">bootjack</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/bs3_makefile_separated_done/less/dropdowns.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="bs3_makefile_separated_done" rel="nofollow" title="bs3_makefile_separated_done">bs3_makefile_separated_done</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/gh-pages/less/dropdowns.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="gh-pages" rel="nofollow" title="gh-pages">gh-pages</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target selected">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/master/less/dropdowns.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="master" rel="nofollow" title="master">master</a>
                </div> <!-- /.select-menu-item -->
            </div>

              <div class="select-menu-no-results">Nothing to show</div>
          </div> <!-- /.select-menu-list -->


          <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket css-truncate" data-tab-filter="tags">
            <div data-filterable-for="commitish-filter-field" data-filterable-type="substring">

                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/v2.3.1/less/dropdowns.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="v2.3.1" rel="nofollow" title="v2.3.1">v2.3.1</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/v2.3.0/less/dropdowns.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="v2.3.0" rel="nofollow" title="v2.3.0">v2.3.0</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/v2.2.2/less/dropdowns.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="v2.2.2" rel="nofollow" title="v2.2.2">v2.2.2</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/v2.2.1/less/dropdowns.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="v2.2.1" rel="nofollow" title="v2.2.1">v2.2.1</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/v2.2.0/less/dropdowns.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="v2.2.0" rel="nofollow" title="v2.2.0">v2.2.0</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/v2.1.1/less/dropdowns.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="v2.1.1" rel="nofollow" title="v2.1.1">v2.1.1</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/v2.1.0/less/dropdowns.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="v2.1.0" rel="nofollow" title="v2.1.0">v2.1.0</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/v2.0.4/less/dropdowns.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="v2.0.4" rel="nofollow" title="v2.0.4">v2.0.4</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/v2.0.3/less/dropdowns.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="v2.0.3" rel="nofollow" title="v2.0.3">v2.0.3</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/v2.0.2/less/dropdowns.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="v2.0.2" rel="nofollow" title="v2.0.2">v2.0.2</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/v2.0.1/less/dropdowns.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="v2.0.1" rel="nofollow" title="v2.0.1">v2.0.1</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/v2.0.0/less/dropdowns.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="v2.0.0" rel="nofollow" title="v2.0.0">v2.0.0</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/v1.4.0/less/dropdowns.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="v1.4.0" rel="nofollow" title="v1.4.0">v1.4.0</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/v1.3.0/less/dropdowns.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="v1.3.0" rel="nofollow" title="v1.3.0">v1.3.0</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/v1.2.0/less/dropdowns.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="v1.2.0" rel="nofollow" title="v1.2.0">v1.2.0</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/v1.1.1/less/dropdowns.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="v1.1.1" rel="nofollow" title="v1.1.1">v1.1.1</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/v1.1.0/less/dropdowns.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="v1.1.0" rel="nofollow" title="v1.1.0">v1.1.0</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/v1.0.0/less/dropdowns.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="v1.0.0" rel="nofollow" title="v1.0.0">v1.0.0</a>
                </div> <!-- /.select-menu-item -->
            </div>

            <div class="select-menu-no-results">Nothing to show</div>

          </div> <!-- /.select-menu-list -->

        </div> <!-- /.select-menu-modal -->
      </div> <!-- /.select-menu-modal-holder -->
    </div> <!-- /.select-menu -->

  </div> <!-- /.scope -->

  <ul class="tabnav-tabs">
    <li><a href="/twitter/bootstrap" class="selected tabnav-tab" highlight="repo_source">Files</a></li>
    <li><a href="/twitter/bootstrap/commits/master" class="tabnav-tab" highlight="repo_commits">Commits</a></li>
    <li><a href="/twitter/bootstrap/branches" class="tabnav-tab" highlight="repo_branches" rel="nofollow">Branches <span class="counter ">5</span></a></li>
  </ul>

</div>

  
  
  


            
          </div>
        </div><!-- /.repohead -->

        <div id="js-repo-pjax-container" class="container context-loader-container" data-pjax-container>
          


<!-- blob contrib key: blob_contributors:v21:2e895c97673692efaaf48b27dd386dc9 -->
<!-- blob contrib frag key: views10/v8/blob_contributors:v21:2e895c97673692efaaf48b27dd386dc9 -->


<div id="slider">
    <div class="frame-meta">

      <p title="This is a placeholder element" class="js-history-link-replace hidden"></p>

        <div class="breadcrumb">
          <span class='bold'><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/twitter/bootstrap" class="js-slide-to" data-branch="master" data-direction="back" itemscope="url"><span itemprop="title">bootstrap</span></a></span></span><span class="separator"> / </span><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/twitter/bootstrap/tree/master/less" class="js-slide-to" data-branch="master" data-direction="back" itemscope="url"><span itemprop="title">less</span></a></span><span class="separator"> / </span><strong class="final-path">dropdowns.less</strong> <span class="js-zeroclipboard zeroclipboard-button" data-clipboard-text="less/dropdowns.less" data-copied-hint="copied!" title="copy to clipboard"><span class="mini-icon mini-icon-clipboard"></span></span>
        </div>

      <a href="/twitter/bootstrap/find/master" class="js-slide-to" data-hotkey="t" style="display:none">Show File Finder</a>


        
  <div class="commit file-history-tease">
    <img class="main-avatar" height="24" src="https://secure.gravatar.com/avatar/bc4ab438f7a4ce1c406aadc688427f2c?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="24" />
    <span class="author"><a href="/mdo" rel="author">mdo</a></span>
    <time class="js-relative-date" datetime="2013-02-05T19:40:32-08:00" title="2013-02-05 19:40:32">February 05, 2013</time>
    <div class="commit-title">
        <a href="/twitter/bootstrap/commit/9443eb6e21dc784a98d01aa2206bf0807e549873" class="message">restore comma between selectors</a>
    </div>

    <div class="participation">
      <p class="quickstat"><a href="#blob_contributors_box" rel="facebox"><strong>10</strong> contributors</a></p>
          <a class="avatar tooltipped downwards" title="mdo" href="/twitter/bootstrap/commits/master/less/dropdowns.less?author=mdo"><img height="20" src="https://secure.gravatar.com/avatar/bc4ab438f7a4ce1c406aadc688427f2c?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="20" /></a>
    <a class="avatar tooltipped downwards" title="fat" href="/twitter/bootstrap/commits/master/less/dropdowns.less?author=fat"><img height="20" src="https://secure.gravatar.com/avatar/a98244cbdacaf1c0b55499466002f7a8?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="20" /></a>
    <a class="avatar tooltipped downwards" title="advancedrei" href="/twitter/bootstrap/commits/master/less/dropdowns.less?author=advancedrei"><img height="20" src="https://secure.gravatar.com/avatar/0b02bf5795b1cd659796f6e9016e5de0?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="20" /></a>
    <a class="avatar tooltipped downwards" title="philippm" href="/twitter/bootstrap/commits/master/less/dropdowns.less?author=philippm"><img height="20" src="https://secure.gravatar.com/avatar/b480ce8cd1cd60992f3e649750cd1288?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="20" /></a>
    <a class="avatar tooltipped downwards" title="phopkins" href="/twitter/bootstrap/commits/master/less/dropdowns.less?author=phopkins"><img height="20" src="https://secure.gravatar.com/avatar/30d1327440bc75e4203b301ca0ee3286?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="20" /></a>
    <a class="avatar tooltipped downwards" title="patrickhlauke" href="/twitter/bootstrap/commits/master/less/dropdowns.less?author=patrickhlauke"><img height="20" src="https://secure.gravatar.com/avatar/357f279672db832fc41a5a2f36559fcb?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="20" /></a>
    <a class="avatar tooltipped downwards" title="jacobrask" href="/twitter/bootstrap/commits/master/less/dropdowns.less?author=jacobrask"><img height="20" src="https://secure.gravatar.com/avatar/741704f57835da6c8a5d17a6c998960c?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="20" /></a>
    <a class="avatar tooltipped downwards" title="Ninir" href="/twitter/bootstrap/commits/master/less/dropdowns.less?author=Ninir"><img height="20" src="https://secure.gravatar.com/avatar/dcd699d644191cbcaf386843e065f893?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="20" /></a>
    <a class="avatar tooltipped downwards" title="charettes" href="/twitter/bootstrap/commits/master/less/dropdowns.less?author=charettes"><img height="20" src="https://secure.gravatar.com/avatar/428a62eedcccc5c82cee1bb972ea3cd5?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="20" /></a>
    <a class="avatar tooltipped downwards" title="buraktuyan" href="/twitter/bootstrap/commits/master/less/dropdowns.less?author=buraktuyan"><img height="20" src="https://secure.gravatar.com/avatar/e5436a0c87b98c2ec786e99a33660a8c?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="20" /></a>


    </div>
    <div id="blob_contributors_box" style="display:none">
      <h2>Users on GitHub who have contributed to this file</h2>
      <ul class="facebox-user-list">
        <li>
          <img height="24" src="https://secure.gravatar.com/avatar/bc4ab438f7a4ce1c406aadc688427f2c?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="24" />
          <a href="/mdo">mdo</a>
        </li>
        <li>
          <img height="24" src="https://secure.gravatar.com/avatar/a98244cbdacaf1c0b55499466002f7a8?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="24" />
          <a href="/fat">fat</a>
        </li>
        <li>
          <img height="24" src="https://secure.gravatar.com/avatar/0b02bf5795b1cd659796f6e9016e5de0?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="24" />
          <a href="/advancedrei">advancedrei</a>
        </li>
        <li>
          <img height="24" src="https://secure.gravatar.com/avatar/b480ce8cd1cd60992f3e649750cd1288?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="24" />
          <a href="/philippm">philippm</a>
        </li>
        <li>
          <img height="24" src="https://secure.gravatar.com/avatar/30d1327440bc75e4203b301ca0ee3286?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="24" />
          <a href="/phopkins">phopkins</a>
        </li>
        <li>
          <img height="24" src="https://secure.gravatar.com/avatar/357f279672db832fc41a5a2f36559fcb?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="24" />
          <a href="/patrickhlauke">patrickhlauke</a>
        </li>
        <li>
          <img height="24" src="https://secure.gravatar.com/avatar/741704f57835da6c8a5d17a6c998960c?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="24" />
          <a href="/jacobrask">jacobrask</a>
        </li>
        <li>
          <img height="24" src="https://secure.gravatar.com/avatar/dcd699d644191cbcaf386843e065f893?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="24" />
          <a href="/Ninir">Ninir</a>
        </li>
        <li>
          <img height="24" src="https://secure.gravatar.com/avatar/428a62eedcccc5c82cee1bb972ea3cd5?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="24" />
          <a href="/charettes">charettes</a>
        </li>
        <li>
          <img height="24" src="https://secure.gravatar.com/avatar/e5436a0c87b98c2ec786e99a33660a8c?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="24" />
          <a href="/buraktuyan">buraktuyan</a>
        </li>
      </ul>
    </div>
  </div>


    </div><!-- ./.frame-meta -->

    <div class="frames">
      <div class="frame" data-permalink-url="/twitter/bootstrap/blob/37d0a30589e8bd74299b2d857c348d91396563ed/less/dropdowns.less" data-title="bootstrap/less/dropdowns.less at master · twitter/bootstrap · GitHub" data-type="blob">

        <div id="files" class="bubble">
          <div class="file">
            <div class="meta">
              <div class="info">
                <span class="icon"><b class="mini-icon mini-icon-text-file"></b></span>
                <span class="mode" title="File Mode">file</span>
                  <span>238 lines (215 sloc)</span>
                <span>5.493 kb</span>
              </div>
              <div class="actions">
                <div class="button-group">
                        <a class="minibutton tooltipped leftwards"
                           title="Clicking this button will automatically fork this project so you can edit the file"
                           href="/twitter/bootstrap/edit/master/less/dropdowns.less"
                           data-method="post" rel="nofollow">Edit</a>
                  <a href="/twitter/bootstrap/raw/master/less/dropdowns.less" class="button minibutton " id="raw-url">Raw</a>
                    <a href="/twitter/bootstrap/blame/master/less/dropdowns.less" class="button minibutton ">Blame</a>
                  <a href="/twitter/bootstrap/commits/master/less/dropdowns.less" class="button minibutton " rel="nofollow">History</a>
                </div><!-- /.button-group -->
              </div><!-- /.actions -->

            </div>
                <div class="blob-wrapper data type-less js-blob-data">
      <table class="file-code file-blob">
        <tr class="file-code-line">
          <td class="blob-line-nums">
            <span id="L1" rel="#L1">1</span>
<span id="L2" rel="#L2">2</span>
<span id="L3" rel="#L3">3</span>
<span id="L4" rel="#L4">4</span>
<span id="L5" rel="#L5">5</span>
<span id="L6" rel="#L6">6</span>
<span id="L7" rel="#L7">7</span>
<span id="L8" rel="#L8">8</span>
<span id="L9" rel="#L9">9</span>
<span id="L10" rel="#L10">10</span>
<span id="L11" rel="#L11">11</span>
<span id="L12" rel="#L12">12</span>
<span id="L13" rel="#L13">13</span>
<span id="L14" rel="#L14">14</span>
<span id="L15" rel="#L15">15</span>
<span id="L16" rel="#L16">16</span>
<span id="L17" rel="#L17">17</span>
<span id="L18" rel="#L18">18</span>
<span id="L19" rel="#L19">19</span>
<span id="L20" rel="#L20">20</span>
<span id="L21" rel="#L21">21</span>
<span id="L22" rel="#L22">22</span>
<span id="L23" rel="#L23">23</span>
<span id="L24" rel="#L24">24</span>
<span id="L25" rel="#L25">25</span>
<span id="L26" rel="#L26">26</span>
<span id="L27" rel="#L27">27</span>
<span id="L28" rel="#L28">28</span>
<span id="L29" rel="#L29">29</span>
<span id="L30" rel="#L30">30</span>
<span id="L31" rel="#L31">31</span>
<span id="L32" rel="#L32">32</span>
<span id="L33" rel="#L33">33</span>
<span id="L34" rel="#L34">34</span>
<span id="L35" rel="#L35">35</span>
<span id="L36" rel="#L36">36</span>
<span id="L37" rel="#L37">37</span>
<span id="L38" rel="#L38">38</span>
<span id="L39" rel="#L39">39</span>
<span id="L40" rel="#L40">40</span>
<span id="L41" rel="#L41">41</span>
<span id="L42" rel="#L42">42</span>
<span id="L43" rel="#L43">43</span>
<span id="L44" rel="#L44">44</span>
<span id="L45" rel="#L45">45</span>
<span id="L46" rel="#L46">46</span>
<span id="L47" rel="#L47">47</span>
<span id="L48" rel="#L48">48</span>
<span id="L49" rel="#L49">49</span>
<span id="L50" rel="#L50">50</span>
<span id="L51" rel="#L51">51</span>
<span id="L52" rel="#L52">52</span>
<span id="L53" rel="#L53">53</span>
<span id="L54" rel="#L54">54</span>
<span id="L55" rel="#L55">55</span>
<span id="L56" rel="#L56">56</span>
<span id="L57" rel="#L57">57</span>
<span id="L58" rel="#L58">58</span>
<span id="L59" rel="#L59">59</span>
<span id="L60" rel="#L60">60</span>
<span id="L61" rel="#L61">61</span>
<span id="L62" rel="#L62">62</span>
<span id="L63" rel="#L63">63</span>
<span id="L64" rel="#L64">64</span>
<span id="L65" rel="#L65">65</span>
<span id="L66" rel="#L66">66</span>
<span id="L67" rel="#L67">67</span>
<span id="L68" rel="#L68">68</span>
<span id="L69" rel="#L69">69</span>
<span id="L70" rel="#L70">70</span>
<span id="L71" rel="#L71">71</span>
<span id="L72" rel="#L72">72</span>
<span id="L73" rel="#L73">73</span>
<span id="L74" rel="#L74">74</span>
<span id="L75" rel="#L75">75</span>
<span id="L76" rel="#L76">76</span>
<span id="L77" rel="#L77">77</span>
<span id="L78" rel="#L78">78</span>
<span id="L79" rel="#L79">79</span>
<span id="L80" rel="#L80">80</span>
<span id="L81" rel="#L81">81</span>
<span id="L82" rel="#L82">82</span>
<span id="L83" rel="#L83">83</span>
<span id="L84" rel="#L84">84</span>
<span id="L85" rel="#L85">85</span>
<span id="L86" rel="#L86">86</span>
<span id="L87" rel="#L87">87</span>
<span id="L88" rel="#L88">88</span>
<span id="L89" rel="#L89">89</span>
<span id="L90" rel="#L90">90</span>
<span id="L91" rel="#L91">91</span>
<span id="L92" rel="#L92">92</span>
<span id="L93" rel="#L93">93</span>
<span id="L94" rel="#L94">94</span>
<span id="L95" rel="#L95">95</span>
<span id="L96" rel="#L96">96</span>
<span id="L97" rel="#L97">97</span>
<span id="L98" rel="#L98">98</span>
<span id="L99" rel="#L99">99</span>
<span id="L100" rel="#L100">100</span>
<span id="L101" rel="#L101">101</span>
<span id="L102" rel="#L102">102</span>
<span id="L103" rel="#L103">103</span>
<span id="L104" rel="#L104">104</span>
<span id="L105" rel="#L105">105</span>
<span id="L106" rel="#L106">106</span>
<span id="L107" rel="#L107">107</span>
<span id="L108" rel="#L108">108</span>
<span id="L109" rel="#L109">109</span>
<span id="L110" rel="#L110">110</span>
<span id="L111" rel="#L111">111</span>
<span id="L112" rel="#L112">112</span>
<span id="L113" rel="#L113">113</span>
<span id="L114" rel="#L114">114</span>
<span id="L115" rel="#L115">115</span>
<span id="L116" rel="#L116">116</span>
<span id="L117" rel="#L117">117</span>
<span id="L118" rel="#L118">118</span>
<span id="L119" rel="#L119">119</span>
<span id="L120" rel="#L120">120</span>
<span id="L121" rel="#L121">121</span>
<span id="L122" rel="#L122">122</span>
<span id="L123" rel="#L123">123</span>
<span id="L124" rel="#L124">124</span>
<span id="L125" rel="#L125">125</span>
<span id="L126" rel="#L126">126</span>
<span id="L127" rel="#L127">127</span>
<span id="L128" rel="#L128">128</span>
<span id="L129" rel="#L129">129</span>
<span id="L130" rel="#L130">130</span>
<span id="L131" rel="#L131">131</span>
<span id="L132" rel="#L132">132</span>
<span id="L133" rel="#L133">133</span>
<span id="L134" rel="#L134">134</span>
<span id="L135" rel="#L135">135</span>
<span id="L136" rel="#L136">136</span>
<span id="L137" rel="#L137">137</span>
<span id="L138" rel="#L138">138</span>
<span id="L139" rel="#L139">139</span>
<span id="L140" rel="#L140">140</span>
<span id="L141" rel="#L141">141</span>
<span id="L142" rel="#L142">142</span>
<span id="L143" rel="#L143">143</span>
<span id="L144" rel="#L144">144</span>
<span id="L145" rel="#L145">145</span>
<span id="L146" rel="#L146">146</span>
<span id="L147" rel="#L147">147</span>
<span id="L148" rel="#L148">148</span>
<span id="L149" rel="#L149">149</span>
<span id="L150" rel="#L150">150</span>
<span id="L151" rel="#L151">151</span>
<span id="L152" rel="#L152">152</span>
<span id="L153" rel="#L153">153</span>
<span id="L154" rel="#L154">154</span>
<span id="L155" rel="#L155">155</span>
<span id="L156" rel="#L156">156</span>
<span id="L157" rel="#L157">157</span>
<span id="L158" rel="#L158">158</span>
<span id="L159" rel="#L159">159</span>
<span id="L160" rel="#L160">160</span>
<span id="L161" rel="#L161">161</span>
<span id="L162" rel="#L162">162</span>
<span id="L163" rel="#L163">163</span>
<span id="L164" rel="#L164">164</span>
<span id="L165" rel="#L165">165</span>
<span id="L166" rel="#L166">166</span>
<span id="L167" rel="#L167">167</span>
<span id="L168" rel="#L168">168</span>
<span id="L169" rel="#L169">169</span>
<span id="L170" rel="#L170">170</span>
<span id="L171" rel="#L171">171</span>
<span id="L172" rel="#L172">172</span>
<span id="L173" rel="#L173">173</span>
<span id="L174" rel="#L174">174</span>
<span id="L175" rel="#L175">175</span>
<span id="L176" rel="#L176">176</span>
<span id="L177" rel="#L177">177</span>
<span id="L178" rel="#L178">178</span>
<span id="L179" rel="#L179">179</span>
<span id="L180" rel="#L180">180</span>
<span id="L181" rel="#L181">181</span>
<span id="L182" rel="#L182">182</span>
<span id="L183" rel="#L183">183</span>
<span id="L184" rel="#L184">184</span>
<span id="L185" rel="#L185">185</span>
<span id="L186" rel="#L186">186</span>
<span id="L187" rel="#L187">187</span>
<span id="L188" rel="#L188">188</span>
<span id="L189" rel="#L189">189</span>
<span id="L190" rel="#L190">190</span>
<span id="L191" rel="#L191">191</span>
<span id="L192" rel="#L192">192</span>
<span id="L193" rel="#L193">193</span>
<span id="L194" rel="#L194">194</span>
<span id="L195" rel="#L195">195</span>
<span id="L196" rel="#L196">196</span>
<span id="L197" rel="#L197">197</span>
<span id="L198" rel="#L198">198</span>
<span id="L199" rel="#L199">199</span>
<span id="L200" rel="#L200">200</span>
<span id="L201" rel="#L201">201</span>
<span id="L202" rel="#L202">202</span>
<span id="L203" rel="#L203">203</span>
<span id="L204" rel="#L204">204</span>
<span id="L205" rel="#L205">205</span>
<span id="L206" rel="#L206">206</span>
<span id="L207" rel="#L207">207</span>
<span id="L208" rel="#L208">208</span>
<span id="L209" rel="#L209">209</span>
<span id="L210" rel="#L210">210</span>
<span id="L211" rel="#L211">211</span>
<span id="L212" rel="#L212">212</span>
<span id="L213" rel="#L213">213</span>
<span id="L214" rel="#L214">214</span>
<span id="L215" rel="#L215">215</span>
<span id="L216" rel="#L216">216</span>
<span id="L217" rel="#L217">217</span>
<span id="L218" rel="#L218">218</span>
<span id="L219" rel="#L219">219</span>
<span id="L220" rel="#L220">220</span>
<span id="L221" rel="#L221">221</span>
<span id="L222" rel="#L222">222</span>
<span id="L223" rel="#L223">223</span>
<span id="L224" rel="#L224">224</span>
<span id="L225" rel="#L225">225</span>
<span id="L226" rel="#L226">226</span>
<span id="L227" rel="#L227">227</span>
<span id="L228" rel="#L228">228</span>
<span id="L229" rel="#L229">229</span>
<span id="L230" rel="#L230">230</span>
<span id="L231" rel="#L231">231</span>
<span id="L232" rel="#L232">232</span>
<span id="L233" rel="#L233">233</span>
<span id="L234" rel="#L234">234</span>
<span id="L235" rel="#L235">235</span>
<span id="L236" rel="#L236">236</span>
<span id="L237" rel="#L237">237</span>

          </td>
          <td class="blob-line-code">
                  <div class="highlight"><pre><div class='line' id='LC1'><span class="o">//</span></div><div class='line' id='LC2'><span class="o">//</span> <span class="nt">Dropdown</span> <span class="nt">menus</span></div><div class='line' id='LC3'><span class="o">//</span> <span class="nt">--------------------------------------------------</span></div><div class='line' id='LC4'><br/></div><div class='line' id='LC5'><br/></div><div class='line' id='LC6'><span class="o">//</span> <span class="nt">Use</span> <span class="nt">the</span> <span class="nc">.menu</span> <span class="nt">class</span> <span class="nt">on</span> <span class="nt">any</span> <span class="o">&lt;</span><span class="nt">li</span><span class="o">&gt;</span> <span class="nt">element</span> <span class="nt">within</span> <span class="nt">the</span> <span class="nt">topbar</span> <span class="nt">or</span> <span class="nt">ul</span><span class="nc">.tabs</span> <span class="nt">and</span> <span class="nt">you</span><span class="s1">&#39;ll get some superfancy dropdowns</span></div><div class='line' id='LC7'><span class="s1">.dropup,</span></div><div class='line' id='LC8'><span class="s1">.dropdown {</span></div><div class='line' id='LC9'><span class="s1">  position: relative;</span></div><div class='line' id='LC10'><span class="s1">}</span></div><div class='line' id='LC11'><span class="s1">.dropdown-toggle {</span></div><div class='line' id='LC12'><span class="s1">  // The caret makes the toggle a bit too tall in IE7</span></div><div class='line' id='LC13'><span class="s1">  *margin-bottom: -3px;</span></div><div class='line' id='LC14'><span class="s1">}</span></div><div class='line' id='LC15'><span class="s1">.dropdown-toggle:active,</span></div><div class='line' id='LC16'><span class="s1">.open .dropdown-toggle {</span></div><div class='line' id='LC17'><span class="s1">  outline: 0;</span></div><div class='line' id='LC18'><span class="s1">}</span></div><div class='line' id='LC19'><br/></div><div class='line' id='LC20'><span class="s1">// Dropdown arrow/caret</span></div><div class='line' id='LC21'><span class="s1">// --------------------</span></div><div class='line' id='LC22'><span class="s1">.caret {</span></div><div class='line' id='LC23'><span class="s1">  display: inline-block;</span></div><div class='line' id='LC24'><span class="s1">  width: 0;</span></div><div class='line' id='LC25'><span class="s1">  height: 0;</span></div><div class='line' id='LC26'><span class="s1">  vertical-align: top;</span></div><div class='line' id='LC27'><span class="s1">  border-top:   4px solid @black;</span></div><div class='line' id='LC28'><span class="s1">  border-right: 4px solid transparent;</span></div><div class='line' id='LC29'><span class="s1">  border-left:  4px solid transparent;</span></div><div class='line' id='LC30'><span class="s1">  content: &quot;&quot;;</span></div><div class='line' id='LC31'><span class="s1">}</span></div><div class='line' id='LC32'><br/></div><div class='line' id='LC33'><span class="s1">// Place the caret</span></div><div class='line' id='LC34'><span class="s1">.dropdown .caret {</span></div><div class='line' id='LC35'><span class="s1">  margin-top: 8px;</span></div><div class='line' id='LC36'><span class="s1">  margin-left: 2px;</span></div><div class='line' id='LC37'><span class="s1">}</span></div><div class='line' id='LC38'><br/></div><div class='line' id='LC39'><span class="s1">// The dropdown menu (ul)</span></div><div class='line' id='LC40'><span class="s1">// ----------------------</span></div><div class='line' id='LC41'><span class="s1">.dropdown-menu {</span></div><div class='line' id='LC42'><span class="s1">  position: absolute;</span></div><div class='line' id='LC43'><span class="s1">  top: 100%;</span></div><div class='line' id='LC44'><span class="s1">  left: 0;</span></div><div class='line' id='LC45'><span class="s1">  z-index: @zindexDropdown;</span></div><div class='line' id='LC46'><span class="s1">  display: none; // none by default, but block on &quot;open&quot; of the menu</span></div><div class='line' id='LC47'><span class="s1">  float: left;</span></div><div class='line' id='LC48'><span class="s1">  min-width: 160px;</span></div><div class='line' id='LC49'><span class="s1">  padding: 5px 0;</span></div><div class='line' id='LC50'><span class="s1">  margin: 2px 0 0; // override default ul</span></div><div class='line' id='LC51'><span class="s1">  list-style: none;</span></div><div class='line' id='LC52'><span class="s1">  background-color: @dropdownBackground;</span></div><div class='line' id='LC53'><span class="s1">  border: 1px solid #ccc; // Fallback for IE7-8</span></div><div class='line' id='LC54'><span class="s1">  border: 1px solid @dropdownBorder;</span></div><div class='line' id='LC55'><span class="s1">  *border-right-width: 2px;</span></div><div class='line' id='LC56'><span class="s1">  *border-bottom-width: 2px;</span></div><div class='line' id='LC57'><span class="s1">  .border-radius(6px);</span></div><div class='line' id='LC58'><span class="s1">  .box-shadow(0 5px 10px rgba(0,0,0,.2));</span></div><div class='line' id='LC59'><span class="s1">  -webkit-background-clip: padding-box;</span></div><div class='line' id='LC60'><span class="s1">     -moz-background-clip: padding;</span></div><div class='line' id='LC61'><span class="s1">          background-clip: padding-box;</span></div><div class='line' id='LC62'><br/></div><div class='line' id='LC63'><span class="s1">  // Aligns the dropdown menu to right</span></div><div class='line' id='LC64'><span class="s1">  &amp;.pull-right {</span></div><div class='line' id='LC65'><span class="s1">    right: 0;</span></div><div class='line' id='LC66'><span class="s1">    left: auto;</span></div><div class='line' id='LC67'><span class="s1">  }</span></div><div class='line' id='LC68'><br/></div><div class='line' id='LC69'><span class="s1">  // Dividers (basically an hr) within the dropdown</span></div><div class='line' id='LC70'><span class="s1">  .divider {</span></div><div class='line' id='LC71'><span class="s1">    .nav-divider(@dropdownDividerTop, @dropdownDividerBottom);</span></div><div class='line' id='LC72'><span class="s1">  }</span></div><div class='line' id='LC73'><br/></div><div class='line' id='LC74'><span class="s1">  // Links within the dropdown menu</span></div><div class='line' id='LC75'><span class="s1">  &gt; li &gt; a {</span></div><div class='line' id='LC76'><span class="s1">    display: block;</span></div><div class='line' id='LC77'><span class="s1">    padding: 3px 20px;</span></div><div class='line' id='LC78'><span class="s1">    clear: both;</span></div><div class='line' id='LC79'><span class="s1">    font-weight: normal;</span></div><div class='line' id='LC80'><span class="s1">    line-height: @baseLineHeight;</span></div><div class='line' id='LC81'><span class="s1">    color: @dropdownLinkColor;</span></div><div class='line' id='LC82'><span class="s1">    white-space: nowrap;</span></div><div class='line' id='LC83'><span class="s1">  }</span></div><div class='line' id='LC84'><span class="s1">}</span></div><div class='line' id='LC85'><br/></div><div class='line' id='LC86'><span class="s1">// Hover/Focus state</span></div><div class='line' id='LC87'><span class="s1">// -----------</span></div><div class='line' id='LC88'><span class="s1">.dropdown-menu &gt; li &gt; a:hover,</span></div><div class='line' id='LC89'><span class="s1">.dropdown-menu &gt; li &gt; a:focus,</span></div><div class='line' id='LC90'><span class="s1">.dropdown-submenu:hover &gt; a,</span></div><div class='line' id='LC91'><span class="s1">.dropdown-submenu:focus &gt; a {</span></div><div class='line' id='LC92'><span class="s1">  text-decoration: none;</span></div><div class='line' id='LC93'><span class="s1">  color: @dropdownLinkColorHover;</span></div><div class='line' id='LC94'><span class="s1">  #gradient &gt; .vertical(@dropdownLinkBackgroundHover, darken(@dropdownLinkBackgroundHover, 5%));</span></div><div class='line' id='LC95'><span class="s1">}</span></div><div class='line' id='LC96'><br/></div><div class='line' id='LC97'><span class="s1">// Active state</span></div><div class='line' id='LC98'><span class="s1">// ------------</span></div><div class='line' id='LC99'><span class="s1">.dropdown-menu &gt; .active &gt; a,</span></div><div class='line' id='LC100'><span class="s1">.dropdown-menu &gt; .active &gt; a:hover,</span></div><div class='line' id='LC101'><span class="s1">.dropdown-menu &gt; .active &gt; a:focus {</span></div><div class='line' id='LC102'><span class="s1">  color: @dropdownLinkColorActive;</span></div><div class='line' id='LC103'><span class="s1">  text-decoration: none;</span></div><div class='line' id='LC104'><span class="s1">  outline: 0;</span></div><div class='line' id='LC105'><span class="s1">  #gradient &gt; .vertical(@dropdownLinkBackgroundActive, darken(@dropdownLinkBackgroundActive, 5%));</span></div><div class='line' id='LC106'><span class="s1">}</span></div><div class='line' id='LC107'><br/></div><div class='line' id='LC108'><span class="s1">// Disabled state</span></div><div class='line' id='LC109'><span class="s1">// --------------</span></div><div class='line' id='LC110'><span class="s1">// Gray out text and ensure the hover/focus state remains gray</span></div><div class='line' id='LC111'><span class="s1">.dropdown-menu &gt; .disabled &gt; a,</span></div><div class='line' id='LC112'><span class="s1">.dropdown-menu &gt; .disabled &gt; a:hover,</span></div><div class='line' id='LC113'><span class="s1">.dropdown-menu &gt; .disabled &gt; a:focus {</span></div><div class='line' id='LC114'><span class="s1">  color: @grayLight;</span></div><div class='line' id='LC115'><span class="s1">}</span></div><div class='line' id='LC116'><span class="s1">// Nuke hover/focus effects</span></div><div class='line' id='LC117'><span class="s1">.dropdown-menu &gt; .disabled &gt; a:hover,</span></div><div class='line' id='LC118'><span class="s1">.dropdown-menu &gt; .disabled &gt; a:focus {</span></div><div class='line' id='LC119'><span class="s1">  text-decoration: none;</span></div><div class='line' id='LC120'><span class="s1">  background-color: transparent;</span></div><div class='line' id='LC121'><span class="s1">  background-image: none; // Remove CSS gradient</span></div><div class='line' id='LC122'><span class="s1">  .reset-filter();</span></div><div class='line' id='LC123'><span class="s1">  cursor: default;</span></div><div class='line' id='LC124'><span class="s1">}</span></div><div class='line' id='LC125'><br/></div><div class='line' id='LC126'><span class="s1">// Open state for the dropdown</span></div><div class='line' id='LC127'><span class="s1">// ---------------------------</span></div><div class='line' id='LC128'><span class="s1">.open {</span></div><div class='line' id='LC129'><span class="s1">  // IE7&#39;</span><span class="nt">s</span> <span class="nt">z-index</span> <span class="nt">only</span> <span class="nt">goes</span> <span class="nt">to</span> <span class="nt">the</span> <span class="nt">nearest</span> <span class="nt">positioned</span> <span class="nt">ancestor</span><span class="o">,</span> <span class="nt">which</span> <span class="nt">would</span></div><div class='line' id='LC130'>&nbsp;&nbsp;<span class="o">//</span> <span class="nt">make</span> <span class="nt">the</span> <span class="nt">menu</span> <span class="nt">appear</span> <span class="nt">below</span> <span class="nt">buttons</span> <span class="nt">that</span> <span class="nt">appeared</span> <span class="nt">later</span> <span class="nt">on</span> <span class="nt">the</span> <span class="nt">page</span></div><div class='line' id='LC131'>&nbsp;&nbsp;<span class="o">*</span><span class="nt">z-index</span><span class="o">:</span> <span class="k">@zindexDropdown</span><span class="p">;</span></div><div class='line' id='LC132'><br/></div><div class='line' id='LC133'>&nbsp;&nbsp;<span class="o">&amp;</span> <span class="o">&gt;</span> <span class="nc">.dropdown-menu</span> <span class="p">{</span></div><div class='line' id='LC134'>&nbsp;&nbsp;&nbsp;&nbsp;<span class="k">display</span><span class="o">:</span> <span class="k">block</span><span class="p">;</span></div><div class='line' id='LC135'>&nbsp;&nbsp;<span class="p">}</span></div><div class='line' id='LC136'><span class="err">}</span></div><div class='line' id='LC137'><br/></div><div class='line' id='LC138'><span class="o">//</span> <span class="nt">Right</span> <span class="nt">aligned</span> <span class="nt">dropdowns</span></div><div class='line' id='LC139'><span class="o">//</span> <span class="nt">---------------------------</span></div><div class='line' id='LC140'><span class="nc">.pull-right</span> <span class="o">&gt;</span> <span class="nc">.dropdown-menu</span> <span class="p">{</span></div><div class='line' id='LC141'>&nbsp;&nbsp;<span class="k">right</span><span class="o">:</span> <span class="m">0</span><span class="p">;</span></div><div class='line' id='LC142'>&nbsp;&nbsp;<span class="k">left</span><span class="o">:</span> <span class="k">auto</span><span class="p">;</span></div><div class='line' id='LC143'><span class="p">}</span></div><div class='line' id='LC144'><br/></div><div class='line' id='LC145'><span class="o">//</span> <span class="nt">Allow</span> <span class="nt">for</span> <span class="nt">dropdowns</span> <span class="nt">to</span> <span class="nt">go</span> <span class="nt">bottom</span> <span class="nt">up</span> <span class="o">(</span><span class="nt">aka</span><span class="o">,</span> <span class="nt">dropup-menu</span><span class="o">)</span></div><div class='line' id='LC146'><span class="o">//</span> <span class="nt">------------------------------------------------------</span></div><div class='line' id='LC147'><span class="o">//</span> <span class="nt">Just</span> <span class="nt">add</span> <span class="nc">.dropup</span> <span class="nt">after</span> <span class="nt">the</span> <span class="nt">standard</span> <span class="nc">.dropdown</span> <span class="nt">class</span> <span class="nt">and</span> <span class="nt">you</span><span class="err">&#39;</span><span class="nt">re</span> <span class="nt">set</span><span class="o">,</span> <span class="nt">bro</span><span class="o">.</span></div><div class='line' id='LC148'><span class="o">//</span> <span class="nt">TODO</span><span class="o">:</span> <span class="nt">abstract</span> <span class="nt">this</span> <span class="nt">so</span> <span class="nt">that</span> <span class="nt">the</span> <span class="nt">navbar</span> <span class="nt">fixed</span> <span class="nt">styles</span> <span class="nt">are</span> <span class="nt">not</span> <span class="nt">placed</span> <span class="nt">here</span><span class="o">?</span></div><div class='line' id='LC149'><span class="nc">.dropup</span><span class="o">,</span></div><div class='line' id='LC150'><span class="nc">.navbar-fixed-bottom</span> <span class="nc">.dropdown</span> <span class="p">{</span></div><div class='line' id='LC151'>&nbsp;&nbsp;<span class="o">//</span> <span class="n">Reverse</span> <span class="n">the</span> <span class="n">caret</span></div><div class='line' id='LC152'>&nbsp;&nbsp;<span class="o">.</span><span class="n">caret</span> <span class="err">{</span></div><div class='line' id='LC153'>&nbsp;&nbsp;&nbsp;&nbsp;<span class="k">border-top</span><span class="o">:</span> <span class="m">0</span><span class="p">;</span></div><div class='line' id='LC154'>&nbsp;&nbsp;&nbsp;&nbsp;<span class="k">border-bottom</span><span class="o">:</span> <span class="m">4px</span> <span class="k">solid</span> <span class="o">@</span><span class="nb">black</span><span class="p">;</span></div><div class='line' id='LC155'>&nbsp;&nbsp;&nbsp;&nbsp;<span class="k">content</span><span class="o">:</span> <span class="s2">&quot;&quot;</span><span class="p">;</span></div><div class='line' id='LC156'>&nbsp;&nbsp;<span class="p">}</span></div><div class='line' id='LC157'>&nbsp;&nbsp;<span class="o">//</span> <span class="nt">Different</span> <span class="nt">positioning</span> <span class="nt">for</span> <span class="nt">bottom</span> <span class="nt">up</span> <span class="nt">menu</span></div><div class='line' id='LC158'>&nbsp;&nbsp;<span class="nc">.dropdown-menu</span> <span class="p">{</span></div><div class='line' id='LC159'>&nbsp;&nbsp;&nbsp;&nbsp;<span class="k">top</span><span class="o">:</span> <span class="k">auto</span><span class="p">;</span></div><div class='line' id='LC160'>&nbsp;&nbsp;&nbsp;&nbsp;<span class="k">bottom</span><span class="o">:</span> <span class="m">100</span><span class="o">%</span><span class="p">;</span></div><div class='line' id='LC161'>&nbsp;&nbsp;&nbsp;&nbsp;<span class="k">margin-bottom</span><span class="o">:</span> <span class="m">1px</span><span class="p">;</span></div><div class='line' id='LC162'>&nbsp;&nbsp;<span class="p">}</span></div><div class='line' id='LC163'><span class="err">}</span></div><div class='line' id='LC164'><br/></div><div class='line' id='LC165'><span class="o">//</span> <span class="nt">Sub</span> <span class="nt">menus</span></div><div class='line' id='LC166'><span class="o">//</span> <span class="nt">---------------------------</span></div><div class='line' id='LC167'><span class="nc">.dropdown-submenu</span> <span class="p">{</span></div><div class='line' id='LC168'>&nbsp;&nbsp;<span class="k">position</span><span class="o">:</span> <span class="k">relative</span><span class="p">;</span></div><div class='line' id='LC169'><span class="p">}</span></div><div class='line' id='LC170'><span class="o">//</span> <span class="nt">Default</span> <span class="nt">dropdowns</span></div><div class='line' id='LC171'><span class="nc">.dropdown-submenu</span> <span class="o">&gt;</span> <span class="nc">.dropdown-menu</span> <span class="p">{</span></div><div class='line' id='LC172'>&nbsp;&nbsp;<span class="k">top</span><span class="o">:</span> <span class="m">0</span><span class="p">;</span></div><div class='line' id='LC173'>&nbsp;&nbsp;<span class="k">left</span><span class="o">:</span> <span class="m">100</span><span class="o">%</span><span class="p">;</span></div><div class='line' id='LC174'>&nbsp;&nbsp;<span class="k">margin-top</span><span class="o">:</span> <span class="m">-6px</span><span class="p">;</span></div><div class='line' id='LC175'>&nbsp;&nbsp;<span class="k">margin-left</span><span class="o">:</span> <span class="m">-1px</span><span class="p">;</span></div><div class='line' id='LC176'>&nbsp;&nbsp;<span class="o">.</span><span class="k">border</span><span class="o">-</span><span class="n">radius</span><span class="p">(</span><span class="m">0</span> <span class="m">6px</span> <span class="m">6px</span> <span class="m">6px</span><span class="p">);</span></div><div class='line' id='LC177'><span class="p">}</span></div><div class='line' id='LC178'><span class="nc">.dropdown-submenu</span><span class="nd">:hover</span> <span class="o">&gt;</span> <span class="nc">.dropdown-menu</span> <span class="p">{</span></div><div class='line' id='LC179'>&nbsp;&nbsp;<span class="k">display</span><span class="o">:</span> <span class="k">block</span><span class="p">;</span></div><div class='line' id='LC180'><span class="p">}</span></div><div class='line' id='LC181'><br/></div><div class='line' id='LC182'><span class="o">//</span> <span class="nt">Dropups</span></div><div class='line' id='LC183'><span class="nc">.dropup</span> <span class="nc">.dropdown-submenu</span> <span class="o">&gt;</span> <span class="nc">.dropdown-menu</span> <span class="p">{</span></div><div class='line' id='LC184'>&nbsp;&nbsp;<span class="k">top</span><span class="o">:</span> <span class="k">auto</span><span class="p">;</span></div><div class='line' id='LC185'>&nbsp;&nbsp;<span class="k">bottom</span><span class="o">:</span> <span class="m">0</span><span class="p">;</span></div><div class='line' id='LC186'>&nbsp;&nbsp;<span class="k">margin-top</span><span class="o">:</span> <span class="m">0</span><span class="p">;</span></div><div class='line' id='LC187'>&nbsp;&nbsp;<span class="k">margin-bottom</span><span class="o">:</span> <span class="m">-2px</span><span class="p">;</span></div><div class='line' id='LC188'>&nbsp;&nbsp;<span class="o">.</span><span class="k">border</span><span class="o">-</span><span class="n">radius</span><span class="p">(</span><span class="m">5px</span> <span class="m">5px</span> <span class="m">5px</span> <span class="m">0</span><span class="p">);</span></div><div class='line' id='LC189'><span class="p">}</span></div><div class='line' id='LC190'><br/></div><div class='line' id='LC191'><span class="o">//</span> <span class="nt">Caret</span> <span class="nt">to</span> <span class="nt">indicate</span> <span class="nt">there</span> <span class="nt">is</span> <span class="nt">a</span> <span class="nt">submenu</span></div><div class='line' id='LC192'><span class="nc">.dropdown-submenu</span> <span class="o">&gt;</span> <span class="nt">a</span><span class="nd">:after</span> <span class="p">{</span></div><div class='line' id='LC193'>&nbsp;&nbsp;<span class="k">display</span><span class="o">:</span> <span class="k">block</span><span class="p">;</span></div><div class='line' id='LC194'>&nbsp;&nbsp;<span class="k">content</span><span class="o">:</span> <span class="s2">&quot; &quot;</span><span class="p">;</span></div><div class='line' id='LC195'>&nbsp;&nbsp;<span class="k">float</span><span class="o">:</span> <span class="k">right</span><span class="p">;</span></div><div class='line' id='LC196'>&nbsp;&nbsp;<span class="k">width</span><span class="o">:</span> <span class="m">0</span><span class="p">;</span></div><div class='line' id='LC197'>&nbsp;&nbsp;<span class="k">height</span><span class="o">:</span> <span class="m">0</span><span class="p">;</span></div><div class='line' id='LC198'>&nbsp;&nbsp;<span class="k">border-color</span><span class="o">:</span> <span class="k">transparent</span><span class="p">;</span></div><div class='line' id='LC199'>&nbsp;&nbsp;<span class="k">border-style</span><span class="o">:</span> <span class="k">solid</span><span class="p">;</span></div><div class='line' id='LC200'>&nbsp;&nbsp;<span class="k">border-width</span><span class="o">:</span> <span class="m">5px</span> <span class="m">0</span> <span class="m">5px</span> <span class="m">5px</span><span class="p">;</span></div><div class='line' id='LC201'>&nbsp;&nbsp;<span class="k">border-left-color</span><span class="o">:</span> <span class="n">darken</span><span class="p">(</span><span class="o">@</span><span class="n">dropdownBackground</span><span class="o">,</span> <span class="m">20</span><span class="o">%</span><span class="p">);</span></div><div class='line' id='LC202'>&nbsp;&nbsp;<span class="k">margin-top</span><span class="o">:</span> <span class="m">5px</span><span class="p">;</span></div><div class='line' id='LC203'>&nbsp;&nbsp;<span class="k">margin-right</span><span class="o">:</span> <span class="m">-10px</span><span class="p">;</span></div><div class='line' id='LC204'><span class="p">}</span></div><div class='line' id='LC205'><span class="nc">.dropdown-submenu</span><span class="nd">:hover</span> <span class="o">&gt;</span> <span class="nt">a</span><span class="nd">:after</span> <span class="p">{</span></div><div class='line' id='LC206'>&nbsp;&nbsp;<span class="k">border-left-color</span><span class="o">:</span> <span class="o">@</span><span class="n">dropdownLinkColorHover</span><span class="p">;</span></div><div class='line' id='LC207'><span class="p">}</span></div><div class='line' id='LC208'><br/></div><div class='line' id='LC209'><span class="o">//</span> <span class="nt">Left</span> <span class="nt">aligned</span> <span class="nt">submenus</span></div><div class='line' id='LC210'><span class="nc">.dropdown-submenu.pull-left</span> <span class="p">{</span></div><div class='line' id='LC211'>&nbsp;&nbsp;<span class="o">//</span> <span class="n">Undo</span> <span class="n">the</span> <span class="k">float</span></div><div class='line' id='LC212'>&nbsp;&nbsp;<span class="o">//</span> <span class="n">Yes</span><span class="o">,</span> <span class="n">this</span> <span class="n">is</span> <span class="n">awkward</span> <span class="n">since</span> <span class="o">.</span><span class="n">pull</span><span class="o">-</span><span class="k">left</span> <span class="n">adds</span> <span class="n">a</span> <span class="k">float</span><span class="o">,</span> <span class="n">but</span> <span class="n">it</span> <span class="n">sticks</span> <span class="n">to</span> <span class="n">our</span> <span class="n">conventions</span> <span class="n">elsewhere</span><span class="o">.</span></div><div class='line' id='LC213'>&nbsp;&nbsp;<span class="k">float</span><span class="o">:</span> <span class="k">none</span><span class="p">;</span></div><div class='line' id='LC214'><br/></div><div class='line' id='LC215'>&nbsp;&nbsp;<span class="o">//</span> <span class="n">Positioning</span> <span class="n">the</span> <span class="n">submenu</span></div><div class='line' id='LC216'>&nbsp;&nbsp;<span class="o">&gt;</span> <span class="o">.</span><span class="n">dropdown</span><span class="o">-</span><span class="n">menu</span> <span class="err">{</span></div><div class='line' id='LC217'>&nbsp;&nbsp;&nbsp;&nbsp;<span class="k">left</span><span class="o">:</span> <span class="m">-100</span><span class="o">%</span><span class="p">;</span></div><div class='line' id='LC218'>&nbsp;&nbsp;&nbsp;&nbsp;<span class="k">margin-left</span><span class="o">:</span> <span class="m">10px</span><span class="p">;</span></div><div class='line' id='LC219'>&nbsp;&nbsp;&nbsp;&nbsp;<span class="o">.</span><span class="k">border</span><span class="o">-</span><span class="n">radius</span><span class="p">(</span><span class="m">6px</span> <span class="m">0</span> <span class="m">6px</span> <span class="m">6px</span><span class="p">);</span></div><div class='line' id='LC220'>&nbsp;&nbsp;<span class="p">}</span></div><div class='line' id='LC221'><span class="err">}</span></div><div class='line' id='LC222'><br/></div><div class='line' id='LC223'><span class="o">//</span> <span class="nt">Tweak</span> <span class="nt">nav</span> <span class="nt">headers</span></div><div class='line' id='LC224'><span class="o">//</span> <span class="nt">-----------------</span></div><div class='line' id='LC225'><span class="o">//</span> <span class="nt">Increase</span> <span class="nt">padding</span> <span class="nt">from</span> <span class="nt">15px</span> <span class="nt">to</span> <span class="nt">20px</span> <span class="nt">on</span> <span class="nt">sides</span></div><div class='line' id='LC226'><span class="nc">.dropdown</span> <span class="nc">.dropdown-menu</span> <span class="nc">.nav-header</span> <span class="p">{</span></div><div class='line' id='LC227'>&nbsp;&nbsp;<span class="k">padding-left</span><span class="o">:</span> <span class="m">20px</span><span class="p">;</span></div><div class='line' id='LC228'>&nbsp;&nbsp;<span class="k">padding-right</span><span class="o">:</span> <span class="m">20px</span><span class="p">;</span></div><div class='line' id='LC229'><span class="p">}</span></div><div class='line' id='LC230'><br/></div><div class='line' id='LC231'><span class="o">//</span> <span class="nt">Typeahead</span></div><div class='line' id='LC232'><span class="o">//</span> <span class="nt">---------</span></div><div class='line' id='LC233'><span class="nc">.typeahead</span> <span class="p">{</span></div><div class='line' id='LC234'>&nbsp;&nbsp;<span class="k">z-index</span><span class="o">:</span> <span class="m">1051</span><span class="p">;</span></div><div class='line' id='LC235'>&nbsp;&nbsp;<span class="k">margin-top</span><span class="o">:</span> <span class="m">2px</span><span class="p">;</span> <span class="o">//</span> <span class="n">give</span> <span class="n">it</span> <span class="n">some</span> <span class="n">space</span> <span class="n">to</span> <span class="n">breathe</span></div><div class='line' id='LC236'>&nbsp;&nbsp;<span class="o">.</span><span class="k">border</span><span class="o">-</span><span class="n">radius</span><span class="p">(</span><span class="o">@</span><span class="n">baseBorderRadius</span><span class="p">);</span></div><div class='line' id='LC237'><span class="p">}</span></div></pre></div>
          </td>
        </tr>
      </table>
  </div>

          </div>
        </div>

        <a href="#jump-to-line" rel="facebox" data-hotkey="l" class="js-jump-to-line" style="display:none">Jump to Line</a>
        <div id="jump-to-line" style="display:none">
          <h2>Jump to Line</h2>
          <form accept-charset="UTF-8" class="js-jump-to-line-form">
            <input class="textfield js-jump-to-line-field" type="text">
            <div class="full-button">
              <button type="submit" class="button">Go</button>
            </div>
          </form>
        </div>

      </div>
    </div>
</div>

<div id="js-frame-loading-template" class="frame frame-loading large-loading-area" style="display:none;">
  <img class="js-frame-loading-spinner" src="https://a248.e.akamai.net/assets.github.com/images/spinners/octocat-spinner-128.gif?1359500886" height="64" width="64">
</div>


        </div>
      </div>
      <div class="context-overlay"></div>
    </div>

      <div id="footer-push"></div><!-- hack for sticky footer -->
    </div><!-- end of wrapper - hack for sticky footer -->

      <!-- footer -->
      <div id="footer">
  <div class="container clearfix">

      <dl class="footer_nav">
        <dt>GitHub</dt>
        <dd><a href="https://github.com/about">About us</a></dd>
        <dd><a href="https://github.com/blog">Blog</a></dd>
        <dd><a href="https://github.com/contact">Contact &amp; support</a></dd>
        <dd><a href="http://enterprise.github.com/">GitHub Enterprise</a></dd>
        <dd><a href="http://status.github.com/">Site status</a></dd>
      </dl>

      <dl class="footer_nav">
        <dt>Applications</dt>
        <dd><a href="http://mac.github.com/">GitHub for Mac</a></dd>
        <dd><a href="http://windows.github.com/">GitHub for Windows</a></dd>
        <dd><a href="http://eclipse.github.com/">GitHub for Eclipse</a></dd>
        <dd><a href="http://mobile.github.com/">GitHub mobile apps</a></dd>
      </dl>

      <dl class="footer_nav">
        <dt>Services</dt>
        <dd><a href="http://get.gaug.es/">Gauges: Web analytics</a></dd>
        <dd><a href="http://speakerdeck.com">Speaker Deck: Presentations</a></dd>
        <dd><a href="https://gist.github.com">Gist: Code snippets</a></dd>
        <dd><a href="http://jobs.github.com/">Job board</a></dd>
      </dl>

      <dl class="footer_nav">
        <dt>Documentation</dt>
        <dd><a href="http://help.github.com/">GitHub Help</a></dd>
        <dd><a href="http://developer.github.com/">Developer API</a></dd>
        <dd><a href="http://github.github.com/github-flavored-markdown/">GitHub Flavored Markdown</a></dd>
        <dd><a href="http://pages.github.com/">GitHub Pages</a></dd>
      </dl>

      <dl class="footer_nav">
        <dt>More</dt>
        <dd><a href="http://training.github.com/">Training</a></dd>
        <dd><a href="https://github.com/edu">Students &amp; teachers</a></dd>
        <dd><a href="http://shop.github.com">The Shop</a></dd>
        <dd><a href="/plans">Plans &amp; pricing</a></dd>
        <dd><a href="http://octodex.github.com/">The Octodex</a></dd>
      </dl>

      <hr class="footer-divider">


    <p class="right">&copy; 2013 <span title="0.07167s from fe19.rs.github.com">GitHub</span>, Inc. All rights reserved.</p>
    <a class="left" href="https://github.com/">
      <span class="mega-icon mega-icon-invertocat"></span>
    </a>
    <ul id="legal">
        <li><a href="https://github.com/site/terms">Terms of Service</a></li>
        <li><a href="https://github.com/site/privacy">Privacy</a></li>
        <li><a href="https://github.com/security">Security</a></li>
    </ul>

  </div><!-- /.container -->

</div><!-- /.#footer -->


    <div class="fullscreen-overlay js-fullscreen-overlay" id="fullscreen_overlay">
  <div class="fullscreen-container js-fullscreen-container">
    <div class="textarea-wrap">
      <textarea name="fullscreen-contents" id="fullscreen-contents" class="js-fullscreen-contents" placeholder="" data-suggester="fullscreen_suggester"></textarea>
          <div class="suggester-container">
              <div class="suggester fullscreen-suggester js-navigation-container" id="fullscreen_suggester"
                 data-url="/twitter/bootstrap/suggestions/commit">
              </div>
          </div>
    </div>
  </div>
  <div class="fullscreen-sidebar">
    <a href="#" class="exit-fullscreen js-exit-fullscreen tooltipped leftwards" title="Exit Zen Mode">
      <span class="mega-icon mega-icon-normalscreen"></span>
    </a>
    <a href="#" class="theme-switcher js-theme-switcher tooltipped leftwards"
      title="Switch themes">
      <span class="mini-icon mini-icon-brightness"></span>
    </a>
  </div>
</div>



    <div id="ajax-error-message" class="flash flash-error">
      <span class="mini-icon mini-icon-exclamation"></span>
      Something went wrong with that request. Please try again.
      <a href="#" class="mini-icon mini-icon-remove-close ajax-error-dismiss"></a>
    </div>

    
    
    <span id='server_response_time' data-time='0.07219' data-host='fe19'></span>
    
  </body>
</html>

                                                                                                                                                                                                                                                                                                                                                                                             master/bootstrap/less/sprites.less                                                                  000644  000767  000024  00000307632 12136500402 020357  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                           


<!DOCTYPE html>
<html>
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# githubog: http://ogp.me/ns/fb/githubog#">
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <title>bootstrap/less/sprites.less at master · twitter/bootstrap</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub" />
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub" />
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-touch-icon-114.png" />
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-touch-icon-114.png" />
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-touch-icon-144.png" />
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-touch-icon-144.png" />
    <link rel="logo" type="image/svg" href="http://github-media-downloads.s3.amazonaws.com/github-logo.svg" />
    <link rel="xhr-socket" href="/_sockets">
    <meta name="msapplication-TileImage" content="/windows-tile.png">
    <meta name="msapplication-TileColor" content="#ffffff">

    
    
    <link rel="icon" type="image/x-icon" href="/favicon.ico" />

    <meta content="authenticity_token" name="csrf-param" />
<meta content="zXcNFkaalMeTegkIBO2aLckNrTRhcPrRqREcKcwfBlU=" name="csrf-token" />

    <link href="https://a248.e.akamai.net/assets.github.com/assets/github-ba9334f20ce3c230182573735217c391db5f0d28.css" media="all" rel="stylesheet" type="text/css" />
    <link href="https://a248.e.akamai.net/assets.github.com/assets/github2-f0f30526f0f97f3b8305a871ece055ff80f65878.css" media="all" rel="stylesheet" type="text/css" />
    


      <script src="https://a248.e.akamai.net/assets.github.com/assets/frameworks-010d500708696b4ecee44478b5229d626367e844.js" type="text/javascript"></script>
      <script src="https://a248.e.akamai.net/assets.github.com/assets/github-3650b119e8cb8e869962cc12cf15570bac2a8847.js" type="text/javascript"></script>
      
      <meta http-equiv="x-pjax-version" content="93043389b7957fb779950962f0003882">

        <link data-pjax-transient rel='permalink' href='/twitter/bootstrap/blob/37d0a30589e8bd74299b2d857c348d91396563ed/less/sprites.less'>
    <meta property="og:title" content="bootstrap"/>
    <meta property="og:type" content="githubog:gitrepository"/>
    <meta property="og:url" content="https://github.com/twitter/bootstrap"/>
    <meta property="og:image" content="https://secure.gravatar.com/avatar/2f4a8254d032a8ec5e4c48d461e54fcc?s=420&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png"/>
    <meta property="og:site_name" content="GitHub"/>
    <meta property="og:description" content="bootstrap - Sleek, intuitive, and powerful front-end framework for faster and easier web development."/>
    <meta property="twitter:card" content="summary"/>
    <meta property="twitter:site" content="@GitHub">
    <meta property="twitter:title" content="twitter/bootstrap"/>

    <meta name="description" content="bootstrap - Sleek, intuitive, and powerful front-end framework for faster and easier web development." />

  <link href="https://github.com/twitter/bootstrap/commits/master.atom" rel="alternate" title="Recent Commits to bootstrap:master" type="application/atom+xml" />

  </head>


  <body class="logged_in page-blob macintosh vis-public env-production  ">
    <div id="wrapper">

      

      
      
      

      <div class="header header-logged-in true">
  <div class="container clearfix">

    <a class="header-logo-blacktocat" href="https://github.com/">
  <span class="mega-icon mega-icon-blacktocat"></span>
</a>

    <div class="divider-vertical"></div>

    
  <a href="/notifications" class="notification-indicator tooltipped downwards" title="You have unread notifications">
    <span class="mail-status unread"></span>
  </a>
  <div class="divider-vertical"></div>


      <div class="command-bar js-command-bar  ">
            <form accept-charset="UTF-8" action="/search" class="command-bar-form" id="top_search_form" method="get">
  <a href="/search/advanced" class="advanced-search-icon tooltipped downwards command-bar-search" id="advanced_search" title="Advanced search"><span class="mini-icon mini-icon-advanced-search "></span></a>

  <input type="text" data-hotkey="/ s" name="q" id="js-command-bar-field" placeholder="Search or type a command" tabindex="1" data-username="jojenki" autocapitalize="off">

  <span class="mini-icon help tooltipped downwards" title="Show command bar help">
    <span class="mini-icon mini-icon-help"></span>
  </span>

  <input type="hidden" name="ref" value="cmdform">

    <input type="hidden" class="js-repository-name-with-owner" value="twitter/bootstrap"/>
    <input type="hidden" class="js-repository-branch" value="master"/>
    <input type="hidden" class="js-repository-tree-sha" value="aa216022c839324948797ba7d75cac577cfbfed0"/>

  <div class="divider-vertical"></div>
</form>
        <ul class="top-nav">
            <li class="explore"><a href="https://github.com/explore">Explore</a></li>
            <li><a href="https://gist.github.com">Gist</a></li>
            <li><a href="/blog">Blog</a></li>
          <li><a href="http://help.github.com">Help</a></li>
        </ul>
      </div>

    

  
    <ul id="user-links">
      <li>
        <a href="https://github.com/jojenki" class="name">
          <img height="20" src="https://secure.gravatar.com/avatar/5f6038d19f287812c9b94ddd1d189d47?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="20" /> jojenki
        </a>
      </li>
      <li>
        <a href="/new" id="new_repo" class="tooltipped downwards" title="Create a new repo">
          <span class="mini-icon mini-icon-create"></span>
        </a>
      </li>
      <li>
        <a href="/settings/profile" id="account_settings"
          class="tooltipped downwards"
          title="Account settings ">
          <span class="mini-icon mini-icon-account-settings"></span>
        </a>
      </li>
      <li>
        <a href="/logout" data-method="post" id="logout" class="tooltipped downwards" title="Sign out">
          <span class="mini-icon mini-icon-logout"></span>
        </a>
      </li>
    </ul>



    
  </div>
</div>

      

      

      


            <div class="site hfeed" itemscope itemtype="http://schema.org/WebPage">
      <div class="hentry">
        
        <div class="pagehead repohead instapaper_ignore readability-menu ">
          <div class="container">
            <div class="title-actions-bar">
              


<ul class="pagehead-actions">


    <li class="subscription">
      <form accept-charset="UTF-8" action="/notifications/subscribe" data-autosubmit="true" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="authenticity_token" type="hidden" value="zXcNFkaalMeTegkIBO2aLckNrTRhcPrRqREcKcwfBlU=" /></div>  <input id="repository_id" name="repository_id" type="hidden" value="2126244" />

    <div class="select-menu js-menu-container js-select-menu">
      <span class="minibutton select-menu-button js-menu-target">
        <span class="js-select-button">
          <span class="mini-icon mini-icon-watching"></span>
          Watch
        </span>
      </span>

      <div class="select-menu-modal-holder js-menu-content">
        <div class="select-menu-modal">
          <div class="select-menu-header">
            <span class="select-menu-title">Notification status</span>
            <span class="mini-icon mini-icon-remove-close js-menu-close"></span>
          </div> <!-- /.select-menu-header -->

          <div class="select-menu-list js-navigation-container">

            <div class="select-menu-item js-navigation-item js-navigation-target selected">
              <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
              <div class="select-menu-item-text">
                <input checked="checked" id="do_included" name="do" type="radio" value="included" />
                <h4>Not watching</h4>
                <span class="description">You only receive notifications for discussions in which you participate or are @mentioned.</span>
                <span class="js-select-button-text hidden-select-button-text">
                  <span class="mini-icon mini-icon-watching"></span>
                  Watch
                </span>
              </div>
            </div> <!-- /.select-menu-item -->

            <div class="select-menu-item js-navigation-item js-navigation-target ">
              <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
              <div class="select-menu-item-text">
                <input id="do_subscribed" name="do" type="radio" value="subscribed" />
                <h4>Watching</h4>
                <span class="description">You receive notifications for all discussions in this repository.</span>
                <span class="js-select-button-text hidden-select-button-text">
                  <span class="mini-icon mini-icon-unwatch"></span>
                  Unwatch
                </span>
              </div>
            </div> <!-- /.select-menu-item -->

            <div class="select-menu-item js-navigation-item js-navigation-target ">
              <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
              <div class="select-menu-item-text">
                <input id="do_ignore" name="do" type="radio" value="ignore" />
                <h4>Ignoring</h4>
                <span class="description">You do not receive any notifications for discussions in this repository.</span>
                <span class="js-select-button-text hidden-select-button-text">
                  <span class="mini-icon mini-icon-mute"></span>
                  Stop ignoring
                </span>
              </div>
            </div> <!-- /.select-menu-item -->

          </div> <!-- /.select-menu-list -->

        </div> <!-- /.select-menu-modal -->
      </div> <!-- /.select-menu-modal-holder -->
    </div> <!-- /.select-menu -->

</form>
    </li>

    <li class="js-toggler-container js-social-container starring-container ">
      <a href="/twitter/bootstrap/unstar" class="minibutton js-toggler-target star-button starred upwards" title="Unstar this repo" data-remote="true" data-method="post" rel="nofollow">
        <span class="mini-icon mini-icon-remove-star"></span>
        <span class="text">Unstar</span>
      </a>
      <a href="/twitter/bootstrap/star" class="minibutton js-toggler-target star-button unstarred upwards" title="Star this repo" data-remote="true" data-method="post" rel="nofollow">
        <span class="mini-icon mini-icon-star"></span>
        <span class="text">Star</span>
      </a>
      <a class="social-count js-social-count" href="/twitter/bootstrap/stargazers">48,271</a>
    </li>

        <li>
          <a href="/twitter/bootstrap/fork_select" class="minibutton js-toggler-target fork-button lighter upwards" title="Fork this repo" rel="facebox nofollow">
            <span class="mini-icon mini-icon-branch-create"></span>
            <span class="text">Fork</span>
          </a>
          <a href="/twitter/bootstrap/network" class="social-count">14,431</a>
        </li>


</ul>

              <h1 itemscope itemtype="http://data-vocabulary.org/Breadcrumb" class="entry-title public">
                <span class="repo-label"><span>public</span></span>
                <span class="mega-icon mega-icon-public-repo"></span>
                <span class="author vcard">
                  <a href="/twitter" class="url fn" itemprop="url" rel="author">
                  <span itemprop="title">twitter</span>
                  </a></span> /
                <strong><a href="/twitter/bootstrap" class="js-current-repository">bootstrap</a></strong>
              </h1>
            </div>

            
  <ul class="tabs">
    <li><a href="/twitter/bootstrap" class="selected" highlight="repo_source repo_downloads repo_commits repo_tags repo_branches">Code</a></li>
    <li><a href="/twitter/bootstrap/network" highlight="repo_network">Network</a></li>
    <li><a href="/twitter/bootstrap/pulls" highlight="repo_pulls">Pull Requests <span class='counter'>76</span></a></li>

      <li><a href="/twitter/bootstrap/issues" highlight="repo_issues">Issues <span class='counter'>175</span></a></li>

      <li><a href="/twitter/bootstrap/wiki" highlight="repo_wiki">Wiki</a></li>


    <li><a href="/twitter/bootstrap/graphs" highlight="repo_graphs repo_contributors">Graphs</a></li>


  </ul>
  
<div class="tabnav">

  <span class="tabnav-right">
    <ul class="tabnav-tabs">
          <li><a href="/twitter/bootstrap/tags" class="tabnav-tab" highlight="repo_tags">Tags <span class="counter ">18</span></a></li>
    </ul>
    
  </span>

  <div class="tabnav-widget scope">


    <div class="select-menu js-menu-container js-select-menu js-branch-menu">
      <a class="minibutton select-menu-button js-menu-target" data-hotkey="w" data-ref="master">
        <span class="mini-icon mini-icon-branch"></span>
        <i>branch:</i>
        <span class="js-select-button">master</span>
      </a>

      <div class="select-menu-modal-holder js-menu-content js-navigation-container">

        <div class="select-menu-modal">
          <div class="select-menu-header">
            <span class="select-menu-title">Switch branches/tags</span>
            <span class="mini-icon mini-icon-remove-close js-menu-close"></span>
          </div> <!-- /.select-menu-header -->

          <div class="select-menu-filters">
            <div class="select-menu-text-filter">
              <input type="text" id="commitish-filter-field" class="js-filterable-field js-navigation-enable" placeholder="Filter branches/tags">
            </div>
            <div class="select-menu-tabs">
              <ul>
                <li class="select-menu-tab">
                  <a href="#" data-tab-filter="branches" class="js-select-menu-tab">Branches</a>
                </li>
                <li class="select-menu-tab">
                  <a href="#" data-tab-filter="tags" class="js-select-menu-tab">Tags</a>
                </li>
              </ul>
            </div><!-- /.select-menu-tabs -->
          </div><!-- /.select-menu-filters -->

          <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket css-truncate" data-tab-filter="branches">

            <div data-filterable-for="commitish-filter-field" data-filterable-type="substring">

                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/3.0.0-wip/less/sprites.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="3.0.0-wip" rel="nofollow" title="3.0.0-wip">3.0.0-wip</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/bootjack/less/sprites.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="bootjack" rel="nofollow" title="bootjack">bootjack</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/bs3_makefile_separated_done/less/sprites.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="bs3_makefile_separated_done" rel="nofollow" title="bs3_makefile_separated_done">bs3_makefile_separated_done</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/gh-pages/less/sprites.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="gh-pages" rel="nofollow" title="gh-pages">gh-pages</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target selected">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/master/less/sprites.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="master" rel="nofollow" title="master">master</a>
                </div> <!-- /.select-menu-item -->
            </div>

              <div class="select-menu-no-results">Nothing to show</div>
          </div> <!-- /.select-menu-list -->


          <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket css-truncate" data-tab-filter="tags">
            <div data-filterable-for="commitish-filter-field" data-filterable-type="substring">

                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/v2.3.1/less/sprites.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="v2.3.1" rel="nofollow" title="v2.3.1">v2.3.1</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/v2.3.0/less/sprites.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="v2.3.0" rel="nofollow" title="v2.3.0">v2.3.0</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/v2.2.2/less/sprites.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="v2.2.2" rel="nofollow" title="v2.2.2">v2.2.2</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/v2.2.1/less/sprites.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="v2.2.1" rel="nofollow" title="v2.2.1">v2.2.1</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/v2.2.0/less/sprites.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="v2.2.0" rel="nofollow" title="v2.2.0">v2.2.0</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/v2.1.1/less/sprites.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="v2.1.1" rel="nofollow" title="v2.1.1">v2.1.1</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/v2.1.0/less/sprites.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="v2.1.0" rel="nofollow" title="v2.1.0">v2.1.0</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/v2.0.4/less/sprites.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="v2.0.4" rel="nofollow" title="v2.0.4">v2.0.4</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/v2.0.3/less/sprites.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="v2.0.3" rel="nofollow" title="v2.0.3">v2.0.3</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/v2.0.2/less/sprites.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="v2.0.2" rel="nofollow" title="v2.0.2">v2.0.2</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/v2.0.1/less/sprites.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="v2.0.1" rel="nofollow" title="v2.0.1">v2.0.1</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/v2.0.0/less/sprites.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="v2.0.0" rel="nofollow" title="v2.0.0">v2.0.0</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/v1.4.0/less/sprites.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="v1.4.0" rel="nofollow" title="v1.4.0">v1.4.0</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/v1.3.0/less/sprites.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="v1.3.0" rel="nofollow" title="v1.3.0">v1.3.0</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/v1.2.0/less/sprites.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="v1.2.0" rel="nofollow" title="v1.2.0">v1.2.0</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/v1.1.1/less/sprites.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="v1.1.1" rel="nofollow" title="v1.1.1">v1.1.1</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/v1.1.0/less/sprites.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="v1.1.0" rel="nofollow" title="v1.1.0">v1.1.0</a>
                </div> <!-- /.select-menu-item -->
                <div class="select-menu-item js-navigation-item js-navigation-target ">
                  <span class="select-menu-item-icon mini-icon mini-icon-confirm"></span>
                  <a href="/twitter/bootstrap/blob/v1.0.0/less/sprites.less" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="v1.0.0" rel="nofollow" title="v1.0.0">v1.0.0</a>
                </div> <!-- /.select-menu-item -->
            </div>

            <div class="select-menu-no-results">Nothing to show</div>

          </div> <!-- /.select-menu-list -->

        </div> <!-- /.select-menu-modal -->
      </div> <!-- /.select-menu-modal-holder -->
    </div> <!-- /.select-menu -->

  </div> <!-- /.scope -->

  <ul class="tabnav-tabs">
    <li><a href="/twitter/bootstrap" class="selected tabnav-tab" highlight="repo_source">Files</a></li>
    <li><a href="/twitter/bootstrap/commits/master" class="tabnav-tab" highlight="repo_commits">Commits</a></li>
    <li><a href="/twitter/bootstrap/branches" class="tabnav-tab" highlight="repo_branches" rel="nofollow">Branches <span class="counter ">5</span></a></li>
  </ul>

</div>

  
  
  


            
          </div>
        </div><!-- /.repohead -->

        <div id="js-repo-pjax-container" class="container context-loader-container" data-pjax-container>
          


<!-- blob contrib key: blob_contributors:v21:274f01dc0f1958177eab7ec3cacb278b -->
<!-- blob contrib frag key: views10/v8/blob_contributors:v21:274f01dc0f1958177eab7ec3cacb278b -->


<div id="slider">
    <div class="frame-meta">

      <p title="This is a placeholder element" class="js-history-link-replace hidden"></p>

        <div class="breadcrumb">
          <span class='bold'><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/twitter/bootstrap" class="js-slide-to" data-branch="master" data-direction="back" itemscope="url"><span itemprop="title">bootstrap</span></a></span></span><span class="separator"> / </span><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/twitter/bootstrap/tree/master/less" class="js-slide-to" data-branch="master" data-direction="back" itemscope="url"><span itemprop="title">less</span></a></span><span class="separator"> / </span><strong class="final-path">sprites.less</strong> <span class="js-zeroclipboard zeroclipboard-button" data-clipboard-text="less/sprites.less" data-copied-hint="copied!" title="copy to clipboard"><span class="mini-icon mini-icon-clipboard"></span></span>
        </div>

      <a href="/twitter/bootstrap/find/master" class="js-slide-to" data-hotkey="t" style="display:none">Show File Finder</a>


        
  <div class="commit file-history-tease">
    <img class="main-avatar" height="24" src="https://secure.gravatar.com/avatar/bc4ab438f7a4ce1c406aadc688427f2c?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="24" />
    <span class="author"><a href="/mdo" rel="author">mdo</a></span>
    <time class="js-relative-date" datetime="2013-02-05T19:39:49-08:00" title="2013-02-05 19:39:49">February 05, 2013</time>
    <div class="commit-title">
        <a href="/twitter/bootstrap/commit/15c7e73abd8d97f0139d177d05c94e26faa17dd2" class="message">Merge branch '2.3.0-wip' of</a> <a href="https://github.com/patrickhlauke/bootstrap">https://github.com/patrickhlauke/bootstrap</a> <a href="/twitter/bootstrap/commit/15c7e73abd8d97f0139d177d05c94e26faa17dd2" class="message">…</a>
    </div>

    <div class="participation">
      <p class="quickstat"><a href="#blob_contributors_box" rel="facebox"><strong>10</strong> contributors</a></p>
          <a class="avatar tooltipped downwards" title="mdo" href="/twitter/bootstrap/commits/master/less/sprites.less?author=mdo"><img height="20" src="https://secure.gravatar.com/avatar/bc4ab438f7a4ce1c406aadc688427f2c?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="20" /></a>
    <a class="avatar tooltipped downwards" title="fat" href="/twitter/bootstrap/commits/master/less/sprites.less?author=fat"><img height="20" src="https://secure.gravatar.com/avatar/a98244cbdacaf1c0b55499466002f7a8?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="20" /></a>
    <a class="avatar tooltipped downwards" title="DominikTo" href="/twitter/bootstrap/commits/master/less/sprites.less?author=DominikTo"><img height="20" src="https://secure.gravatar.com/avatar/501f51f370e22d8fafac7038d3e4eb87?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="20" /></a>
    <a class="avatar tooltipped downwards" title="natansh" href="/twitter/bootstrap/commits/master/less/sprites.less?author=natansh"><img height="20" src="https://secure.gravatar.com/avatar/33c5b27d9e26a76f70afb5e5cceb0b14?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="20" /></a>
    <a class="avatar tooltipped downwards" title="phopkins" href="/twitter/bootstrap/commits/master/less/sprites.less?author=phopkins"><img height="20" src="https://secure.gravatar.com/avatar/30d1327440bc75e4203b301ca0ee3286?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="20" /></a>
    <a class="avatar tooltipped downwards" title="patrickhlauke" href="/twitter/bootstrap/commits/master/less/sprites.less?author=patrickhlauke"><img height="20" src="https://secure.gravatar.com/avatar/357f279672db832fc41a5a2f36559fcb?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="20" /></a>
    <a class="avatar tooltipped downwards" title="spantaleev" href="/twitter/bootstrap/commits/master/less/sprites.less?author=spantaleev"><img height="20" src="https://secure.gravatar.com/avatar/da5da7021799f9f1336e493601402493?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="20" /></a>
    <a class="avatar tooltipped downwards" title="baslr" href="/twitter/bootstrap/commits/master/less/sprites.less?author=baslr"><img height="20" src="https://secure.gravatar.com/avatar/d41d8cd98f00b204e9800998ecf8427e?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="20" /></a>
    <a class="avatar tooltipped downwards" title="tobz" href="/twitter/bootstrap/commits/master/less/sprites.less?author=tobz"><img height="20" src="https://secure.gravatar.com/avatar/c9f1a441d44b2e155c93a1c5ecf13ddc?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="20" /></a>
    <a class="avatar tooltipped downwards" title="buraktuyan" href="/twitter/bootstrap/commits/master/less/sprites.less?author=buraktuyan"><img height="20" src="https://secure.gravatar.com/avatar/e5436a0c87b98c2ec786e99a33660a8c?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="20" /></a>


    </div>
    <div id="blob_contributors_box" style="display:none">
      <h2>Users on GitHub who have contributed to this file</h2>
      <ul class="facebox-user-list">
        <li>
          <img height="24" src="https://secure.gravatar.com/avatar/bc4ab438f7a4ce1c406aadc688427f2c?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="24" />
          <a href="/mdo">mdo</a>
        </li>
        <li>
          <img height="24" src="https://secure.gravatar.com/avatar/a98244cbdacaf1c0b55499466002f7a8?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="24" />
          <a href="/fat">fat</a>
        </li>
        <li>
          <img height="24" src="https://secure.gravatar.com/avatar/501f51f370e22d8fafac7038d3e4eb87?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="24" />
          <a href="/DominikTo">DominikTo</a>
        </li>
        <li>
          <img height="24" src="https://secure.gravatar.com/avatar/33c5b27d9e26a76f70afb5e5cceb0b14?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="24" />
          <a href="/natansh">natansh</a>
        </li>
        <li>
          <img height="24" src="https://secure.gravatar.com/avatar/30d1327440bc75e4203b301ca0ee3286?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="24" />
          <a href="/phopkins">phopkins</a>
        </li>
        <li>
          <img height="24" src="https://secure.gravatar.com/avatar/357f279672db832fc41a5a2f36559fcb?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="24" />
          <a href="/patrickhlauke">patrickhlauke</a>
        </li>
        <li>
          <img height="24" src="https://secure.gravatar.com/avatar/da5da7021799f9f1336e493601402493?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="24" />
          <a href="/spantaleev">spantaleev</a>
        </li>
        <li>
          <img height="24" src="https://secure.gravatar.com/avatar/d41d8cd98f00b204e9800998ecf8427e?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="24" />
          <a href="/baslr">baslr</a>
        </li>
        <li>
          <img height="24" src="https://secure.gravatar.com/avatar/c9f1a441d44b2e155c93a1c5ecf13ddc?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="24" />
          <a href="/tobz">tobz</a>
        </li>
        <li>
          <img height="24" src="https://secure.gravatar.com/avatar/e5436a0c87b98c2ec786e99a33660a8c?s=140&amp;d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png" width="24" />
          <a href="/buraktuyan">buraktuyan</a>
        </li>
      </ul>
    </div>
  </div>


    </div><!-- ./.frame-meta -->

    <div class="frames">
      <div class="frame" data-permalink-url="/twitter/bootstrap/blob/37d0a30589e8bd74299b2d857c348d91396563ed/less/sprites.less" data-title="bootstrap/less/sprites.less at master · twitter/bootstrap · GitHub" data-type="blob">

        <div id="files" class="bubble">
          <div class="file">
            <div class="meta">
              <div class="info">
                <span class="icon"><b class="mini-icon mini-icon-text-file"></b></span>
                <span class="mode" title="File Mode">file</span>
                  <span>198 lines (184 sloc)</span>
                <span>10.841 kb</span>
              </div>
              <div class="actions">
                <div class="button-group">
                        <a class="minibutton tooltipped leftwards"
                           title="Clicking this button will automatically fork this project so you can edit the file"
                           href="/twitter/bootstrap/edit/master/less/sprites.less"
                           data-method="post" rel="nofollow">Edit</a>
                  <a href="/twitter/bootstrap/raw/master/less/sprites.less" class="button minibutton " id="raw-url">Raw</a>
                    <a href="/twitter/bootstrap/blame/master/less/sprites.less" class="button minibutton ">Blame</a>
                  <a href="/twitter/bootstrap/commits/master/less/sprites.less" class="button minibutton " rel="nofollow">History</a>
                </div><!-- /.button-group -->
              </div><!-- /.actions -->

            </div>
                <div class="blob-wrapper data type-less js-blob-data">
      <table class="file-code file-blob">
        <tr class="file-code-line">
          <td class="blob-line-nums">
            <span id="L1" rel="#L1">1</span>
<span id="L2" rel="#L2">2</span>
<span id="L3" rel="#L3">3</span>
<span id="L4" rel="#L4">4</span>
<span id="L5" rel="#L5">5</span>
<span id="L6" rel="#L6">6</span>
<span id="L7" rel="#L7">7</span>
<span id="L8" rel="#L8">8</span>
<span id="L9" rel="#L9">9</span>
<span id="L10" rel="#L10">10</span>
<span id="L11" rel="#L11">11</span>
<span id="L12" rel="#L12">12</span>
<span id="L13" rel="#L13">13</span>
<span id="L14" rel="#L14">14</span>
<span id="L15" rel="#L15">15</span>
<span id="L16" rel="#L16">16</span>
<span id="L17" rel="#L17">17</span>
<span id="L18" rel="#L18">18</span>
<span id="L19" rel="#L19">19</span>
<span id="L20" rel="#L20">20</span>
<span id="L21" rel="#L21">21</span>
<span id="L22" rel="#L22">22</span>
<span id="L23" rel="#L23">23</span>
<span id="L24" rel="#L24">24</span>
<span id="L25" rel="#L25">25</span>
<span id="L26" rel="#L26">26</span>
<span id="L27" rel="#L27">27</span>
<span id="L28" rel="#L28">28</span>
<span id="L29" rel="#L29">29</span>
<span id="L30" rel="#L30">30</span>
<span id="L31" rel="#L31">31</span>
<span id="L32" rel="#L32">32</span>
<span id="L33" rel="#L33">33</span>
<span id="L34" rel="#L34">34</span>
<span id="L35" rel="#L35">35</span>
<span id="L36" rel="#L36">36</span>
<span id="L37" rel="#L37">37</span>
<span id="L38" rel="#L38">38</span>
<span id="L39" rel="#L39">39</span>
<span id="L40" rel="#L40">40</span>
<span id="L41" rel="#L41">41</span>
<span id="L42" rel="#L42">42</span>
<span id="L43" rel="#L43">43</span>
<span id="L44" rel="#L44">44</span>
<span id="L45" rel="#L45">45</span>
<span id="L46" rel="#L46">46</span>
<span id="L47" rel="#L47">47</span>
<span id="L48" rel="#L48">48</span>
<span id="L49" rel="#L49">49</span>
<span id="L50" rel="#L50">50</span>
<span id="L51" rel="#L51">51</span>
<span id="L52" rel="#L52">52</span>
<span id="L53" rel="#L53">53</span>
<span id="L54" rel="#L54">54</span>
<span id="L55" rel="#L55">55</span>
<span id="L56" rel="#L56">56</span>
<span id="L57" rel="#L57">57</span>
<span id="L58" rel="#L58">58</span>
<span id="L59" rel="#L59">59</span>
<span id="L60" rel="#L60">60</span>
<span id="L61" rel="#L61">61</span>
<span id="L62" rel="#L62">62</span>
<span id="L63" rel="#L63">63</span>
<span id="L64" rel="#L64">64</span>
<span id="L65" rel="#L65">65</span>
<span id="L66" rel="#L66">66</span>
<span id="L67" rel="#L67">67</span>
<span id="L68" rel="#L68">68</span>
<span id="L69" rel="#L69">69</span>
<span id="L70" rel="#L70">70</span>
<span id="L71" rel="#L71">71</span>
<span id="L72" rel="#L72">72</span>
<span id="L73" rel="#L73">73</span>
<span id="L74" rel="#L74">74</span>
<span id="L75" rel="#L75">75</span>
<span id="L76" rel="#L76">76</span>
<span id="L77" rel="#L77">77</span>
<span id="L78" rel="#L78">78</span>
<span id="L79" rel="#L79">79</span>
<span id="L80" rel="#L80">80</span>
<span id="L81" rel="#L81">81</span>
<span id="L82" rel="#L82">82</span>
<span id="L83" rel="#L83">83</span>
<span id="L84" rel="#L84">84</span>
<span id="L85" rel="#L85">85</span>
<span id="L86" rel="#L86">86</span>
<span id="L87" rel="#L87">87</span>
<span id="L88" rel="#L88">88</span>
<span id="L89" rel="#L89">89</span>
<span id="L90" rel="#L90">90</span>
<span id="L91" rel="#L91">91</span>
<span id="L92" rel="#L92">92</span>
<span id="L93" rel="#L93">93</span>
<span id="L94" rel="#L94">94</span>
<span id="L95" rel="#L95">95</span>
<span id="L96" rel="#L96">96</span>
<span id="L97" rel="#L97">97</span>
<span id="L98" rel="#L98">98</span>
<span id="L99" rel="#L99">99</span>
<span id="L100" rel="#L100">100</span>
<span id="L101" rel="#L101">101</span>
<span id="L102" rel="#L102">102</span>
<span id="L103" rel="#L103">103</span>
<span id="L104" rel="#L104">104</span>
<span id="L105" rel="#L105">105</span>
<span id="L106" rel="#L106">106</span>
<span id="L107" rel="#L107">107</span>
<span id="L108" rel="#L108">108</span>
<span id="L109" rel="#L109">109</span>
<span id="L110" rel="#L110">110</span>
<span id="L111" rel="#L111">111</span>
<span id="L112" rel="#L112">112</span>
<span id="L113" rel="#L113">113</span>
<span id="L114" rel="#L114">114</span>
<span id="L115" rel="#L115">115</span>
<span id="L116" rel="#L116">116</span>
<span id="L117" rel="#L117">117</span>
<span id="L118" rel="#L118">118</span>
<span id="L119" rel="#L119">119</span>
<span id="L120" rel="#L120">120</span>
<span id="L121" rel="#L121">121</span>
<span id="L122" rel="#L122">122</span>
<span id="L123" rel="#L123">123</span>
<span id="L124" rel="#L124">124</span>
<span id="L125" rel="#L125">125</span>
<span id="L126" rel="#L126">126</span>
<span id="L127" rel="#L127">127</span>
<span id="L128" rel="#L128">128</span>
<span id="L129" rel="#L129">129</span>
<span id="L130" rel="#L130">130</span>
<span id="L131" rel="#L131">131</span>
<span id="L132" rel="#L132">132</span>
<span id="L133" rel="#L133">133</span>
<span id="L134" rel="#L134">134</span>
<span id="L135" rel="#L135">135</span>
<span id="L136" rel="#L136">136</span>
<span id="L137" rel="#L137">137</span>
<span id="L138" rel="#L138">138</span>
<span id="L139" rel="#L139">139</span>
<span id="L140" rel="#L140">140</span>
<span id="L141" rel="#L141">141</span>
<span id="L142" rel="#L142">142</span>
<span id="L143" rel="#L143">143</span>
<span id="L144" rel="#L144">144</span>
<span id="L145" rel="#L145">145</span>
<span id="L146" rel="#L146">146</span>
<span id="L147" rel="#L147">147</span>
<span id="L148" rel="#L148">148</span>
<span id="L149" rel="#L149">149</span>
<span id="L150" rel="#L150">150</span>
<span id="L151" rel="#L151">151</span>
<span id="L152" rel="#L152">152</span>
<span id="L153" rel="#L153">153</span>
<span id="L154" rel="#L154">154</span>
<span id="L155" rel="#L155">155</span>
<span id="L156" rel="#L156">156</span>
<span id="L157" rel="#L157">157</span>
<span id="L158" rel="#L158">158</span>
<span id="L159" rel="#L159">159</span>
<span id="L160" rel="#L160">160</span>
<span id="L161" rel="#L161">161</span>
<span id="L162" rel="#L162">162</span>
<span id="L163" rel="#L163">163</span>
<span id="L164" rel="#L164">164</span>
<span id="L165" rel="#L165">165</span>
<span id="L166" rel="#L166">166</span>
<span id="L167" rel="#L167">167</span>
<span id="L168" rel="#L168">168</span>
<span id="L169" rel="#L169">169</span>
<span id="L170" rel="#L170">170</span>
<span id="L171" rel="#L171">171</span>
<span id="L172" rel="#L172">172</span>
<span id="L173" rel="#L173">173</span>
<span id="L174" rel="#L174">174</span>
<span id="L175" rel="#L175">175</span>
<span id="L176" rel="#L176">176</span>
<span id="L177" rel="#L177">177</span>
<span id="L178" rel="#L178">178</span>
<span id="L179" rel="#L179">179</span>
<span id="L180" rel="#L180">180</span>
<span id="L181" rel="#L181">181</span>
<span id="L182" rel="#L182">182</span>
<span id="L183" rel="#L183">183</span>
<span id="L184" rel="#L184">184</span>
<span id="L185" rel="#L185">185</span>
<span id="L186" rel="#L186">186</span>
<span id="L187" rel="#L187">187</span>
<span id="L188" rel="#L188">188</span>
<span id="L189" rel="#L189">189</span>
<span id="L190" rel="#L190">190</span>
<span id="L191" rel="#L191">191</span>
<span id="L192" rel="#L192">192</span>
<span id="L193" rel="#L193">193</span>
<span id="L194" rel="#L194">194</span>
<span id="L195" rel="#L195">195</span>
<span id="L196" rel="#L196">196</span>
<span id="L197" rel="#L197">197</span>

          </td>
          <td class="blob-line-code">
                  <div class="highlight"><pre><div class='line' id='LC1'><span class="o">//</span></div><div class='line' id='LC2'><span class="o">//</span> <span class="nt">Sprites</span></div><div class='line' id='LC3'><span class="o">//</span> <span class="nt">--------------------------------------------------</span></div><div class='line' id='LC4'><br/></div><div class='line' id='LC5'><br/></div><div class='line' id='LC6'><span class="o">//</span> <span class="nt">ICONS</span></div><div class='line' id='LC7'><span class="o">//</span> <span class="nt">-----</span></div><div class='line' id='LC8'><br/></div><div class='line' id='LC9'><span class="o">//</span> <span class="nt">All</span> <span class="nt">icons</span> <span class="nt">receive</span> <span class="nt">the</span> <span class="nt">styles</span> <span class="nt">of</span> <span class="nt">the</span> <span class="o">&lt;</span><span class="nt">i</span><span class="o">&gt;</span> <span class="nt">tag</span> <span class="nt">with</span> <span class="nt">a</span> <span class="nt">base</span> <span class="nt">class</span></div><div class='line' id='LC10'><span class="o">//</span> <span class="nt">of</span> <span class="nc">.i</span> <span class="nt">and</span> <span class="nt">are</span> <span class="nt">then</span> <span class="nt">given</span> <span class="nt">a</span> <span class="nt">unique</span> <span class="nt">class</span> <span class="nt">to</span> <span class="nt">add</span> <span class="nt">width</span><span class="o">,</span> <span class="nt">height</span><span class="o">,</span></div><div class='line' id='LC11'><span class="o">//</span> <span class="nt">and</span> <span class="nt">background-position</span><span class="o">.</span> <span class="nt">Your</span> <span class="nt">resulting</span> <span class="nt">HTML</span> <span class="nt">will</span> <span class="nt">look</span> <span class="nt">like</span></div><div class='line' id='LC12'><span class="o">//</span> <span class="o">&lt;</span><span class="nt">i</span> <span class="nt">class</span><span class="o">=</span><span class="s2">&quot;icon-inbox&quot;</span><span class="o">&gt;&lt;/</span><span class="nt">i</span><span class="o">&gt;.</span></div><div class='line' id='LC13'><br/></div><div class='line' id='LC14'><span class="o">//</span> <span class="nt">For</span> <span class="nt">the</span> <span class="nt">white</span> <span class="nt">version</span> <span class="nt">of</span> <span class="nt">the</span> <span class="nt">icons</span><span class="o">,</span> <span class="nt">just</span> <span class="nt">add</span> <span class="nt">the</span> <span class="nc">.icon-white</span> <span class="nt">class</span><span class="o">:</span></div><div class='line' id='LC15'><span class="o">//</span> <span class="o">&lt;</span><span class="nt">i</span> <span class="nt">class</span><span class="o">=</span><span class="s2">&quot;icon-inbox icon-white&quot;</span><span class="o">&gt;&lt;/</span><span class="nt">i</span><span class="o">&gt;</span></div><div class='line' id='LC16'><br/></div><div class='line' id='LC17'><span class="o">[</span><span class="nt">class</span><span class="o">^=</span><span class="s2">&quot;icon-&quot;</span><span class="o">],</span></div><div class='line' id='LC18'><span class="o">[</span><span class="nt">class</span><span class="o">*=</span><span class="s2">&quot; icon-&quot;</span><span class="o">]</span> <span class="p">{</span></div><div class='line' id='LC19'>&nbsp;&nbsp;<span class="k">display</span><span class="o">:</span> <span class="k">inline</span><span class="o">-</span><span class="k">block</span><span class="p">;</span></div><div class='line' id='LC20'>&nbsp;&nbsp;<span class="k">width</span><span class="o">:</span> <span class="m">14px</span><span class="p">;</span></div><div class='line' id='LC21'>&nbsp;&nbsp;<span class="k">height</span><span class="o">:</span> <span class="m">14px</span><span class="p">;</span></div><div class='line' id='LC22'>&nbsp;&nbsp;<span class="o">.</span><span class="n">ie7</span><span class="o">-</span><span class="n">restore</span><span class="o">-</span><span class="k">right</span><span class="o">-</span><span class="n">whitespace</span><span class="p">();</span></div><div class='line' id='LC23'>&nbsp;&nbsp;<span class="k">line-height</span><span class="o">:</span> <span class="m">14px</span><span class="p">;</span></div><div class='line' id='LC24'>&nbsp;&nbsp;<span class="k">vertical-align</span><span class="o">:</span> <span class="k">text</span><span class="o">-</span><span class="k">top</span><span class="p">;</span></div><div class='line' id='LC25'>&nbsp;&nbsp;<span class="k">background-image</span><span class="o">:</span> <span class="sx">url(&quot;@{iconSpritePath}&quot;)</span><span class="p">;</span></div><div class='line' id='LC26'>&nbsp;&nbsp;<span class="k">background-position</span><span class="o">:</span> <span class="m">14px</span> <span class="m">14px</span><span class="p">;</span></div><div class='line' id='LC27'>&nbsp;&nbsp;<span class="k">background-repeat</span><span class="o">:</span> <span class="k">no-repeat</span><span class="p">;</span></div><div class='line' id='LC28'>&nbsp;&nbsp;<span class="k">margin-top</span><span class="o">:</span> <span class="m">1px</span><span class="p">;</span></div><div class='line' id='LC29'><span class="p">}</span></div><div class='line' id='LC30'><br/></div><div class='line' id='LC31'><span class="c">/* White icons with optional class, or on hover/focus/active states of certain elements */</span></div><div class='line' id='LC32'><span class="nc">.icon-white</span><span class="o">,</span></div><div class='line' id='LC33'><span class="nc">.nav-pills</span> <span class="o">&gt;</span> <span class="nc">.active</span> <span class="o">&gt;</span> <span class="nt">a</span> <span class="o">&gt;</span> <span class="o">[</span><span class="nt">class</span><span class="o">^=</span><span class="s2">&quot;icon-&quot;</span><span class="o">],</span></div><div class='line' id='LC34'><span class="nc">.nav-pills</span> <span class="o">&gt;</span> <span class="nc">.active</span> <span class="o">&gt;</span> <span class="nt">a</span> <span class="o">&gt;</span> <span class="o">[</span><span class="nt">class</span><span class="o">*=</span><span class="s2">&quot; icon-&quot;</span><span class="o">],</span></div><div class='line' id='LC35'><span class="nc">.nav-list</span> <span class="o">&gt;</span> <span class="nc">.active</span> <span class="o">&gt;</span> <span class="nt">a</span> <span class="o">&gt;</span> <span class="o">[</span><span class="nt">class</span><span class="o">^=</span><span class="s2">&quot;icon-&quot;</span><span class="o">],</span></div><div class='line' id='LC36'><span class="nc">.nav-list</span> <span class="o">&gt;</span> <span class="nc">.active</span> <span class="o">&gt;</span> <span class="nt">a</span> <span class="o">&gt;</span> <span class="o">[</span><span class="nt">class</span><span class="o">*=</span><span class="s2">&quot; icon-&quot;</span><span class="o">],</span></div><div class='line' id='LC37'><span class="nc">.navbar-inverse</span> <span class="nc">.nav</span> <span class="o">&gt;</span> <span class="nc">.active</span> <span class="o">&gt;</span> <span class="nt">a</span> <span class="o">&gt;</span> <span class="o">[</span><span class="nt">class</span><span class="o">^=</span><span class="s2">&quot;icon-&quot;</span><span class="o">],</span></div><div class='line' id='LC38'><span class="nc">.navbar-inverse</span> <span class="nc">.nav</span> <span class="o">&gt;</span> <span class="nc">.active</span> <span class="o">&gt;</span> <span class="nt">a</span> <span class="o">&gt;</span> <span class="o">[</span><span class="nt">class</span><span class="o">*=</span><span class="s2">&quot; icon-&quot;</span><span class="o">],</span></div><div class='line' id='LC39'><span class="nc">.dropdown-menu</span> <span class="o">&gt;</span> <span class="nt">li</span> <span class="o">&gt;</span> <span class="nt">a</span><span class="nd">:hover</span> <span class="o">&gt;</span> <span class="o">[</span><span class="nt">class</span><span class="o">^=</span><span class="s2">&quot;icon-&quot;</span><span class="o">],</span></div><div class='line' id='LC40'><span class="nc">.dropdown-menu</span> <span class="o">&gt;</span> <span class="nt">li</span> <span class="o">&gt;</span> <span class="nt">a</span><span class="nd">:focus</span> <span class="o">&gt;</span> <span class="o">[</span><span class="nt">class</span><span class="o">^=</span><span class="s2">&quot;icon-&quot;</span><span class="o">],</span></div><div class='line' id='LC41'><span class="nc">.dropdown-menu</span> <span class="o">&gt;</span> <span class="nt">li</span> <span class="o">&gt;</span> <span class="nt">a</span><span class="nd">:hover</span> <span class="o">&gt;</span> <span class="o">[</span><span class="nt">class</span><span class="o">*=</span><span class="s2">&quot; icon-&quot;</span><span class="o">],</span></div><div class='line' id='LC42'><span class="nc">.dropdown-menu</span> <span class="o">&gt;</span> <span class="nt">li</span> <span class="o">&gt;</span> <span class="nt">a</span><span class="nd">:focus</span> <span class="o">&gt;</span> <span class="o">[</span><span class="nt">class</span><span class="o">*=</span><span class="s2">&quot; icon-&quot;</span><span class="o">],</span></div><div class='line' id='LC43'><span class="nc">.dropdown-menu</span> <span class="o">&gt;</span> <span class="nc">.active</span> <span class="o">&gt;</span> <span class="nt">a</span> <span class="o">&gt;</span> <span class="o">[</span><span class="nt">class</span><span class="o">^=</span><span class="s2">&quot;icon-&quot;</span><span class="o">],</span></div><div class='line' id='LC44'><span class="nc">.dropdown-menu</span> <span class="o">&gt;</span> <span class="nc">.active</span> <span class="o">&gt;</span> <span class="nt">a</span> <span class="o">&gt;</span> <span class="o">[</span><span class="nt">class</span><span class="o">*=</span><span class="s2">&quot; icon-&quot;</span><span class="o">],</span></div><div class='line' id='LC45'><span class="nc">.dropdown-submenu</span><span class="nd">:hover</span> <span class="o">&gt;</span> <span class="nt">a</span> <span class="o">&gt;</span> <span class="o">[</span><span class="nt">class</span><span class="o">^=</span><span class="s2">&quot;icon-&quot;</span><span class="o">],</span></div><div class='line' id='LC46'><span class="nc">.dropdown-submenu</span><span class="nd">:focus</span> <span class="o">&gt;</span> <span class="nt">a</span> <span class="o">&gt;</span> <span class="o">[</span><span class="nt">class</span><span class="o">^=</span><span class="s2">&quot;icon-&quot;</span><span class="o">],</span></div><div class='line' id='LC47'><span class="nc">.dropdown-submenu</span><span class="nd">:hover</span> <span class="o">&gt;</span> <span class="nt">a</span> <span class="o">&gt;</span> <span class="o">[</span><span class="nt">class</span><span class="o">*=</span><span class="s2">&quot; icon-&quot;</span><span class="o">],</span></div><div class='line' id='LC48'><span class="nc">.dropdown-submenu</span><span class="nd">:focus</span> <span class="o">&gt;</span> <span class="nt">a</span> <span class="o">&gt;</span> <span class="o">[</span><span class="nt">class</span><span class="o">*=</span><span class="s2">&quot; icon-&quot;</span><span class="o">]</span> <span class="p">{</span></div><div class='line' id='LC49'>&nbsp;&nbsp;<span class="k">background-image</span><span class="o">:</span> <span class="sx">url(&quot;@{iconWhiteSpritePath}&quot;)</span><span class="p">;</span></div><div class='line' id='LC50'><span class="p">}</span></div><div class='line' id='LC51'><br/></div><div class='line' id='LC52'><span class="nc">.icon-glass</span>              <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">0</span>      <span class="m">0</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC53'><span class="nc">.icon-music</span>              <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-24px</span>  <span class="m">0</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC54'><span class="nc">.icon-search</span>             <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-48px</span>  <span class="m">0</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC55'><span class="nc">.icon-envelope</span>           <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-72px</span>  <span class="m">0</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC56'><span class="nc">.icon-heart</span>              <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-96px</span>  <span class="m">0</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC57'><span class="nc">.icon-star</span>               <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-120px</span> <span class="m">0</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC58'><span class="nc">.icon-star-empty</span>         <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-144px</span> <span class="m">0</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC59'><span class="nc">.icon-user</span>               <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-168px</span> <span class="m">0</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC60'><span class="nc">.icon-film</span>               <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-192px</span> <span class="m">0</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC61'><span class="nc">.icon-th-large</span>           <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-216px</span> <span class="m">0</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC62'><span class="nc">.icon-th</span>                 <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-240px</span> <span class="m">0</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC63'><span class="nc">.icon-th-list</span>            <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-264px</span> <span class="m">0</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC64'><span class="nc">.icon-ok</span>                 <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-288px</span> <span class="m">0</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC65'><span class="nc">.icon-remove</span>             <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-312px</span> <span class="m">0</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC66'><span class="nc">.icon-zoom-in</span>            <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-336px</span> <span class="m">0</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC67'><span class="nc">.icon-zoom-out</span>           <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-360px</span> <span class="m">0</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC68'><span class="nc">.icon-off</span>                <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-384px</span> <span class="m">0</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC69'><span class="nc">.icon-signal</span>             <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-408px</span> <span class="m">0</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC70'><span class="nc">.icon-cog</span>                <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-432px</span> <span class="m">0</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC71'><span class="nc">.icon-trash</span>              <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-456px</span> <span class="m">0</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC72'><br/></div><div class='line' id='LC73'><span class="nc">.icon-home</span>               <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">0</span>      <span class="m">-24px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC74'><span class="nc">.icon-file</span>               <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-24px</span>  <span class="m">-24px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC75'><span class="nc">.icon-time</span>               <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-48px</span>  <span class="m">-24px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC76'><span class="nc">.icon-road</span>               <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-72px</span>  <span class="m">-24px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC77'><span class="nc">.icon-download-alt</span>       <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-96px</span>  <span class="m">-24px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC78'><span class="nc">.icon-download</span>           <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-120px</span> <span class="m">-24px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC79'><span class="nc">.icon-upload</span>             <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-144px</span> <span class="m">-24px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC80'><span class="nc">.icon-inbox</span>              <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-168px</span> <span class="m">-24px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC81'><span class="nc">.icon-play-circle</span>        <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-192px</span> <span class="m">-24px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC82'><span class="nc">.icon-repeat</span>             <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-216px</span> <span class="m">-24px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC83'><span class="nc">.icon-refresh</span>            <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-240px</span> <span class="m">-24px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC84'><span class="nc">.icon-list-alt</span>           <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-264px</span> <span class="m">-24px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC85'><span class="nc">.icon-lock</span>               <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-287px</span> <span class="m">-24px</span><span class="p">;</span> <span class="p">}</span> <span class="o">//</span> <span class="nt">1px</span> <span class="nt">off</span></div><div class='line' id='LC86'><span class="nc">.icon-flag</span>               <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-312px</span> <span class="m">-24px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC87'><span class="nc">.icon-headphones</span>         <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-336px</span> <span class="m">-24px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC88'><span class="nc">.icon-volume-off</span>         <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-360px</span> <span class="m">-24px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC89'><span class="nc">.icon-volume-down</span>        <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-384px</span> <span class="m">-24px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC90'><span class="nc">.icon-volume-up</span>          <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-408px</span> <span class="m">-24px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC91'><span class="nc">.icon-qrcode</span>             <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-432px</span> <span class="m">-24px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC92'><span class="nc">.icon-barcode</span>            <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-456px</span> <span class="m">-24px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC93'><br/></div><div class='line' id='LC94'><span class="nc">.icon-tag</span>                <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">0</span>      <span class="m">-48px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC95'><span class="nc">.icon-tags</span>               <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-25px</span>  <span class="m">-48px</span><span class="p">;</span> <span class="p">}</span> <span class="o">//</span> <span class="nt">1px</span> <span class="nt">off</span></div><div class='line' id='LC96'><span class="nc">.icon-book</span>               <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-48px</span>  <span class="m">-48px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC97'><span class="nc">.icon-bookmark</span>           <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-72px</span>  <span class="m">-48px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC98'><span class="nc">.icon-print</span>              <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-96px</span>  <span class="m">-48px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC99'><span class="nc">.icon-camera</span>             <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-120px</span> <span class="m">-48px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC100'><span class="nc">.icon-font</span>               <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-144px</span> <span class="m">-48px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC101'><span class="nc">.icon-bold</span>               <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-167px</span> <span class="m">-48px</span><span class="p">;</span> <span class="p">}</span> <span class="o">//</span> <span class="nt">1px</span> <span class="nt">off</span></div><div class='line' id='LC102'><span class="nc">.icon-italic</span>             <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-192px</span> <span class="m">-48px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC103'><span class="nc">.icon-text-height</span>        <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-216px</span> <span class="m">-48px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC104'><span class="nc">.icon-text-width</span>         <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-240px</span> <span class="m">-48px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC105'><span class="nc">.icon-align-left</span>         <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-264px</span> <span class="m">-48px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC106'><span class="nc">.icon-align-center</span>       <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-288px</span> <span class="m">-48px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC107'><span class="nc">.icon-align-right</span>        <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-312px</span> <span class="m">-48px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC108'><span class="nc">.icon-align-justify</span>      <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-336px</span> <span class="m">-48px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC109'><span class="nc">.icon-list</span>               <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-360px</span> <span class="m">-48px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC110'><span class="nc">.icon-indent-left</span>        <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-384px</span> <span class="m">-48px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC111'><span class="nc">.icon-indent-right</span>       <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-408px</span> <span class="m">-48px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC112'><span class="nc">.icon-facetime-video</span>     <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-432px</span> <span class="m">-48px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC113'><span class="nc">.icon-picture</span>            <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-456px</span> <span class="m">-48px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC114'><br/></div><div class='line' id='LC115'><span class="nc">.icon-pencil</span>             <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">0</span>      <span class="m">-72px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC116'><span class="nc">.icon-map-marker</span>         <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-24px</span>  <span class="m">-72px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC117'><span class="nc">.icon-adjust</span>             <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-48px</span>  <span class="m">-72px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC118'><span class="nc">.icon-tint</span>               <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-72px</span>  <span class="m">-72px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC119'><span class="nc">.icon-edit</span>               <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-96px</span>  <span class="m">-72px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC120'><span class="nc">.icon-share</span>              <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-120px</span> <span class="m">-72px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC121'><span class="nc">.icon-check</span>              <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-144px</span> <span class="m">-72px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC122'><span class="nc">.icon-move</span>               <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-168px</span> <span class="m">-72px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC123'><span class="nc">.icon-step-backward</span>      <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-192px</span> <span class="m">-72px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC124'><span class="nc">.icon-fast-backward</span>      <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-216px</span> <span class="m">-72px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC125'><span class="nc">.icon-backward</span>           <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-240px</span> <span class="m">-72px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC126'><span class="nc">.icon-play</span>               <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-264px</span> <span class="m">-72px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC127'><span class="nc">.icon-pause</span>              <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-288px</span> <span class="m">-72px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC128'><span class="nc">.icon-stop</span>               <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-312px</span> <span class="m">-72px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC129'><span class="nc">.icon-forward</span>            <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-336px</span> <span class="m">-72px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC130'><span class="nc">.icon-fast-forward</span>       <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-360px</span> <span class="m">-72px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC131'><span class="nc">.icon-step-forward</span>       <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-384px</span> <span class="m">-72px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC132'><span class="nc">.icon-eject</span>              <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-408px</span> <span class="m">-72px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC133'><span class="nc">.icon-chevron-left</span>       <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-432px</span> <span class="m">-72px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC134'><span class="nc">.icon-chevron-right</span>      <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-456px</span> <span class="m">-72px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC135'><br/></div><div class='line' id='LC136'><span class="nc">.icon-plus-sign</span>          <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">0</span>      <span class="m">-96px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC137'><span class="nc">.icon-minus-sign</span>         <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-24px</span>  <span class="m">-96px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC138'><span class="nc">.icon-remove-sign</span>        <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-48px</span>  <span class="m">-96px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC139'><span class="nc">.icon-ok-sign</span>            <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-72px</span>  <span class="m">-96px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC140'><span class="nc">.icon-question-sign</span>      <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-96px</span>  <span class="m">-96px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC141'><span class="nc">.icon-info-sign</span>          <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-120px</span> <span class="m">-96px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC142'><span class="nc">.icon-screenshot</span>         <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-144px</span> <span class="m">-96px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC143'><span class="nc">.icon-remove-circle</span>      <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-168px</span> <span class="m">-96px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC144'><span class="nc">.icon-ok-circle</span>          <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-192px</span> <span class="m">-96px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC145'><span class="nc">.icon-ban-circle</span>         <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-216px</span> <span class="m">-96px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC146'><span class="nc">.icon-arrow-left</span>         <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-240px</span> <span class="m">-96px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC147'><span class="nc">.icon-arrow-right</span>        <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-264px</span> <span class="m">-96px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC148'><span class="nc">.icon-arrow-up</span>           <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-289px</span> <span class="m">-96px</span><span class="p">;</span> <span class="p">}</span> <span class="o">//</span> <span class="nt">1px</span> <span class="nt">off</span></div><div class='line' id='LC149'><span class="nc">.icon-arrow-down</span>         <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-312px</span> <span class="m">-96px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC150'><span class="nc">.icon-share-alt</span>          <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-336px</span> <span class="m">-96px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC151'><span class="nc">.icon-resize-full</span>        <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-360px</span> <span class="m">-96px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC152'><span class="nc">.icon-resize-small</span>       <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-384px</span> <span class="m">-96px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC153'><span class="nc">.icon-plus</span>               <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-408px</span> <span class="m">-96px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC154'><span class="nc">.icon-minus</span>              <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-433px</span> <span class="m">-96px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC155'><span class="nc">.icon-asterisk</span>           <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-456px</span> <span class="m">-96px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC156'><br/></div><div class='line' id='LC157'><span class="nc">.icon-exclamation-sign</span>   <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">0</span>      <span class="m">-120px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC158'><span class="nc">.icon-gift</span>               <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-24px</span>  <span class="m">-120px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC159'><span class="nc">.icon-leaf</span>               <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-48px</span>  <span class="m">-120px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC160'><span class="nc">.icon-fire</span>               <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-72px</span>  <span class="m">-120px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC161'><span class="nc">.icon-eye-open</span>           <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-96px</span>  <span class="m">-120px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC162'><span class="nc">.icon-eye-close</span>          <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-120px</span> <span class="m">-120px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC163'><span class="nc">.icon-warning-sign</span>       <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-144px</span> <span class="m">-120px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC164'><span class="nc">.icon-plane</span>              <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-168px</span> <span class="m">-120px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC165'><span class="nc">.icon-calendar</span>           <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-192px</span> <span class="m">-120px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC166'><span class="nc">.icon-random</span>             <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-216px</span> <span class="m">-120px</span><span class="p">;</span> <span class="k">width</span><span class="o">:</span> <span class="m">16px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC167'><span class="nc">.icon-comment</span>            <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-240px</span> <span class="m">-120px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC168'><span class="nc">.icon-magnet</span>             <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-264px</span> <span class="m">-120px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC169'><span class="nc">.icon-chevron-up</span>         <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-288px</span> <span class="m">-120px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC170'><span class="nc">.icon-chevron-down</span>       <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-313px</span> <span class="m">-119px</span><span class="p">;</span> <span class="p">}</span> <span class="o">//</span> <span class="nt">1px</span><span class="o">,</span> <span class="nt">1px</span> <span class="nt">off</span></div><div class='line' id='LC171'><span class="nc">.icon-retweet</span>            <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-336px</span> <span class="m">-120px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC172'><span class="nc">.icon-shopping-cart</span>      <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-360px</span> <span class="m">-120px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC173'><span class="nc">.icon-folder-close</span>       <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-384px</span> <span class="m">-120px</span><span class="p">;</span> <span class="k">width</span><span class="o">:</span> <span class="m">16px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC174'><span class="nc">.icon-folder-open</span>        <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-408px</span> <span class="m">-120px</span><span class="p">;</span> <span class="k">width</span><span class="o">:</span> <span class="m">16px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC175'><span class="nc">.icon-resize-vertical</span>    <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-432px</span> <span class="m">-119px</span><span class="p">;</span> <span class="p">}</span> <span class="o">//</span> <span class="nt">1px</span><span class="o">,</span> <span class="nt">1px</span> <span class="nt">off</span></div><div class='line' id='LC176'><span class="nc">.icon-resize-horizontal</span>  <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-456px</span> <span class="m">-118px</span><span class="p">;</span> <span class="p">}</span> <span class="o">//</span> <span class="nt">1px</span><span class="o">,</span> <span class="nt">2px</span> <span class="nt">off</span></div><div class='line' id='LC177'><br/></div><div class='line' id='LC178'><span class="nc">.icon-hdd</span>                     <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">0</span>      <span class="m">-144px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC179'><span class="nc">.icon-bullhorn</span>                <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-24px</span>  <span class="m">-144px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC180'><span class="nc">.icon-bell</span>                    <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-48px</span>  <span class="m">-144px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC181'><span class="nc">.icon-certificate</span>             <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-72px</span>  <span class="m">-144px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC182'><span class="nc">.icon-thumbs-up</span>               <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-96px</span>  <span class="m">-144px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC183'><span class="nc">.icon-thumbs-down</span>             <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-120px</span> <span class="m">-144px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC184'><span class="nc">.icon-hand-right</span>              <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-144px</span> <span class="m">-144px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC185'><span class="nc">.icon-hand-left</span>               <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-168px</span> <span class="m">-144px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC186'><span class="nc">.icon-hand-up</span>                 <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-192px</span> <span class="m">-144px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC187'><span class="nc">.icon-hand-down</span>               <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-216px</span> <span class="m">-144px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC188'><span class="nc">.icon-circle-arrow-right</span>      <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-240px</span> <span class="m">-144px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC189'><span class="nc">.icon-circle-arrow-left</span>       <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-264px</span> <span class="m">-144px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC190'><span class="nc">.icon-circle-arrow-up</span>         <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-288px</span> <span class="m">-144px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC191'><span class="nc">.icon-circle-arrow-down</span>       <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-312px</span> <span class="m">-144px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC192'><span class="nc">.icon-globe</span>                   <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-336px</span> <span class="m">-144px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC193'><span class="nc">.icon-wrench</span>                  <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-360px</span> <span class="m">-144px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC194'><span class="nc">.icon-tasks</span>                   <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-384px</span> <span class="m">-144px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC195'><span class="nc">.icon-filter</span>                  <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-408px</span> <span class="m">-144px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC196'><span class="nc">.icon-briefcase</span>               <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-432px</span> <span class="m">-144px</span><span class="p">;</span> <span class="p">}</span></div><div class='line' id='LC197'><span class="nc">.icon-fullscreen</span>              <span class="p">{</span> <span class="k">background-position</span><span class="o">:</span> <span class="m">-456px</span> <span class="m">-144px</span><span class="p">;</span> <span class="p">}</span></div></pre></div>
          </td>
        </tr>
      </table>
  </div>

          </div>
        </div>

        <a href="#jump-to-line" rel="facebox" data-hotkey="l" class="js-jump-to-line" style="display:none">Jump to Line</a>
        <div id="jump-to-line" style="display:none">
          <h2>Jump to Line</h2>
          <form accept-charset="UTF-8" class="js-jump-to-line-form">
            <input class="textfield js-jump-to-line-field" type="text">
            <div class="full-button">
              <button type="submit" class="button">Go</button>
            </div>
          </form>
        </div>

      </div>
    </div>
</div>

<div id="js-frame-loading-template" class="frame frame-loading large-loading-area" style="display:none;">
  <img class="js-frame-loading-spinner" src="https://a248.e.akamai.net/assets.github.com/images/spinners/octocat-spinner-128.gif?1347543527" height="64" width="64">
</div>


        </div>
      </div>
      <div class="context-overlay"></div>
    </div>

      <div id="footer-push"></div><!-- hack for sticky footer -->
    </div><!-- end of wrapper - hack for sticky footer -->

      <!-- footer -->
      <div id="footer">
  <div class="container clearfix">

      <dl class="footer_nav">
        <dt>GitHub</dt>
        <dd><a href="https://github.com/about">About us</a></dd>
        <dd><a href="https://github.com/blog">Blog</a></dd>
        <dd><a href="https://github.com/contact">Contact &amp; support</a></dd>
        <dd><a href="http://enterprise.github.com/">GitHub Enterprise</a></dd>
        <dd><a href="http://status.github.com/">Site status</a></dd>
      </dl>

      <dl class="footer_nav">
        <dt>Applications</dt>
        <dd><a href="http://mac.github.com/">GitHub for Mac</a></dd>
        <dd><a href="http://windows.github.com/">GitHub for Windows</a></dd>
        <dd><a href="http://eclipse.github.com/">GitHub for Eclipse</a></dd>
        <dd><a href="http://mobile.github.com/">GitHub mobile apps</a></dd>
      </dl>

      <dl class="footer_nav">
        <dt>Services</dt>
        <dd><a href="http://get.gaug.es/">Gauges: Web analytics</a></dd>
        <dd><a href="http://speakerdeck.com">Speaker Deck: Presentations</a></dd>
        <dd><a href="https://gist.github.com">Gist: Code snippets</a></dd>
        <dd><a href="http://jobs.github.com/">Job board</a></dd>
      </dl>

      <dl class="footer_nav">
        <dt>Documentation</dt>
        <dd><a href="http://help.github.com/">GitHub Help</a></dd>
        <dd><a href="http://developer.github.com/">Developer API</a></dd>
        <dd><a href="http://github.github.com/github-flavored-markdown/">GitHub Flavored Markdown</a></dd>
        <dd><a href="http://pages.github.com/">GitHub Pages</a></dd>
      </dl>

      <dl class="footer_nav">
        <dt>More</dt>
        <dd><a href="http://training.github.com/">Training</a></dd>
        <dd><a href="https://github.com/edu">Students &amp; teachers</a></dd>
        <dd><a href="http://shop.github.com">The Shop</a></dd>
        <dd><a href="/plans">Plans &amp; pricing</a></dd>
        <dd><a href="http://octodex.github.com/">The Octodex</a></dd>
      </dl>

      <hr class="footer-divider">


    <p class="right">&copy; 2013 <span title="0.08066s from fe16.rs.github.com">GitHub</span>, Inc. All rights reserved.</p>
    <a class="left" href="https://github.com/">
      <span class="mega-icon mega-icon-invertocat"></span>
    </a>
    <ul id="legal">
        <li><a href="https://github.com/site/terms">Terms of Service</a></li>
        <li><a href="https://github.com/site/privacy">Privacy</a></li>
        <li><a href="https://github.com/security">Security</a></li>
    </ul>

  </div><!-- /.container -->

</div><!-- /.#footer -->


    <div class="fullscreen-overlay js-fullscreen-overlay" id="fullscreen_overlay">
  <div class="fullscreen-container js-fullscreen-container">
    <div class="textarea-wrap">
      <textarea name="fullscreen-contents" id="fullscreen-contents" class="js-fullscreen-contents" placeholder="" data-suggester="fullscreen_suggester"></textarea>
          <div class="suggester-container">
              <div class="suggester fullscreen-suggester js-navigation-container" id="fullscreen_suggester"
                 data-url="/twitter/bootstrap/suggestions/commit">
              </div>
          </div>
    </div>
  </div>
  <div class="fullscreen-sidebar">
    <a href="#" class="exit-fullscreen js-exit-fullscreen tooltipped leftwards" title="Exit Zen Mode">
      <span class="mega-icon mega-icon-normalscreen"></span>
    </a>
    <a href="#" class="theme-switcher js-theme-switcher tooltipped leftwards"
      title="Switch themes">
      <span class="mini-icon mini-icon-brightness"></span>
    </a>
  </div>
</div>



    <div id="ajax-error-message" class="flash flash-error">
      <span class="mini-icon mini-icon-exclamation"></span>
      Something went wrong with that request. Please try again.
      <a href="#" class="mini-icon mini-icon-remove-close ajax-error-dismiss"></a>
    </div>

    
    
    <span id='server_response_time' data-time='0.08118' data-host='fe16'></span>
    
  </body>
</html>

                                                                                                      master/bootstrap/js/bootstrap.min.js                                                                000644  000767  000024  00000067402 12110524611 020577  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /*!
* Bootstrap.js by @fat & @mdo
* Copyright 2012 Twitter, Inc.
* http://www.apache.org/licenses/LICENSE-2.0.txt
*/
!function(e){"use strict";e(function(){e.support.transition=function(){var e=function(){var e=document.createElement("bootstrap"),t={WebkitTransition:"webkitTransitionEnd",MozTransition:"transitionend",OTransition:"oTransitionEnd otransitionend",transition:"transitionend"},n;for(n in t)if(e.style[n]!==undefined)return t[n]}();return e&&{end:e}}()})}(window.jQuery),!function(e){"use strict";var t='[data-dismiss="alert"]',n=function(n){e(n).on("click",t,this.close)};n.prototype.close=function(t){function s(){i.trigger("closed").remove()}var n=e(this),r=n.attr("data-target"),i;r||(r=n.attr("href"),r=r&&r.replace(/.*(?=#[^\s]*$)/,"")),i=e(r),t&&t.preventDefault(),i.length||(i=n.hasClass("alert")?n:n.parent()),i.trigger(t=e.Event("close"));if(t.isDefaultPrevented())return;i.removeClass("in"),e.support.transition&&i.hasClass("fade")?i.on(e.support.transition.end,s):s()};var r=e.fn.alert;e.fn.alert=function(t){return this.each(function(){var r=e(this),i=r.data("alert");i||r.data("alert",i=new n(this)),typeof t=="string"&&i[t].call(r)})},e.fn.alert.Constructor=n,e.fn.alert.noConflict=function(){return e.fn.alert=r,this},e(document).on("click.alert.data-api",t,n.prototype.close)}(window.jQuery),!function(e){"use strict";var t=function(t,n){this.$element=e(t),this.options=e.extend({},e.fn.button.defaults,n)};t.prototype.setState=function(e){var t="disabled",n=this.$element,r=n.data(),i=n.is("input")?"val":"html";e+="Text",r.resetText||n.data("resetText",n[i]()),n[i](r[e]||this.options[e]),setTimeout(function(){e=="loadingText"?n.addClass(t).attr(t,t):n.removeClass(t).removeAttr(t)},0)},t.prototype.toggle=function(){var e=this.$element.closest('[data-toggle="buttons-radio"]');e&&e.find(".active").removeClass("active"),this.$element.toggleClass("active")};var n=e.fn.button;e.fn.button=function(n){return this.each(function(){var r=e(this),i=r.data("button"),s=typeof n=="object"&&n;i||r.data("button",i=new t(this,s)),n=="toggle"?i.toggle():n&&i.setState(n)})},e.fn.button.defaults={loadingText:"loading..."},e.fn.button.Constructor=t,e.fn.button.noConflict=function(){return e.fn.button=n,this},e(document).on("click.button.data-api","[data-toggle^=button]",function(t){var n=e(t.target);n.hasClass("btn")||(n=n.closest(".btn")),n.button("toggle")})}(window.jQuery),!function(e){"use strict";var t=function(t,n){this.$element=e(t),this.$indicators=this.$element.find(".carousel-indicators"),this.options=n,this.options.pause=="hover"&&this.$element.on("mouseenter",e.proxy(this.pause,this)).on("mouseleave",e.proxy(this.cycle,this))};t.prototype={cycle:function(t){return t||(this.paused=!1),this.interval&&clearInterval(this.interval),this.options.interval&&!this.paused&&(this.interval=setInterval(e.proxy(this.next,this),this.options.interval)),this},getActiveIndex:function(){return this.$active=this.$element.find(".item.active"),this.$items=this.$active.parent().children(),this.$items.index(this.$active)},to:function(t){var n=this.getActiveIndex(),r=this;if(t>this.$items.length-1||t<0)return;return this.sliding?this.$element.one("slid",function(){r.to(t)}):n==t?this.pause().cycle():this.slide(t>n?"next":"prev",e(this.$items[t]))},pause:function(t){return t||(this.paused=!0),this.$element.find(".next, .prev").length&&e.support.transition.end&&(this.$element.trigger(e.support.transition.end),this.cycle()),clearInterval(this.interval),this.interval=null,this},next:function(){if(this.sliding)return;return this.slide("next")},prev:function(){if(this.sliding)return;return this.slide("prev")},slide:function(t,n){var r=this.$element.find(".item.active"),i=n||r[t](),s=this.interval,o=t=="next"?"left":"right",u=t=="next"?"first":"last",a=this,f;this.sliding=!0,s&&this.pause(),i=i.length?i:this.$element.find(".item")[u](),f=e.Event("slide",{relatedTarget:i[0],direction:o});if(i.hasClass("active"))return;this.$indicators.length&&(this.$indicators.find(".active").removeClass("active"),this.$element.one("slid",function(){var t=e(a.$indicators.children()[a.getActiveIndex()]);t&&t.addClass("active")}));if(e.support.transition&&this.$element.hasClass("slide")){this.$element.trigger(f);if(f.isDefaultPrevented())return;i.addClass(t),i[0].offsetWidth,r.addClass(o),i.addClass(o),this.$element.one(e.support.transition.end,function(){i.removeClass([t,o].join(" ")).addClass("active"),r.removeClass(["active",o].join(" ")),a.sliding=!1,setTimeout(function(){a.$element.trigger("slid")},0)})}else{this.$element.trigger(f);if(f.isDefaultPrevented())return;r.removeClass("active"),i.addClass("active"),this.sliding=!1,this.$element.trigger("slid")}return s&&this.cycle(),this}};var n=e.fn.carousel;e.fn.carousel=function(n){return this.each(function(){var r=e(this),i=r.data("carousel"),s=e.extend({},e.fn.carousel.defaults,typeof n=="object"&&n),o=typeof n=="string"?n:s.slide;i||r.data("carousel",i=new t(this,s)),typeof n=="number"?i.to(n):o?i[o]():s.interval&&i.pause().cycle()})},e.fn.carousel.defaults={interval:5e3,pause:"hover"},e.fn.carousel.Constructor=t,e.fn.carousel.noConflict=function(){return e.fn.carousel=n,this},e(document).on("click.carousel.data-api","[data-slide], [data-slide-to]",function(t){var n=e(this),r,i=e(n.attr("data-target")||(r=n.attr("href"))&&r.replace(/.*(?=#[^\s]+$)/,"")),s=e.extend({},i.data(),n.data()),o;i.carousel(s),(o=n.attr("data-slide-to"))&&i.data("carousel").pause().to(o).cycle(),t.preventDefault()})}(window.jQuery),!function(e){"use strict";var t=function(t,n){this.$element=e(t),this.options=e.extend({},e.fn.collapse.defaults,n),this.options.parent&&(this.$parent=e(this.options.parent)),this.options.toggle&&this.toggle()};t.prototype={constructor:t,dimension:function(){var e=this.$element.hasClass("width");return e?"width":"height"},show:function(){var t,n,r,i;if(this.transitioning||this.$element.hasClass("in"))return;t=this.dimension(),n=e.camelCase(["scroll",t].join("-")),r=this.$parent&&this.$parent.find("> .accordion-group > .in");if(r&&r.length){i=r.data("collapse");if(i&&i.transitioning)return;r.collapse("hide"),i||r.data("collapse",null)}this.$element[t](0),this.transition("addClass",e.Event("show"),"shown"),e.support.transition&&this.$element[t](this.$element[0][n])},hide:function(){var t;if(this.transitioning||!this.$element.hasClass("in"))return;t=this.dimension(),this.reset(this.$element[t]()),this.transition("removeClass",e.Event("hide"),"hidden"),this.$element[t](0)},reset:function(e){var t=this.dimension();return this.$element.removeClass("collapse")[t](e||"auto")[0].offsetWidth,this.$element[e!==null?"addClass":"removeClass"]("collapse"),this},transition:function(t,n,r){var i=this,s=function(){n.type=="show"&&i.reset(),i.transitioning=0,i.$element.trigger(r)};this.$element.trigger(n);if(n.isDefaultPrevented())return;this.transitioning=1,this.$element[t]("in"),e.support.transition&&this.$element.hasClass("collapse")?this.$element.one(e.support.transition.end,s):s()},toggle:function(){this[this.$element.hasClass("in")?"hide":"show"]()}};var n=e.fn.collapse;e.fn.collapse=function(n){return this.each(function(){var r=e(this),i=r.data("collapse"),s=e.extend({},e.fn.collapse.defaults,r.data(),typeof n=="object"&&n);i||r.data("collapse",i=new t(this,s)),typeof n=="string"&&i[n]()})},e.fn.collapse.defaults={toggle:!0},e.fn.collapse.Constructor=t,e.fn.collapse.noConflict=function(){return e.fn.collapse=n,this},e(document).on("click.collapse.data-api","[data-toggle=collapse]",function(t){var n=e(this),r,i=n.attr("data-target")||t.preventDefault()||(r=n.attr("href"))&&r.replace(/.*(?=#[^\s]+$)/,""),s=e(i).data("collapse")?"toggle":n.data();n[e(i).hasClass("in")?"addClass":"removeClass"]("collapsed"),e(i).collapse(s)})}(window.jQuery),!function(e){"use strict";function r(){e(t).each(function(){i(e(this)).removeClass("open")})}function i(t){var n=t.attr("data-target"),r;n||(n=t.attr("href"),n=n&&/#/.test(n)&&n.replace(/.*(?=#[^\s]*$)/,"")),r=n&&e(n);if(!r||!r.length)r=t.parent();return r}var t="[data-toggle=dropdown]",n=function(t){var n=e(t).on("click.dropdown.data-api",this.toggle);e("html").on("click.dropdown.data-api",function(){n.parent().removeClass("open")})};n.prototype={constructor:n,toggle:function(t){var n=e(this),s,o;if(n.is(".disabled, :disabled"))return;return s=i(n),o=s.hasClass("open"),r(),o||s.toggleClass("open"),n.focus(),!1},keydown:function(n){var r,s,o,u,a,f;if(!/(38|40|27)/.test(n.keyCode))return;r=e(this),n.preventDefault(),n.stopPropagation();if(r.is(".disabled, :disabled"))return;u=i(r),a=u.hasClass("open");if(!a||a&&n.keyCode==27)return n.which==27&&u.find(t).focus(),r.click();s=e("[role=menu] li:not(.divider):visible a",u);if(!s.length)return;f=s.index(s.filter(":focus")),n.keyCode==38&&f>0&&f--,n.keyCode==40&&f<s.length-1&&f++,~f||(f=0),s.eq(f).focus()}};var s=e.fn.dropdown;e.fn.dropdown=function(t){return this.each(function(){var r=e(this),i=r.data("dropdown");i||r.data("dropdown",i=new n(this)),typeof t=="string"&&i[t].call(r)})},e.fn.dropdown.Constructor=n,e.fn.dropdown.noConflict=function(){return e.fn.dropdown=s,this},e(document).on("click.dropdown.data-api",r).on("click.dropdown.data-api",".dropdown form",function(e){e.stopPropagation()}).on(".dropdown-menu",function(e){e.stopPropagation()}).on("click.dropdown.data-api",t,n.prototype.toggle).on("keydown.dropdown.data-api",t+", [role=menu]",n.prototype.keydown)}(window.jQuery),!function(e){"use strict";var t=function(t,n){this.options=n,this.$element=e(t).delegate('[data-dismiss="modal"]',"click.dismiss.modal",e.proxy(this.hide,this)),this.options.remote&&this.$element.find(".modal-body").load(this.options.remote)};t.prototype={constructor:t,toggle:function(){return this[this.isShown?"hide":"show"]()},show:function(){var t=this,n=e.Event("show");this.$element.trigger(n);if(this.isShown||n.isDefaultPrevented())return;this.isShown=!0,this.escape(),this.backdrop(function(){var n=e.support.transition&&t.$element.hasClass("fade");t.$element.parent().length||t.$element.appendTo(document.body),t.$element.show(),n&&t.$element[0].offsetWidth,t.$element.addClass("in").attr("aria-hidden",!1),t.enforceFocus(),n?t.$element.one(e.support.transition.end,function(){t.$element.focus().trigger("shown")}):t.$element.focus().trigger("shown")})},hide:function(t){t&&t.preventDefault();var n=this;t=e.Event("hide"),this.$element.trigger(t);if(!this.isShown||t.isDefaultPrevented())return;this.isShown=!1,this.escape(),e(document).off("focusin.modal"),this.$element.removeClass("in").attr("aria-hidden",!0),e.support.transition&&this.$element.hasClass("fade")?this.hideWithTransition():this.hideModal()},enforceFocus:function(){var t=this;e(document).on("focusin.modal",function(e){t.$element[0]!==e.target&&!t.$element.has(e.target).length&&t.$element.focus()})},escape:function(){var e=this;this.isShown&&this.options.keyboard?this.$element.on("keyup.dismiss.modal",function(t){t.which==27&&e.hide()}):this.isShown||this.$element.off("keyup.dismiss.modal")},hideWithTransition:function(){var t=this,n=setTimeout(function(){t.$element.off(e.support.transition.end),t.hideModal()},500);this.$element.one(e.support.transition.end,function(){clearTimeout(n),t.hideModal()})},hideModal:function(){var e=this;this.$element.hide(),this.backdrop(function(){e.removeBackdrop(),e.$element.trigger("hidden")})},removeBackdrop:function(){this.$backdrop.remove(),this.$backdrop=null},backdrop:function(t){var n=this,r=this.$element.hasClass("fade")?"fade":"";if(this.isShown&&this.options.backdrop){var i=e.support.transition&&r;this.$backdrop=e('<div class="modal-backdrop '+r+'" />').appendTo(document.body),this.$backdrop.click(this.options.backdrop=="static"?e.proxy(this.$element[0].focus,this.$element[0]):e.proxy(this.hide,this)),i&&this.$backdrop[0].offsetWidth,this.$backdrop.addClass("in");if(!t)return;i?this.$backdrop.one(e.support.transition.end,t):t()}else!this.isShown&&this.$backdrop?(this.$backdrop.removeClass("in"),e.support.transition&&this.$element.hasClass("fade")?this.$backdrop.one(e.support.transition.end,t):t()):t&&t()}};var n=e.fn.modal;e.fn.modal=function(n){return this.each(function(){var r=e(this),i=r.data("modal"),s=e.extend({},e.fn.modal.defaults,r.data(),typeof n=="object"&&n);i||r.data("modal",i=new t(this,s)),typeof n=="string"?i[n]():s.show&&i.show()})},e.fn.modal.defaults={backdrop:!0,keyboard:!0,show:!0},e.fn.modal.Constructor=t,e.fn.modal.noConflict=function(){return e.fn.modal=n,this},e(document).on("click.modal.data-api",'[data-toggle="modal"]',function(t){var n=e(this),r=n.attr("href"),i=e(n.attr("data-target")||r&&r.replace(/.*(?=#[^\s]+$)/,"")),s=i.data("modal")?"toggle":e.extend({remote:!/#/.test(r)&&r},i.data(),n.data());t.preventDefault(),i.modal(s).one("hide",function(){n.focus()})})}(window.jQuery),!function(e){"use strict";var t=function(e,t){this.init("tooltip",e,t)};t.prototype={constructor:t,init:function(t,n,r){var i,s,o,u,a;this.type=t,this.$element=e(n),this.options=this.getOptions(r),this.enabled=!0,o=this.options.trigger.split(" ");for(a=o.length;a--;)u=o[a],u=="click"?this.$element.on("click."+this.type,this.options.selector,e.proxy(this.toggle,this)):u!="manual"&&(i=u=="hover"?"mouseenter":"focus",s=u=="hover"?"mouseleave":"blur",this.$element.on(i+"."+this.type,this.options.selector,e.proxy(this.enter,this)),this.$element.on(s+"."+this.type,this.options.selector,e.proxy(this.leave,this)));this.options.selector?this._options=e.extend({},this.options,{trigger:"manual",selector:""}):this.fixTitle()},getOptions:function(t){return t=e.extend({},e.fn[this.type].defaults,this.$element.data(),t),t.delay&&typeof t.delay=="number"&&(t.delay={show:t.delay,hide:t.delay}),t},enter:function(t){var n=e(t.currentTarget)[this.type](this._options).data(this.type);if(!n.options.delay||!n.options.delay.show)return n.show();clearTimeout(this.timeout),n.hoverState="in",this.timeout=setTimeout(function(){n.hoverState=="in"&&n.show()},n.options.delay.show)},leave:function(t){var n=e(t.currentTarget)[this.type](this._options).data(this.type);this.timeout&&clearTimeout(this.timeout);if(!n.options.delay||!n.options.delay.hide)return n.hide();n.hoverState="out",this.timeout=setTimeout(function(){n.hoverState=="out"&&n.hide()},n.options.delay.hide)},show:function(){var t,n,r,i,s,o,u=e.Event("show");if(this.hasContent()&&this.enabled){this.$element.trigger(u);if(u.isDefaultPrevented())return;t=this.tip(),this.setContent(),this.options.animation&&t.addClass("fade"),s=typeof this.options.placement=="function"?this.options.placement.call(this,t[0],this.$element[0]):this.options.placement,t.detach().css({top:0,left:0,display:"block"}),this.options.container?t.appendTo(this.options.container):t.insertAfter(this.$element),n=this.getPosition(),r=t[0].offsetWidth,i=t[0].offsetHeight;switch(s){case"bottom":o={top:n.top+n.height,left:n.left+n.width/2-r/2};break;case"top":o={top:n.top-i,left:n.left+n.width/2-r/2};break;case"left":o={top:n.top+n.height/2-i/2,left:n.left-r};break;case"right":o={top:n.top+n.height/2-i/2,left:n.left+n.width}}this.applyPlacement(o,s),this.$element.trigger("shown")}},applyPlacement:function(e,t){var n=this.tip(),r=n[0].offsetWidth,i=n[0].offsetHeight,s,o,u,a;n.offset(e).addClass(t).addClass("in"),s=n[0].offsetWidth,o=n[0].offsetHeight,t=="top"&&o!=i&&(e.top=e.top+i-o,a=!0),t=="bottom"||t=="top"?(u=0,e.left<0&&(u=e.left*-2,e.left=0,n.offset(e),s=n[0].offsetWidth,o=n[0].offsetHeight),this.replaceArrow(u-r+s,s,"left")):this.replaceArrow(o-i,o,"top"),a&&n.offset(e)},replaceArrow:function(e,t,n){this.arrow().css(n,e?50*(1-e/t)+"%":"")},setContent:function(){var e=this.tip(),t=this.getTitle();e.find(".tooltip-inner")[this.options.html?"html":"text"](t),e.removeClass("fade in top bottom left right")},hide:function(){function i(){var t=setTimeout(function(){n.off(e.support.transition.end).detach()},500);n.one(e.support.transition.end,function(){clearTimeout(t),n.detach()})}var t=this,n=this.tip(),r=e.Event("hide");this.$element.trigger(r);if(r.isDefaultPrevented())return;return n.removeClass("in"),e.support.transition&&this.$tip.hasClass("fade")?i():n.detach(),this.$element.trigger("hidden"),this},fixTitle:function(){var e=this.$element;(e.attr("title")||typeof e.attr("data-original-title")!="string")&&e.attr("data-original-title",e.attr("title")||"").attr("title","")},hasContent:function(){return this.getTitle()},getPosition:function(){var t=this.$element[0];return e.extend({},typeof t.getBoundingClientRect=="function"?t.getBoundingClientRect():{width:t.offsetWidth,height:t.offsetHeight},this.$element.offset())},getTitle:function(){var e,t=this.$element,n=this.options;return e=t.attr("data-original-title")||(typeof n.title=="function"?n.title.call(t[0]):n.title),e},tip:function(){return this.$tip=this.$tip||e(this.options.template)},arrow:function(){return this.$arrow=this.$arrow||this.tip().find(".tooltip-arrow")},validate:function(){this.$element[0].parentNode||(this.hide(),this.$element=null,this.options=null)},enable:function(){this.enabled=!0},disable:function(){this.enabled=!1},toggleEnabled:function(){this.enabled=!this.enabled},toggle:function(t){var n=t?e(t.currentTarget)[this.type](this._options).data(this.type):this;n.tip().hasClass("in")?n.hide():n.show()},destroy:function(){this.hide().$element.off("."+this.type).removeData(this.type)}};var n=e.fn.tooltip;e.fn.tooltip=function(n){return this.each(function(){var r=e(this),i=r.data("tooltip"),s=typeof n=="object"&&n;i||r.data("tooltip",i=new t(this,s)),typeof n=="string"&&i[n]()})},e.fn.tooltip.Constructor=t,e.fn.tooltip.defaults={animation:!0,placement:"top",selector:!1,template:'<div class="tooltip"><div class="tooltip-arrow"></div><div class="tooltip-inner"></div></div>',trigger:"hover focus",title:"",delay:0,html:!1,container:!1},e.fn.tooltip.noConflict=function(){return e.fn.tooltip=n,this}}(window.jQuery),!function(e){"use strict";var t=function(e,t){this.init("popover",e,t)};t.prototype=e.extend({},e.fn.tooltip.Constructor.prototype,{constructor:t,setContent:function(){var e=this.tip(),t=this.getTitle(),n=this.getContent();e.find(".popover-title")[this.options.html?"html":"text"](t),e.find(".popover-content")[this.options.html?"html":"text"](n),e.removeClass("fade top bottom left right in")},hasContent:function(){return this.getTitle()||this.getContent()},getContent:function(){var e,t=this.$element,n=this.options;return e=(typeof n.content=="function"?n.content.call(t[0]):n.content)||t.attr("data-content"),e},tip:function(){return this.$tip||(this.$tip=e(this.options.template)),this.$tip},destroy:function(){this.hide().$element.off("."+this.type).removeData(this.type)}});var n=e.fn.popover;e.fn.popover=function(n){return this.each(function(){var r=e(this),i=r.data("popover"),s=typeof n=="object"&&n;i||r.data("popover",i=new t(this,s)),typeof n=="string"&&i[n]()})},e.fn.popover.Constructor=t,e.fn.popover.defaults=e.extend({},e.fn.tooltip.defaults,{placement:"right",trigger:"click",content:"",template:'<div class="popover"><div class="arrow"></div><h3 class="popover-title"></h3><div class="popover-content"></div></div>'}),e.fn.popover.noConflict=function(){return e.fn.popover=n,this}}(window.jQuery),!function(e){"use strict";function t(t,n){var r=e.proxy(this.process,this),i=e(t).is("body")?e(window):e(t),s;this.options=e.extend({},e.fn.scrollspy.defaults,n),this.$scrollElement=i.on("scroll.scroll-spy.data-api",r),this.selector=(this.options.target||(s=e(t).attr("href"))&&s.replace(/.*(?=#[^\s]+$)/,"")||"")+" .nav li > a",this.$body=e("body"),this.refresh(),this.process()}t.prototype={constructor:t,refresh:function(){var t=this,n;this.offsets=e([]),this.targets=e([]),n=this.$body.find(this.selector).map(function(){var n=e(this),r=n.data("target")||n.attr("href"),i=/^#\w/.test(r)&&e(r);return i&&i.length&&[[i.position().top+(!e.isWindow(t.$scrollElement.get(0))&&t.$scrollElement.scrollTop()),r]]||null}).sort(function(e,t){return e[0]-t[0]}).each(function(){t.offsets.push(this[0]),t.targets.push(this[1])})},process:function(){var e=this.$scrollElement.scrollTop()+this.options.offset,t=this.$scrollElement[0].scrollHeight||this.$body[0].scrollHeight,n=t-this.$scrollElement.height(),r=this.offsets,i=this.targets,s=this.activeTarget,o;if(e>=n)return s!=(o=i.last()[0])&&this.activate(o);for(o=r.length;o--;)s!=i[o]&&e>=r[o]&&(!r[o+1]||e<=r[o+1])&&this.activate(i[o])},activate:function(t){var n,r;this.activeTarget=t,e(this.selector).parent(".active").removeClass("active"),r=this.selector+'[data-target="'+t+'"],'+this.selector+'[href="'+t+'"]',n=e(r).parent("li").addClass("active"),n.parent(".dropdown-menu").length&&(n=n.closest("li.dropdown").addClass("active")),n.trigger("activate")}};var n=e.fn.scrollspy;e.fn.scrollspy=function(n){return this.each(function(){var r=e(this),i=r.data("scrollspy"),s=typeof n=="object"&&n;i||r.data("scrollspy",i=new t(this,s)),typeof n=="string"&&i[n]()})},e.fn.scrollspy.Constructor=t,e.fn.scrollspy.defaults={offset:10},e.fn.scrollspy.noConflict=function(){return e.fn.scrollspy=n,this},e(window).on("load",function(){e('[data-spy="scroll"]').each(function(){var t=e(this);t.scrollspy(t.data())})})}(window.jQuery),!function(e){"use strict";var t=function(t){this.element=e(t)};t.prototype={constructor:t,show:function(){var t=this.element,n=t.closest("ul:not(.dropdown-menu)"),r=t.attr("data-target"),i,s,o;r||(r=t.attr("href"),r=r&&r.replace(/.*(?=#[^\s]*$)/,""));if(t.parent("li").hasClass("active"))return;i=n.find(".active:last a")[0],o=e.Event("show",{relatedTarget:i}),t.trigger(o);if(o.isDefaultPrevented())return;s=e(r),this.activate(t.parent("li"),n),this.activate(s,s.parent(),function(){t.trigger({type:"shown",relatedTarget:i})})},activate:function(t,n,r){function o(){i.removeClass("active").find("> .dropdown-menu > .active").removeClass("active"),t.addClass("active"),s?(t[0].offsetWidth,t.addClass("in")):t.removeClass("fade"),t.parent(".dropdown-menu")&&t.closest("li.dropdown").addClass("active"),r&&r()}var i=n.find("> .active"),s=r&&e.support.transition&&i.hasClass("fade");s?i.one(e.support.transition.end,o):o(),i.removeClass("in")}};var n=e.fn.tab;e.fn.tab=function(n){return this.each(function(){var r=e(this),i=r.data("tab");i||r.data("tab",i=new t(this)),typeof n=="string"&&i[n]()})},e.fn.tab.Constructor=t,e.fn.tab.noConflict=function(){return e.fn.tab=n,this},e(document).on("click.tab.data-api",'[data-toggle="tab"], [data-toggle="pill"]',function(t){t.preventDefault(),e(this).tab("show")})}(window.jQuery),!function(e){"use strict";var t=function(t,n){this.$element=e(t),this.options=e.extend({},e.fn.typeahead.defaults,n),this.matcher=this.options.matcher||this.matcher,this.sorter=this.options.sorter||this.sorter,this.highlighter=this.options.highlighter||this.highlighter,this.updater=this.options.updater||this.updater,this.source=this.options.source,this.$menu=e(this.options.menu),this.shown=!1,this.listen()};t.prototype={constructor:t,select:function(){var e=this.$menu.find(".active").attr("data-value");return this.$element.val(this.updater(e)).change(),this.hide()},updater:function(e){return e},show:function(){var t=e.extend({},this.$element.position(),{height:this.$element[0].offsetHeight});return this.$menu.insertAfter(this.$element).css({top:t.top+t.height,left:t.left}).show(),this.shown=!0,this},hide:function(){return this.$menu.hide(),this.shown=!1,this},lookup:function(t){var n;return this.query=this.$element.val(),!this.query||this.query.length<this.options.minLength?this.shown?this.hide():this:(n=e.isFunction(this.source)?this.source(this.query,e.proxy(this.process,this)):this.source,n?this.process(n):this)},process:function(t){var n=this;return t=e.grep(t,function(e){return n.matcher(e)}),t=this.sorter(t),t.length?this.render(t.slice(0,this.options.items)).show():this.shown?this.hide():this},matcher:function(e){return~e.toLowerCase().indexOf(this.query.toLowerCase())},sorter:function(e){var t=[],n=[],r=[],i;while(i=e.shift())i.toLowerCase().indexOf(this.query.toLowerCase())?~i.indexOf(this.query)?n.push(i):r.push(i):t.push(i);return t.concat(n,r)},highlighter:function(e){var t=this.query.replace(/[\-\[\]{}()*+?.,\\\^$|#\s]/g,"\\$&");return e.replace(new RegExp("("+t+")","ig"),function(e,t){return"<strong>"+t+"</strong>"})},render:function(t){var n=this;return t=e(t).map(function(t,r){return t=e(n.options.item).attr("data-value",r),t.find("a").html(n.highlighter(r)),t[0]}),t.first().addClass("active"),this.$menu.html(t),this},next:function(t){var n=this.$menu.find(".active").removeClass("active"),r=n.next();r.length||(r=e(this.$menu.find("li")[0])),r.addClass("active")},prev:function(e){var t=this.$menu.find(".active").removeClass("active"),n=t.prev();n.length||(n=this.$menu.find("li").last()),n.addClass("active")},listen:function(){this.$element.on("focus",e.proxy(this.focus,this)).on("blur",e.proxy(this.blur,this)).on("keypress",e.proxy(this.keypress,this)).on("keyup",e.proxy(this.keyup,this)),this.eventSupported("keydown")&&this.$element.on("keydown",e.proxy(this.keydown,this)),this.$menu.on("click",e.proxy(this.click,this)).on("mouseenter","li",e.proxy(this.mouseenter,this)).on("mouseleave","li",e.proxy(this.mouseleave,this))},eventSupported:function(e){var t=e in this.$element;return t||(this.$element.setAttribute(e,"return;"),t=typeof this.$element[e]=="function"),t},move:function(e){if(!this.shown)return;switch(e.keyCode){case 9:case 13:case 27:e.preventDefault();break;case 38:e.preventDefault(),this.prev();break;case 40:e.preventDefault(),this.next()}e.stopPropagation()},keydown:function(t){this.suppressKeyPressRepeat=~e.inArray(t.keyCode,[40,38,9,13,27]),this.move(t)},keypress:function(e){if(this.suppressKeyPressRepeat)return;this.move(e)},keyup:function(e){switch(e.keyCode){case 40:case 38:case 16:case 17:case 18:break;case 9:case 13:if(!this.shown)return;this.select();break;case 27:if(!this.shown)return;this.hide();break;default:this.lookup()}e.stopPropagation(),e.preventDefault()},focus:function(e){this.focused=!0},blur:function(e){this.focused=!1,!this.mousedover&&this.shown&&this.hide()},click:function(e){e.stopPropagation(),e.preventDefault(),this.select(),this.$element.focus()},mouseenter:function(t){this.mousedover=!0,this.$menu.find(".active").removeClass("active"),e(t.currentTarget).addClass("active")},mouseleave:function(e){this.mousedover=!1,!this.focused&&this.shown&&this.hide()}};var n=e.fn.typeahead;e.fn.typeahead=function(n){return this.each(function(){var r=e(this),i=r.data("typeahead"),s=typeof n=="object"&&n;i||r.data("typeahead",i=new t(this,s)),typeof n=="string"&&i[n]()})},e.fn.typeahead.defaults={source:[],items:8,menu:'<ul class="typeahead dropdown-menu"></ul>',item:'<li><a href="#"></a></li>',minLength:1},e.fn.typeahead.Constructor=t,e.fn.typeahead.noConflict=function(){return e.fn.typeahead=n,this},e(document).on("focus.typeahead.data-api",'[data-provide="typeahead"]',function(t){var n=e(this);if(n.data("typeahead"))return;n.typeahead(n.data())})}(window.jQuery),!function(e){"use strict";var t=function(t,n){this.options=e.extend({},e.fn.affix.defaults,n),this.$window=e(window).on("scroll.affix.data-api",e.proxy(this.checkPosition,this)).on("click.affix.data-api",e.proxy(function(){setTimeout(e.proxy(this.checkPosition,this),1)},this)),this.$element=e(t),this.checkPosition()};t.prototype.checkPosition=function(){if(!this.$element.is(":visible"))return;var t=e(document).height(),n=this.$window.scrollTop(),r=this.$element.offset(),i=this.options.offset,s=i.bottom,o=i.top,u="affix affix-top affix-bottom",a;typeof i!="object"&&(s=o=i),typeof o=="function"&&(o=i.top()),typeof s=="function"&&(s=i.bottom()),a=this.unpin!=null&&n+this.unpin<=r.top?!1:s!=null&&r.top+this.$element.height()>=t-s?"bottom":o!=null&&n<=o?"top":!1;if(this.affixed===a)return;this.affixed=a,this.unpin=a=="bottom"?r.top-n:null,this.$element.removeClass(u).addClass("affix"+(a?"-"+a:""))};var n=e.fn.affix;e.fn.affix=function(n){return this.each(function(){var r=e(this),i=r.data("affix"),s=typeof n=="object"&&n;i||r.data("affix",i=new t(this,s)),typeof n=="string"&&i[n]()})},e.fn.affix.Constructor=t,e.fn.affix.defaults={offset:0},e.fn.affix.noConflict=function(){return e.fn.affix=n,this},e(window).on("load",function(){e('[data-spy="affix"]').each(function(){var t=e(this),n=t.data();n.offset=n.offset||{},n.offsetBottom&&(n.offset.bottom=n.offsetBottom),n.offsetTop&&(n.offset.top=n.offsetTop),t.affix(n)})})}(window.jQuery);                                                                                                                                                                                                                                                              master/bootstrap/img/glyphicons-halflings-white.png                                                 000644  000767  000024  00000021111 12110524611 023535  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         �PNG

   IHDR  �   �   �ӳ{  �PLTE���      ������   ������mmm   ���������      ������������   ���      ���������   ���������������������      ������   ��ⰰ�������������������   ���   ���   ��������������������ᒒ�������������ttt������   ��󻻻������������bbb������������������������������������������������������������������eeeggg��𶶶���������������������������������xxx��������������������������������󛛛�����������������������������������Ƽ��������������������������������������������������   �����������������������������������������������������������������������������������������������������������������������������������몪������������������֢�����������UUU������������������������������������������������������������   ��������������鿿�����������������rO�   �tRNS  ���#�_
/�����oS��?��C�kD���OS_������6��>4!~a�@1�_'o�n�ҋ���M���3�BQj��p&%!l��"Xqr;�� A[�<`�am}4�3/0I��PCM!6(*gK&YQ�GDP,�`�{VP�-�x�)h�7�e1]��W��$��1�b�zSܕcO��]����U;Zi<N#�)	86pV��:h�#�0Z�Q�JN��EDT��~��^  -IDATx^읇#Ǚ��b'4A$Ah �)�p�3�<M�F9Y9X��,�r�i���ھ��|�s��t9�s��޿�X� k��jv�@�l_��I��*~h��>�'y�"�������؆�K64�Y�*.v�@���c.};��tN%�DI����	!Z�Џ5L�H�2�6 ��ɯ��"��-b�E,,)�ʏ �B���>m�����n��6pm�R�O
wm@���V�#?�'C�ȑZ#��q����b��|$�:�)��/E�%��nR�q�C�hn��%�i�̓�����}l�m
?i�d�d�"�,��� `�H�"r.z�����~���(b�Q�U&��)�5��X#�����EM���R<�*p[�[%.�O�̣��k7� lIo�������J�F��lV!̡ăuH�`��������&�,�z��Rk$���|$�l���Xb�����jߪ�dU��?Σ$H���W��$U�'���H�E3*խ����U\}���(�
�zhVk}g�u�Rk$��%�|�T�|��ck�獳"��D����_W+����.Q���)�@���ƽ�H����b�s��l��T���D���R �2Xm�#a��3lY��z�j����㒚#!�	4�J��8�( ��c�v���t]�a��T����	��� D΅��Q?^-��_^$:\���V	�$��N|�=(v�Z'q�6�Z�׆���B5V���!y���3��K��㱿b� v4��x����R]al��!��I�o�P�@�t��Vy����L��٪ml�ڿI�Ub|[*��lke'*�Wd���d���D�ӝ}\W��_Wߝ����r�N�?���vޫ�۲X%��0u��oui*��JV��Ʀ�b%�}���i5I�YlN�E-w�ς�f_W3m�I��������-�m����Q)�S��k��TC7��m�<"��܌�b�T|��'��$�Ҙ�����R&>��Op��������6�������t���S��N\�ׯL��m��\�����r@�3�u�T
b7��t.5.q���3�r0�=�8T����i�J�\��6uF
��R�32^���'Ū�����x��I�	��F�8O{%8��kJ��MS�ȴd�BEd����W��CY��O:/O�N/�I��_=��xFE��! �=��i:o�~��� y�?��'��'��[͓[͓[͓[͓[ͭ��.�U>�$�P�Ʀ�c%�]��\c��:�|	�,e�S�Z,�o��Xr����X�!�R����@�Z�v� �0��> ?�*��<��� |����N6�0��;{�a�d��2��v+D��^t����[q !�۞V}��f��ۨϏ���Y��eॗ��)Vy�l|"f�U��q��@�Ǽ�4Y-��Y��-!�6a���B:o%�J��I���UQ|�U�K�O�`��=\����:�0���x��Pa��u�@��!�K��P�d�xhw1>�$j΍��v��Zd���x��S�UA�&[UR�d��7�ø��z�k��/���r�U^������w:I.�VǮ���c>q�.!�zS�r&���2�)Wg�	��R	-�i�Q	8����Pa\О�U%�iݡ��U�_=��p��	�Lu��(�N�?���0?�Æ:]�ά���t�B%�U|�����NsorN��f��	�,�P	!�v"
Y�6�hL�_� @ @�b�s�c���qg�v4|��|0lϟ���$S��9����bʱ��j#���~�����?o��}����}7sAPm:IV�=n���
!���{��{��h��Eࢪ�8�s �u ��oL���T�$��;V����s��cq�D�3������༂3.D�B������ B4 �&�V'��T�	`��D� 6����Ϸ�q�y�j�8V����*���X%���@s�\�jrN�$�|�=5�Ά '�mU��i��K��i�%C��I�:ssaƅ`*`��=�l��)>�u՘MeuS����I�_�O��L��_�}�o&���jz��� p���{�����lu�:O������)�s�%Q@��$�<]f�	��xO%��PCbhr2����� ���� PK���p�f5�Në3^o�����]�e�J����i�B��464��^t���uٲ�U֌:G4'���22Y�p���u�G'/Py�4?���.��SB�P_>����I	1t3Γ�B�ɭ�ɭ�ɭ�ɭ�V��V��V��V��Vs���]�!�67(��g�����y��@��4>Q�� ��V�F�}^Xׇ�ڼ���j���e�26	L���%��Y�G�h���l�C�}�)��<
�!�E����E�P�ZWZ���V+�@�R5{@ou�ɐ�4���&� ���H���6�e�y V��݀�Vť�����cqZ�ޒ�r��J��yB��y���Fz��FN�$��Hb����*+�jՏq�э�� ګ�kݿU�X��l�e������1����d�0d^�-�B%���}����{Y���%r�*�j5Ak5�u��"�,�:~�Ҹ�Y��~
h����SA�~��6���fu�lՇf��{ȵQtATH�Z�k���ƭ/ _���S��n���
�u']b�]|m`�B��ā����J,O$��du]�Zs��FL�:������a�����Ǚ���T4�o�~by?wp�j滥�A����(�x�]�����f���~an֧/����^�d�ڲ�c��� �Շ,!��1��i&�xi_VK@ip�̓9���Vi%a;��L?�0J�*���Ū5���U����'���x^�6�V[�^ �{�eU���|�:0�=0���d۫o���*J�q%�[���Y�N��.sQ�L�ud�[2��9�I��:W�n��������m�Xl�ڃ�6�!l�Nl��V�էKU���jV�\J%�Uߊ��B��LcKf�b��>a�=�b�~�R]aG%[����js@�<i�[Х*^.d;UI�R+�OD�2e�ܶ� ��Q��N3�4"1�������g�0���u�\��I}����wFV��4y/D��j��j��jn5On5On5On5On5��h�,ҷUr��]��]L^����%J��D���iɭ��G�ԝߴ�/ �%='q�å)����:��Q�<�X�.��'���[�@�P����v�/ɼ����>/9�MطݘU�>yɲX�@}����F��t�g^��vO\��Ӹwv�p���z3��K5i�!$P>�ā����'��Vƛ���L�2r��@�UM��K��Z�����6���tw�맟¦b�m�1�h|�|�]}~�0��MjA ����(J� ����JP68�C&yr��׉e}�j�_c�J�?�I0��k��>�W����	������|�B�ޝ�."TEXd� ��8��!cw�*E(�J)���!�[W"�j_���ТeX_��XB;���o��O0~?�:P�C�(.����[�����!Wq�%��*le��Y)E�<^�K�Z�T�60�.���#���A\���5;Rm�tkd�/8�)5~����^0� #�Ckg���e��y)����Ͷ��Ժ� �6ĥ�<�(?��&���u�A��V���m0^h�.�t�xR*��a��'�:,�H�|�ō���l5z�;8+e�#b'#|�}2�w(|Kc�J��l6�����w��^�Տ�o��i��3H��R	��̔9�,Y�gP�ְ:N�[5S����R��!���[)��]���i}` ���m���N�4Х���v�`|;f�(��F�lt���L�8��÷Z#�AO%��Y)N�U�5Y��e��d�J�E�3dZذ���<�x����ɝ��e �@�Pڧ���F�TR��2S�·��Φ/u�Z�~�C�3���X�z���U���x�\2�s���e �D��D.���fBO&en�'i��R%��?Fy�VsS~$u��m��w()��r��o�0*D���i!3�:On[B�!sʇB�p>ݣHT�1��;�8M�jnʏ��Ӥ��qp�1h�^�<��<��<���j��j��j��j��jn�����q�(qp�Ok���}���I?TY8H��mh�yK�̝u5�����I�t�e�nQBޗ`�R��`��E�P��ڦ����x�����>�>����yt�{?|��'j)�����}YU���U���{�@V�/�J1�F+���7䀉[OW�O[������y���UY������!?B��D%�D��Wj�>-Ai6x�z)���U 	R�����7d���@�g�� ��\�so�)�a�4�zf�[�W+���>�����P��>�
|��qL��G8�v���ȣ��l�j���2Z��t��+��V��A�6g<�/��Q�H��SrΣ����d}��Y�q��g]�sY]�;]F�C�@5�Y��Ֆ�5�C�3�8o�)k�1'��d6�>T*�ʆ��Uz(�m)��CD`��He/�.�:�zN��9pgo&N�C�׃�އ�>�W��հ_��Hj��)�Xe6F� �7p�m�-�`'�c���.����AZ=���^�e8��F�;<����J1{��+8'�ɪ'�և\A�*����[���R$U�Y)V��AyɃ�w)�Ec#<�T����\vW<�U1�IؘCDo��Yo��]�wm�aw��:B� :'�Z+�v�}��|�0��q���1�P�΃�*��u��T��7 �F3��9���A}$���f�+�o����[��I�5��ʰ�޽x(&����i ��ʼY���:c�Pp*��b��¸J���j�V7 l�jtsNk��v����[�fy3��g]�������u����鲱���g�J��E�0)Vił��ù�����\vW<�Ug�t �e�~B�[����A�����H�J��'�.��n��&	1Ԕ��	��o%gͱ_��N�
���5�.W���3y/D��d�yr���<��<��<��<��<���j�ܪ{�����waw�:6�dJ�;&���3�ptl���as������W_U���T�_'9{?�a���Ԭ���l /0���dHgqll�c����8�R�y�����m=ˢ�_�ͺ�[Է71�x"�"��S�IfV��r���x3�3y�) h����h�ՠ��0���?�r��5�x�����_�-����j����������чoO:��$��� XBX J��ѣ�1����#ֈu7�`�zu2��{�\;��uܗ�9@�0��V$2X���S�����&���Ba��[�O�~��j�N2ߠȪ/����jz_� ��n A��������~���u��h @GL�O�eɵ��?T���f<V�����e��@���* �-}�e��@��0Zt�/~������Xm0�*���*��H'\������u��S�E��m�Lֻ��6������;+{l��5۽����?u*����_�	Ni-:�I@,;�]����W�Y�`	*���߀n �SO��~�n���W�P�.��c����Z�T�u��� Po^ǃ7����w��B�RB�W�_m�dj���������B���6�:��*��H����]�����d�Q>�{R��������t�n(��z�!S�7o
����Ie���w �3]��bܗ���8�5|�i��Ϡ��R� �JkʱZ�RO+�8�U&�:]�Z�ieR����<I��~�|�d���,�j��릟�{��;�7�U �݌�X�B���`�����[�u5~�=z�q굵Ű�޹e ��b�c5���o���{;����ߩ�@;���n*T�ĵ2�$ܨ��0�'�Y-?
�j�[�Z��j����ӭ�v���i�-�*rD{�mL-,L�=��y��m��x���c:���We����vұ��oÏń�
��"dF����8[�T}ӵF�-�I��V��lV[P�����)DVC�8ݪ}|kZ������{����Y�|��xrr��xa���G_���>�(��J�M�ޗ7����Z@��5�a^�\G�z��s���ρU��*�rM�e�zT�^�:ɬ��ͦX=>�$
bi>�U&X�Qoybb�G��k��8� �
�Ҙ���n).Ս���� o���^M�m�d�Z���i�$s��o�o��*{�4���eLb�Lٳ"�"mx:�`:m�k�[�geT���ެ)���'0*T��B�{!��I��'��'��'��'��[͓[͓[͓[͓[]�Z���jQ�.e�'/��y�vQ�71�(Z&���X��?(_��Z�����){t�ڀm�Z���W�Ϗ�)��-C����jq�n�,̋�"�Iv���UL�!h���꛿���s�k��AcrN���佚ф���VE4�0�y�X��~�4zʸV㳰%��,���)f���qt�p�u�~�������*���^��0:����ܲ�3�3���J��O�(�����ZB?K�^ �v]�un��l����W����i0�p6��[착�C_5X�#�[��wX3�b��廫�R�{���NK�A�����e S���e�|���w��x���s��o>�P\儔ԕ6�;nV�m�f�I$�����V͓J- �J%֌��0��Uw�YЎ�S����n�u��m�藮���xz��˗V�ƫ�I�vn�W��_�qL�Z����"_�X�z���� 8�]Ap�����?��C�� ���5�4��3�zw(�{7e�*Ȳ`۰�!A�Q�:�KUn�����z�]�1y�V���Ga��C��m0�PY
ٚUx6TT&�hV�9V�
���Ӭ�zÑ� 1[�X�z�Z�����9�e�r�q�J���ND�/���g��X��*9o���N6�D��`�{���I�%�M�z9�T�Q�������7f�\"j��_3����~xB�'���ܷ��Y��]*KЌ�%"���5�"��qxq~���ƕ=����j���S�>j�V�&~]2�xz�F����1X��_y��D��<#N����RB��}K����/���i��y�����!V^��˿e�J���}/Fk��A��7��� ��S���+.�(ec���J:�z����W�Z���몖w���Q������~a����̈́�p�6,e5��,�+����,���������t�v�%O^O��O}�ן -O��7>e��kC�6�wa�_��C���|���9���*�����W��A�)�U�Jg�8<�Z���x^?���2�u��Y�����*^?��ڇKC�Z�[�����0.���C��@m�����$-��/~�|�Y��[e�w�eQ ���׶&c��O�4s|��c��J���ws��X�8/��6�/ڼ;�'F�LN^�8]��ead�Z1'�� ����^�������L��sBd�%�+M��`��SK��8פ����*��)gl�#�3"��gъ�S�����qtcxx��|H>����=��:�����m�j������U����v�q�y��s�ܒ�Lgl�C6+[F�SWg���9���wV3�1�A	��N��D�<�����$5e�(s������[�    ۨb�����aF.��]�K���    IEND�B`�                                                                                                                                                                                                                                                                                                                                                                                                                                                       master/bootstrap/img/glyphicons-halflings.png                                                       000644  000767  000024  00000030777 12110524611 022441  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         �PNG

   IHDR  �   �   ��   tEXtSoftware Adobe ImageReadyq�e<  1�IDATx��}ml\E��W��^ɺ�D$|nw'��;vю�8�m0��k<f�8ـ�<�h3$� b,mn��� ғ����0��L Y`6s'>�Q������S������n�S�V�;1K�G���s�ԩ�>Uo���TU�1cƖ�Yuּ��c��a&���#C,pؚ��>kں����U�LW
-s�n�3V�q��~N����o��c���I�~L� �{��-	���H8%_��M�£w�B��6EW��,Ģp������Y�2+�(Y���@��&��A�/�����3kX�h�ߍ�-a����A���<>P���'\���J�;(�}�# �Qz������:4��%m?nf�ntK*����l�9J���+�D��I��Yu1Y���Z^��(]YYE��f@���О�lX��z]�U�t�	��u��&�5-P���W�}��@t�|�#L��Y�=��s��܂���,w#+�R�+?�Ƌa�x��	X�0�"ea)�t�G�*ԡwV�w�V^�� rf%xB(qּ�4>��W�G�#��lWU<Ё����XJVѶ��l�����R���$k�DVr�I����7:�X<�s>%X�1��N��Ez��w���;y��9�z�9�O�%~��~��u��ɗ*�=�����I�x�c�y}��Y(���o��u
±N$�^�j���e\��iX�񝜬]��;Y-�r�� ��Ѳ�&��>�!�zlY�aVHVN԰�9=��]�=������mR��M���d��OUC�JUiT}r�W��W'�ڹu��)ʢ����F"YU�#��P�׾����&ܑ�Ѕ���R�O����wyz��m$���O����s?  +^�FT�����I�E�q�%��&�����~�>�M���}]��Ԗ��w�A��?
[���Nteexn�(�措���B�d��MT��pʥ�nq�q�S�?���bW����XmW6��x*{V_����!V�jΧ�s�VL^j���Xk�Qj�U����6���sk��̩n~�[�q�Ǹ�-��`�O���:G�����7��l��"k�������sR�e�2��v�Q�=�QƼJ�U�X`�g�Qy~	ď�K��Ȱ��E�]��#��P��:�t���d�\T�/u���������;�س�:�J�c-%'��e��q���
?j�"/yh���4��8�Zi������1�|JU���u�>��_���N���;hxw�NU�J�QU7\�j�̮bT�:�����B�?6����o�J��1Ί%��I
UY-I���i4{�=�rǤ7��@)H�K�J+�f�4�X�8C�d�?'j��1��� ��N���<�3�9����E<�w߬��V���z�E}��^_e檴p��t붾3��9�,��?���g�l�Y�O���<���x�x�|���a؎��Ue����F����	�1�;��{EF�0`����D�R���+�U�YiD����4�?�Y`|B���s2��yip�I�q�>W�o��V���T��G��zg#�
%���D0#ܠ3���[t�i�آ�(U�,�]�125��|��N�̭fw�7w� �����u+���]�D�b]��K� ��xbW�՛7|�В��X㕛���{U����c��G����X�k¬�|�(� h)IU�a)�lp 3��l���uPU�]D��)�/7~4W��t5�J}��V���
X�0���z� �VM���;>�Gԙ�^���|��gF:��jaZ��^)74C#j�wr,еS�l��G�u�;1���v�m><�)�}��<���VZue۠D�+j�y����J6V{j���K��>��Z���QՖ���&�mZ:���1�U�MB�~���
�a���:�/᜗:K�W�WOҠ&�����Y���2f����7cƌ3f̘1cƌ3f̘1cƌ3f̘1cƌ3f̘��g��*3f�F5�Lb���N��2#Tf=C�`!��ZG�Ue꣇�e��2V���<�1mkS����4iϗ*.�{N�8X�aj~���ڀ�nA�x,���%fE:�|�Y�DV�j
��¢�lg6�(:�k~���M�M��5?�4	]WO�>��诋W����Z�iG�|�Q�G�Je��K[Ycյ�pmjE\f/�ǎ8&�OQ�3� ����.3t��t2'�-V�8���p�X�S�r�Y#J!���Q�� �"�,ub�@F���K�:�u�^��iy��[]<.Cw�� ���+W\�)��b���
k�r-���.M�t�ڀ�M��q�ʄ������۰����#$�^X$��"�������V`�T�4�m��~�w%P�p1��|�+&Ux�Y��8��*�r�8:��� ��k7QЃҀT���������$��Ў��ƙ�
�S>~�S�����j�s�:5�q.w�&_Z.�X=����:ވbw�`��� _�kd�{'��0�:�d��s��#�q���i!224����nq�\�9�-��KUT�sSU��uVo�@;�U��z�>^��=��N��������p��>o��P��O���
��@I���@���'G��j5�o�*U�>��^�*�e�w��>ͫʧ��᫠Q���5̈́���<$�#�5�J�ٻ�j��6e�)��_����d]��2���B:���^�(*�:8J���Y�S鬆����Kݗ��]U4_�rj�{���5�ׇ�aǑ/�y�V��?��G�t��G�����b@xPU��7O3�|�鍪	�I��Q5��Q��Gw�	*(;�w�f�0*�P�UU�<Y�Ɣ���v����b��t��5{2!�,}����Ҧ���:)��j2Ok�Ϊ�'֊0I.q\(�%ojQ���ĖՇ�a<��ԍ��ex�Agt��'�[d;׸�����`r�cd�����j��P�FU�$�UeJ�I6�T���&Z}���z���(�z�vfu�z� ��{}ۿߝ��ݞlx��U�Z�謊�.�Y岟b���%�����nw��@��ǩ��S9��|źs%�>�_�o#���9�\�EU~�/�ځ�t(r�[�Q��Zu��Oo;�����!MrU�]��0T��cpDő�? .���c��Pu����F������;����L_�������S��b}�R/�J_��+��h�2$�a��i��U�ǩ��S9>��Є}7�6r���zu�����~国4��oĨ
1J����
��^�̘��~��i C޸�5��5<P�ھ�r�/�G��Y�k૵��5�mK
��2姪�Ϊ5,���?�1'�jÓQ���pT뾺���
*��~�I?H�ם�):����\������J��:3�ѴUGo)X��.�Ë���*j�\��?}�㉎�G~A{Y#�W/3��鬶�!ʼ��=��C�g�u	*���u_��ޮ+�Qe�5�w�:���U���K��?U�W�1j\��S5/<�z7P^����<,S��j�UU8�����v,�2�_��_��i�뻊��^����R5^v��Nl>G׹]�g���w��s�nzTuO=�?/����zƲc>��Οb�#7ֻcg��k��ޛT�U�j���*-T=]����uu}��>ݨ�NЭ���[]�:%/_���S�z]6D.�m������D7Uƌ3f̘1cƌ3f̘1cƌ3f̘1cƌ3f̘1cƌ3f̘1c����>�J4h�PP��+��A�;'�G_�XK��mL���5I.},wFFu��m$S�-�E�-;Õ
C3I-`�B��R��x1��ғT�Jݕ;hΊ�8�D�Y��J��o;������Y5�M����K��ɰM��;���%P��� d9K�h���n�D[z��gVh�,��'C�
p!^M�(�WK2�X�>UQ��%���^��p8	˽�^#�Ζ؄+.@���g�C�z%ɔ-Pr
���K�X��
����n���>���=�Ք�Ѩ��eSvR����L�z���5%9UQS ��\�W�ի��K��'�h�p)ô
J��r�h����M0�F��(f_�R5�/�//�G��+������x	1"����eS��5��
��:T��f��=+�7�Qɧ�\�����TE����s�༬�r���Y�s8��&�k��������#pSՊ5�M�T�b��D܊[Ng�5Q�\s�� 5PB@[� 8ɨ�V1������&��4Wsy[�Ǿ
�w�U���2�V�����7��7��j������މd^~Yf��C��_��h;a.���&�M�
i� ��U�����Wpzs`>�/�"��'O�I����۲�y�����:�Bzd������T���q£�=й��b:���"����m�/��-/P��W�DQ�Ǵ͐��5���7������m�`�H��%A���V��!�H�ԛ׿���@"Q�� z��ދ|�ߒT���-�*OU�^��Ҧ6�����!��Cw�k�|h�&Hd5�LEY�y��'�ƣ7��%�*�<C'@�l ���b!w L�WW(%���C��4��������3\��������x������*������QF�Ҩ�<��m�������߃g?߉������^�)D�}�{�U��֘|�Q����=C'@�| �uw L�ׂQ�E�=�?�x+�x�"����g���S��O�Ҩj��׈.��fqj[��Y��Gͤ�C���焓m>{��=)���Z�%ٝ��P	���*G���]���� /� �8L�� w��$?8��M�)\į���/#�7U�fd7'6�\h1�
vI�f�EIr���=��1�w��\�WK��VZ�HK��g�Z��͡�$m��x���� %���`j}�TuT���QJZ��*H>*Q�xkLFT����y��U���-�)�ôb��iA���|q`��F�'���+	���4^Q�y�x��H)��#�t^��?@]^`A�R�S��q�jg�B:�r<h̆�Rn���z���PΦ�)��[+�n��M�X�H!����0��I����r����sKϡէU�R2��T	X�g ƴڳE�cƌ3f̘1cƌ3f̘1cƌ3f̘1cƌ3f̘1c�n��j����ǴyƌI��xQ�q�7fM���4E�F��.���34<.�i��;��eВi���1c%9����K	���͠2��J�C��n��w���E¤�c�F������`��5v6�%˿]�3��T��y��`�~���a���[[�J�>K�۷l<2�-4�Y��K�hgQ���L��x�V�w�P��~��M�Φ�����0l 3�ƅ�aŊIT�ȀhwJ�m��������xIM�չ��|��U7xˆS��~2�ߕ?�kW1k���C3]��;Y��nS���ґA�e�X�Yz�8,'�x�<k7Kx�����]��$��x�$�v�g�T#w��;o�����@�z�_V���m�n|�Hֵ��h��Zg-^TAn��-�)����@4�[*�9xK��Ƌ�����j>�!,�Vt�:e�����qn8%oh���S�(2�\Q��^�aig�����F��3��v�TUDV�l�Q�ꅧ�W�c��%�U��e�q�4�ҝº/��U��$�_�Q!��>�����t�|� �,țG<t�C���[�xTXmf|��<��Oڡ�MT�|(w:���_X����j7w���t�� �
AX�ͦ�p�$�^xZ�R��������j�x����`�3=�^��ll�+˗e�Q��8g8V��+�9M���/����� �o�14sn�b���tX�܍�s�����vE�l+@\��e�,�,�cѮ�<�(��i�HVY�r��Q�O7�a��I��>Q%d�#jUՆ�|;H��[b����ά�#������,W�s7NT1~���m&ǻ�{' \��㟾��b�BKJ�o8�%�!���$��Q����j:��/�RX)$Sy�޳䍧�R��DUg_D��軦�J�\�����j�N��֖SU;~�?��O��h�ss�d��ƣ}�6�(T<��_�4���b5���� �^N���N�%8QejF�7to��My�ө�`)g�[��/�������|����?��өJ���u�G����L�坕��/=�CTܠhd�ifH���cǞ�����G4��,��������`�D՞�{'x���G_p/5��@m +�$jV�H���3�a"��*ũ,�,��H�Jҵ�ȸ�T^Qy��o&IÉ�JUVwW���L�eM��~���3t�������A��6����r��wɤ�6���տ�� ��\0H�L%L�X5�c����@�HHÃZ��|NV��+7WM��{����cig���*���ȸU���7iÉ��бz���d� *�?�gt��X���8��̝O��X��:��]2�ɍ]�p^��++��>���A���VڛE�{�����DB.�&�/������56���A�rxY#ܕ�y�)��cKQtȪ��~� ���������! �;�C}ʃ��tf{�6��$N��Vsj��wup�Z)zŁ�|�-�w�g+n�MVj�/d+U������~ͯ�����i���:_ix��w��hq��r>�駃-�x�뼬)��ݷ�y��R=! ���ì:��J/l��Ik���V@�n��7�475��8�Z��K�J�(��Ux�z�1w�)^�\�ԣ��zȪ󲦨c���2f�؍�v�+�6f̘1cƌ3f̘1cƌ3f̘1cƌ3f̘1cƌ3f̘�2��N��o�C��\�����F1�ִ��UZ�JV̚\�4����M����gq1z{&��Y��T
�,�HX~D�u�\��g��}x�>�+Y���dN�̮��o�l�Z�X+F��[�/j��+S~2/jV��8�J�r^�����ԉ]J}J��*ۏ<��2԰&�Jݣ�jO��M@�ѯ#0��O�[��S�������X�B^uz�e��\�����]���d���d.���/���xXE
�f'v��O�_����H�${�%;�k�t�7ށ�m��ő|���d{a�ފ�^���Ǜ�ڎE��5ʋ��Br]W���=�_����SA���f(�0  ��oU�5�q,�_\�l�uz�˪uz���㻲���o�=Yi���~|��
0+�=V������ �J�ت��/��ލ��zM��\�zC�L����[U�:|k*^8"��\Wٚ\.��XTjX�5�Sk�F�u\�1� ���q'��m�ģ/�Q���Uؕ�*�AɽDNZ׮?_�[#�ˍ4�:�^j|�5�L�G���|| ���ø�BW{6[uQF����.1��$qF��9���IHg)\������5��>C�#��u�X�Z��$�#*<�ߐ�sR�v�1Tj>J��m>*����#��(��
��[F�h�sש�5��*jQʼ�&���&��&P��犛L��[�Q��1*���� ��;����X}�I�ΰ�[Q�?�q�Q�ZH�����ݙ���֞V��EsB��C�Z9��JTK������tu���p��˷��/�O���,.k�Ud�s�OHMg4=-)�+ؿ���h2��N��w�/r|W�Qn=�GIU�;��'���j,��v��f�ǳ���p�e����$���VGTY�sBZ�O�1p�j:����r���"n�TUSCg��r�ve���A�ۘ��F�C+Ֆ#�[J���Te�'v9-�3	D�m�ӻ�u�uz������?��0�� �o���	����h�x�u�Y��&�����_�54�=f���07��kלU��0��]D:�����j�dw�/+��P��GUV��S��<��\2�u��at�c�^zY�R�ąmC�+��7����#��,|��:��i�N��w��*|^s��m�|�X>Ъ�^��1�\�#���͹�	&���%�{,2��U��>�ݎ.c0�5�z�#�
o�g��N��O+��Q�쓭�� ������,��˗�-%K\����[S_`�y��+��b���_9��4����"�U��+��Ύap�}�I����[�M,B��.�Nt���w�H��j�漬���E������L��߀0DX(�k�ڵ�����NoU��{�gquz
R�wkէRx'�uZ�[����3'��z�yy��ד%�<U��hN[����tz�x1� c�c���]Fݯ�B�"]a[J����Dս[cƌ3f̘1cƌ3f̘1cƌ3f̘1cƌ3f̘1cƌ3V�es{L+3VH]YP�A	�>�s�����ƕ���3jYF\��s���=m1�&���V���Aɼ?k\+]�6y�ﾓ��1���gt�OIW7�a�l|1��� ����>$]e�7��؝�W�I�e?ަ�L#���>|����
�ҭ��]��
p�M5M�U�dI���61��Ԡ�eǼY�G����h�O�n��3�խR:^�k_'Yuuq#���p�#
�J�����2�x����l>��Oj������cY��馃��!�ڡ+�sZ/�����D�}��2��A�Ym��� �p�c#�<'x��SKx��`�*W[,e|��6�B�H)㶤kj���p��D�U(2qzx��9����*tqa�/,�
Z[��	0�>��Ө�֜����xN)f�ă��@qը����FU՝��w(��a;ˋ�>�|T�c|�w2����eiT]*�!_\�WG{
���]��^���݅��Z5����t|��6�oYH�����a������O@�=�����my^ak����E�.����u��z�]#٥��hWv�(��:�,��6��A��߉J��Fa���\�w��W���ex>v�<��?|����&i_�q�z����]e�R_�7�|& c*�kր4f���,J �U���_�h��\1A�������������u\��-�L\Ϝ^��~�P�hr��*tqa0��fT��:�MU��;q�>�et�u�M��Y��A>�����).,��;ɦ�C�bw�jE)��W������Fӫ@�s4��e�6^�Q9oI}4�x<���.�B?��B��߫�#��$��Hx�.x9,��a!�RT�pgd5������xB��e�����.L7@�*�
Asdutt�S��VUa��RU|��I	xG�߃$T�����񭟬���#_��IF�M�_X�@f�o���Q�ID��I��I?|�%����$�r�	���{�����E��Nĸ�wޕ�qq�?����D�ؽ}�}o�/`ӣ�CT�i	���<Q�R{\yY�����F���QJkh������^?Us:�E��|]���V� )Z|H�jsW����|�H'|��o����=d|�߼j �#��T���%�O��	W��!�N#�w�1[i�H(��SV����s�����[=�Ɉ����7���1�ȳ���T]A G�換��3����CT׻�lR�ݕCV9Q�\V#ܛ��N�ӏj�ˇ1�/�s�l �R���%^s1���nU�j����,�x}��f��W�|JuK�w���p�����S��m,�<��7<����
��Ȼ�����[�R<&���p��?���'��,�Й��\�;����5�bH$�3�#�Q�4\���_���>�/�yw�O��rD9���YUD]���	Ή����@s���]���+'UaL}��h��r�U����'7�:��sU|k)H��@����h�N�q�#�ϵ�8��y�˭�X���ű#��w��
�1!�흉�R'7��f�u�ד��0�����p�!W��ÖW+Nm�p�\����-�ioD$� ���g�٠˅%�%�Ð�m��V�]�̱��r�w*��Z�}��y�+L�
N��o�u�j�}�xt������)lS��tuq���x����m�NyK�U��OnDb�hf}�k�>�6��u�fT�%�����{��� <񐮸���mj��F�c�mU�ï����c��;�w��8��@dG�FUA��&��� �����=n�q�5]iP���}�z�:�k⼶��-��ʓ�	Κl*'U��z�ax�W���F�dZ��zT��NR�s+��#��� w��zgi:��MB��q���t��M��l#��^�'G�ߣ�*^�t�{����=�rE���R��n�Q�$adJl�02%��Tڊ^����<�~g�?�O�f*U�^��?��:��N�����+�o�[�P�U�s�|�Q��R']�V�-L)H�K�䐞mY��n�\��4}Y��V�D��h���R��;g��-��'�3aס�M�D�h�}�1cƌ3f̘1cƌ3f̘1cƌ3f̘1cƌ3f̘1cƌ��k�*Ț4�`L�$�b�	���U���4\dt���'���>�HȄ|�.��+Y+/�G��y���2�OCWv���3v,�'kia��������W����O6߯E�=Hv
$L�l�xI��躍/��}�^]�����x��\3���ɮ5�� ���Q�T&G�9A�y^������i�}O��[5ޱ�wq�4,sJJ��I.myE�^�%���'V�B~�d�ׯ��}�*�j��*�	~��u��T�k���\f�KЬ�*��Y]����_v'I��˨����鑩6�X��o��'�j&u��ɧn�g��T]�o��ڌ��9����\*�wVHӖ�|�	�>��:�5EF�'J����ɝ`���!��A������ �
���e~��_;���5�ױϊ����镋m_&�O����Vi����<}"�靍��hW9�X�6��KPƣG�"�ƭ�?��/����O�^���hC�H���L��c���i��P��j���)}���Q�Qզ��#tM��g��9���xGw�����~d;_�J+�RỲ�<���;�e�����5/Qs�/5��N[��!�a+�N�P�b+�Ѻ��I�}����-��t_�q�U=�MK�ʞ�Y���5no��*����v��v�b�ʊ{]��|�~	Z��{-�������끇^����FVviϵ3��Ya�������=6n���dS;�-�ʹ^;�uꪪ^�|�=��_�w+��"�����i�&4��l�#�w��i��r|W��3U�$��"J�~���O@]~t��RJV��MH�w:̦����@?��>�O���?�vdr��tS�*$�&~1>��������Z}^�n�L(��]�f*�&�*�Q��a�I����Ꝅ|��3�*����O���?�������r�?�*�4�Gyz[�k/t�k��Q��ϖ���WC�C�K�k/��x��5�|��S�*`��Ϲγ�Q����E�w���y�
o��K�YqT�b����$����-/Pt�sZN�K��Q��*>��ݢ���U�@�Џ"JQ;���¹&�
�Lx�;+T�/+���O�赟��>�(T���?ķD^N*�'�p�����$I���W֐��W~�=��J|��_��UTe��7ְP`�;CYjk�=�s�U[��mߙ-���;�};�2|���w��o�1�p�0��~>��0���m��
@J�rǟ�cٷ4�͜��?q��\�UU�IV?2��L��/�+Шꄾ<�܇^T����?t�j\�Jr���Ҁ���B*�����=k�m����X�,n}a����Ւ�Ia��d�p׷��l�l{\��6v8��R��ꅟ����Ҳ��f�1��F|Տ�;�e�=\D��,D�:ψ��r�xQ�T◎�*|{n��S
9~�=�}ӕ��G~%j�:D��j�<�ឫ:��jO%���
�$T8!j����vm��|'O��З��¹➱z\vsIv`�Ȕ�ʨj��-�^�$-��^���G�Q��{�m���`��T��#�c�֞�㸝�|n�.ߪN�$��O�������JUV���ʼ�t,�����j�g�-����mסּ�NV�����z��:����(�Ι*|1U�x�=�Y��k*����t��M����N��N�DU�hK��� ؞X(刄Rv�!�#B_��c�xR����Ź���o��E5Dg>�?�f���XQ��Q�˔|@�"�աM�����veC�>��m�O$H��#]Y���I=���)_���`���k���*
�:a�>!X���!��W�^���wҒ��l'�<;�vwgI��t�_�?Jh��`��#E:fdx=��6Wu<������ �Ӌ�d2�di���˂�c#h¬c4��� �?<���H���FYo��Vp�N�;�ݷJ\�� �����>�`(���t�3{�>⦊��;;q��F���x�4�Yc����S�$w�.�����d��a*k���|��Q�,��+x��s^��K߫���P^���n�O֮L5m�I�wl?-.ʲ����J8�F�����B.-:2��Ȕ�!����/A�#b��_m%�I�(���$|�PZ[����1�G�{^�#�����o>�3��m�w?'�cx���[�^�:W�k/�`'=���~֥���W�(�gQ���bf�v7U�z��M�3����+؍�K�:��4|G�Ct��A�+K��ʨ�{@���Ɩ�[0�5�����E�|yn4M    IEND�B`� master/bootstrap/css/bootstrap-responsive.css                                                       000644  000767  000024  00000053137 12110524611 022540  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /*!
 * Bootstrap Responsive v2.3.0
 *
 * Copyright 2012 Twitter, Inc
 * Licensed under the Apache License v2.0
 * http://www.apache.org/licenses/LICENSE-2.0
 *
 * Designed and built with all the love in the world @twitter by @mdo and @fat.
 */

.clearfix {
  *zoom: 1;
}

.clearfix:before,
.clearfix:after {
  display: table;
  line-height: 0;
  content: "";
}

.clearfix:after {
  clear: both;
}

.hide-text {
  font: 0/0 a;
  color: transparent;
  text-shadow: none;
  background-color: transparent;
  border: 0;
}

.input-block-level {
  display: block;
  width: 100%;
  min-height: 30px;
  -webkit-box-sizing: border-box;
     -moz-box-sizing: border-box;
          box-sizing: border-box;
}

@-ms-viewport {
  width: device-width;
}

.hidden {
  display: none;
  visibility: hidden;
}

.visible-phone {
  display: none !important;
}

.visible-tablet {
  display: none !important;
}

.hidden-desktop {
  display: none !important;
}

.visible-desktop {
  display: inherit !important;
}

@media (min-width: 768px) and (max-width: 979px) {
  .hidden-desktop {
    display: inherit !important;
  }
  .visible-desktop {
    display: none !important ;
  }
  .visible-tablet {
    display: inherit !important;
  }
  .hidden-tablet {
    display: none !important;
  }
}

@media (max-width: 767px) {
  .hidden-desktop {
    display: inherit !important;
  }
  .visible-desktop {
    display: none !important;
  }
  .visible-phone {
    display: inherit !important;
  }
  .hidden-phone {
    display: none !important;
  }
}

.visible-print {
  display: none !important;
}

@media print {
  .visible-print {
    display: inherit !important;
  }
  .hidden-print {
    display: none !important;
  }
}

@media (min-width: 1200px) {
  .row {
    margin-left: -30px;
    *zoom: 1;
  }
  .row:before,
  .row:after {
    display: table;
    line-height: 0;
    content: "";
  }
  .row:after {
    clear: both;
  }
  [class*="span"] {
    float: left;
    min-height: 1px;
    margin-left: 30px;
  }
  .container,
  .navbar-static-top .container,
  .navbar-fixed-top .container,
  .navbar-fixed-bottom .container {
    width: 1170px;
  }
  .span12 {
    width: 1170px;
  }
  .span11 {
    width: 1070px;
  }
  .span10 {
    width: 970px;
  }
  .span9 {
    width: 870px;
  }
  .span8 {
    width: 770px;
  }
  .span7 {
    width: 670px;
  }
  .span6 {
    width: 570px;
  }
  .span5 {
    width: 470px;
  }
  .span4 {
    width: 370px;
  }
  .span3 {
    width: 270px;
  }
  .span2 {
    width: 170px;
  }
  .span1 {
    width: 70px;
  }
  .offset12 {
    margin-left: 1230px;
  }
  .offset11 {
    margin-left: 1130px;
  }
  .offset10 {
    margin-left: 1030px;
  }
  .offset9 {
    margin-left: 930px;
  }
  .offset8 {
    margin-left: 830px;
  }
  .offset7 {
    margin-left: 730px;
  }
  .offset6 {
    margin-left: 630px;
  }
  .offset5 {
    margin-left: 530px;
  }
  .offset4 {
    margin-left: 430px;
  }
  .offset3 {
    margin-left: 330px;
  }
  .offset2 {
    margin-left: 230px;
  }
  .offset1 {
    margin-left: 130px;
  }
  .row-fluid {
    width: 100%;
    *zoom: 1;
  }
  .row-fluid:before,
  .row-fluid:after {
    display: table;
    line-height: 0;
    content: "";
  }
  .row-fluid:after {
    clear: both;
  }
  .row-fluid [class*="span"] {
    display: block;
    float: left;
    width: 100%;
    min-height: 30px;
    margin-left: 2.564102564102564%;
    *margin-left: 2.5109110747408616%;
    -webkit-box-sizing: border-box;
       -moz-box-sizing: border-box;
            box-sizing: border-box;
  }
  .row-fluid [class*="span"]:first-child {
    margin-left: 0;
  }
  .row-fluid .controls-row [class*="span"] + [class*="span"] {
    margin-left: 2.564102564102564%;
  }
  .row-fluid .span12 {
    width: 100%;
    *width: 99.94680851063829%;
  }
  .row-fluid .span11 {
    width: 91.45299145299145%;
    *width: 91.39979996362975%;
  }
  .row-fluid .span10 {
    width: 82.90598290598291%;
    *width: 82.8527914166212%;
  }
  .row-fluid .span9 {
    width: 74.35897435897436%;
    *width: 74.30578286961266%;
  }
  .row-fluid .span8 {
    width: 65.81196581196582%;
    *width: 65.75877432260411%;
  }
  .row-fluid .span7 {
    width: 57.26495726495726%;
    *width: 57.21176577559556%;
  }
  .row-fluid .span6 {
    width: 48.717948717948715%;
    *width: 48.664757228587014%;
  }
  .row-fluid .span5 {
    width: 40.17094017094017%;
    *width: 40.11774868157847%;
  }
  .row-fluid .span4 {
    width: 31.623931623931625%;
    *width: 31.570740134569924%;
  }
  .row-fluid .span3 {
    width: 23.076923076923077%;
    *width: 23.023731587561375%;
  }
  .row-fluid .span2 {
    width: 14.52991452991453%;
    *width: 14.476723040552828%;
  }
  .row-fluid .span1 {
    width: 5.982905982905983%;
    *width: 5.929714493544281%;
  }
  .row-fluid .offset12 {
    margin-left: 105.12820512820512%;
    *margin-left: 105.02182214948171%;
  }
  .row-fluid .offset12:first-child {
    margin-left: 102.56410256410257%;
    *margin-left: 102.45771958537915%;
  }
  .row-fluid .offset11 {
    margin-left: 96.58119658119658%;
    *margin-left: 96.47481360247316%;
  }
  .row-fluid .offset11:first-child {
    margin-left: 94.01709401709402%;
    *margin-left: 93.91071103837061%;
  }
  .row-fluid .offset10 {
    margin-left: 88.03418803418803%;
    *margin-left: 87.92780505546462%;
  }
  .row-fluid .offset10:first-child {
    margin-left: 85.47008547008548%;
    *margin-left: 85.36370249136206%;
  }
  .row-fluid .offset9 {
    margin-left: 79.48717948717949%;
    *margin-left: 79.38079650845607%;
  }
  .row-fluid .offset9:first-child {
    margin-left: 76.92307692307693%;
    *margin-left: 76.81669394435352%;
  }
  .row-fluid .offset8 {
    margin-left: 70.94017094017094%;
    *margin-left: 70.83378796144753%;
  }
  .row-fluid .offset8:first-child {
    margin-left: 68.37606837606839%;
    *margin-left: 68.26968539734497%;
  }
  .row-fluid .offset7 {
    margin-left: 62.393162393162385%;
    *margin-left: 62.28677941443899%;
  }
  .row-fluid .offset7:first-child {
    margin-left: 59.82905982905982%;
    *margin-left: 59.72267685033642%;
  }
  .row-fluid .offset6 {
    margin-left: 53.84615384615384%;
    *margin-left: 53.739770867430444%;
  }
  .row-fluid .offset6:first-child {
    margin-left: 51.28205128205128%;
    *margin-left: 51.175668303327875%;
  }
  .row-fluid .offset5 {
    margin-left: 45.299145299145295%;
    *margin-left: 45.1927623204219%;
  }
  .row-fluid .offset5:first-child {
    margin-left: 42.73504273504273%;
    *margin-left: 42.62865975631933%;
  }
  .row-fluid .offset4 {
    margin-left: 36.75213675213675%;
    *margin-left: 36.645753773413354%;
  }
  .row-fluid .offset4:first-child {
    margin-left: 34.18803418803419%;
    *margin-left: 34.081651209310785%;
  }
  .row-fluid .offset3 {
    margin-left: 28.205128205128204%;
    *margin-left: 28.0987452264048%;
  }
  .row-fluid .offset3:first-child {
    margin-left: 25.641025641025642%;
    *margin-left: 25.53464266230224%;
  }
  .row-fluid .offset2 {
    margin-left: 19.65811965811966%;
    *margin-left: 19.551736679396257%;
  }
  .row-fluid .offset2:first-child {
    margin-left: 17.094017094017094%;
    *margin-left: 16.98763411529369%;
  }
  .row-fluid .offset1 {
    margin-left: 11.11111111111111%;
    *margin-left: 11.004728132387708%;
  }
  .row-fluid .offset1:first-child {
    margin-left: 8.547008547008547%;
    *margin-left: 8.440625568285142%;
  }
  input,
  textarea,
  .uneditable-input {
    margin-left: 0;
  }
  .controls-row [class*="span"] + [class*="span"] {
    margin-left: 30px;
  }
  input.span12,
  textarea.span12,
  .uneditable-input.span12 {
    width: 1156px;
  }
  input.span11,
  textarea.span11,
  .uneditable-input.span11 {
    width: 1056px;
  }
  input.span10,
  textarea.span10,
  .uneditable-input.span10 {
    width: 956px;
  }
  input.span9,
  textarea.span9,
  .uneditable-input.span9 {
    width: 856px;
  }
  input.span8,
  textarea.span8,
  .uneditable-input.span8 {
    width: 756px;
  }
  input.span7,
  textarea.span7,
  .uneditable-input.span7 {
    width: 656px;
  }
  input.span6,
  textarea.span6,
  .uneditable-input.span6 {
    width: 556px;
  }
  input.span5,
  textarea.span5,
  .uneditable-input.span5 {
    width: 456px;
  }
  input.span4,
  textarea.span4,
  .uneditable-input.span4 {
    width: 356px;
  }
  input.span3,
  textarea.span3,
  .uneditable-input.span3 {
    width: 256px;
  }
  input.span2,
  textarea.span2,
  .uneditable-input.span2 {
    width: 156px;
  }
  input.span1,
  textarea.span1,
  .uneditable-input.span1 {
    width: 56px;
  }
  .thumbnails {
    margin-left: -30px;
  }
  .thumbnails > li {
    margin-left: 30px;
  }
  .row-fluid .thumbnails {
    margin-left: 0;
  }
}

@media (min-width: 768px) and (max-width: 979px) {
  .row {
    margin-left: -20px;
    *zoom: 1;
  }
  .row:before,
  .row:after {
    display: table;
    line-height: 0;
    content: "";
  }
  .row:after {
    clear: both;
  }
  [class*="span"] {
    float: left;
    min-height: 1px;
    margin-left: 20px;
  }
  .container,
  .navbar-static-top .container,
  .navbar-fixed-top .container,
  .navbar-fixed-bottom .container {
    width: 724px;
  }
  .span12 {
    width: 724px;
  }
  .span11 {
    width: 662px;
  }
  .span10 {
    width: 600px;
  }
  .span9 {
    width: 538px;
  }
  .span8 {
    width: 476px;
  }
  .span7 {
    width: 414px;
  }
  .span6 {
    width: 352px;
  }
  .span5 {
    width: 290px;
  }
  .span4 {
    width: 228px;
  }
  .span3 {
    width: 166px;
  }
  .span2 {
    width: 104px;
  }
  .span1 {
    width: 42px;
  }
  .offset12 {
    margin-left: 764px;
  }
  .offset11 {
    margin-left: 702px;
  }
  .offset10 {
    margin-left: 640px;
  }
  .offset9 {
    margin-left: 578px;
  }
  .offset8 {
    margin-left: 516px;
  }
  .offset7 {
    margin-left: 454px;
  }
  .offset6 {
    margin-left: 392px;
  }
  .offset5 {
    margin-left: 330px;
  }
  .offset4 {
    margin-left: 268px;
  }
  .offset3 {
    margin-left: 206px;
  }
  .offset2 {
    margin-left: 144px;
  }
  .offset1 {
    margin-left: 82px;
  }
  .row-fluid {
    width: 100%;
    *zoom: 1;
  }
  .row-fluid:before,
  .row-fluid:after {
    display: table;
    line-height: 0;
    content: "";
  }
  .row-fluid:after {
    clear: both;
  }
  .row-fluid [class*="span"] {
    display: block;
    float: left;
    width: 100%;
    min-height: 30px;
    margin-left: 2.7624309392265194%;
    *margin-left: 2.709239449864817%;
    -webkit-box-sizing: border-box;
       -moz-box-sizing: border-box;
            box-sizing: border-box;
  }
  .row-fluid [class*="span"]:first-child {
    margin-left: 0;
  }
  .row-fluid .controls-row [class*="span"] + [class*="span"] {
    margin-left: 2.7624309392265194%;
  }
  .row-fluid .span12 {
    width: 100%;
    *width: 99.94680851063829%;
  }
  .row-fluid .span11 {
    width: 91.43646408839778%;
    *width: 91.38327259903608%;
  }
  .row-fluid .span10 {
    width: 82.87292817679558%;
    *width: 82.81973668743387%;
  }
  .row-fluid .span9 {
    width: 74.30939226519337%;
    *width: 74.25620077583166%;
  }
  .row-fluid .span8 {
    width: 65.74585635359117%;
    *width: 65.69266486422946%;
  }
  .row-fluid .span7 {
    width: 57.18232044198895%;
    *width: 57.12912895262725%;
  }
  .row-fluid .span6 {
    width: 48.61878453038674%;
    *width: 48.56559304102504%;
  }
  .row-fluid .span5 {
    width: 40.05524861878453%;
    *width: 40.00205712942283%;
  }
  .row-fluid .span4 {
    width: 31.491712707182323%;
    *width: 31.43852121782062%;
  }
  .row-fluid .span3 {
    width: 22.92817679558011%;
    *width: 22.87498530621841%;
  }
  .row-fluid .span2 {
    width: 14.3646408839779%;
    *width: 14.311449394616199%;
  }
  .row-fluid .span1 {
    width: 5.801104972375691%;
    *width: 5.747913483013988%;
  }
  .row-fluid .offset12 {
    margin-left: 105.52486187845304%;
    *margin-left: 105.41847889972962%;
  }
  .row-fluid .offset12:first-child {
    margin-left: 102.76243093922652%;
    *margin-left: 102.6560479605031%;
  }
  .row-fluid .offset11 {
    margin-left: 96.96132596685082%;
    *margin-left: 96.8549429881274%;
  }
  .row-fluid .offset11:first-child {
    margin-left: 94.1988950276243%;
    *margin-left: 94.09251204890089%;
  }
  .row-fluid .offset10 {
    margin-left: 88.39779005524862%;
    *margin-left: 88.2914070765252%;
  }
  .row-fluid .offset10:first-child {
    margin-left: 85.6353591160221%;
    *margin-left: 85.52897613729868%;
  }
  .row-fluid .offset9 {
    margin-left: 79.8342541436464%;
    *margin-left: 79.72787116492299%;
  }
  .row-fluid .offset9:first-child {
    margin-left: 77.07182320441989%;
    *margin-left: 76.96544022569647%;
  }
  .row-fluid .offset8 {
    margin-left: 71.2707182320442%;
    *margin-left: 71.16433525332079%;
  }
  .row-fluid .offset8:first-child {
    margin-left: 68.50828729281768%;
    *margin-left: 68.40190431409427%;
  }
  .row-fluid .offset7 {
    margin-left: 62.70718232044199%;
    *margin-left: 62.600799341718584%;
  }
  .row-fluid .offset7:first-child {
    margin-left: 59.94475138121547%;
    *margin-left: 59.838368402492065%;
  }
  .row-fluid .offset6 {
    margin-left: 54.14364640883978%;
    *margin-left: 54.037263430116376%;
  }
  .row-fluid .offset6:first-child {
    margin-left: 51.38121546961326%;
    *margin-left: 51.27483249088986%;
  }
  .row-fluid .offset5 {
    margin-left: 45.58011049723757%;
    *margin-left: 45.47372751851417%;
  }
  .row-fluid .offset5:first-child {
    margin-left: 42.81767955801105%;
    *margin-left: 42.71129657928765%;
  }
  .row-fluid .offset4 {
    margin-left: 37.01657458563536%;
    *margin-left: 36.91019160691196%;
  }
  .row-fluid .offset4:first-child {
    margin-left: 34.25414364640884%;
    *margin-left: 34.14776066768544%;
  }
  .row-fluid .offset3 {
    margin-left: 28.45303867403315%;
    *margin-left: 28.346655695309746%;
  }
  .row-fluid .offset3:first-child {
    margin-left: 25.69060773480663%;
    *margin-left: 25.584224756083227%;
  }
  .row-fluid .offset2 {
    margin-left: 19.88950276243094%;
    *margin-left: 19.783119783707537%;
  }
  .row-fluid .offset2:first-child {
    margin-left: 17.12707182320442%;
    *margin-left: 17.02068884448102%;
  }
  .row-fluid .offset1 {
    margin-left: 11.32596685082873%;
    *margin-left: 11.219583872105325%;
  }
  .row-fluid .offset1:first-child {
    margin-left: 8.56353591160221%;
    *margin-left: 8.457152932878806%;
  }
  input,
  textarea,
  .uneditable-input {
    margin-left: 0;
  }
  .controls-row [class*="span"] + [class*="span"] {
    margin-left: 20px;
  }
  input.span12,
  textarea.span12,
  .uneditable-input.span12 {
    width: 710px;
  }
  input.span11,
  textarea.span11,
  .uneditable-input.span11 {
    width: 648px;
  }
  input.span10,
  textarea.span10,
  .uneditable-input.span10 {
    width: 586px;
  }
  input.span9,
  textarea.span9,
  .uneditable-input.span9 {
    width: 524px;
  }
  input.span8,
  textarea.span8,
  .uneditable-input.span8 {
    width: 462px;
  }
  input.span7,
  textarea.span7,
  .uneditable-input.span7 {
    width: 400px;
  }
  input.span6,
  textarea.span6,
  .uneditable-input.span6 {
    width: 338px;
  }
  input.span5,
  textarea.span5,
  .uneditable-input.span5 {
    width: 276px;
  }
  input.span4,
  textarea.span4,
  .uneditable-input.span4 {
    width: 214px;
  }
  input.span3,
  textarea.span3,
  .uneditable-input.span3 {
    width: 152px;
  }
  input.span2,
  textarea.span2,
  .uneditable-input.span2 {
    width: 90px;
  }
  input.span1,
  textarea.span1,
  .uneditable-input.span1 {
    width: 28px;
  }
}

@media (max-width: 767px) {
  body {
    padding-right: 20px;
    padding-left: 20px;
  }
  .navbar-fixed-top,
  .navbar-fixed-bottom,
  .navbar-static-top {
    margin-right: -20px;
    margin-left: -20px;
  }
  .container-fluid {
    padding: 0;
  }
  .dl-horizontal dt {
    float: none;
    width: auto;
    clear: none;
    text-align: left;
  }
  .dl-horizontal dd {
    margin-left: 0;
  }
  .container {
    width: auto;
  }
  .row-fluid {
    width: 100%;
  }
  .row,
  .thumbnails {
    margin-left: 0;
  }
  .thumbnails > li {
    float: none;
    margin-left: 0;
  }
  [class*="span"],
  .uneditable-input[class*="span"],
  .row-fluid [class*="span"] {
    display: block;
    float: none;
    width: 100%;
    margin-left: 0;
    -webkit-box-sizing: border-box;
       -moz-box-sizing: border-box;
            box-sizing: border-box;
  }
  .span12,
  .row-fluid .span12 {
    width: 100%;
    -webkit-box-sizing: border-box;
       -moz-box-sizing: border-box;
            box-sizing: border-box;
  }
  .row-fluid [class*="offset"]:first-child {
    margin-left: 0;
  }
  .input-large,
  .input-xlarge,
  .input-xxlarge,
  input[class*="span"],
  select[class*="span"],
  textarea[class*="span"],
  .uneditable-input {
    display: block;
    width: 100%;
    min-height: 30px;
    -webkit-box-sizing: border-box;
       -moz-box-sizing: border-box;
            box-sizing: border-box;
  }
  .input-prepend input,
  .input-append input,
  .input-prepend input[class*="span"],
  .input-append input[class*="span"] {
    display: inline-block;
    width: auto;
  }
  .controls-row [class*="span"] + [class*="span"] {
    margin-left: 0;
  }
  .modal {
    position: fixed;
    top: 20px;
    right: 20px;
    left: 20px;
    width: auto;
    margin: 0;
  }
  .modal.fade {
    top: -100px;
  }
  .modal.fade.in {
    top: 20px;
  }
}

@media (max-width: 480px) {
  .nav-collapse {
    -webkit-transform: translate3d(0, 0, 0);
  }
  .page-header h1 small {
    display: block;
    line-height: 20px;
  }
  input[type="checkbox"],
  input[type="radio"] {
    border: 1px solid #ccc;
  }
  .form-horizontal .control-label {
    float: none;
    width: auto;
    padding-top: 0;
    text-align: left;
  }
  .form-horizontal .controls {
    margin-left: 0;
  }
  .form-horizontal .control-list {
    padding-top: 0;
  }
  .form-horizontal .form-actions {
    padding-right: 10px;
    padding-left: 10px;
  }
  .media .pull-left,
  .media .pull-right {
    display: block;
    float: none;
    margin-bottom: 10px;
  }
  .media-object {
    margin-right: 0;
    margin-left: 0;
  }
  .modal {
    top: 10px;
    right: 10px;
    left: 10px;
  }
  .modal-header .close {
    padding: 10px;
    margin: -10px;
  }
  .carousel-caption {
    position: static;
  }
}

@media (max-width: 979px) {
  body {
    padding-top: 0;
  }
  .navbar-fixed-top,
  .navbar-fixed-bottom {
    position: static;
  }
  .navbar-fixed-top {
    margin-bottom: 20px;
  }
  .navbar-fixed-bottom {
    margin-top: 20px;
  }
  .navbar-fixed-top .navbar-inner,
  .navbar-fixed-bottom .navbar-inner {
    padding: 5px;
  }
  .navbar .container {
    width: auto;
    padding: 0;
  }
  .navbar .brand {
    padding-right: 10px;
    padding-left: 10px;
    margin: 0 0 0 -5px;
  }
  .nav-collapse {
    clear: both;
  }
  .nav-collapse .nav {
    float: none;
    margin: 0 0 10px;
  }
  .nav-collapse .nav > li {
    float: none;
  }
  .nav-collapse .nav > li > a {
    margin-bottom: 2px;
  }
  .nav-collapse .nav > .divider-vertical {
    display: none;
  }
  .nav-collapse .nav .nav-header {
    color: #777777;
    text-shadow: none;
  }
  .nav-collapse .nav > li > a,
  .nav-collapse .dropdown-menu a {
    padding: 9px 15px;
    font-weight: bold;
    color: #777777;
    -webkit-border-radius: 3px;
       -moz-border-radius: 3px;
            border-radius: 3px;
  }
  .nav-collapse .btn {
    padding: 4px 10px 4px;
    font-weight: normal;
    -webkit-border-radius: 4px;
       -moz-border-radius: 4px;
            border-radius: 4px;
  }
  .nav-collapse .dropdown-menu li + li a {
    margin-bottom: 2px;
  }
  .nav-collapse .nav > li > a:hover,
  .nav-collapse .nav > li > a:focus,
  .nav-collapse .dropdown-menu a:hover,
  .nav-collapse .dropdown-menu a:focus {
    background-color: #f2f2f2;
  }
  .navbar-inverse .nav-collapse .nav > li > a,
  .navbar-inverse .nav-collapse .dropdown-menu a {
    color: #999999;
  }
  .navbar-inverse .nav-collapse .nav > li > a:hover,
  .navbar-inverse .nav-collapse .nav > li > a:focus,
  .navbar-inverse .nav-collapse .dropdown-menu a:hover,
  .navbar-inverse .nav-collapse .dropdown-menu a:focus {
    background-color: #111111;
  }
  .nav-collapse.in .btn-group {
    padding: 0;
    margin-top: 5px;
  }
  .nav-collapse .dropdown-menu {
    position: static;
    top: auto;
    left: auto;
    display: none;
    float: none;
    max-width: none;
    padding: 0;
    margin: 0 15px;
    background-color: transparent;
    border: none;
    -webkit-border-radius: 0;
       -moz-border-radius: 0;
            border-radius: 0;
    -webkit-box-shadow: none;
       -moz-box-shadow: none;
            box-shadow: none;
  }
  .nav-collapse .open > .dropdown-menu {
    display: block;
  }
  .nav-collapse .dropdown-menu:before,
  .nav-collapse .dropdown-menu:after {
    display: none;
  }
  .nav-collapse .dropdown-menu .divider {
    display: none;
  }
  .nav-collapse .nav > li > .dropdown-menu:before,
  .nav-collapse .nav > li > .dropdown-menu:after {
    display: none;
  }
  .nav-collapse .navbar-form,
  .nav-collapse .navbar-search {
    float: none;
    padding: 10px 15px;
    margin: 10px 0;
    border-top: 1px solid #f2f2f2;
    border-bottom: 1px solid #f2f2f2;
    -webkit-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
       -moz-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
            box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  }
  .navbar-inverse .nav-collapse .navbar-form,
  .navbar-inverse .nav-collapse .navbar-search {
    border-top-color: #111111;
    border-bottom-color: #111111;
  }
  .navbar .nav-collapse .nav.pull-right {
    float: none;
    margin-left: 0;
  }
  .nav-collapse,
  .nav-collapse.collapse {
    height: 0;
    overflow: hidden;
  }
  .navbar .btn-navbar {
    display: block;
  }
  .navbar-static .navbar-inner {
    padding-right: 10px;
    padding-left: 10px;
  }
}

@media (min-width: 980px) {
  .nav-collapse.collapse {
    height: auto !important;
    overflow: visible !important;
  }
}
                                                                                                                                                                                                                                                                                                                                                                                                                                 master/bootstrap/css/bootstrap-responsive.min.css                                                   000644  000767  000024  00000040721 12110524611 023315  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /*!
 * Bootstrap Responsive v2.3.0
 *
 * Copyright 2012 Twitter, Inc
 * Licensed under the Apache License v2.0
 * http://www.apache.org/licenses/LICENSE-2.0
 *
 * Designed and built with all the love in the world @twitter by @mdo and @fat.
 */.clearfix{*zoom:1}.clearfix:before,.clearfix:after{display:table;line-height:0;content:""}.clearfix:after{clear:both}.hide-text{font:0/0 a;color:transparent;text-shadow:none;background-color:transparent;border:0}.input-block-level{display:block;width:100%;min-height:30px;-webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box}@-ms-viewport{width:device-width}.hidden{display:none;visibility:hidden}.visible-phone{display:none!important}.visible-tablet{display:none!important}.hidden-desktop{display:none!important}.visible-desktop{display:inherit!important}@media(min-width:768px) and (max-width:979px){.hidden-desktop{display:inherit!important}.visible-desktop{display:none!important}.visible-tablet{display:inherit!important}.hidden-tablet{display:none!important}}@media(max-width:767px){.hidden-desktop{display:inherit!important}.visible-desktop{display:none!important}.visible-phone{display:inherit!important}.hidden-phone{display:none!important}}.visible-print{display:none!important}@media print{.visible-print{display:inherit!important}.hidden-print{display:none!important}}@media(min-width:1200px){.row{margin-left:-30px;*zoom:1}.row:before,.row:after{display:table;line-height:0;content:""}.row:after{clear:both}[class*="span"]{float:left;min-height:1px;margin-left:30px}.container,.navbar-static-top .container,.navbar-fixed-top .container,.navbar-fixed-bottom .container{width:1170px}.span12{width:1170px}.span11{width:1070px}.span10{width:970px}.span9{width:870px}.span8{width:770px}.span7{width:670px}.span6{width:570px}.span5{width:470px}.span4{width:370px}.span3{width:270px}.span2{width:170px}.span1{width:70px}.offset12{margin-left:1230px}.offset11{margin-left:1130px}.offset10{margin-left:1030px}.offset9{margin-left:930px}.offset8{margin-left:830px}.offset7{margin-left:730px}.offset6{margin-left:630px}.offset5{margin-left:530px}.offset4{margin-left:430px}.offset3{margin-left:330px}.offset2{margin-left:230px}.offset1{margin-left:130px}.row-fluid{width:100%;*zoom:1}.row-fluid:before,.row-fluid:after{display:table;line-height:0;content:""}.row-fluid:after{clear:both}.row-fluid [class*="span"]{display:block;float:left;width:100%;min-height:30px;margin-left:2.564102564102564%;*margin-left:2.5109110747408616%;-webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box}.row-fluid [class*="span"]:first-child{margin-left:0}.row-fluid .controls-row [class*="span"]+[class*="span"]{margin-left:2.564102564102564%}.row-fluid .span12{width:100%;*width:99.94680851063829%}.row-fluid .span11{width:91.45299145299145%;*width:91.39979996362975%}.row-fluid .span10{width:82.90598290598291%;*width:82.8527914166212%}.row-fluid .span9{width:74.35897435897436%;*width:74.30578286961266%}.row-fluid .span8{width:65.81196581196582%;*width:65.75877432260411%}.row-fluid .span7{width:57.26495726495726%;*width:57.21176577559556%}.row-fluid .span6{width:48.717948717948715%;*width:48.664757228587014%}.row-fluid .span5{width:40.17094017094017%;*width:40.11774868157847%}.row-fluid .span4{width:31.623931623931625%;*width:31.570740134569924%}.row-fluid .span3{width:23.076923076923077%;*width:23.023731587561375%}.row-fluid .span2{width:14.52991452991453%;*width:14.476723040552828%}.row-fluid .span1{width:5.982905982905983%;*width:5.929714493544281%}.row-fluid .offset12{margin-left:105.12820512820512%;*margin-left:105.02182214948171%}.row-fluid .offset12:first-child{margin-left:102.56410256410257%;*margin-left:102.45771958537915%}.row-fluid .offset11{margin-left:96.58119658119658%;*margin-left:96.47481360247316%}.row-fluid .offset11:first-child{margin-left:94.01709401709402%;*margin-left:93.91071103837061%}.row-fluid .offset10{margin-left:88.03418803418803%;*margin-left:87.92780505546462%}.row-fluid .offset10:first-child{margin-left:85.47008547008548%;*margin-left:85.36370249136206%}.row-fluid .offset9{margin-left:79.48717948717949%;*margin-left:79.38079650845607%}.row-fluid .offset9:first-child{margin-left:76.92307692307693%;*margin-left:76.81669394435352%}.row-fluid .offset8{margin-left:70.94017094017094%;*margin-left:70.83378796144753%}.row-fluid .offset8:first-child{margin-left:68.37606837606839%;*margin-left:68.26968539734497%}.row-fluid .offset7{margin-left:62.393162393162385%;*margin-left:62.28677941443899%}.row-fluid .offset7:first-child{margin-left:59.82905982905982%;*margin-left:59.72267685033642%}.row-fluid .offset6{margin-left:53.84615384615384%;*margin-left:53.739770867430444%}.row-fluid .offset6:first-child{margin-left:51.28205128205128%;*margin-left:51.175668303327875%}.row-fluid .offset5{margin-left:45.299145299145295%;*margin-left:45.1927623204219%}.row-fluid .offset5:first-child{margin-left:42.73504273504273%;*margin-left:42.62865975631933%}.row-fluid .offset4{margin-left:36.75213675213675%;*margin-left:36.645753773413354%}.row-fluid .offset4:first-child{margin-left:34.18803418803419%;*margin-left:34.081651209310785%}.row-fluid .offset3{margin-left:28.205128205128204%;*margin-left:28.0987452264048%}.row-fluid .offset3:first-child{margin-left:25.641025641025642%;*margin-left:25.53464266230224%}.row-fluid .offset2{margin-left:19.65811965811966%;*margin-left:19.551736679396257%}.row-fluid .offset2:first-child{margin-left:17.094017094017094%;*margin-left:16.98763411529369%}.row-fluid .offset1{margin-left:11.11111111111111%;*margin-left:11.004728132387708%}.row-fluid .offset1:first-child{margin-left:8.547008547008547%;*margin-left:8.440625568285142%}input,textarea,.uneditable-input{margin-left:0}.controls-row [class*="span"]+[class*="span"]{margin-left:30px}input.span12,textarea.span12,.uneditable-input.span12{width:1156px}input.span11,textarea.span11,.uneditable-input.span11{width:1056px}input.span10,textarea.span10,.uneditable-input.span10{width:956px}input.span9,textarea.span9,.uneditable-input.span9{width:856px}input.span8,textarea.span8,.uneditable-input.span8{width:756px}input.span7,textarea.span7,.uneditable-input.span7{width:656px}input.span6,textarea.span6,.uneditable-input.span6{width:556px}input.span5,textarea.span5,.uneditable-input.span5{width:456px}input.span4,textarea.span4,.uneditable-input.span4{width:356px}input.span3,textarea.span3,.uneditable-input.span3{width:256px}input.span2,textarea.span2,.uneditable-input.span2{width:156px}input.span1,textarea.span1,.uneditable-input.span1{width:56px}.thumbnails{margin-left:-30px}.thumbnails>li{margin-left:30px}.row-fluid .thumbnails{margin-left:0}}@media(min-width:768px) and (max-width:979px){.row{margin-left:-20px;*zoom:1}.row:before,.row:after{display:table;line-height:0;content:""}.row:after{clear:both}[class*="span"]{float:left;min-height:1px;margin-left:20px}.container,.navbar-static-top .container,.navbar-fixed-top .container,.navbar-fixed-bottom .container{width:724px}.span12{width:724px}.span11{width:662px}.span10{width:600px}.span9{width:538px}.span8{width:476px}.span7{width:414px}.span6{width:352px}.span5{width:290px}.span4{width:228px}.span3{width:166px}.span2{width:104px}.span1{width:42px}.offset12{margin-left:764px}.offset11{margin-left:702px}.offset10{margin-left:640px}.offset9{margin-left:578px}.offset8{margin-left:516px}.offset7{margin-left:454px}.offset6{margin-left:392px}.offset5{margin-left:330px}.offset4{margin-left:268px}.offset3{margin-left:206px}.offset2{margin-left:144px}.offset1{margin-left:82px}.row-fluid{width:100%;*zoom:1}.row-fluid:before,.row-fluid:after{display:table;line-height:0;content:""}.row-fluid:after{clear:both}.row-fluid [class*="span"]{display:block;float:left;width:100%;min-height:30px;margin-left:2.7624309392265194%;*margin-left:2.709239449864817%;-webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box}.row-fluid [class*="span"]:first-child{margin-left:0}.row-fluid .controls-row [class*="span"]+[class*="span"]{margin-left:2.7624309392265194%}.row-fluid .span12{width:100%;*width:99.94680851063829%}.row-fluid .span11{width:91.43646408839778%;*width:91.38327259903608%}.row-fluid .span10{width:82.87292817679558%;*width:82.81973668743387%}.row-fluid .span9{width:74.30939226519337%;*width:74.25620077583166%}.row-fluid .span8{width:65.74585635359117%;*width:65.69266486422946%}.row-fluid .span7{width:57.18232044198895%;*width:57.12912895262725%}.row-fluid .span6{width:48.61878453038674%;*width:48.56559304102504%}.row-fluid .span5{width:40.05524861878453%;*width:40.00205712942283%}.row-fluid .span4{width:31.491712707182323%;*width:31.43852121782062%}.row-fluid .span3{width:22.92817679558011%;*width:22.87498530621841%}.row-fluid .span2{width:14.3646408839779%;*width:14.311449394616199%}.row-fluid .span1{width:5.801104972375691%;*width:5.747913483013988%}.row-fluid .offset12{margin-left:105.52486187845304%;*margin-left:105.41847889972962%}.row-fluid .offset12:first-child{margin-left:102.76243093922652%;*margin-left:102.6560479605031%}.row-fluid .offset11{margin-left:96.96132596685082%;*margin-left:96.8549429881274%}.row-fluid .offset11:first-child{margin-left:94.1988950276243%;*margin-left:94.09251204890089%}.row-fluid .offset10{margin-left:88.39779005524862%;*margin-left:88.2914070765252%}.row-fluid .offset10:first-child{margin-left:85.6353591160221%;*margin-left:85.52897613729868%}.row-fluid .offset9{margin-left:79.8342541436464%;*margin-left:79.72787116492299%}.row-fluid .offset9:first-child{margin-left:77.07182320441989%;*margin-left:76.96544022569647%}.row-fluid .offset8{margin-left:71.2707182320442%;*margin-left:71.16433525332079%}.row-fluid .offset8:first-child{margin-left:68.50828729281768%;*margin-left:68.40190431409427%}.row-fluid .offset7{margin-left:62.70718232044199%;*margin-left:62.600799341718584%}.row-fluid .offset7:first-child{margin-left:59.94475138121547%;*margin-left:59.838368402492065%}.row-fluid .offset6{margin-left:54.14364640883978%;*margin-left:54.037263430116376%}.row-fluid .offset6:first-child{margin-left:51.38121546961326%;*margin-left:51.27483249088986%}.row-fluid .offset5{margin-left:45.58011049723757%;*margin-left:45.47372751851417%}.row-fluid .offset5:first-child{margin-left:42.81767955801105%;*margin-left:42.71129657928765%}.row-fluid .offset4{margin-left:37.01657458563536%;*margin-left:36.91019160691196%}.row-fluid .offset4:first-child{margin-left:34.25414364640884%;*margin-left:34.14776066768544%}.row-fluid .offset3{margin-left:28.45303867403315%;*margin-left:28.346655695309746%}.row-fluid .offset3:first-child{margin-left:25.69060773480663%;*margin-left:25.584224756083227%}.row-fluid .offset2{margin-left:19.88950276243094%;*margin-left:19.783119783707537%}.row-fluid .offset2:first-child{margin-left:17.12707182320442%;*margin-left:17.02068884448102%}.row-fluid .offset1{margin-left:11.32596685082873%;*margin-left:11.219583872105325%}.row-fluid .offset1:first-child{margin-left:8.56353591160221%;*margin-left:8.457152932878806%}input,textarea,.uneditable-input{margin-left:0}.controls-row [class*="span"]+[class*="span"]{margin-left:20px}input.span12,textarea.span12,.uneditable-input.span12{width:710px}input.span11,textarea.span11,.uneditable-input.span11{width:648px}input.span10,textarea.span10,.uneditable-input.span10{width:586px}input.span9,textarea.span9,.uneditable-input.span9{width:524px}input.span8,textarea.span8,.uneditable-input.span8{width:462px}input.span7,textarea.span7,.uneditable-input.span7{width:400px}input.span6,textarea.span6,.uneditable-input.span6{width:338px}input.span5,textarea.span5,.uneditable-input.span5{width:276px}input.span4,textarea.span4,.uneditable-input.span4{width:214px}input.span3,textarea.span3,.uneditable-input.span3{width:152px}input.span2,textarea.span2,.uneditable-input.span2{width:90px}input.span1,textarea.span1,.uneditable-input.span1{width:28px}}@media(max-width:767px){body{padding-right:20px;padding-left:20px}.navbar-fixed-top,.navbar-fixed-bottom,.navbar-static-top{margin-right:-20px;margin-left:-20px}.container-fluid{padding:0}.dl-horizontal dt{float:none;width:auto;clear:none;text-align:left}.dl-horizontal dd{margin-left:0}.container{width:auto}.row-fluid{width:100%}.row,.thumbnails{margin-left:0}.thumbnails>li{float:none;margin-left:0}[class*="span"],.uneditable-input[class*="span"],.row-fluid [class*="span"]{display:block;float:none;width:100%;margin-left:0;-webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box}.span12,.row-fluid .span12{width:100%;-webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box}.row-fluid [class*="offset"]:first-child{margin-left:0}.input-large,.input-xlarge,.input-xxlarge,input[class*="span"],select[class*="span"],textarea[class*="span"],.uneditable-input{display:block;width:100%;min-height:30px;-webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box}.input-prepend input,.input-append input,.input-prepend input[class*="span"],.input-append input[class*="span"]{display:inline-block;width:auto}.controls-row [class*="span"]+[class*="span"]{margin-left:0}.modal{position:fixed;top:20px;right:20px;left:20px;width:auto;margin:0}.modal.fade{top:-100px}.modal.fade.in{top:20px}}@media(max-width:480px){.nav-collapse{-webkit-transform:translate3d(0,0,0)}.page-header h1 small{display:block;line-height:20px}input[type="checkbox"],input[type="radio"]{border:1px solid #ccc}.form-horizontal .control-label{float:none;width:auto;padding-top:0;text-align:left}.form-horizontal .controls{margin-left:0}.form-horizontal .control-list{padding-top:0}.form-horizontal .form-actions{padding-right:10px;padding-left:10px}.media .pull-left,.media .pull-right{display:block;float:none;margin-bottom:10px}.media-object{margin-right:0;margin-left:0}.modal{top:10px;right:10px;left:10px}.modal-header .close{padding:10px;margin:-10px}.carousel-caption{position:static}}@media(max-width:979px){body{padding-top:0}.navbar-fixed-top,.navbar-fixed-bottom{position:static}.navbar-fixed-top{margin-bottom:20px}.navbar-fixed-bottom{margin-top:20px}.navbar-fixed-top .navbar-inner,.navbar-fixed-bottom .navbar-inner{padding:5px}.navbar .container{width:auto;padding:0}.navbar .brand{padding-right:10px;padding-left:10px;margin:0 0 0 -5px}.nav-collapse{clear:both}.nav-collapse .nav{float:none;margin:0 0 10px}.nav-collapse .nav>li{float:none}.nav-collapse .nav>li>a{margin-bottom:2px}.nav-collapse .nav>.divider-vertical{display:none}.nav-collapse .nav .nav-header{color:#777;text-shadow:none}.nav-collapse .nav>li>a,.nav-collapse .dropdown-menu a{padding:9px 15px;font-weight:bold;color:#777;-webkit-border-radius:3px;-moz-border-radius:3px;border-radius:3px}.nav-collapse .btn{padding:4px 10px 4px;font-weight:normal;-webkit-border-radius:4px;-moz-border-radius:4px;border-radius:4px}.nav-collapse .dropdown-menu li+li a{margin-bottom:2px}.nav-collapse .nav>li>a:hover,.nav-collapse .nav>li>a:focus,.nav-collapse .dropdown-menu a:hover,.nav-collapse .dropdown-menu a:focus{background-color:#f2f2f2}.navbar-inverse .nav-collapse .nav>li>a,.navbar-inverse .nav-collapse .dropdown-menu a{color:#999}.navbar-inverse .nav-collapse .nav>li>a:hover,.navbar-inverse .nav-collapse .nav>li>a:focus,.navbar-inverse .nav-collapse .dropdown-menu a:hover,.navbar-inverse .nav-collapse .dropdown-menu a:focus{background-color:#111}.nav-collapse.in .btn-group{padding:0;margin-top:5px}.nav-collapse .dropdown-menu{position:static;top:auto;left:auto;display:none;float:none;max-width:none;padding:0;margin:0 15px;background-color:transparent;border:0;-webkit-border-radius:0;-moz-border-radius:0;border-radius:0;-webkit-box-shadow:none;-moz-box-shadow:none;box-shadow:none}.nav-collapse .open>.dropdown-menu{display:block}.nav-collapse .dropdown-menu:before,.nav-collapse .dropdown-menu:after{display:none}.nav-collapse .dropdown-menu .divider{display:none}.nav-collapse .nav>li>.dropdown-menu:before,.nav-collapse .nav>li>.dropdown-menu:after{display:none}.nav-collapse .navbar-form,.nav-collapse .navbar-search{float:none;padding:10px 15px;margin:10px 0;border-top:1px solid #f2f2f2;border-bottom:1px solid #f2f2f2;-webkit-box-shadow:inset 0 1px 0 rgba(255,255,255,0.1),0 1px 0 rgba(255,255,255,0.1);-moz-box-shadow:inset 0 1px 0 rgba(255,255,255,0.1),0 1px 0 rgba(255,255,255,0.1);box-shadow:inset 0 1px 0 rgba(255,255,255,0.1),0 1px 0 rgba(255,255,255,0.1)}.navbar-inverse .nav-collapse .navbar-form,.navbar-inverse .nav-collapse .navbar-search{border-top-color:#111;border-bottom-color:#111}.navbar .nav-collapse .nav.pull-right{float:none;margin-left:0}.nav-collapse,.nav-collapse.collapse{height:0;overflow:hidden}.navbar .btn-navbar{display:block}.navbar-static .navbar-inner{padding-right:10px;padding-left:10px}}@media(min-width:980px){.nav-collapse.collapse{height:auto!important;overflow:visible!important}}
                                               master/bootstrap/css/bootstrap.css                                                                  000644  000767  000024  00000370417 12110524611 020350  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /*!
 * Bootstrap v2.3.0
 *
 * Copyright 2012 Twitter, Inc
 * Licensed under the Apache License v2.0
 * http://www.apache.org/licenses/LICENSE-2.0
 *
 * Designed and built with all the love in the world @twitter by @mdo and @fat.
 */

.clearfix {
  *zoom: 1;
}

.clearfix:before,
.clearfix:after {
  display: table;
  line-height: 0;
  content: "";
}

.clearfix:after {
  clear: both;
}

.hide-text {
  font: 0/0 a;
  color: transparent;
  text-shadow: none;
  background-color: transparent;
  border: 0;
}

.input-block-level {
  display: block;
  width: 100%;
  min-height: 30px;
  -webkit-box-sizing: border-box;
     -moz-box-sizing: border-box;
          box-sizing: border-box;
}

article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
nav,
section {
  display: block;
}

audio,
canvas,
video {
  display: inline-block;
  *display: inline;
  *zoom: 1;
}

audio:not([controls]) {
  display: none;
}

html {
  font-size: 100%;
  -webkit-text-size-adjust: 100%;
      -ms-text-size-adjust: 100%;
}

a:focus {
  outline: thin dotted #333;
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}

a:hover,
a:active {
  outline: 0;
}

sub,
sup {
  position: relative;
  font-size: 75%;
  line-height: 0;
  vertical-align: baseline;
}

sup {
  top: -0.5em;
}

sub {
  bottom: -0.25em;
}

img {
  width: auto\9;
  height: auto;
  max-width: 100%;
  vertical-align: middle;
  border: 0;
  -ms-interpolation-mode: bicubic;
}

#map_canvas img,
.google-maps img {
  max-width: none;
}

button,
input,
select,
textarea {
  margin: 0;
  font-size: 100%;
  vertical-align: middle;
}

button,
input {
  *overflow: visible;
  line-height: normal;
}

button::-moz-focus-inner,
input::-moz-focus-inner {
  padding: 0;
  border: 0;
}

button,
html input[type="button"],
input[type="reset"],
input[type="submit"] {
  cursor: pointer;
  -webkit-appearance: button;
}

label,
select,
button,
input[type="button"],
input[type="reset"],
input[type="submit"],
input[type="radio"],
input[type="checkbox"] {
  cursor: pointer;
}

input[type="search"] {
  -webkit-box-sizing: content-box;
     -moz-box-sizing: content-box;
          box-sizing: content-box;
  -webkit-appearance: textfield;
}

input[type="search"]::-webkit-search-decoration,
input[type="search"]::-webkit-search-cancel-button {
  -webkit-appearance: none;
}

textarea {
  overflow: auto;
  vertical-align: top;
}

@media print {
  * {
    color: #000 !important;
    text-shadow: none !important;
    background: transparent !important;
    box-shadow: none !important;
  }
  a,
  a:visited {
    text-decoration: underline;
  }
  a[href]:after {
    content: " (" attr(href) ")";
  }
  abbr[title]:after {
    content: " (" attr(title) ")";
  }
  .ir a:after,
  a[href^="javascript:"]:after,
  a[href^="#"]:after {
    content: "";
  }
  pre,
  blockquote {
    border: 1px solid #999;
    page-break-inside: avoid;
  }
  thead {
    display: table-header-group;
  }
  tr,
  img {
    page-break-inside: avoid;
  }
  img {
    max-width: 100% !important;
  }
  @page  {
    margin: 0.5cm;
  }
  p,
  h2,
  h3 {
    orphans: 3;
    widows: 3;
  }
  h2,
  h3 {
    page-break-after: avoid;
  }
}

body {
  margin: 0;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-size: 14px;
  line-height: 20px;
  color: #333333;
  background-color: #ffffff;
}

a {
  color: #0088cc;
  text-decoration: none;
}

a:hover,
a:focus {
  color: #005580;
  text-decoration: underline;
}

.img-rounded {
  -webkit-border-radius: 6px;
     -moz-border-radius: 6px;
          border-radius: 6px;
}

.img-polaroid {
  padding: 4px;
  background-color: #fff;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.2);
  -webkit-box-shadow: 0 1px 3px rgba(0, 0, 0, 0.1);
     -moz-box-shadow: 0 1px 3px rgba(0, 0, 0, 0.1);
          box-shadow: 0 1px 3px rgba(0, 0, 0, 0.1);
}

.img-circle {
  -webkit-border-radius: 500px;
     -moz-border-radius: 500px;
          border-radius: 500px;
}

.row {
  margin-left: -20px;
  *zoom: 1;
}

.row:before,
.row:after {
  display: table;
  line-height: 0;
  content: "";
}

.row:after {
  clear: both;
}

[class*="span"] {
  float: left;
  min-height: 1px;
  margin-left: 20px;
}

.container,
.navbar-static-top .container,
.navbar-fixed-top .container,
.navbar-fixed-bottom .container {
  width: 940px;
}

.span12 {
  width: 940px;
}

.span11 {
  width: 860px;
}

.span10 {
  width: 780px;
}

.span9 {
  width: 700px;
}

.span8 {
  width: 620px;
}

.span7 {
  width: 540px;
}

.span6 {
  width: 460px;
}

.span5 {
  width: 380px;
}

.span4 {
  width: 300px;
}

.span3 {
  width: 220px;
}

.span2 {
  width: 140px;
}

.span1 {
  width: 60px;
}

.offset12 {
  margin-left: 980px;
}

.offset11 {
  margin-left: 900px;
}

.offset10 {
  margin-left: 820px;
}

.offset9 {
  margin-left: 740px;
}

.offset8 {
  margin-left: 660px;
}

.offset7 {
  margin-left: 580px;
}

.offset6 {
  margin-left: 500px;
}

.offset5 {
  margin-left: 420px;
}

.offset4 {
  margin-left: 340px;
}

.offset3 {
  margin-left: 260px;
}

.offset2 {
  margin-left: 180px;
}

.offset1 {
  margin-left: 100px;
}

.row-fluid {
  width: 100%;
  *zoom: 1;
}

.row-fluid:before,
.row-fluid:after {
  display: table;
  line-height: 0;
  content: "";
}

.row-fluid:after {
  clear: both;
}

.row-fluid [class*="span"] {
  display: block;
  float: left;
  width: 100%;
  min-height: 30px;
  margin-left: 2.127659574468085%;
  *margin-left: 2.074468085106383%;
  -webkit-box-sizing: border-box;
     -moz-box-sizing: border-box;
          box-sizing: border-box;
}

.row-fluid [class*="span"]:first-child {
  margin-left: 0;
}

.row-fluid .controls-row [class*="span"] + [class*="span"] {
  margin-left: 2.127659574468085%;
}

.row-fluid .span12 {
  width: 100%;
  *width: 99.94680851063829%;
}

.row-fluid .span11 {
  width: 91.48936170212765%;
  *width: 91.43617021276594%;
}

.row-fluid .span10 {
  width: 82.97872340425532%;
  *width: 82.92553191489361%;
}

.row-fluid .span9 {
  width: 74.46808510638297%;
  *width: 74.41489361702126%;
}

.row-fluid .span8 {
  width: 65.95744680851064%;
  *width: 65.90425531914893%;
}

.row-fluid .span7 {
  width: 57.44680851063829%;
  *width: 57.39361702127659%;
}

.row-fluid .span6 {
  width: 48.93617021276595%;
  *width: 48.88297872340425%;
}

.row-fluid .span5 {
  width: 40.42553191489362%;
  *width: 40.37234042553192%;
}

.row-fluid .span4 {
  width: 31.914893617021278%;
  *width: 31.861702127659576%;
}

.row-fluid .span3 {
  width: 23.404255319148934%;
  *width: 23.351063829787233%;
}

.row-fluid .span2 {
  width: 14.893617021276595%;
  *width: 14.840425531914894%;
}

.row-fluid .span1 {
  width: 6.382978723404255%;
  *width: 6.329787234042553%;
}

.row-fluid .offset12 {
  margin-left: 104.25531914893617%;
  *margin-left: 104.14893617021275%;
}

.row-fluid .offset12:first-child {
  margin-left: 102.12765957446808%;
  *margin-left: 102.02127659574467%;
}

.row-fluid .offset11 {
  margin-left: 95.74468085106382%;
  *margin-left: 95.6382978723404%;
}

.row-fluid .offset11:first-child {
  margin-left: 93.61702127659574%;
  *margin-left: 93.51063829787232%;
}

.row-fluid .offset10 {
  margin-left: 87.23404255319149%;
  *margin-left: 87.12765957446807%;
}

.row-fluid .offset10:first-child {
  margin-left: 85.1063829787234%;
  *margin-left: 84.99999999999999%;
}

.row-fluid .offset9 {
  margin-left: 78.72340425531914%;
  *margin-left: 78.61702127659572%;
}

.row-fluid .offset9:first-child {
  margin-left: 76.59574468085106%;
  *margin-left: 76.48936170212764%;
}

.row-fluid .offset8 {
  margin-left: 70.2127659574468%;
  *margin-left: 70.10638297872339%;
}

.row-fluid .offset8:first-child {
  margin-left: 68.08510638297872%;
  *margin-left: 67.9787234042553%;
}

.row-fluid .offset7 {
  margin-left: 61.70212765957446%;
  *margin-left: 61.59574468085106%;
}

.row-fluid .offset7:first-child {
  margin-left: 59.574468085106375%;
  *margin-left: 59.46808510638297%;
}

.row-fluid .offset6 {
  margin-left: 53.191489361702125%;
  *margin-left: 53.085106382978715%;
}

.row-fluid .offset6:first-child {
  margin-left: 51.063829787234035%;
  *margin-left: 50.95744680851063%;
}

.row-fluid .offset5 {
  margin-left: 44.68085106382979%;
  *margin-left: 44.57446808510638%;
}

.row-fluid .offset5:first-child {
  margin-left: 42.5531914893617%;
  *margin-left: 42.4468085106383%;
}

.row-fluid .offset4 {
  margin-left: 36.170212765957444%;
  *margin-left: 36.06382978723405%;
}

.row-fluid .offset4:first-child {
  margin-left: 34.04255319148936%;
  *margin-left: 33.93617021276596%;
}

.row-fluid .offset3 {
  margin-left: 27.659574468085104%;
  *margin-left: 27.5531914893617%;
}

.row-fluid .offset3:first-child {
  margin-left: 25.53191489361702%;
  *margin-left: 25.425531914893618%;
}

.row-fluid .offset2 {
  margin-left: 19.148936170212764%;
  *margin-left: 19.04255319148936%;
}

.row-fluid .offset2:first-child {
  margin-left: 17.02127659574468%;
  *margin-left: 16.914893617021278%;
}

.row-fluid .offset1 {
  margin-left: 10.638297872340425%;
  *margin-left: 10.53191489361702%;
}

.row-fluid .offset1:first-child {
  margin-left: 8.51063829787234%;
  *margin-left: 8.404255319148938%;
}

[class*="span"].hide,
.row-fluid [class*="span"].hide {
  display: none;
}

[class*="span"].pull-right,
.row-fluid [class*="span"].pull-right {
  float: right;
}

.container {
  margin-right: auto;
  margin-left: auto;
  *zoom: 1;
}

.container:before,
.container:after {
  display: table;
  line-height: 0;
  content: "";
}

.container:after {
  clear: both;
}

.container-fluid {
  padding-right: 20px;
  padding-left: 20px;
  *zoom: 1;
}

.container-fluid:before,
.container-fluid:after {
  display: table;
  line-height: 0;
  content: "";
}

.container-fluid:after {
  clear: both;
}

p {
  margin: 0 0 10px;
}

.lead {
  margin-bottom: 20px;
  font-size: 21px;
  font-weight: 200;
  line-height: 30px;
}

small {
  font-size: 85%;
}

strong {
  font-weight: bold;
}

em {
  font-style: italic;
}

cite {
  font-style: normal;
}

.muted {
  color: #999999;
}

a.muted:hover,
a.muted:focus {
  color: #808080;
}

.text-warning {
  color: #c09853;
}

a.text-warning:hover,
a.text-warning:focus {
  color: #a47e3c;
}

.text-error {
  color: #b94a48;
}

a.text-error:hover,
a.text-error:focus {
  color: #953b39;
}

.text-info {
  color: #3a87ad;
}

a.text-info:hover,
a.text-info:focus {
  color: #2d6987;
}

.text-success {
  color: #468847;
}

a.text-success:hover,
a.text-success:focus {
  color: #356635;
}

.text-left {
  text-align: left;
}

.text-right {
  text-align: right;
}

.text-center {
  text-align: center;
}

h1,
h2,
h3,
h4,
h5,
h6 {
  margin: 10px 0;
  font-family: inherit;
  font-weight: bold;
  line-height: 20px;
  color: inherit;
  text-rendering: optimizelegibility;
}

h1 small,
h2 small,
h3 small,
h4 small,
h5 small,
h6 small {
  font-weight: normal;
  line-height: 1;
  color: #999999;
}

h1,
h2,
h3 {
  line-height: 40px;
}

h1 {
  font-size: 38.5px;
}

h2 {
  font-size: 31.5px;
}

h3 {
  font-size: 24.5px;
}

h4 {
  font-size: 17.5px;
}

h5 {
  font-size: 14px;
}

h6 {
  font-size: 11.9px;
}

h1 small {
  font-size: 24.5px;
}

h2 small {
  font-size: 17.5px;
}

h3 small {
  font-size: 14px;
}

h4 small {
  font-size: 14px;
}

.page-header {
  padding-bottom: 9px;
  margin: 20px 0 30px;
  border-bottom: 1px solid #eeeeee;
}

ul,
ol {
  padding: 0;
  margin: 0 0 10px 25px;
}

ul ul,
ul ol,
ol ol,
ol ul {
  margin-bottom: 0;
}

li {
  line-height: 20px;
}

ul.unstyled,
ol.unstyled {
  margin-left: 0;
  list-style: none;
}

ul.inline,
ol.inline {
  margin-left: 0;
  list-style: none;
}

ul.inline > li,
ol.inline > li {
  display: inline-block;
  *display: inline;
  padding-right: 5px;
  padding-left: 5px;
  *zoom: 1;
}

dl {
  margin-bottom: 20px;
}

dt,
dd {
  line-height: 20px;
}

dt {
  font-weight: bold;
}

dd {
  margin-left: 10px;
}

.dl-horizontal {
  *zoom: 1;
}

.dl-horizontal:before,
.dl-horizontal:after {
  display: table;
  line-height: 0;
  content: "";
}

.dl-horizontal:after {
  clear: both;
}

.dl-horizontal dt {
  float: left;
  width: 160px;
  overflow: hidden;
  clear: left;
  text-align: right;
  text-overflow: ellipsis;
  white-space: nowrap;
}

.dl-horizontal dd {
  margin-left: 180px;
}

hr {
  margin: 20px 0;
  border: 0;
  border-top: 1px solid #eeeeee;
  border-bottom: 1px solid #ffffff;
}

abbr[title],
abbr[data-original-title] {
  cursor: help;
  border-bottom: 1px dotted #999999;
}

abbr.initialism {
  font-size: 90%;
  text-transform: uppercase;
}

blockquote {
  padding: 0 0 0 15px;
  margin: 0 0 20px;
  border-left: 5px solid #eeeeee;
}

blockquote p {
  margin-bottom: 0;
  font-size: 17.5px;
  font-weight: 300;
  line-height: 1.25;
}

blockquote small {
  display: block;
  line-height: 20px;
  color: #999999;
}

blockquote small:before {
  content: '\2014 \00A0';
}

blockquote.pull-right {
  float: right;
  padding-right: 15px;
  padding-left: 0;
  border-right: 5px solid #eeeeee;
  border-left: 0;
}

blockquote.pull-right p,
blockquote.pull-right small {
  text-align: right;
}

blockquote.pull-right small:before {
  content: '';
}

blockquote.pull-right small:after {
  content: '\00A0 \2014';
}

q:before,
q:after,
blockquote:before,
blockquote:after {
  content: "";
}

address {
  display: block;
  margin-bottom: 20px;
  font-style: normal;
  line-height: 20px;
}

code,
pre {
  padding: 0 3px 2px;
  font-family: Monaco, Menlo, Consolas, "Courier New", monospace;
  font-size: 12px;
  color: #333333;
  -webkit-border-radius: 3px;
     -moz-border-radius: 3px;
          border-radius: 3px;
}

code {
  padding: 2px 4px;
  color: #d14;
  white-space: nowrap;
  background-color: #f7f7f9;
  border: 1px solid #e1e1e8;
}

pre {
  display: block;
  padding: 9.5px;
  margin: 0 0 10px;
  font-size: 13px;
  line-height: 20px;
  word-break: break-all;
  word-wrap: break-word;
  white-space: pre;
  white-space: pre-wrap;
  background-color: #f5f5f5;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.15);
  -webkit-border-radius: 4px;
     -moz-border-radius: 4px;
          border-radius: 4px;
}

pre.prettyprint {
  margin-bottom: 20px;
}

pre code {
  padding: 0;
  color: inherit;
  white-space: pre;
  white-space: pre-wrap;
  background-color: transparent;
  border: 0;
}

.pre-scrollable {
  max-height: 340px;
  overflow-y: scroll;
}

form {
  margin: 0 0 20px;
}

fieldset {
  padding: 0;
  margin: 0;
  border: 0;
}

legend {
  display: block;
  width: 100%;
  padding: 0;
  margin-bottom: 20px;
  font-size: 21px;
  line-height: 40px;
  color: #333333;
  border: 0;
  border-bottom: 1px solid #e5e5e5;
}

legend small {
  font-size: 15px;
  color: #999999;
}

label,
input,
button,
select,
textarea {
  font-size: 14px;
  font-weight: normal;
  line-height: 20px;
}

input,
button,
select,
textarea {
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
}

label {
  display: block;
  margin-bottom: 5px;
}

select,
textarea,
input[type="text"],
input[type="password"],
input[type="datetime"],
input[type="datetime-local"],
input[type="date"],
input[type="month"],
input[type="time"],
input[type="week"],
input[type="number"],
input[type="email"],
input[type="url"],
input[type="search"],
input[type="tel"],
input[type="color"],
.uneditable-input {
  display: inline-block;
  height: 20px;
  padding: 4px 6px;
  margin-bottom: 10px;
  font-size: 14px;
  line-height: 20px;
  color: #555555;
  vertical-align: middle;
  -webkit-border-radius: 4px;
     -moz-border-radius: 4px;
          border-radius: 4px;
}

input,
textarea,
.uneditable-input {
  width: 206px;
}

textarea {
  height: auto;
}

textarea,
input[type="text"],
input[type="password"],
input[type="datetime"],
input[type="datetime-local"],
input[type="date"],
input[type="month"],
input[type="time"],
input[type="week"],
input[type="number"],
input[type="email"],
input[type="url"],
input[type="search"],
input[type="tel"],
input[type="color"],
.uneditable-input {
  background-color: #ffffff;
  border: 1px solid #cccccc;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
     -moz-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
          box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border linear 0.2s, box-shadow linear 0.2s;
     -moz-transition: border linear 0.2s, box-shadow linear 0.2s;
       -o-transition: border linear 0.2s, box-shadow linear 0.2s;
          transition: border linear 0.2s, box-shadow linear 0.2s;
}

textarea:focus,
input[type="text"]:focus,
input[type="password"]:focus,
input[type="datetime"]:focus,
input[type="datetime-local"]:focus,
input[type="date"]:focus,
input[type="month"]:focus,
input[type="time"]:focus,
input[type="week"]:focus,
input[type="number"]:focus,
input[type="email"]:focus,
input[type="url"]:focus,
input[type="search"]:focus,
input[type="tel"]:focus,
input[type="color"]:focus,
.uneditable-input:focus {
  border-color: rgba(82, 168, 236, 0.8);
  outline: 0;
  outline: thin dotted \9;
  /* IE6-9 */

  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 8px rgba(82, 168, 236, 0.6);
     -moz-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 8px rgba(82, 168, 236, 0.6);
          box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 8px rgba(82, 168, 236, 0.6);
}

input[type="radio"],
input[type="checkbox"] {
  margin: 4px 0 0;
  margin-top: 1px \9;
  *margin-top: 0;
  line-height: normal;
}

input[type="file"],
input[type="image"],
input[type="submit"],
input[type="reset"],
input[type="button"],
input[type="radio"],
input[type="checkbox"] {
  width: auto;
}

select,
input[type="file"] {
  height: 30px;
  /* In IE7, the height of the select element cannot be changed by height, only font-size */

  *margin-top: 4px;
  /* For IE7, add top margin to align select with labels */

  line-height: 30px;
}

select {
  width: 220px;
  background-color: #ffffff;
  border: 1px solid #cccccc;
}

select[multiple],
select[size] {
  height: auto;
}

select:focus,
input[type="file"]:focus,
input[type="radio"]:focus,
input[type="checkbox"]:focus {
  outline: thin dotted #333;
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}

.uneditable-input,
.uneditable-textarea {
  color: #999999;
  cursor: not-allowed;
  background-color: #fcfcfc;
  border-color: #cccccc;
  -webkit-box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.025);
     -moz-box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.025);
          box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.025);
}

.uneditable-input {
  overflow: hidden;
  white-space: nowrap;
}

.uneditable-textarea {
  width: auto;
  height: auto;
}

input:-moz-placeholder,
textarea:-moz-placeholder {
  color: #999999;
}

input:-ms-input-placeholder,
textarea:-ms-input-placeholder {
  color: #999999;
}

input::-webkit-input-placeholder,
textarea::-webkit-input-placeholder {
  color: #999999;
}

.radio,
.checkbox {
  min-height: 20px;
  padding-left: 20px;
}

.radio input[type="radio"],
.checkbox input[type="checkbox"] {
  float: left;
  margin-left: -20px;
}

.controls > .radio:first-child,
.controls > .checkbox:first-child {
  padding-top: 5px;
}

.radio.inline,
.checkbox.inline {
  display: inline-block;
  padding-top: 5px;
  margin-bottom: 0;
  vertical-align: middle;
}

.radio.inline + .radio.inline,
.checkbox.inline + .checkbox.inline {
  margin-left: 10px;
}

.input-mini {
  width: 60px;
}

.input-small {
  width: 90px;
}

.input-medium {
  width: 150px;
}

.input-large {
  width: 210px;
}

.input-xlarge {
  width: 270px;
}

.input-xxlarge {
  width: 530px;
}

input[class*="span"],
select[class*="span"],
textarea[class*="span"],
.uneditable-input[class*="span"],
.row-fluid input[class*="span"],
.row-fluid select[class*="span"],
.row-fluid textarea[class*="span"],
.row-fluid .uneditable-input[class*="span"] {
  float: none;
  margin-left: 0;
}

.input-append input[class*="span"],
.input-append .uneditable-input[class*="span"],
.input-prepend input[class*="span"],
.input-prepend .uneditable-input[class*="span"],
.row-fluid input[class*="span"],
.row-fluid select[class*="span"],
.row-fluid textarea[class*="span"],
.row-fluid .uneditable-input[class*="span"],
.row-fluid .input-prepend [class*="span"],
.row-fluid .input-append [class*="span"] {
  display: inline-block;
}

input,
textarea,
.uneditable-input {
  margin-left: 0;
}

.controls-row [class*="span"] + [class*="span"] {
  margin-left: 20px;
}

input.span12,
textarea.span12,
.uneditable-input.span12 {
  width: 926px;
}

input.span11,
textarea.span11,
.uneditable-input.span11 {
  width: 846px;
}

input.span10,
textarea.span10,
.uneditable-input.span10 {
  width: 766px;
}

input.span9,
textarea.span9,
.uneditable-input.span9 {
  width: 686px;
}

input.span8,
textarea.span8,
.uneditable-input.span8 {
  width: 606px;
}

input.span7,
textarea.span7,
.uneditable-input.span7 {
  width: 526px;
}

input.span6,
textarea.span6,
.uneditable-input.span6 {
  width: 446px;
}

input.span5,
textarea.span5,
.uneditable-input.span5 {
  width: 366px;
}

input.span4,
textarea.span4,
.uneditable-input.span4 {
  width: 286px;
}

input.span3,
textarea.span3,
.uneditable-input.span3 {
  width: 206px;
}

input.span2,
textarea.span2,
.uneditable-input.span2 {
  width: 126px;
}

input.span1,
textarea.span1,
.uneditable-input.span1 {
  width: 46px;
}

.controls-row {
  *zoom: 1;
}

.controls-row:before,
.controls-row:after {
  display: table;
  line-height: 0;
  content: "";
}

.controls-row:after {
  clear: both;
}

.controls-row [class*="span"],
.row-fluid .controls-row [class*="span"] {
  float: left;
}

.controls-row .checkbox[class*="span"],
.controls-row .radio[class*="span"] {
  padding-top: 5px;
}

input[disabled],
select[disabled],
textarea[disabled],
input[readonly],
select[readonly],
textarea[readonly] {
  cursor: not-allowed;
  background-color: #eeeeee;
}

input[type="radio"][disabled],
input[type="checkbox"][disabled],
input[type="radio"][readonly],
input[type="checkbox"][readonly] {
  background-color: transparent;
}

.control-group.warning .control-label,
.control-group.warning .help-block,
.control-group.warning .help-inline {
  color: #c09853;
}

.control-group.warning .checkbox,
.control-group.warning .radio,
.control-group.warning input,
.control-group.warning select,
.control-group.warning textarea {
  color: #c09853;
}

.control-group.warning input,
.control-group.warning select,
.control-group.warning textarea {
  border-color: #c09853;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
     -moz-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
          box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}

.control-group.warning input:focus,
.control-group.warning select:focus,
.control-group.warning textarea:focus {
  border-color: #a47e3c;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #dbc59e;
     -moz-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #dbc59e;
          box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #dbc59e;
}

.control-group.warning .input-prepend .add-on,
.control-group.warning .input-append .add-on {
  color: #c09853;
  background-color: #fcf8e3;
  border-color: #c09853;
}

.control-group.error .control-label,
.control-group.error .help-block,
.control-group.error .help-inline {
  color: #b94a48;
}

.control-group.error .checkbox,
.control-group.error .radio,
.control-group.error input,
.control-group.error select,
.control-group.error textarea {
  color: #b94a48;
}

.control-group.error input,
.control-group.error select,
.control-group.error textarea {
  border-color: #b94a48;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
     -moz-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
          box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}

.control-group.error input:focus,
.control-group.error select:focus,
.control-group.error textarea:focus {
  border-color: #953b39;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #d59392;
     -moz-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #d59392;
          box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #d59392;
}

.control-group.error .input-prepend .add-on,
.control-group.error .input-append .add-on {
  color: #b94a48;
  background-color: #f2dede;
  border-color: #b94a48;
}

.control-group.success .control-label,
.control-group.success .help-block,
.control-group.success .help-inline {
  color: #468847;
}

.control-group.success .checkbox,
.control-group.success .radio,
.control-group.success input,
.control-group.success select,
.control-group.success textarea {
  color: #468847;
}

.control-group.success input,
.control-group.success select,
.control-group.success textarea {
  border-color: #468847;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
     -moz-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
          box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}

.control-group.success input:focus,
.control-group.success select:focus,
.control-group.success textarea:focus {
  border-color: #356635;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #7aba7b;
     -moz-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #7aba7b;
          box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #7aba7b;
}

.control-group.success .input-prepend .add-on,
.control-group.success .input-append .add-on {
  color: #468847;
  background-color: #dff0d8;
  border-color: #468847;
}

.control-group.info .control-label,
.control-group.info .help-block,
.control-group.info .help-inline {
  color: #3a87ad;
}

.control-group.info .checkbox,
.control-group.info .radio,
.control-group.info input,
.control-group.info select,
.control-group.info textarea {
  color: #3a87ad;
}

.control-group.info input,
.control-group.info select,
.control-group.info textarea {
  border-color: #3a87ad;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
     -moz-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
          box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}

.control-group.info input:focus,
.control-group.info select:focus,
.control-group.info textarea:focus {
  border-color: #2d6987;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #7ab5d3;
     -moz-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #7ab5d3;
          box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #7ab5d3;
}

.control-group.info .input-prepend .add-on,
.control-group.info .input-append .add-on {
  color: #3a87ad;
  background-color: #d9edf7;
  border-color: #3a87ad;
}

input:focus:invalid,
textarea:focus:invalid,
select:focus:invalid {
  color: #b94a48;
  border-color: #ee5f5b;
}

input:focus:invalid:focus,
textarea:focus:invalid:focus,
select:focus:invalid:focus {
  border-color: #e9322d;
  -webkit-box-shadow: 0 0 6px #f8b9b7;
     -moz-box-shadow: 0 0 6px #f8b9b7;
          box-shadow: 0 0 6px #f8b9b7;
}

.form-actions {
  padding: 19px 20px 20px;
  margin-top: 20px;
  margin-bottom: 20px;
  background-color: #f5f5f5;
  border-top: 1px solid #e5e5e5;
  *zoom: 1;
}

.form-actions:before,
.form-actions:after {
  display: table;
  line-height: 0;
  content: "";
}

.form-actions:after {
  clear: both;
}

.help-block,
.help-inline {
  color: #595959;
}

.help-block {
  display: block;
  margin-bottom: 10px;
}

.help-inline {
  display: inline-block;
  *display: inline;
  padding-left: 5px;
  vertical-align: middle;
  *zoom: 1;
}

.input-append,
.input-prepend {
  display: inline-block;
  margin-bottom: 10px;
  font-size: 0;
  white-space: nowrap;
  vertical-align: middle;
}

.input-append input,
.input-prepend input,
.input-append select,
.input-prepend select,
.input-append .uneditable-input,
.input-prepend .uneditable-input,
.input-append .dropdown-menu,
.input-prepend .dropdown-menu,
.input-append .popover,
.input-prepend .popover {
  font-size: 14px;
}

.input-append input,
.input-prepend input,
.input-append select,
.input-prepend select,
.input-append .uneditable-input,
.input-prepend .uneditable-input {
  position: relative;
  margin-bottom: 0;
  *margin-left: 0;
  vertical-align: top;
  -webkit-border-radius: 0 4px 4px 0;
     -moz-border-radius: 0 4px 4px 0;
          border-radius: 0 4px 4px 0;
}

.input-append input:focus,
.input-prepend input:focus,
.input-append select:focus,
.input-prepend select:focus,
.input-append .uneditable-input:focus,
.input-prepend .uneditable-input:focus {
  z-index: 2;
}

.input-append .add-on,
.input-prepend .add-on {
  display: inline-block;
  width: auto;
  height: 20px;
  min-width: 16px;
  padding: 4px 5px;
  font-size: 14px;
  font-weight: normal;
  line-height: 20px;
  text-align: center;
  text-shadow: 0 1px 0 #ffffff;
  background-color: #eeeeee;
  border: 1px solid #ccc;
}

.input-append .add-on,
.input-prepend .add-on,
.input-append .btn,
.input-prepend .btn,
.input-append .btn-group > .dropdown-toggle,
.input-prepend .btn-group > .dropdown-toggle {
  vertical-align: top;
  -webkit-border-radius: 0;
     -moz-border-radius: 0;
          border-radius: 0;
}

.input-append .active,
.input-prepend .active {
  background-color: #a9dba9;
  border-color: #46a546;
}

.input-prepend .add-on,
.input-prepend .btn {
  margin-right: -1px;
}

.input-prepend .add-on:first-child,
.input-prepend .btn:first-child {
  -webkit-border-radius: 4px 0 0 4px;
     -moz-border-radius: 4px 0 0 4px;
          border-radius: 4px 0 0 4px;
}

.input-append input,
.input-append select,
.input-append .uneditable-input {
  -webkit-border-radius: 4px 0 0 4px;
     -moz-border-radius: 4px 0 0 4px;
          border-radius: 4px 0 0 4px;
}

.input-append input + .btn-group .btn:last-child,
.input-append select + .btn-group .btn:last-child,
.input-append .uneditable-input + .btn-group .btn:last-child {
  -webkit-border-radius: 0 4px 4px 0;
     -moz-border-radius: 0 4px 4px 0;
          border-radius: 0 4px 4px 0;
}

.input-append .add-on,
.input-append .btn,
.input-append .btn-group {
  margin-left: -1px;
}

.input-append .add-on:last-child,
.input-append .btn:last-child,
.input-append .btn-group:last-child > .dropdown-toggle {
  -webkit-border-radius: 0 4px 4px 0;
     -moz-border-radius: 0 4px 4px 0;
          border-radius: 0 4px 4px 0;
}

.input-prepend.input-append input,
.input-prepend.input-append select,
.input-prepend.input-append .uneditable-input {
  -webkit-border-radius: 0;
     -moz-border-radius: 0;
          border-radius: 0;
}

.input-prepend.input-append input + .btn-group .btn,
.input-prepend.input-append select + .btn-group .btn,
.input-prepend.input-append .uneditable-input + .btn-group .btn {
  -webkit-border-radius: 0 4px 4px 0;
     -moz-border-radius: 0 4px 4px 0;
          border-radius: 0 4px 4px 0;
}

.input-prepend.input-append .add-on:first-child,
.input-prepend.input-append .btn:first-child {
  margin-right: -1px;
  -webkit-border-radius: 4px 0 0 4px;
     -moz-border-radius: 4px 0 0 4px;
          border-radius: 4px 0 0 4px;
}

.input-prepend.input-append .add-on:last-child,
.input-prepend.input-append .btn:last-child {
  margin-left: -1px;
  -webkit-border-radius: 0 4px 4px 0;
     -moz-border-radius: 0 4px 4px 0;
          border-radius: 0 4px 4px 0;
}

.input-prepend.input-append .btn-group:first-child {
  margin-left: 0;
}

input.search-query {
  padding-right: 14px;
  padding-right: 4px \9;
  padding-left: 14px;
  padding-left: 4px \9;
  /* IE7-8 doesn't have border-radius, so don't indent the padding */

  margin-bottom: 0;
  -webkit-border-radius: 15px;
     -moz-border-radius: 15px;
          border-radius: 15px;
}

/* Allow for input prepend/append in search forms */

.form-search .input-append .search-query,
.form-search .input-prepend .search-query {
  -webkit-border-radius: 0;
     -moz-border-radius: 0;
          border-radius: 0;
}

.form-search .input-append .search-query {
  -webkit-border-radius: 14px 0 0 14px;
     -moz-border-radius: 14px 0 0 14px;
          border-radius: 14px 0 0 14px;
}

.form-search .input-append .btn {
  -webkit-border-radius: 0 14px 14px 0;
     -moz-border-radius: 0 14px 14px 0;
          border-radius: 0 14px 14px 0;
}

.form-search .input-prepend .search-query {
  -webkit-border-radius: 0 14px 14px 0;
     -moz-border-radius: 0 14px 14px 0;
          border-radius: 0 14px 14px 0;
}

.form-search .input-prepend .btn {
  -webkit-border-radius: 14px 0 0 14px;
     -moz-border-radius: 14px 0 0 14px;
          border-radius: 14px 0 0 14px;
}

.form-search input,
.form-inline input,
.form-horizontal input,
.form-search textarea,
.form-inline textarea,
.form-horizontal textarea,
.form-search select,
.form-inline select,
.form-horizontal select,
.form-search .help-inline,
.form-inline .help-inline,
.form-horizontal .help-inline,
.form-search .uneditable-input,
.form-inline .uneditable-input,
.form-horizontal .uneditable-input,
.form-search .input-prepend,
.form-inline .input-prepend,
.form-horizontal .input-prepend,
.form-search .input-append,
.form-inline .input-append,
.form-horizontal .input-append {
  display: inline-block;
  *display: inline;
  margin-bottom: 0;
  vertical-align: middle;
  *zoom: 1;
}

.form-search .hide,
.form-inline .hide,
.form-horizontal .hide {
  display: none;
}

.form-search label,
.form-inline label,
.form-search .btn-group,
.form-inline .btn-group {
  display: inline-block;
}

.form-search .input-append,
.form-inline .input-append,
.form-search .input-prepend,
.form-inline .input-prepend {
  margin-bottom: 0;
}

.form-search .radio,
.form-search .checkbox,
.form-inline .radio,
.form-inline .checkbox {
  padding-left: 0;
  margin-bottom: 0;
  vertical-align: middle;
}

.form-search .radio input[type="radio"],
.form-search .checkbox input[type="checkbox"],
.form-inline .radio input[type="radio"],
.form-inline .checkbox input[type="checkbox"] {
  float: left;
  margin-right: 3px;
  margin-left: 0;
}

.control-group {
  margin-bottom: 10px;
}

legend + .control-group {
  margin-top: 20px;
  -webkit-margin-top-collapse: separate;
}

.form-horizontal .control-group {
  margin-bottom: 20px;
  *zoom: 1;
}

.form-horizontal .control-group:before,
.form-horizontal .control-group:after {
  display: table;
  line-height: 0;
  content: "";
}

.form-horizontal .control-group:after {
  clear: both;
}

.form-horizontal .control-label {
  float: left;
  width: 160px;
  padding-top: 5px;
  text-align: right;
}

.form-horizontal .controls {
  *display: inline-block;
  *padding-left: 20px;
  margin-left: 180px;
  *margin-left: 0;
}

.form-horizontal .controls:first-child {
  *padding-left: 180px;
}

.form-horizontal .help-block {
  margin-bottom: 0;
}

.form-horizontal input + .help-block,
.form-horizontal select + .help-block,
.form-horizontal textarea + .help-block,
.form-horizontal .uneditable-input + .help-block,
.form-horizontal .input-prepend + .help-block,
.form-horizontal .input-append + .help-block {
  margin-top: 10px;
}

.form-horizontal .form-actions {
  padding-left: 180px;
}

table {
  max-width: 100%;
  background-color: transparent;
  border-collapse: collapse;
  border-spacing: 0;
}

.table {
  width: 100%;
  margin-bottom: 20px;
}

.table th,
.table td {
  padding: 8px;
  line-height: 20px;
  text-align: left;
  vertical-align: top;
  border-top: 1px solid #dddddd;
}

.table th {
  font-weight: bold;
}

.table thead th {
  vertical-align: bottom;
}

.table caption + thead tr:first-child th,
.table caption + thead tr:first-child td,
.table colgroup + thead tr:first-child th,
.table colgroup + thead tr:first-child td,
.table thead:first-child tr:first-child th,
.table thead:first-child tr:first-child td {
  border-top: 0;
}

.table tbody + tbody {
  border-top: 2px solid #dddddd;
}

.table .table {
  background-color: #ffffff;
}

.table-condensed th,
.table-condensed td {
  padding: 4px 5px;
}

.table-bordered {
  border: 1px solid #dddddd;
  border-collapse: separate;
  *border-collapse: collapse;
  border-left: 0;
  -webkit-border-radius: 4px;
     -moz-border-radius: 4px;
          border-radius: 4px;
}

.table-bordered th,
.table-bordered td {
  border-left: 1px solid #dddddd;
}

.table-bordered caption + thead tr:first-child th,
.table-bordered caption + tbody tr:first-child th,
.table-bordered caption + tbody tr:first-child td,
.table-bordered colgroup + thead tr:first-child th,
.table-bordered colgroup + tbody tr:first-child th,
.table-bordered colgroup + tbody tr:first-child td,
.table-bordered thead:first-child tr:first-child th,
.table-bordered tbody:first-child tr:first-child th,
.table-bordered tbody:first-child tr:first-child td {
  border-top: 0;
}

.table-bordered thead:first-child tr:first-child > th:first-child,
.table-bordered tbody:first-child tr:first-child > td:first-child,
.table-bordered tbody:first-child tr:first-child > th:first-child {
  -webkit-border-top-left-radius: 4px;
          border-top-left-radius: 4px;
  -moz-border-radius-topleft: 4px;
}

.table-bordered thead:first-child tr:first-child > th:last-child,
.table-bordered tbody:first-child tr:first-child > td:last-child,
.table-bordered tbody:first-child tr:first-child > th:last-child {
  -webkit-border-top-right-radius: 4px;
          border-top-right-radius: 4px;
  -moz-border-radius-topright: 4px;
}

.table-bordered thead:last-child tr:last-child > th:first-child,
.table-bordered tbody:last-child tr:last-child > td:first-child,
.table-bordered tbody:last-child tr:last-child > th:first-child,
.table-bordered tfoot:last-child tr:last-child > td:first-child,
.table-bordered tfoot:last-child tr:last-child > th:first-child {
  -webkit-border-bottom-left-radius: 4px;
          border-bottom-left-radius: 4px;
  -moz-border-radius-bottomleft: 4px;
}

.table-bordered thead:last-child tr:last-child > th:last-child,
.table-bordered tbody:last-child tr:last-child > td:last-child,
.table-bordered tbody:last-child tr:last-child > th:last-child,
.table-bordered tfoot:last-child tr:last-child > td:last-child,
.table-bordered tfoot:last-child tr:last-child > th:last-child {
  -webkit-border-bottom-right-radius: 4px;
          border-bottom-right-radius: 4px;
  -moz-border-radius-bottomright: 4px;
}

.table-bordered tfoot + tbody:last-child tr:last-child td:first-child {
  -webkit-border-bottom-left-radius: 0;
          border-bottom-left-radius: 0;
  -moz-border-radius-bottomleft: 0;
}

.table-bordered tfoot + tbody:last-child tr:last-child td:last-child {
  -webkit-border-bottom-right-radius: 0;
          border-bottom-right-radius: 0;
  -moz-border-radius-bottomright: 0;
}

.table-bordered caption + thead tr:first-child th:first-child,
.table-bordered caption + tbody tr:first-child td:first-child,
.table-bordered colgroup + thead tr:first-child th:first-child,
.table-bordered colgroup + tbody tr:first-child td:first-child {
  -webkit-border-top-left-radius: 4px;
          border-top-left-radius: 4px;
  -moz-border-radius-topleft: 4px;
}

.table-bordered caption + thead tr:first-child th:last-child,
.table-bordered caption + tbody tr:first-child td:last-child,
.table-bordered colgroup + thead tr:first-child th:last-child,
.table-bordered colgroup + tbody tr:first-child td:last-child {
  -webkit-border-top-right-radius: 4px;
          border-top-right-radius: 4px;
  -moz-border-radius-topright: 4px;
}

.table-striped tbody > tr:nth-child(odd) > td,
.table-striped tbody > tr:nth-child(odd) > th {
  background-color: #f9f9f9;
}

.table-hover tbody tr:hover > td,
.table-hover tbody tr:hover > th {
  background-color: #f5f5f5;
}

table td[class*="span"],
table th[class*="span"],
.row-fluid table td[class*="span"],
.row-fluid table th[class*="span"] {
  display: table-cell;
  float: none;
  margin-left: 0;
}

.table td.span1,
.table th.span1 {
  float: none;
  width: 44px;
  margin-left: 0;
}

.table td.span2,
.table th.span2 {
  float: none;
  width: 124px;
  margin-left: 0;
}

.table td.span3,
.table th.span3 {
  float: none;
  width: 204px;
  margin-left: 0;
}

.table td.span4,
.table th.span4 {
  float: none;
  width: 284px;
  margin-left: 0;
}

.table td.span5,
.table th.span5 {
  float: none;
  width: 364px;
  margin-left: 0;
}

.table td.span6,
.table th.span6 {
  float: none;
  width: 444px;
  margin-left: 0;
}

.table td.span7,
.table th.span7 {
  float: none;
  width: 524px;
  margin-left: 0;
}

.table td.span8,
.table th.span8 {
  float: none;
  width: 604px;
  margin-left: 0;
}

.table td.span9,
.table th.span9 {
  float: none;
  width: 684px;
  margin-left: 0;
}

.table td.span10,
.table th.span10 {
  float: none;
  width: 764px;
  margin-left: 0;
}

.table td.span11,
.table th.span11 {
  float: none;
  width: 844px;
  margin-left: 0;
}

.table td.span12,
.table th.span12 {
  float: none;
  width: 924px;
  margin-left: 0;
}

.table tbody tr.success > td {
  background-color: #dff0d8;
}

.table tbody tr.error > td {
  background-color: #f2dede;
}

.table tbody tr.warning > td {
  background-color: #fcf8e3;
}

.table tbody tr.info > td {
  background-color: #d9edf7;
}

.table-hover tbody tr.success:hover > td {
  background-color: #d0e9c6;
}

.table-hover tbody tr.error:hover > td {
  background-color: #ebcccc;
}

.table-hover tbody tr.warning:hover > td {
  background-color: #faf2cc;
}

.table-hover tbody tr.info:hover > td {
  background-color: #c4e3f3;
}

[class^="icon-"],
[class*=" icon-"] {
  display: inline-block;
  width: 14px;
  height: 14px;
  margin-top: 1px;
  *margin-right: .3em;
  line-height: 14px;
  vertical-align: text-top;
  background-image: url("../img/glyphicons-halflings.png");
  background-position: 14px 14px;
  background-repeat: no-repeat;
}

/* White icons with optional class, or on hover/focus/active states of certain elements */

.icon-white,
.nav-pills > .active > a > [class^="icon-"],
.nav-pills > .active > a > [class*=" icon-"],
.nav-list > .active > a > [class^="icon-"],
.nav-list > .active > a > [class*=" icon-"],
.navbar-inverse .nav > .active > a > [class^="icon-"],
.navbar-inverse .nav > .active > a > [class*=" icon-"],
.dropdown-menu > li > a:hover > [class^="icon-"],
.dropdown-menu > li > a:focus > [class^="icon-"],
.dropdown-menu > li > a:hover > [class*=" icon-"],
.dropdown-menu > li > a:focus > [class*=" icon-"],
.dropdown-menu > .active > a > [class^="icon-"],
.dropdown-menu > .active > a > [class*=" icon-"],
.dropdown-submenu:hover > a > [class^="icon-"],
.dropdown-submenu:focus > a > [class^="icon-"],
.dropdown-submenu:hover > a > [class*=" icon-"],
.dropdown-submenu:focus > a > [class*=" icon-"] {
  background-image: url("../img/glyphicons-halflings-white.png");
}

.icon-glass {
  background-position: 0      0;
}

.icon-music {
  background-position: -24px 0;
}

.icon-search {
  background-position: -48px 0;
}

.icon-envelope {
  background-position: -72px 0;
}

.icon-heart {
  background-position: -96px 0;
}

.icon-star {
  background-position: -120px 0;
}

.icon-star-empty {
  background-position: -144px 0;
}

.icon-user {
  background-position: -168px 0;
}

.icon-film {
  background-position: -192px 0;
}

.icon-th-large {
  background-position: -216px 0;
}

.icon-th {
  background-position: -240px 0;
}

.icon-th-list {
  background-position: -264px 0;
}

.icon-ok {
  background-position: -288px 0;
}

.icon-remove {
  background-position: -312px 0;
}

.icon-zoom-in {
  background-position: -336px 0;
}

.icon-zoom-out {
  background-position: -360px 0;
}

.icon-off {
  background-position: -384px 0;
}

.icon-signal {
  background-position: -408px 0;
}

.icon-cog {
  background-position: -432px 0;
}

.icon-trash {
  background-position: -456px 0;
}

.icon-home {
  background-position: 0 -24px;
}

.icon-file {
  background-position: -24px -24px;
}

.icon-time {
  background-position: -48px -24px;
}

.icon-road {
  background-position: -72px -24px;
}

.icon-download-alt {
  background-position: -96px -24px;
}

.icon-download {
  background-position: -120px -24px;
}

.icon-upload {
  background-position: -144px -24px;
}

.icon-inbox {
  background-position: -168px -24px;
}

.icon-play-circle {
  background-position: -192px -24px;
}

.icon-repeat {
  background-position: -216px -24px;
}

.icon-refresh {
  background-position: -240px -24px;
}

.icon-list-alt {
  background-position: -264px -24px;
}

.icon-lock {
  background-position: -287px -24px;
}

.icon-flag {
  background-position: -312px -24px;
}

.icon-headphones {
  background-position: -336px -24px;
}

.icon-volume-off {
  background-position: -360px -24px;
}

.icon-volume-down {
  background-position: -384px -24px;
}

.icon-volume-up {
  background-position: -408px -24px;
}

.icon-qrcode {
  background-position: -432px -24px;
}

.icon-barcode {
  background-position: -456px -24px;
}

.icon-tag {
  background-position: 0 -48px;
}

.icon-tags {
  background-position: -25px -48px;
}

.icon-book {
  background-position: -48px -48px;
}

.icon-bookmark {
  background-position: -72px -48px;
}

.icon-print {
  background-position: -96px -48px;
}

.icon-camera {
  background-position: -120px -48px;
}

.icon-font {
  background-position: -144px -48px;
}

.icon-bold {
  background-position: -167px -48px;
}

.icon-italic {
  background-position: -192px -48px;
}

.icon-text-height {
  background-position: -216px -48px;
}

.icon-text-width {
  background-position: -240px -48px;
}

.icon-align-left {
  background-position: -264px -48px;
}

.icon-align-center {
  background-position: -288px -48px;
}

.icon-align-right {
  background-position: -312px -48px;
}

.icon-align-justify {
  background-position: -336px -48px;
}

.icon-list {
  background-position: -360px -48px;
}

.icon-indent-left {
  background-position: -384px -48px;
}

.icon-indent-right {
  background-position: -408px -48px;
}

.icon-facetime-video {
  background-position: -432px -48px;
}

.icon-picture {
  background-position: -456px -48px;
}

.icon-pencil {
  background-position: 0 -72px;
}

.icon-map-marker {
  background-position: -24px -72px;
}

.icon-adjust {
  background-position: -48px -72px;
}

.icon-tint {
  background-position: -72px -72px;
}

.icon-edit {
  background-position: -96px -72px;
}

.icon-share {
  background-position: -120px -72px;
}

.icon-check {
  background-position: -144px -72px;
}

.icon-move {
  background-position: -168px -72px;
}

.icon-step-backward {
  background-position: -192px -72px;
}

.icon-fast-backward {
  background-position: -216px -72px;
}

.icon-backward {
  background-position: -240px -72px;
}

.icon-play {
  background-position: -264px -72px;
}

.icon-pause {
  background-position: -288px -72px;
}

.icon-stop {
  background-position: -312px -72px;
}

.icon-forward {
  background-position: -336px -72px;
}

.icon-fast-forward {
  background-position: -360px -72px;
}

.icon-step-forward {
  background-position: -384px -72px;
}

.icon-eject {
  background-position: -408px -72px;
}

.icon-chevron-left {
  background-position: -432px -72px;
}

.icon-chevron-right {
  background-position: -456px -72px;
}

.icon-plus-sign {
  background-position: 0 -96px;
}

.icon-minus-sign {
  background-position: -24px -96px;
}

.icon-remove-sign {
  background-position: -48px -96px;
}

.icon-ok-sign {
  background-position: -72px -96px;
}

.icon-question-sign {
  background-position: -96px -96px;
}

.icon-info-sign {
  background-position: -120px -96px;
}

.icon-screenshot {
  background-position: -144px -96px;
}

.icon-remove-circle {
  background-position: -168px -96px;
}

.icon-ok-circle {
  background-position: -192px -96px;
}

.icon-ban-circle {
  background-position: -216px -96px;
}

.icon-arrow-left {
  background-position: -240px -96px;
}

.icon-arrow-right {
  background-position: -264px -96px;
}

.icon-arrow-up {
  background-position: -289px -96px;
}

.icon-arrow-down {
  background-position: -312px -96px;
}

.icon-share-alt {
  background-position: -336px -96px;
}

.icon-resize-full {
  background-position: -360px -96px;
}

.icon-resize-small {
  background-position: -384px -96px;
}

.icon-plus {
  background-position: -408px -96px;
}

.icon-minus {
  background-position: -433px -96px;
}

.icon-asterisk {
  background-position: -456px -96px;
}

.icon-exclamation-sign {
  background-position: 0 -120px;
}

.icon-gift {
  background-position: -24px -120px;
}

.icon-leaf {
  background-position: -48px -120px;
}

.icon-fire {
  background-position: -72px -120px;
}

.icon-eye-open {
  background-position: -96px -120px;
}

.icon-eye-close {
  background-position: -120px -120px;
}

.icon-warning-sign {
  background-position: -144px -120px;
}

.icon-plane {
  background-position: -168px -120px;
}

.icon-calendar {
  background-position: -192px -120px;
}

.icon-random {
  width: 16px;
  background-position: -216px -120px;
}

.icon-comment {
  background-position: -240px -120px;
}

.icon-magnet {
  background-position: -264px -120px;
}

.icon-chevron-up {
  background-position: -288px -120px;
}

.icon-chevron-down {
  background-position: -313px -119px;
}

.icon-retweet {
  background-position: -336px -120px;
}

.icon-shopping-cart {
  background-position: -360px -120px;
}

.icon-folder-close {
  width: 16px;
  background-position: -384px -120px;
}

.icon-folder-open {
  width: 16px;
  background-position: -408px -120px;
}

.icon-resize-vertical {
  background-position: -432px -119px;
}

.icon-resize-horizontal {
  background-position: -456px -118px;
}

.icon-hdd {
  background-position: 0 -144px;
}

.icon-bullhorn {
  background-position: -24px -144px;
}

.icon-bell {
  background-position: -48px -144px;
}

.icon-certificate {
  background-position: -72px -144px;
}

.icon-thumbs-up {
  background-position: -96px -144px;
}

.icon-thumbs-down {
  background-position: -120px -144px;
}

.icon-hand-right {
  background-position: -144px -144px;
}

.icon-hand-left {
  background-position: -168px -144px;
}

.icon-hand-up {
  background-position: -192px -144px;
}

.icon-hand-down {
  background-position: -216px -144px;
}

.icon-circle-arrow-right {
  background-position: -240px -144px;
}

.icon-circle-arrow-left {
  background-position: -264px -144px;
}

.icon-circle-arrow-up {
  background-position: -288px -144px;
}

.icon-circle-arrow-down {
  background-position: -312px -144px;
}

.icon-globe {
  background-position: -336px -144px;
}

.icon-wrench {
  background-position: -360px -144px;
}

.icon-tasks {
  background-position: -384px -144px;
}

.icon-filter {
  background-position: -408px -144px;
}

.icon-briefcase {
  background-position: -432px -144px;
}

.icon-fullscreen {
  background-position: -456px -144px;
}

.dropup,
.dropdown {
  position: relative;
}

.dropdown-toggle {
  *margin-bottom: -3px;
}

.dropdown-toggle:active,
.open .dropdown-toggle {
  outline: 0;
}

.caret {
  display: inline-block;
  width: 0;
  height: 0;
  vertical-align: top;
  border-top: 4px solid #000000;
  border-right: 4px solid transparent;
  border-left: 4px solid transparent;
  content: "";
}

.dropdown .caret {
  margin-top: 8px;
  margin-left: 2px;
}

.dropdown-menu {
  position: absolute;
  top: 100%;
  left: 0;
  z-index: 1000;
  display: none;
  float: left;
  min-width: 160px;
  padding: 5px 0;
  margin: 2px 0 0;
  list-style: none;
  background-color: #ffffff;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.2);
  *border-right-width: 2px;
  *border-bottom-width: 2px;
  -webkit-border-radius: 6px;
     -moz-border-radius: 6px;
          border-radius: 6px;
  -webkit-box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
     -moz-box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
          box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
  -webkit-background-clip: padding-box;
     -moz-background-clip: padding;
          background-clip: padding-box;
}

.dropdown-menu.pull-right {
  right: 0;
  left: auto;
}

.dropdown-menu .divider {
  *width: 100%;
  height: 1px;
  margin: 9px 1px;
  *margin: -5px 0 5px;
  overflow: hidden;
  background-color: #e5e5e5;
  border-bottom: 1px solid #ffffff;
}

.dropdown-menu > li > a {
  display: block;
  padding: 3px 20px;
  clear: both;
  font-weight: normal;
  line-height: 20px;
  color: #333333;
  white-space: nowrap;
}

.dropdown-menu > li > a:hover,
.dropdown-menu > li > a:focus,
.dropdown-submenu:hover > a,
.dropdown-submenu:focus > a {
  color: #ffffff;
  text-decoration: none;
  background-color: #0081c2;
  background-image: -moz-linear-gradient(top, #0088cc, #0077b3);
  background-image: -webkit-gradient(linear, 0 0, 0 100%, from(#0088cc), to(#0077b3));
  background-image: -webkit-linear-gradient(top, #0088cc, #0077b3);
  background-image: -o-linear-gradient(top, #0088cc, #0077b3);
  background-image: linear-gradient(to bottom, #0088cc, #0077b3);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#ff0088cc', endColorstr='#ff0077b3', GradientType=0);
}

.dropdown-menu > .active > a,
.dropdown-menu > .active > a:hover,
.dropdown-menu > .active > a:focus {
  color: #ffffff;
  text-decoration: none;
  background-color: #0081c2;
  background-image: -moz-linear-gradient(top, #0088cc, #0077b3);
  background-image: -webkit-gradient(linear, 0 0, 0 100%, from(#0088cc), to(#0077b3));
  background-image: -webkit-linear-gradient(top, #0088cc, #0077b3);
  background-image: -o-linear-gradient(top, #0088cc, #0077b3);
  background-image: linear-gradient(to bottom, #0088cc, #0077b3);
  background-repeat: repeat-x;
  outline: 0;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#ff0088cc', endColorstr='#ff0077b3', GradientType=0);
}

.dropdown-menu > .disabled > a,
.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  color: #999999;
}

.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  text-decoration: none;
  cursor: default;
  background-color: transparent;
  background-image: none;
  filter: progid:DXImageTransform.Microsoft.gradient(enabled=false);
}

.open {
  *z-index: 1000;
}

.open > .dropdown-menu {
  display: block;
}

.pull-right > .dropdown-menu {
  right: 0;
  left: auto;
}

.dropup .caret,
.navbar-fixed-bottom .dropdown .caret {
  border-top: 0;
  border-bottom: 4px solid #000000;
  content: "";
}

.dropup .dropdown-menu,
.navbar-fixed-bottom .dropdown .dropdown-menu {
  top: auto;
  bottom: 100%;
  margin-bottom: 1px;
}

.dropdown-submenu {
  position: relative;
}

.dropdown-submenu > .dropdown-menu {
  top: 0;
  left: 100%;
  margin-top: -6px;
  margin-left: -1px;
  -webkit-border-radius: 0 6px 6px 6px;
     -moz-border-radius: 0 6px 6px 6px;
          border-radius: 0 6px 6px 6px;
}

.dropdown-submenu:hover > .dropdown-menu {
  display: block;
}

.dropup .dropdown-submenu > .dropdown-menu {
  top: auto;
  bottom: 0;
  margin-top: 0;
  margin-bottom: -2px;
  -webkit-border-radius: 5px 5px 5px 0;
     -moz-border-radius: 5px 5px 5px 0;
          border-radius: 5px 5px 5px 0;
}

.dropdown-submenu > a:after {
  display: block;
  float: right;
  width: 0;
  height: 0;
  margin-top: 5px;
  margin-right: -10px;
  border-color: transparent;
  border-left-color: #cccccc;
  border-style: solid;
  border-width: 5px 0 5px 5px;
  content: " ";
}

.dropdown-submenu:hover > a:after {
  border-left-color: #ffffff;
}

.dropdown-submenu.pull-left {
  float: none;
}

.dropdown-submenu.pull-left > .dropdown-menu {
  left: -100%;
  margin-left: 10px;
  -webkit-border-radius: 6px 0 6px 6px;
     -moz-border-radius: 6px 0 6px 6px;
          border-radius: 6px 0 6px 6px;
}

.dropdown .dropdown-menu .nav-header {
  padding-right: 20px;
  padding-left: 20px;
}

.typeahead {
  z-index: 1051;
  margin-top: 2px;
  -webkit-border-radius: 4px;
     -moz-border-radius: 4px;
          border-radius: 4px;
}

.well {
  min-height: 20px;
  padding: 19px;
  margin-bottom: 20px;
  background-color: #f5f5f5;
  border: 1px solid #e3e3e3;
  -webkit-border-radius: 4px;
     -moz-border-radius: 4px;
          border-radius: 4px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
     -moz-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
          box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
}

.well blockquote {
  border-color: #ddd;
  border-color: rgba(0, 0, 0, 0.15);
}

.well-large {
  padding: 24px;
  -webkit-border-radius: 6px;
     -moz-border-radius: 6px;
          border-radius: 6px;
}

.well-small {
  padding: 9px;
  -webkit-border-radius: 3px;
     -moz-border-radius: 3px;
          border-radius: 3px;
}

.fade {
  opacity: 0;
  -webkit-transition: opacity 0.15s linear;
     -moz-transition: opacity 0.15s linear;
       -o-transition: opacity 0.15s linear;
          transition: opacity 0.15s linear;
}

.fade.in {
  opacity: 1;
}

.collapse {
  position: relative;
  height: 0;
  overflow: hidden;
  -webkit-transition: height 0.35s ease;
     -moz-transition: height 0.35s ease;
       -o-transition: height 0.35s ease;
          transition: height 0.35s ease;
}

.collapse.in {
  height: auto;
}

.close {
  float: right;
  font-size: 20px;
  font-weight: bold;
  line-height: 20px;
  color: #000000;
  text-shadow: 0 1px 0 #ffffff;
  opacity: 0.2;
  filter: alpha(opacity=20);
}

.close:hover,
.close:focus {
  color: #000000;
  text-decoration: none;
  cursor: pointer;
  opacity: 0.4;
  filter: alpha(opacity=40);
}

button.close {
  padding: 0;
  cursor: pointer;
  background: transparent;
  border: 0;
  -webkit-appearance: none;
}

.btn {
  display: inline-block;
  *display: inline;
  padding: 4px 12px;
  margin-bottom: 0;
  *margin-left: .3em;
  font-size: 14px;
  line-height: 20px;
  color: #333333;
  text-align: center;
  text-shadow: 0 1px 1px rgba(255, 255, 255, 0.75);
  vertical-align: middle;
  cursor: pointer;
  background-color: #f5f5f5;
  *background-color: #e6e6e6;
  background-image: -moz-linear-gradient(top, #ffffff, #e6e6e6);
  background-image: -webkit-gradient(linear, 0 0, 0 100%, from(#ffffff), to(#e6e6e6));
  background-image: -webkit-linear-gradient(top, #ffffff, #e6e6e6);
  background-image: -o-linear-gradient(top, #ffffff, #e6e6e6);
  background-image: linear-gradient(to bottom, #ffffff, #e6e6e6);
  background-repeat: repeat-x;
  border: 1px solid #cccccc;
  *border: 0;
  border-color: #e6e6e6 #e6e6e6 #bfbfbf;
  border-color: rgba(0, 0, 0, 0.1) rgba(0, 0, 0, 0.1) rgba(0, 0, 0, 0.25);
  border-bottom-color: #b3b3b3;
  -webkit-border-radius: 4px;
     -moz-border-radius: 4px;
          border-radius: 4px;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#ffffffff', endColorstr='#ffe6e6e6', GradientType=0);
  filter: progid:DXImageTransform.Microsoft.gradient(enabled=false);
  *zoom: 1;
  -webkit-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.2), 0 1px 2px rgba(0, 0, 0, 0.05);
     -moz-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.2), 0 1px 2px rgba(0, 0, 0, 0.05);
          box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.2), 0 1px 2px rgba(0, 0, 0, 0.05);
}

.btn:hover,
.btn:focus,
.btn:active,
.btn.active,
.btn.disabled,
.btn[disabled] {
  color: #333333;
  background-color: #e6e6e6;
  *background-color: #d9d9d9;
}

.btn:active,
.btn.active {
  background-color: #cccccc \9;
}

.btn:first-child {
  *margin-left: 0;
}

.btn:hover,
.btn:focus {
  color: #333333;
  text-decoration: none;
  background-position: 0 -15px;
  -webkit-transition: background-position 0.1s linear;
     -moz-transition: background-position 0.1s linear;
       -o-transition: background-position 0.1s linear;
          transition: background-position 0.1s linear;
}

.btn:focus {
  outline: thin dotted #333;
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}

.btn.active,
.btn:active {
  background-image: none;
  outline: 0;
  -webkit-box-shadow: inset 0 2px 4px rgba(0, 0, 0, 0.15), 0 1px 2px rgba(0, 0, 0, 0.05);
     -moz-box-shadow: inset 0 2px 4px rgba(0, 0, 0, 0.15), 0 1px 2px rgba(0, 0, 0, 0.05);
          box-shadow: inset 0 2px 4px rgba(0, 0, 0, 0.15), 0 1px 2px rgba(0, 0, 0, 0.05);
}

.btn.disabled,
.btn[disabled] {
  cursor: default;
  background-image: none;
  opacity: 0.65;
  filter: alpha(opacity=65);
  -webkit-box-shadow: none;
     -moz-box-shadow: none;
          box-shadow: none;
}

.btn-large {
  padding: 11px 19px;
  font-size: 17.5px;
  -webkit-border-radius: 6px;
     -moz-border-radius: 6px;
          border-radius: 6px;
}

.btn-large [class^="icon-"],
.btn-large [class*=" icon-"] {
  margin-top: 4px;
}

.btn-small {
  padding: 2px 10px;
  font-size: 11.9px;
  -webkit-border-radius: 3px;
     -moz-border-radius: 3px;
          border-radius: 3px;
}

.btn-small [class^="icon-"],
.btn-small [class*=" icon-"] {
  margin-top: 0;
}

.btn-mini [class^="icon-"],
.btn-mini [class*=" icon-"] {
  margin-top: -1px;
}

.btn-mini {
  padding: 0 6px;
  font-size: 10.5px;
  -webkit-border-radius: 3px;
     -moz-border-radius: 3px;
          border-radius: 3px;
}

.btn-block {
  display: block;
  width: 100%;
  padding-right: 0;
  padding-left: 0;
  -webkit-box-sizing: border-box;
     -moz-box-sizing: border-box;
          box-sizing: border-box;
}

.btn-block + .btn-block {
  margin-top: 5px;
}

input[type="submit"].btn-block,
input[type="reset"].btn-block,
input[type="button"].btn-block {
  width: 100%;
}

.btn-primary.active,
.btn-warning.active,
.btn-danger.active,
.btn-success.active,
.btn-info.active,
.btn-inverse.active {
  color: rgba(255, 255, 255, 0.75);
}

.btn-primary {
  color: #ffffff;
  text-shadow: 0 -1px 0 rgba(0, 0, 0, 0.25);
  background-color: #006dcc;
  *background-color: #0044cc;
  background-image: -moz-linear-gradient(top, #0088cc, #0044cc);
  background-image: -webkit-gradient(linear, 0 0, 0 100%, from(#0088cc), to(#0044cc));
  background-image: -webkit-linear-gradient(top, #0088cc, #0044cc);
  background-image: -o-linear-gradient(top, #0088cc, #0044cc);
  background-image: linear-gradient(to bottom, #0088cc, #0044cc);
  background-repeat: repeat-x;
  border-color: #0044cc #0044cc #002a80;
  border-color: rgba(0, 0, 0, 0.1) rgba(0, 0, 0, 0.1) rgba(0, 0, 0, 0.25);
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#ff0088cc', endColorstr='#ff0044cc', GradientType=0);
  filter: progid:DXImageTransform.Microsoft.gradient(enabled=false);
}

.btn-primary:hover,
.btn-primary:focus,
.btn-primary:active,
.btn-primary.active,
.btn-primary.disabled,
.btn-primary[disabled] {
  color: #ffffff;
  background-color: #0044cc;
  *background-color: #003bb3;
}

.btn-primary:active,
.btn-primary.active {
  background-color: #003399 \9;
}

.btn-warning {
  color: #ffffff;
  text-shadow: 0 -1px 0 rgba(0, 0, 0, 0.25);
  background-color: #faa732;
  *background-color: #f89406;
  background-image: -moz-linear-gradient(top, #fbb450, #f89406);
  background-image: -webkit-gradient(linear, 0 0, 0 100%, from(#fbb450), to(#f89406));
  background-image: -webkit-linear-gradient(top, #fbb450, #f89406);
  background-image: -o-linear-gradient(top, #fbb450, #f89406);
  background-image: linear-gradient(to bottom, #fbb450, #f89406);
  background-repeat: repeat-x;
  border-color: #f89406 #f89406 #ad6704;
  border-color: rgba(0, 0, 0, 0.1) rgba(0, 0, 0, 0.1) rgba(0, 0, 0, 0.25);
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#fffbb450', endColorstr='#fff89406', GradientType=0);
  filter: progid:DXImageTransform.Microsoft.gradient(enabled=false);
}

.btn-warning:hover,
.btn-warning:focus,
.btn-warning:active,
.btn-warning.active,
.btn-warning.disabled,
.btn-warning[disabled] {
  color: #ffffff;
  background-color: #f89406;
  *background-color: #df8505;
}

.btn-warning:active,
.btn-warning.active {
  background-color: #c67605 \9;
}

.btn-danger {
  color: #ffffff;
  text-shadow: 0 -1px 0 rgba(0, 0, 0, 0.25);
  background-color: #da4f49;
  *background-color: #bd362f;
  background-image: -moz-linear-gradient(top, #ee5f5b, #bd362f);
  background-image: -webkit-gradient(linear, 0 0, 0 100%, from(#ee5f5b), to(#bd362f));
  background-image: -webkit-linear-gradient(top, #ee5f5b, #bd362f);
  background-image: -o-linear-gradient(top, #ee5f5b, #bd362f);
  background-image: linear-gradient(to bottom, #ee5f5b, #bd362f);
  background-repeat: repeat-x;
  border-color: #bd362f #bd362f #802420;
  border-color: rgba(0, 0, 0, 0.1) rgba(0, 0, 0, 0.1) rgba(0, 0, 0, 0.25);
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#ffee5f5b', endColorstr='#ffbd362f', GradientType=0);
  filter: progid:DXImageTransform.Microsoft.gradient(enabled=false);
}

.btn-danger:hover,
.btn-danger:focus,
.btn-danger:active,
.btn-danger.active,
.btn-danger.disabled,
.btn-danger[disabled] {
  color: #ffffff;
  background-color: #bd362f;
  *background-color: #a9302a;
}

.btn-danger:active,
.btn-danger.active {
  background-color: #942a25 \9;
}

.btn-success {
  color: #ffffff;
  text-shadow: 0 -1px 0 rgba(0, 0, 0, 0.25);
  background-color: #5bb75b;
  *background-color: #51a351;
  background-image: -moz-linear-gradient(top, #62c462, #51a351);
  background-image: -webkit-gradient(linear, 0 0, 0 100%, from(#62c462), to(#51a351));
  background-image: -webkit-linear-gradient(top, #62c462, #51a351);
  background-image: -o-linear-gradient(top, #62c462, #51a351);
  background-image: linear-gradient(to bottom, #62c462, #51a351);
  background-repeat: repeat-x;
  border-color: #51a351 #51a351 #387038;
  border-color: rgba(0, 0, 0, 0.1) rgba(0, 0, 0, 0.1) rgba(0, 0, 0, 0.25);
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#ff62c462', endColorstr='#ff51a351', GradientType=0);
  filter: progid:DXImageTransform.Microsoft.gradient(enabled=false);
}

.btn-success:hover,
.btn-success:focus,
.btn-success:active,
.btn-success.active,
.btn-success.disabled,
.btn-success[disabled] {
  color: #ffffff;
  background-color: #51a351;
  *background-color: #499249;
}

.btn-success:active,
.btn-success.active {
  background-color: #408140 \9;
}

.btn-info {
  color: #ffffff;
  text-shadow: 0 -1px 0 rgba(0, 0, 0, 0.25);
  background-color: #49afcd;
  *background-color: #2f96b4;
  background-image: -moz-linear-gradient(top, #5bc0de, #2f96b4);
  background-image: -webkit-gradient(linear, 0 0, 0 100%, from(#5bc0de), to(#2f96b4));
  background-image: -webkit-linear-gradient(top, #5bc0de, #2f96b4);
  background-image: -o-linear-gradient(top, #5bc0de, #2f96b4);
  background-image: linear-gradient(to bottom, #5bc0de, #2f96b4);
  background-repeat: repeat-x;
  border-color: #2f96b4 #2f96b4 #1f6377;
  border-color: rgba(0, 0, 0, 0.1) rgba(0, 0, 0, 0.1) rgba(0, 0, 0, 0.25);
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#ff5bc0de', endColorstr='#ff2f96b4', GradientType=0);
  filter: progid:DXImageTransform.Microsoft.gradient(enabled=false);
}

.btn-info:hover,
.btn-info:focus,
.btn-info:active,
.btn-info.active,
.btn-info.disabled,
.btn-info[disabled] {
  color: #ffffff;
  background-color: #2f96b4;
  *background-color: #2a85a0;
}

.btn-info:active,
.btn-info.active {
  background-color: #24748c \9;
}

.btn-inverse {
  color: #ffffff;
  text-shadow: 0 -1px 0 rgba(0, 0, 0, 0.25);
  background-color: #363636;
  *background-color: #222222;
  background-image: -moz-linear-gradient(top, #444444, #222222);
  background-image: -webkit-gradient(linear, 0 0, 0 100%, from(#444444), to(#222222));
  background-image: -webkit-linear-gradient(top, #444444, #222222);
  background-image: -o-linear-gradient(top, #444444, #222222);
  background-image: linear-gradient(to bottom, #444444, #222222);
  background-repeat: repeat-x;
  border-color: #222222 #222222 #000000;
  border-color: rgba(0, 0, 0, 0.1) rgba(0, 0, 0, 0.1) rgba(0, 0, 0, 0.25);
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#ff444444', endColorstr='#ff222222', GradientType=0);
  filter: progid:DXImageTransform.Microsoft.gradient(enabled=false);
}

.btn-inverse:hover,
.btn-inverse:focus,
.btn-inverse:active,
.btn-inverse.active,
.btn-inverse.disabled,
.btn-inverse[disabled] {
  color: #ffffff;
  background-color: #222222;
  *background-color: #151515;
}

.btn-inverse:active,
.btn-inverse.active {
  background-color: #080808 \9;
}

button.btn,
input[type="submit"].btn {
  *padding-top: 3px;
  *padding-bottom: 3px;
}

button.btn::-moz-focus-inner,
input[type="submit"].btn::-moz-focus-inner {
  padding: 0;
  border: 0;
}

button.btn.btn-large,
input[type="submit"].btn.btn-large {
  *padding-top: 7px;
  *padding-bottom: 7px;
}

button.btn.btn-small,
input[type="submit"].btn.btn-small {
  *padding-top: 3px;
  *padding-bottom: 3px;
}

button.btn.btn-mini,
input[type="submit"].btn.btn-mini {
  *padding-top: 1px;
  *padding-bottom: 1px;
}

.btn-link,
.btn-link:active,
.btn-link[disabled] {
  background-color: transparent;
  background-image: none;
  -webkit-box-shadow: none;
     -moz-box-shadow: none;
          box-shadow: none;
}

.btn-link {
  color: #0088cc;
  cursor: pointer;
  border-color: transparent;
  -webkit-border-radius: 0;
     -moz-border-radius: 0;
          border-radius: 0;
}

.btn-link:hover,
.btn-link:focus {
  color: #005580;
  text-decoration: underline;
  background-color: transparent;
}

.btn-link[disabled]:hover,
.btn-link[disabled]:focus {
  color: #333333;
  text-decoration: none;
}

.btn-group {
  position: relative;
  display: inline-block;
  *display: inline;
  *margin-left: .3em;
  font-size: 0;
  white-space: nowrap;
  vertical-align: middle;
  *zoom: 1;
}

.btn-group:first-child {
  *margin-left: 0;
}

.btn-group + .btn-group {
  margin-left: 5px;
}

.btn-toolbar {
  margin-top: 10px;
  margin-bottom: 10px;
  font-size: 0;
}

.btn-toolbar > .btn + .btn,
.btn-toolbar > .btn-group + .btn,
.btn-toolbar > .btn + .btn-group {
  margin-left: 5px;
}

.btn-group > .btn {
  position: relative;
  -webkit-border-radius: 0;
     -moz-border-radius: 0;
          border-radius: 0;
}

.btn-group > .btn + .btn {
  margin-left: -1px;
}

.btn-group > .btn,
.btn-group > .dropdown-menu,
.btn-group > .popover {
  font-size: 14px;
}

.btn-group > .btn-mini {
  font-size: 10.5px;
}

.btn-group > .btn-small {
  font-size: 11.9px;
}

.btn-group > .btn-large {
  font-size: 17.5px;
}

.btn-group > .btn:first-child {
  margin-left: 0;
  -webkit-border-bottom-left-radius: 4px;
          border-bottom-left-radius: 4px;
  -webkit-border-top-left-radius: 4px;
          border-top-left-radius: 4px;
  -moz-border-radius-bottomleft: 4px;
  -moz-border-radius-topleft: 4px;
}

.btn-group > .btn:last-child,
.btn-group > .dropdown-toggle {
  -webkit-border-top-right-radius: 4px;
          border-top-right-radius: 4px;
  -webkit-border-bottom-right-radius: 4px;
          border-bottom-right-radius: 4px;
  -moz-border-radius-topright: 4px;
  -moz-border-radius-bottomright: 4px;
}

.btn-group > .btn.large:first-child {
  margin-left: 0;
  -webkit-border-bottom-left-radius: 6px;
          border-bottom-left-radius: 6px;
  -webkit-border-top-left-radius: 6px;
          border-top-left-radius: 6px;
  -moz-border-radius-bottomleft: 6px;
  -moz-border-radius-topleft: 6px;
}

.btn-group > .btn.large:last-child,
.btn-group > .large.dropdown-toggle {
  -webkit-border-top-right-radius: 6px;
          border-top-right-radius: 6px;
  -webkit-border-bottom-right-radius: 6px;
          border-bottom-right-radius: 6px;
  -moz-border-radius-topright: 6px;
  -moz-border-radius-bottomright: 6px;
}

.btn-group > .btn:hover,
.btn-group > .btn:focus,
.btn-group > .btn:active,
.btn-group > .btn.active {
  z-index: 2;
}

.btn-group .dropdown-toggle:active,
.btn-group.open .dropdown-toggle {
  outline: 0;
}

.btn-group > .btn + .dropdown-toggle {
  *padding-top: 5px;
  padding-right: 8px;
  *padding-bottom: 5px;
  padding-left: 8px;
  -webkit-box-shadow: inset 1px 0 0 rgba(255, 255, 255, 0.125), inset 0 1px 0 rgba(255, 255, 255, 0.2), 0 1px 2px rgba(0, 0, 0, 0.05);
     -moz-box-shadow: inset 1px 0 0 rgba(255, 255, 255, 0.125), inset 0 1px 0 rgba(255, 255, 255, 0.2), 0 1px 2px rgba(0, 0, 0, 0.05);
          box-shadow: inset 1px 0 0 rgba(255, 255, 255, 0.125), inset 0 1px 0 rgba(255, 255, 255, 0.2), 0 1px 2px rgba(0, 0, 0, 0.05);
}

.btn-group > .btn-mini + .dropdown-toggle {
  *padding-top: 2px;
  padding-right: 5px;
  *padding-bottom: 2px;
  padding-left: 5px;
}

.btn-group > .btn-small + .dropdown-toggle {
  *padding-top: 5px;
  *padding-bottom: 4px;
}

.btn-group > .btn-large + .dropdown-toggle {
  *padding-top: 7px;
  padding-right: 12px;
  *padding-bottom: 7px;
  padding-left: 12px;
}

.btn-group.open .dropdown-toggle {
  background-image: none;
  -webkit-box-shadow: inset 0 2px 4px rgba(0, 0, 0, 0.15), 0 1px 2px rgba(0, 0, 0, 0.05);
     -moz-box-shadow: inset 0 2px 4px rgba(0, 0, 0, 0.15), 0 1px 2px rgba(0, 0, 0, 0.05);
          box-shadow: inset 0 2px 4px rgba(0, 0, 0, 0.15), 0 1px 2px rgba(0, 0, 0, 0.05);
}

.btn-group.open .btn.dropdown-toggle {
  background-color: #e6e6e6;
}

.btn-group.open .btn-primary.dropdown-toggle {
  background-color: #0044cc;
}

.btn-group.open .btn-warning.dropdown-toggle {
  background-color: #f89406;
}

.btn-group.open .btn-danger.dropdown-toggle {
  background-color: #bd362f;
}

.btn-group.open .btn-success.dropdown-toggle {
  background-color: #51a351;
}

.btn-group.open .btn-info.dropdown-toggle {
  background-color: #2f96b4;
}

.btn-group.open .btn-inverse.dropdown-toggle {
  background-color: #222222;
}

.btn .caret {
  margin-top: 8px;
  margin-left: 0;
}

.btn-large .caret {
  margin-top: 6px;
}

.btn-large .caret {
  border-top-width: 5px;
  border-right-width: 5px;
  border-left-width: 5px;
}

.btn-mini .caret,
.btn-small .caret {
  margin-top: 8px;
}

.dropup .btn-large .caret {
  border-bottom-width: 5px;
}

.btn-primary .caret,
.btn-warning .caret,
.btn-danger .caret,
.btn-info .caret,
.btn-success .caret,
.btn-inverse .caret {
  border-top-color: #ffffff;
  border-bottom-color: #ffffff;
}

.btn-group-vertical {
  display: inline-block;
  *display: inline;
  /* IE7 inline-block hack */

  *zoom: 1;
}

.btn-group-vertical > .btn {
  display: block;
  float: none;
  max-width: 100%;
  -webkit-border-radius: 0;
     -moz-border-radius: 0;
          border-radius: 0;
}

.btn-group-vertical > .btn + .btn {
  margin-top: -1px;
  margin-left: 0;
}

.btn-group-vertical > .btn:first-child {
  -webkit-border-radius: 4px 4px 0 0;
     -moz-border-radius: 4px 4px 0 0;
          border-radius: 4px 4px 0 0;
}

.btn-group-vertical > .btn:last-child {
  -webkit-border-radius: 0 0 4px 4px;
     -moz-border-radius: 0 0 4px 4px;
          border-radius: 0 0 4px 4px;
}

.btn-group-vertical > .btn-large:first-child {
  -webkit-border-radius: 6px 6px 0 0;
     -moz-border-radius: 6px 6px 0 0;
          border-radius: 6px 6px 0 0;
}

.btn-group-vertical > .btn-large:last-child {
  -webkit-border-radius: 0 0 6px 6px;
     -moz-border-radius: 0 0 6px 6px;
          border-radius: 0 0 6px 6px;
}

.alert {
  padding: 8px 35px 8px 14px;
  margin-bottom: 20px;
  text-shadow: 0 1px 0 rgba(255, 255, 255, 0.5);
  background-color: #fcf8e3;
  border: 1px solid #fbeed5;
  -webkit-border-radius: 4px;
     -moz-border-radius: 4px;
          border-radius: 4px;
}

.alert,
.alert h4 {
  color: #c09853;
}

.alert h4 {
  margin: 0;
}

.alert .close {
  position: relative;
  top: -2px;
  right: -21px;
  line-height: 20px;
}

.alert-success {
  color: #468847;
  background-color: #dff0d8;
  border-color: #d6e9c6;
}

.alert-success h4 {
  color: #468847;
}

.alert-danger,
.alert-error {
  color: #b94a48;
  background-color: #f2dede;
  border-color: #eed3d7;
}

.alert-danger h4,
.alert-error h4 {
  color: #b94a48;
}

.alert-info {
  color: #3a87ad;
  background-color: #d9edf7;
  border-color: #bce8f1;
}

.alert-info h4 {
  color: #3a87ad;
}

.alert-block {
  padding-top: 14px;
  padding-bottom: 14px;
}

.alert-block > p,
.alert-block > ul {
  margin-bottom: 0;
}

.alert-block p + p {
  margin-top: 5px;
}

.nav {
  margin-bottom: 20px;
  margin-left: 0;
  list-style: none;
}

.nav > li > a {
  display: block;
}

.nav > li > a:hover,
.nav > li > a:focus {
  text-decoration: none;
  background-color: #eeeeee;
}

.nav > li > a > img {
  max-width: none;
}

.nav > .pull-right {
  float: right;
}

.nav-header {
  display: block;
  padding: 3px 15px;
  font-size: 11px;
  font-weight: bold;
  line-height: 20px;
  color: #999999;
  text-shadow: 0 1px 0 rgba(255, 255, 255, 0.5);
  text-transform: uppercase;
}

.nav li + .nav-header {
  margin-top: 9px;
}

.nav-list {
  padding-right: 15px;
  padding-left: 15px;
  margin-bottom: 0;
}

.nav-list > li > a,
.nav-list .nav-header {
  margin-right: -15px;
  margin-left: -15px;
  text-shadow: 0 1px 0 rgba(255, 255, 255, 0.5);
}

.nav-list > li > a {
  padding: 3px 15px;
}

.nav-list > .active > a,
.nav-list > .active > a:hover,
.nav-list > .active > a:focus {
  color: #ffffff;
  text-shadow: 0 -1px 0 rgba(0, 0, 0, 0.2);
  background-color: #0088cc;
}

.nav-list [class^="icon-"],
.nav-list [class*=" icon-"] {
  margin-right: 2px;
}

.nav-list .divider {
  *width: 100%;
  height: 1px;
  margin: 9px 1px;
  *margin: -5px 0 5px;
  overflow: hidden;
  background-color: #e5e5e5;
  border-bottom: 1px solid #ffffff;
}

.nav-tabs,
.nav-pills {
  *zoom: 1;
}

.nav-tabs:before,
.nav-pills:before,
.nav-tabs:after,
.nav-pills:after {
  display: table;
  line-height: 0;
  content: "";
}

.nav-tabs:after,
.nav-pills:after {
  clear: both;
}

.nav-tabs > li,
.nav-pills > li {
  float: left;
}

.nav-tabs > li > a,
.nav-pills > li > a {
  padding-right: 12px;
  padding-left: 12px;
  margin-right: 2px;
  line-height: 14px;
}

.nav-tabs {
  border-bottom: 1px solid #ddd;
}

.nav-tabs > li {
  margin-bottom: -1px;
}

.nav-tabs > li > a {
  padding-top: 8px;
  padding-bottom: 8px;
  line-height: 20px;
  border: 1px solid transparent;
  -webkit-border-radius: 4px 4px 0 0;
     -moz-border-radius: 4px 4px 0 0;
          border-radius: 4px 4px 0 0;
}

.nav-tabs > li > a:hover,
.nav-tabs > li > a:focus {
  border-color: #eeeeee #eeeeee #dddddd;
}

.nav-tabs > .active > a,
.nav-tabs > .active > a:hover,
.nav-tabs > .active > a:focus {
  color: #555555;
  cursor: default;
  background-color: #ffffff;
  border: 1px solid #ddd;
  border-bottom-color: transparent;
}

.nav-pills > li > a {
  padding-top: 8px;
  padding-bottom: 8px;
  margin-top: 2px;
  margin-bottom: 2px;
  -webkit-border-radius: 5px;
     -moz-border-radius: 5px;
          border-radius: 5px;
}

.nav-pills > .active > a,
.nav-pills > .active > a:hover,
.nav-pills > .active > a:focus {
  color: #ffffff;
  background-color: #0088cc;
}

.nav-stacked > li {
  float: none;
}

.nav-stacked > li > a {
  margin-right: 0;
}

.nav-tabs.nav-stacked {
  border-bottom: 0;
}

.nav-tabs.nav-stacked > li > a {
  border: 1px solid #ddd;
  -webkit-border-radius: 0;
     -moz-border-radius: 0;
          border-radius: 0;
}

.nav-tabs.nav-stacked > li:first-child > a {
  -webkit-border-top-right-radius: 4px;
          border-top-right-radius: 4px;
  -webkit-border-top-left-radius: 4px;
          border-top-left-radius: 4px;
  -moz-border-radius-topright: 4px;
  -moz-border-radius-topleft: 4px;
}

.nav-tabs.nav-stacked > li:last-child > a {
  -webkit-border-bottom-right-radius: 4px;
          border-bottom-right-radius: 4px;
  -webkit-border-bottom-left-radius: 4px;
          border-bottom-left-radius: 4px;
  -moz-border-radius-bottomright: 4px;
  -moz-border-radius-bottomleft: 4px;
}

.nav-tabs.nav-stacked > li > a:hover,
.nav-tabs.nav-stacked > li > a:focus {
  z-index: 2;
  border-color: #ddd;
}

.nav-pills.nav-stacked > li > a {
  margin-bottom: 3px;
}

.nav-pills.nav-stacked > li:last-child > a {
  margin-bottom: 1px;
}

.nav-tabs .dropdown-menu {
  -webkit-border-radius: 0 0 6px 6px;
     -moz-border-radius: 0 0 6px 6px;
          border-radius: 0 0 6px 6px;
}

.nav-pills .dropdown-menu {
  -webkit-border-radius: 6px;
     -moz-border-radius: 6px;
          border-radius: 6px;
}

.nav .dropdown-toggle .caret {
  margin-top: 6px;
  border-top-color: #0088cc;
  border-bottom-color: #0088cc;
}

.nav .dropdown-toggle:hover .caret,
.nav .dropdown-toggle:focus .caret {
  border-top-color: #005580;
  border-bottom-color: #005580;
}

/* move down carets for tabs */

.nav-tabs .dropdown-toggle .caret {
  margin-top: 8px;
}

.nav .active .dropdown-toggle .caret {
  border-top-color: #fff;
  border-bottom-color: #fff;
}

.nav-tabs .active .dropdown-toggle .caret {
  border-top-color: #555555;
  border-bottom-color: #555555;
}

.nav > .dropdown.active > a:hover,
.nav > .dropdown.active > a:focus {
  cursor: pointer;
}

.nav-tabs .open .dropdown-toggle,
.nav-pills .open .dropdown-toggle,
.nav > li.dropdown.open.active > a:hover,
.nav > li.dropdown.open.active > a:focus {
  color: #ffffff;
  background-color: #999999;
  border-color: #999999;
}

.nav li.dropdown.open .caret,
.nav li.dropdown.open.active .caret,
.nav li.dropdown.open a:hover .caret,
.nav li.dropdown.open a:focus .caret {
  border-top-color: #ffffff;
  border-bottom-color: #ffffff;
  opacity: 1;
  filter: alpha(opacity=100);
}

.tabs-stacked .open > a:hover,
.tabs-stacked .open > a:focus {
  border-color: #999999;
}

.tabbable {
  *zoom: 1;
}

.tabbable:before,
.tabbable:after {
  display: table;
  line-height: 0;
  content: "";
}

.tabbable:after {
  clear: both;
}

.tab-content {
  overflow: auto;
}

.tabs-below > .nav-tabs,
.tabs-right > .nav-tabs,
.tabs-left > .nav-tabs {
  border-bottom: 0;
}

.tab-content > .tab-pane,
.pill-content > .pill-pane {
  display: none;
}

.tab-content > .active,
.pill-content > .active {
  display: block;
}

.tabs-below > .nav-tabs {
  border-top: 1px solid #ddd;
}

.tabs-below > .nav-tabs > li {
  margin-top: -1px;
  margin-bottom: 0;
}

.tabs-below > .nav-tabs > li > a {
  -webkit-border-radius: 0 0 4px 4px;
     -moz-border-radius: 0 0 4px 4px;
          border-radius: 0 0 4px 4px;
}

.tabs-below > .nav-tabs > li > a:hover,
.tabs-below > .nav-tabs > li > a:focus {
  border-top-color: #ddd;
  border-bottom-color: transparent;
}

.tabs-below > .nav-tabs > .active > a,
.tabs-below > .nav-tabs > .active > a:hover,
.tabs-below > .nav-tabs > .active > a:focus {
  border-color: transparent #ddd #ddd #ddd;
}

.tabs-left > .nav-tabs > li,
.tabs-right > .nav-tabs > li {
  float: none;
}

.tabs-left > .nav-tabs > li > a,
.tabs-right > .nav-tabs > li > a {
  min-width: 74px;
  margin-right: 0;
  margin-bottom: 3px;
}

.tabs-left > .nav-tabs {
  float: left;
  margin-right: 19px;
  border-right: 1px solid #ddd;
}

.tabs-left > .nav-tabs > li > a {
  margin-right: -1px;
  -webkit-border-radius: 4px 0 0 4px;
     -moz-border-radius: 4px 0 0 4px;
          border-radius: 4px 0 0 4px;
}

.tabs-left > .nav-tabs > li > a:hover,
.tabs-left > .nav-tabs > li > a:focus {
  border-color: #eeeeee #dddddd #eeeeee #eeeeee;
}

.tabs-left > .nav-tabs .active > a,
.tabs-left > .nav-tabs .active > a:hover,
.tabs-left > .nav-tabs .active > a:focus {
  border-color: #ddd transparent #ddd #ddd;
  *border-right-color: #ffffff;
}

.tabs-right > .nav-tabs {
  float: right;
  margin-left: 19px;
  border-left: 1px solid #ddd;
}

.tabs-right > .nav-tabs > li > a {
  margin-left: -1px;
  -webkit-border-radius: 0 4px 4px 0;
     -moz-border-radius: 0 4px 4px 0;
          border-radius: 0 4px 4px 0;
}

.tabs-right > .nav-tabs > li > a:hover,
.tabs-right > .nav-tabs > li > a:focus {
  border-color: #eeeeee #eeeeee #eeeeee #dddddd;
}

.tabs-right > .nav-tabs .active > a,
.tabs-right > .nav-tabs .active > a:hover,
.tabs-right > .nav-tabs .active > a:focus {
  border-color: #ddd #ddd #ddd transparent;
  *border-left-color: #ffffff;
}

.nav > .disabled > a {
  color: #999999;
}

.nav > .disabled > a:hover,
.nav > .disabled > a:focus {
  text-decoration: none;
  cursor: default;
  background-color: transparent;
}

.navbar {
  *position: relative;
  *z-index: 2;
  margin-bottom: 20px;
  overflow: visible;
}

.navbar-inner {
  min-height: 40px;
  padding-right: 20px;
  padding-left: 20px;
  background-color: #fafafa;
  background-image: -moz-linear-gradient(top, #ffffff, #f2f2f2);
  background-image: -webkit-gradient(linear, 0 0, 0 100%, from(#ffffff), to(#f2f2f2));
  background-image: -webkit-linear-gradient(top, #ffffff, #f2f2f2);
  background-image: -o-linear-gradient(top, #ffffff, #f2f2f2);
  background-image: linear-gradient(to bottom, #ffffff, #f2f2f2);
  background-repeat: repeat-x;
  border: 1px solid #d4d4d4;
  -webkit-border-radius: 4px;
     -moz-border-radius: 4px;
          border-radius: 4px;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#ffffffff', endColorstr='#fff2f2f2', GradientType=0);
  *zoom: 1;
  -webkit-box-shadow: 0 1px 4px rgba(0, 0, 0, 0.065);
     -moz-box-shadow: 0 1px 4px rgba(0, 0, 0, 0.065);
          box-shadow: 0 1px 4px rgba(0, 0, 0, 0.065);
}

.navbar-inner:before,
.navbar-inner:after {
  display: table;
  line-height: 0;
  content: "";
}

.navbar-inner:after {
  clear: both;
}

.navbar .container {
  width: auto;
}

.nav-collapse.collapse {
  height: auto;
  overflow: visible;
}

.navbar .brand {
  display: block;
  float: left;
  padding: 10px 20px 10px;
  margin-left: -20px;
  font-size: 20px;
  font-weight: 200;
  color: #777777;
  text-shadow: 0 1px 0 #ffffff;
}

.navbar .brand:hover,
.navbar .brand:focus {
  text-decoration: none;
}

.navbar-text {
  margin-bottom: 0;
  line-height: 40px;
  color: #777777;
}

.navbar-link {
  color: #777777;
}

.navbar-link:hover,
.navbar-link:focus {
  color: #333333;
}

.navbar .divider-vertical {
  height: 40px;
  margin: 0 9px;
  border-right: 1px solid #ffffff;
  border-left: 1px solid #f2f2f2;
}

.navbar .btn,
.navbar .btn-group {
  margin-top: 5px;
}

.navbar .btn-group .btn,
.navbar .input-prepend .btn,
.navbar .input-append .btn,
.navbar .input-prepend .btn-group,
.navbar .input-append .btn-group {
  margin-top: 0;
}

.navbar-form {
  margin-bottom: 0;
  *zoom: 1;
}

.navbar-form:before,
.navbar-form:after {
  display: table;
  line-height: 0;
  content: "";
}

.navbar-form:after {
  clear: both;
}

.navbar-form input,
.navbar-form select,
.navbar-form .radio,
.navbar-form .checkbox {
  margin-top: 5px;
}

.navbar-form input,
.navbar-form select,
.navbar-form .btn {
  display: inline-block;
  margin-bottom: 0;
}

.navbar-form input[type="image"],
.navbar-form input[type="checkbox"],
.navbar-form input[type="radio"] {
  margin-top: 3px;
}

.navbar-form .input-append,
.navbar-form .input-prepend {
  margin-top: 5px;
  white-space: nowrap;
}

.navbar-form .input-append input,
.navbar-form .input-prepend input {
  margin-top: 0;
}

.navbar-search {
  position: relative;
  float: left;
  margin-top: 5px;
  margin-bottom: 0;
}

.navbar-search .search-query {
  padding: 4px 14px;
  margin-bottom: 0;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-size: 13px;
  font-weight: normal;
  line-height: 1;
  -webkit-border-radius: 15px;
     -moz-border-radius: 15px;
          border-radius: 15px;
}

.navbar-static-top {
  position: static;
  margin-bottom: 0;
}

.navbar-static-top .navbar-inner {
  -webkit-border-radius: 0;
     -moz-border-radius: 0;
          border-radius: 0;
}

.navbar-fixed-top,
.navbar-fixed-bottom {
  position: fixed;
  right: 0;
  left: 0;
  z-index: 1030;
  margin-bottom: 0;
}

.navbar-fixed-top .navbar-inner,
.navbar-static-top .navbar-inner {
  border-width: 0 0 1px;
}

.navbar-fixed-bottom .navbar-inner {
  border-width: 1px 0 0;
}

.navbar-fixed-top .navbar-inner,
.navbar-fixed-bottom .navbar-inner {
  padding-right: 0;
  padding-left: 0;
  -webkit-border-radius: 0;
     -moz-border-radius: 0;
          border-radius: 0;
}

.navbar-static-top .container,
.navbar-fixed-top .container,
.navbar-fixed-bottom .container {
  width: 940px;
}

.navbar-fixed-top {
  top: 0;
}

.navbar-fixed-top .navbar-inner,
.navbar-static-top .navbar-inner {
  -webkit-box-shadow: 0 1px 10px rgba(0, 0, 0, 0.1);
     -moz-box-shadow: 0 1px 10px rgba(0, 0, 0, 0.1);
          box-shadow: 0 1px 10px rgba(0, 0, 0, 0.1);
}

.navbar-fixed-bottom {
  bottom: 0;
}

.navbar-fixed-bottom .navbar-inner {
  -webkit-box-shadow: 0 -1px 10px rgba(0, 0, 0, 0.1);
     -moz-box-shadow: 0 -1px 10px rgba(0, 0, 0, 0.1);
          box-shadow: 0 -1px 10px rgba(0, 0, 0, 0.1);
}

.navbar .nav {
  position: relative;
  left: 0;
  display: block;
  float: left;
  margin: 0 10px 0 0;
}

.navbar .nav.pull-right {
  float: right;
  margin-right: 0;
}

.navbar .nav > li {
  float: left;
}

.navbar .nav > li > a {
  float: none;
  padding: 10px 15px 10px;
  color: #777777;
  text-decoration: none;
  text-shadow: 0 1px 0 #ffffff;
}

.navbar .nav .dropdown-toggle .caret {
  margin-top: 8px;
}

.navbar .nav > li > a:focus,
.navbar .nav > li > a:hover {
  color: #333333;
  text-decoration: none;
  background-color: transparent;
}

.navbar .nav > .active > a,
.navbar .nav > .active > a:hover,
.navbar .nav > .active > a:focus {
  color: #555555;
  text-decoration: none;
  background-color: #e5e5e5;
  -webkit-box-shadow: inset 0 3px 8px rgba(0, 0, 0, 0.125);
     -moz-box-shadow: inset 0 3px 8px rgba(0, 0, 0, 0.125);
          box-shadow: inset 0 3px 8px rgba(0, 0, 0, 0.125);
}

.navbar .btn-navbar {
  display: none;
  float: right;
  padding: 7px 10px;
  margin-right: 5px;
  margin-left: 5px;
  color: #ffffff;
  text-shadow: 0 -1px 0 rgba(0, 0, 0, 0.25);
  background-color: #ededed;
  *background-color: #e5e5e5;
  background-image: -moz-linear-gradient(top, #f2f2f2, #e5e5e5);
  background-image: -webkit-gradient(linear, 0 0, 0 100%, from(#f2f2f2), to(#e5e5e5));
  background-image: -webkit-linear-gradient(top, #f2f2f2, #e5e5e5);
  background-image: -o-linear-gradient(top, #f2f2f2, #e5e5e5);
  background-image: linear-gradient(to bottom, #f2f2f2, #e5e5e5);
  background-repeat: repeat-x;
  border-color: #e5e5e5 #e5e5e5 #bfbfbf;
  border-color: rgba(0, 0, 0, 0.1) rgba(0, 0, 0, 0.1) rgba(0, 0, 0, 0.25);
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#fff2f2f2', endColorstr='#ffe5e5e5', GradientType=0);
  filter: progid:DXImageTransform.Microsoft.gradient(enabled=false);
  -webkit-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.075);
     -moz-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.075);
          box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.075);
}

.navbar .btn-navbar:hover,
.navbar .btn-navbar:focus,
.navbar .btn-navbar:active,
.navbar .btn-navbar.active,
.navbar .btn-navbar.disabled,
.navbar .btn-navbar[disabled] {
  color: #ffffff;
  background-color: #e5e5e5;
  *background-color: #d9d9d9;
}

.navbar .btn-navbar:active,
.navbar .btn-navbar.active {
  background-color: #cccccc \9;
}

.navbar .btn-navbar .icon-bar {
  display: block;
  width: 18px;
  height: 2px;
  background-color: #f5f5f5;
  -webkit-border-radius: 1px;
     -moz-border-radius: 1px;
          border-radius: 1px;
  -webkit-box-shadow: 0 1px 0 rgba(0, 0, 0, 0.25);
     -moz-box-shadow: 0 1px 0 rgba(0, 0, 0, 0.25);
          box-shadow: 0 1px 0 rgba(0, 0, 0, 0.25);
}

.btn-navbar .icon-bar + .icon-bar {
  margin-top: 3px;
}

.navbar .nav > li > .dropdown-menu:before {
  position: absolute;
  top: -7px;
  left: 9px;
  display: inline-block;
  border-right: 7px solid transparent;
  border-bottom: 7px solid #ccc;
  border-left: 7px solid transparent;
  border-bottom-color: rgba(0, 0, 0, 0.2);
  content: '';
}

.navbar .nav > li > .dropdown-menu:after {
  position: absolute;
  top: -6px;
  left: 10px;
  display: inline-block;
  border-right: 6px solid transparent;
  border-bottom: 6px solid #ffffff;
  border-left: 6px solid transparent;
  content: '';
}

.navbar-fixed-bottom .nav > li > .dropdown-menu:before {
  top: auto;
  bottom: -7px;
  border-top: 7px solid #ccc;
  border-bottom: 0;
  border-top-color: rgba(0, 0, 0, 0.2);
}

.navbar-fixed-bottom .nav > li > .dropdown-menu:after {
  top: auto;
  bottom: -6px;
  border-top: 6px solid #ffffff;
  border-bottom: 0;
}

.navbar .nav li.dropdown > a:hover .caret,
.navbar .nav li.dropdown > a:focus .caret {
  border-top-color: #333333;
  border-bottom-color: #333333;
}

.navbar .nav li.dropdown.open > .dropdown-toggle,
.navbar .nav li.dropdown.active > .dropdown-toggle,
.navbar .nav li.dropdown.open.active > .dropdown-toggle {
  color: #555555;
  background-color: #e5e5e5;
}

.navbar .nav li.dropdown > .dropdown-toggle .caret {
  border-top-color: #777777;
  border-bottom-color: #777777;
}

.navbar .nav li.dropdown.open > .dropdown-toggle .caret,
.navbar .nav li.dropdown.active > .dropdown-toggle .caret,
.navbar .nav li.dropdown.open.active > .dropdown-toggle .caret {
  border-top-color: #555555;
  border-bottom-color: #555555;
}

.navbar .pull-right > li > .dropdown-menu,
.navbar .nav > li > .dropdown-menu.pull-right {
  right: 0;
  left: auto;
}

.navbar .pull-right > li > .dropdown-menu:before,
.navbar .nav > li > .dropdown-menu.pull-right:before {
  right: 12px;
  left: auto;
}

.navbar .pull-right > li > .dropdown-menu:after,
.navbar .nav > li > .dropdown-menu.pull-right:after {
  right: 13px;
  left: auto;
}

.navbar .pull-right > li > .dropdown-menu .dropdown-menu,
.navbar .nav > li > .dropdown-menu.pull-right .dropdown-menu {
  right: 100%;
  left: auto;
  margin-right: -1px;
  margin-left: 0;
  -webkit-border-radius: 6px 0 6px 6px;
     -moz-border-radius: 6px 0 6px 6px;
          border-radius: 6px 0 6px 6px;
}

.navbar-inverse .navbar-inner {
  background-color: #1b1b1b;
  background-image: -moz-linear-gradient(top, #222222, #111111);
  background-image: -webkit-gradient(linear, 0 0, 0 100%, from(#222222), to(#111111));
  background-image: -webkit-linear-gradient(top, #222222, #111111);
  background-image: -o-linear-gradient(top, #222222, #111111);
  background-image: linear-gradient(to bottom, #222222, #111111);
  background-repeat: repeat-x;
  border-color: #252525;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#ff222222', endColorstr='#ff111111', GradientType=0);
}

.navbar-inverse .brand,
.navbar-inverse .nav > li > a {
  color: #999999;
  text-shadow: 0 -1px 0 rgba(0, 0, 0, 0.25);
}

.navbar-inverse .brand:hover,
.navbar-inverse .nav > li > a:hover,
.navbar-inverse .brand:focus,
.navbar-inverse .nav > li > a:focus {
  color: #ffffff;
}

.navbar-inverse .brand {
  color: #999999;
}

.navbar-inverse .navbar-text {
  color: #999999;
}

.navbar-inverse .nav > li > a:focus,
.navbar-inverse .nav > li > a:hover {
  color: #ffffff;
  background-color: transparent;
}

.navbar-inverse .nav .active > a,
.navbar-inverse .nav .active > a:hover,
.navbar-inverse .nav .active > a:focus {
  color: #ffffff;
  background-color: #111111;
}

.navbar-inverse .navbar-link {
  color: #999999;
}

.navbar-inverse .navbar-link:hover,
.navbar-inverse .navbar-link:focus {
  color: #ffffff;
}

.navbar-inverse .divider-vertical {
  border-right-color: #222222;
  border-left-color: #111111;
}

.navbar-inverse .nav li.dropdown.open > .dropdown-toggle,
.navbar-inverse .nav li.dropdown.active > .dropdown-toggle,
.navbar-inverse .nav li.dropdown.open.active > .dropdown-toggle {
  color: #ffffff;
  background-color: #111111;
}

.navbar-inverse .nav li.dropdown > a:hover .caret,
.navbar-inverse .nav li.dropdown > a:focus .caret {
  border-top-color: #ffffff;
  border-bottom-color: #ffffff;
}

.navbar-inverse .nav li.dropdown > .dropdown-toggle .caret {
  border-top-color: #999999;
  border-bottom-color: #999999;
}

.navbar-inverse .nav li.dropdown.open > .dropdown-toggle .caret,
.navbar-inverse .nav li.dropdown.active > .dropdown-toggle .caret,
.navbar-inverse .nav li.dropdown.open.active > .dropdown-toggle .caret {
  border-top-color: #ffffff;
  border-bottom-color: #ffffff;
}

.navbar-inverse .navbar-search .search-query {
  color: #ffffff;
  background-color: #515151;
  border-color: #111111;
  -webkit-box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1), 0 1px 0 rgba(255, 255, 255, 0.15);
     -moz-box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1), 0 1px 0 rgba(255, 255, 255, 0.15);
          box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1), 0 1px 0 rgba(255, 255, 255, 0.15);
  -webkit-transition: none;
     -moz-transition: none;
       -o-transition: none;
          transition: none;
}

.navbar-inverse .navbar-search .search-query:-moz-placeholder {
  color: #cccccc;
}

.navbar-inverse .navbar-search .search-query:-ms-input-placeholder {
  color: #cccccc;
}

.navbar-inverse .navbar-search .search-query::-webkit-input-placeholder {
  color: #cccccc;
}

.navbar-inverse .navbar-search .search-query:focus,
.navbar-inverse .navbar-search .search-query.focused {
  padding: 5px 15px;
  color: #333333;
  text-shadow: 0 1px 0 #ffffff;
  background-color: #ffffff;
  border: 0;
  outline: 0;
  -webkit-box-shadow: 0 0 3px rgba(0, 0, 0, 0.15);
     -moz-box-shadow: 0 0 3px rgba(0, 0, 0, 0.15);
          box-shadow: 0 0 3px rgba(0, 0, 0, 0.15);
}

.navbar-inverse .btn-navbar {
  color: #ffffff;
  text-shadow: 0 -1px 0 rgba(0, 0, 0, 0.25);
  background-color: #0e0e0e;
  *background-color: #040404;
  background-image: -moz-linear-gradient(top, #151515, #040404);
  background-image: -webkit-gradient(linear, 0 0, 0 100%, from(#151515), to(#040404));
  background-image: -webkit-linear-gradient(top, #151515, #040404);
  background-image: -o-linear-gradient(top, #151515, #040404);
  background-image: linear-gradient(to bottom, #151515, #040404);
  background-repeat: repeat-x;
  border-color: #040404 #040404 #000000;
  border-color: rgba(0, 0, 0, 0.1) rgba(0, 0, 0, 0.1) rgba(0, 0, 0, 0.25);
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#ff151515', endColorstr='#ff040404', GradientType=0);
  filter: progid:DXImageTransform.Microsoft.gradient(enabled=false);
}

.navbar-inverse .btn-navbar:hover,
.navbar-inverse .btn-navbar:focus,
.navbar-inverse .btn-navbar:active,
.navbar-inverse .btn-navbar.active,
.navbar-inverse .btn-navbar.disabled,
.navbar-inverse .btn-navbar[disabled] {
  color: #ffffff;
  background-color: #040404;
  *background-color: #000000;
}

.navbar-inverse .btn-navbar:active,
.navbar-inverse .btn-navbar.active {
  background-color: #000000 \9;
}

.breadcrumb {
  padding: 8px 15px;
  margin: 0 0 20px;
  list-style: none;
  background-color: #f5f5f5;
  -webkit-border-radius: 4px;
     -moz-border-radius: 4px;
          border-radius: 4px;
}

.breadcrumb > li {
  display: inline-block;
  *display: inline;
  text-shadow: 0 1px 0 #ffffff;
  *zoom: 1;
}

.breadcrumb > li > .divider {
  padding: 0 5px;
  color: #ccc;
}

.breadcrumb > .active {
  color: #999999;
}

.pagination {
  margin: 20px 0;
}

.pagination ul {
  display: inline-block;
  *display: inline;
  margin-bottom: 0;
  margin-left: 0;
  -webkit-border-radius: 4px;
     -moz-border-radius: 4px;
          border-radius: 4px;
  *zoom: 1;
  -webkit-box-shadow: 0 1px 2px rgba(0, 0, 0, 0.05);
     -moz-box-shadow: 0 1px 2px rgba(0, 0, 0, 0.05);
          box-shadow: 0 1px 2px rgba(0, 0, 0, 0.05);
}

.pagination ul > li {
  display: inline;
}

.pagination ul > li > a,
.pagination ul > li > span {
  float: left;
  padding: 4px 12px;
  line-height: 20px;
  text-decoration: none;
  background-color: #ffffff;
  border: 1px solid #dddddd;
  border-left-width: 0;
}

.pagination ul > li > a:hover,
.pagination ul > li > a:focus,
.pagination ul > .active > a,
.pagination ul > .active > span {
  background-color: #f5f5f5;
}

.pagination ul > .active > a,
.pagination ul > .active > span {
  color: #999999;
  cursor: default;
}

.pagination ul > .disabled > span,
.pagination ul > .disabled > a,
.pagination ul > .disabled > a:hover,
.pagination ul > .disabled > a:focus {
  color: #999999;
  cursor: default;
  background-color: transparent;
}

.pagination ul > li:first-child > a,
.pagination ul > li:first-child > span {
  border-left-width: 1px;
  -webkit-border-bottom-left-radius: 4px;
          border-bottom-left-radius: 4px;
  -webkit-border-top-left-radius: 4px;
          border-top-left-radius: 4px;
  -moz-border-radius-bottomleft: 4px;
  -moz-border-radius-topleft: 4px;
}

.pagination ul > li:last-child > a,
.pagination ul > li:last-child > span {
  -webkit-border-top-right-radius: 4px;
          border-top-right-radius: 4px;
  -webkit-border-bottom-right-radius: 4px;
          border-bottom-right-radius: 4px;
  -moz-border-radius-topright: 4px;
  -moz-border-radius-bottomright: 4px;
}

.pagination-centered {
  text-align: center;
}

.pagination-right {
  text-align: right;
}

.pagination-large ul > li > a,
.pagination-large ul > li > span {
  padding: 11px 19px;
  font-size: 17.5px;
}

.pagination-large ul > li:first-child > a,
.pagination-large ul > li:first-child > span {
  -webkit-border-bottom-left-radius: 6px;
          border-bottom-left-radius: 6px;
  -webkit-border-top-left-radius: 6px;
          border-top-left-radius: 6px;
  -moz-border-radius-bottomleft: 6px;
  -moz-border-radius-topleft: 6px;
}

.pagination-large ul > li:last-child > a,
.pagination-large ul > li:last-child > span {
  -webkit-border-top-right-radius: 6px;
          border-top-right-radius: 6px;
  -webkit-border-bottom-right-radius: 6px;
          border-bottom-right-radius: 6px;
  -moz-border-radius-topright: 6px;
  -moz-border-radius-bottomright: 6px;
}

.pagination-mini ul > li:first-child > a,
.pagination-small ul > li:first-child > a,
.pagination-mini ul > li:first-child > span,
.pagination-small ul > li:first-child > span {
  -webkit-border-bottom-left-radius: 3px;
          border-bottom-left-radius: 3px;
  -webkit-border-top-left-radius: 3px;
          border-top-left-radius: 3px;
  -moz-border-radius-bottomleft: 3px;
  -moz-border-radius-topleft: 3px;
}

.pagination-mini ul > li:last-child > a,
.pagination-small ul > li:last-child > a,
.pagination-mini ul > li:last-child > span,
.pagination-small ul > li:last-child > span {
  -webkit-border-top-right-radius: 3px;
          border-top-right-radius: 3px;
  -webkit-border-bottom-right-radius: 3px;
          border-bottom-right-radius: 3px;
  -moz-border-radius-topright: 3px;
  -moz-border-radius-bottomright: 3px;
}

.pagination-small ul > li > a,
.pagination-small ul > li > span {
  padding: 2px 10px;
  font-size: 11.9px;
}

.pagination-mini ul > li > a,
.pagination-mini ul > li > span {
  padding: 0 6px;
  font-size: 10.5px;
}

.pager {
  margin: 20px 0;
  text-align: center;
  list-style: none;
  *zoom: 1;
}

.pager:before,
.pager:after {
  display: table;
  line-height: 0;
  content: "";
}

.pager:after {
  clear: both;
}

.pager li {
  display: inline;
}

.pager li > a,
.pager li > span {
  display: inline-block;
  padding: 5px 14px;
  background-color: #fff;
  border: 1px solid #ddd;
  -webkit-border-radius: 15px;
     -moz-border-radius: 15px;
          border-radius: 15px;
}

.pager li > a:hover,
.pager li > a:focus {
  text-decoration: none;
  background-color: #f5f5f5;
}

.pager .next > a,
.pager .next > span {
  float: right;
}

.pager .previous > a,
.pager .previous > span {
  float: left;
}

.pager .disabled > a,
.pager .disabled > a:hover,
.pager .disabled > a:focus,
.pager .disabled > span {
  color: #999999;
  cursor: default;
  background-color: #fff;
}

.modal-backdrop {
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1040;
  background-color: #000000;
}

.modal-backdrop.fade {
  opacity: 0;
}

.modal-backdrop,
.modal-backdrop.fade.in {
  opacity: 0.8;
  filter: alpha(opacity=80);
}

.modal {
  position: fixed;
  top: 10%;
  left: 50%;
  z-index: 1050;
  width: 560px;
  margin-left: -280px;
  background-color: #ffffff;
  border: 1px solid #999;
  border: 1px solid rgba(0, 0, 0, 0.3);
  *border: 1px solid #999;
  -webkit-border-radius: 6px;
     -moz-border-radius: 6px;
          border-radius: 6px;
  outline: none;
  -webkit-box-shadow: 0 3px 7px rgba(0, 0, 0, 0.3);
     -moz-box-shadow: 0 3px 7px rgba(0, 0, 0, 0.3);
          box-shadow: 0 3px 7px rgba(0, 0, 0, 0.3);
  -webkit-background-clip: padding-box;
     -moz-background-clip: padding-box;
          background-clip: padding-box;
}

.modal.fade {
  top: -25%;
  -webkit-transition: opacity 0.3s linear, top 0.3s ease-out;
     -moz-transition: opacity 0.3s linear, top 0.3s ease-out;
       -o-transition: opacity 0.3s linear, top 0.3s ease-out;
          transition: opacity 0.3s linear, top 0.3s ease-out;
}

.modal.fade.in {
  top: 10%;
}

.modal-header {
  padding: 9px 15px;
  border-bottom: 1px solid #eee;
}

.modal-header .close {
  margin-top: 2px;
}

.modal-header h3 {
  margin: 0;
  line-height: 30px;
}

.modal-body {
  position: relative;
  max-height: 400px;
  padding: 15px;
  overflow-y: auto;
}

.modal-form {
  margin-bottom: 0;
}

.modal-footer {
  padding: 14px 15px 15px;
  margin-bottom: 0;
  text-align: right;
  background-color: #f5f5f5;
  border-top: 1px solid #ddd;
  -webkit-border-radius: 0 0 6px 6px;
     -moz-border-radius: 0 0 6px 6px;
          border-radius: 0 0 6px 6px;
  *zoom: 1;
  -webkit-box-shadow: inset 0 1px 0 #ffffff;
     -moz-box-shadow: inset 0 1px 0 #ffffff;
          box-shadow: inset 0 1px 0 #ffffff;
}

.modal-footer:before,
.modal-footer:after {
  display: table;
  line-height: 0;
  content: "";
}

.modal-footer:after {
  clear: both;
}

.modal-footer .btn + .btn {
  margin-bottom: 0;
  margin-left: 5px;
}

.modal-footer .btn-group .btn + .btn {
  margin-left: -1px;
}

.modal-footer .btn-block + .btn-block {
  margin-left: 0;
}

.tooltip {
  position: absolute;
  z-index: 1030;
  display: block;
  font-size: 11px;
  line-height: 1.4;
  opacity: 0;
  filter: alpha(opacity=0);
  visibility: visible;
}

.tooltip.in {
  opacity: 0.8;
  filter: alpha(opacity=80);
}

.tooltip.top {
  padding: 5px 0;
  margin-top: -3px;
}

.tooltip.right {
  padding: 0 5px;
  margin-left: 3px;
}

.tooltip.bottom {
  padding: 5px 0;
  margin-top: 3px;
}

.tooltip.left {
  padding: 0 5px;
  margin-left: -3px;
}

.tooltip-inner {
  max-width: 200px;
  padding: 8px;
  color: #ffffff;
  text-align: center;
  text-decoration: none;
  background-color: #000000;
  -webkit-border-radius: 4px;
     -moz-border-radius: 4px;
          border-radius: 4px;
}

.tooltip-arrow {
  position: absolute;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}

.tooltip.top .tooltip-arrow {
  bottom: 0;
  left: 50%;
  margin-left: -5px;
  border-top-color: #000000;
  border-width: 5px 5px 0;
}

.tooltip.right .tooltip-arrow {
  top: 50%;
  left: 0;
  margin-top: -5px;
  border-right-color: #000000;
  border-width: 5px 5px 5px 0;
}

.tooltip.left .tooltip-arrow {
  top: 50%;
  right: 0;
  margin-top: -5px;
  border-left-color: #000000;
  border-width: 5px 0 5px 5px;
}

.tooltip.bottom .tooltip-arrow {
  top: 0;
  left: 50%;
  margin-left: -5px;
  border-bottom-color: #000000;
  border-width: 0 5px 5px;
}

.popover {
  position: absolute;
  top: 0;
  left: 0;
  z-index: 1010;
  display: none;
  max-width: 276px;
  padding: 1px;
  text-align: left;
  white-space: normal;
  background-color: #ffffff;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.2);
  -webkit-border-radius: 6px;
     -moz-border-radius: 6px;
          border-radius: 6px;
  -webkit-box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
     -moz-box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
          box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
  -webkit-background-clip: padding-box;
     -moz-background-clip: padding;
          background-clip: padding-box;
}

.popover.top {
  margin-top: -10px;
}

.popover.right {
  margin-left: 10px;
}

.popover.bottom {
  margin-top: 10px;
}

.popover.left {
  margin-left: -10px;
}

.popover-title {
  padding: 8px 14px;
  margin: 0;
  font-size: 14px;
  font-weight: normal;
  line-height: 18px;
  background-color: #f7f7f7;
  border-bottom: 1px solid #ebebeb;
  -webkit-border-radius: 5px 5px 0 0;
     -moz-border-radius: 5px 5px 0 0;
          border-radius: 5px 5px 0 0;
}

.popover-title:empty {
  display: none;
}

.popover-content {
  padding: 9px 14px;
}

.popover .arrow,
.popover .arrow:after {
  position: absolute;
  display: block;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}

.popover .arrow {
  border-width: 11px;
}

.popover .arrow:after {
  border-width: 10px;
  content: "";
}

.popover.top .arrow {
  bottom: -11px;
  left: 50%;
  margin-left: -11px;
  border-top-color: #999;
  border-top-color: rgba(0, 0, 0, 0.25);
  border-bottom-width: 0;
}

.popover.top .arrow:after {
  bottom: 1px;
  margin-left: -10px;
  border-top-color: #ffffff;
  border-bottom-width: 0;
}

.popover.right .arrow {
  top: 50%;
  left: -11px;
  margin-top: -11px;
  border-right-color: #999;
  border-right-color: rgba(0, 0, 0, 0.25);
  border-left-width: 0;
}

.popover.right .arrow:after {
  bottom: -10px;
  left: 1px;
  border-right-color: #ffffff;
  border-left-width: 0;
}

.popover.bottom .arrow {
  top: -11px;
  left: 50%;
  margin-left: -11px;
  border-bottom-color: #999;
  border-bottom-color: rgba(0, 0, 0, 0.25);
  border-top-width: 0;
}

.popover.bottom .arrow:after {
  top: 1px;
  margin-left: -10px;
  border-bottom-color: #ffffff;
  border-top-width: 0;
}

.popover.left .arrow {
  top: 50%;
  right: -11px;
  margin-top: -11px;
  border-left-color: #999;
  border-left-color: rgba(0, 0, 0, 0.25);
  border-right-width: 0;
}

.popover.left .arrow:after {
  right: 1px;
  bottom: -10px;
  border-left-color: #ffffff;
  border-right-width: 0;
}

.thumbnails {
  margin-left: -20px;
  list-style: none;
  *zoom: 1;
}

.thumbnails:before,
.thumbnails:after {
  display: table;
  line-height: 0;
  content: "";
}

.thumbnails:after {
  clear: both;
}

.row-fluid .thumbnails {
  margin-left: 0;
}

.thumbnails > li {
  float: left;
  margin-bottom: 20px;
  margin-left: 20px;
}

.thumbnail {
  display: block;
  padding: 4px;
  line-height: 20px;
  border: 1px solid #ddd;
  -webkit-border-radius: 4px;
     -moz-border-radius: 4px;
          border-radius: 4px;
  -webkit-box-shadow: 0 1px 3px rgba(0, 0, 0, 0.055);
     -moz-box-shadow: 0 1px 3px rgba(0, 0, 0, 0.055);
          box-shadow: 0 1px 3px rgba(0, 0, 0, 0.055);
  -webkit-transition: all 0.2s ease-in-out;
     -moz-transition: all 0.2s ease-in-out;
       -o-transition: all 0.2s ease-in-out;
          transition: all 0.2s ease-in-out;
}

a.thumbnail:hover,
a.thumbnail:focus {
  border-color: #0088cc;
  -webkit-box-shadow: 0 1px 4px rgba(0, 105, 214, 0.25);
     -moz-box-shadow: 0 1px 4px rgba(0, 105, 214, 0.25);
          box-shadow: 0 1px 4px rgba(0, 105, 214, 0.25);
}

.thumbnail > img {
  display: block;
  max-width: 100%;
  margin-right: auto;
  margin-left: auto;
}

.thumbnail .caption {
  padding: 9px;
  color: #555555;
}

.media,
.media-body {
  overflow: hidden;
  *overflow: visible;
  zoom: 1;
}

.media,
.media .media {
  margin-top: 15px;
}

.media:first-child {
  margin-top: 0;
}

.media-object {
  display: block;
}

.media-heading {
  margin: 0 0 5px;
}

.media > .pull-left {
  margin-right: 10px;
}

.media > .pull-right {
  margin-left: 10px;
}

.media-list {
  margin-left: 0;
  list-style: none;
}

.label,
.badge {
  display: inline-block;
  padding: 2px 4px;
  font-size: 11.844px;
  font-weight: bold;
  line-height: 14px;
  color: #ffffff;
  text-shadow: 0 -1px 0 rgba(0, 0, 0, 0.25);
  white-space: nowrap;
  vertical-align: baseline;
  background-color: #999999;
}

.label {
  -webkit-border-radius: 3px;
     -moz-border-radius: 3px;
          border-radius: 3px;
}

.badge {
  padding-right: 9px;
  padding-left: 9px;
  -webkit-border-radius: 9px;
     -moz-border-radius: 9px;
          border-radius: 9px;
}

.label:empty,
.badge:empty {
  display: none;
}

a.label:hover,
a.label:focus,
a.badge:hover,
a.badge:focus {
  color: #ffffff;
  text-decoration: none;
  cursor: pointer;
}

.label-important,
.badge-important {
  background-color: #b94a48;
}

.label-important[href],
.badge-important[href] {
  background-color: #953b39;
}

.label-warning,
.badge-warning {
  background-color: #f89406;
}

.label-warning[href],
.badge-warning[href] {
  background-color: #c67605;
}

.label-success,
.badge-success {
  background-color: #468847;
}

.label-success[href],
.badge-success[href] {
  background-color: #356635;
}

.label-info,
.badge-info {
  background-color: #3a87ad;
}

.label-info[href],
.badge-info[href] {
  background-color: #2d6987;
}

.label-inverse,
.badge-inverse {
  background-color: #333333;
}

.label-inverse[href],
.badge-inverse[href] {
  background-color: #1a1a1a;
}

.btn .label,
.btn .badge {
  position: relative;
  top: -1px;
}

.btn-mini .label,
.btn-mini .badge {
  top: 0;
}

@-webkit-keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}

@-moz-keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}

@-ms-keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}

@-o-keyframes progress-bar-stripes {
  from {
    background-position: 0 0;
  }
  to {
    background-position: 40px 0;
  }
}

@keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}

.progress {
  height: 20px;
  margin-bottom: 20px;
  overflow: hidden;
  background-color: #f7f7f7;
  background-image: -moz-linear-gradient(top, #f5f5f5, #f9f9f9);
  background-image: -webkit-gradient(linear, 0 0, 0 100%, from(#f5f5f5), to(#f9f9f9));
  background-image: -webkit-linear-gradient(top, #f5f5f5, #f9f9f9);
  background-image: -o-linear-gradient(top, #f5f5f5, #f9f9f9);
  background-image: linear-gradient(to bottom, #f5f5f5, #f9f9f9);
  background-repeat: repeat-x;
  -webkit-border-radius: 4px;
     -moz-border-radius: 4px;
          border-radius: 4px;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#fff5f5f5', endColorstr='#fff9f9f9', GradientType=0);
  -webkit-box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
     -moz-box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
          box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
}

.progress .bar {
  float: left;
  width: 0;
  height: 100%;
  font-size: 12px;
  color: #ffffff;
  text-align: center;
  text-shadow: 0 -1px 0 rgba(0, 0, 0, 0.25);
  background-color: #0e90d2;
  background-image: -moz-linear-gradient(top, #149bdf, #0480be);
  background-image: -webkit-gradient(linear, 0 0, 0 100%, from(#149bdf), to(#0480be));
  background-image: -webkit-linear-gradient(top, #149bdf, #0480be);
  background-image: -o-linear-gradient(top, #149bdf, #0480be);
  background-image: linear-gradient(to bottom, #149bdf, #0480be);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#ff149bdf', endColorstr='#ff0480be', GradientType=0);
  -webkit-box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
     -moz-box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
          box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  -webkit-box-sizing: border-box;
     -moz-box-sizing: border-box;
          box-sizing: border-box;
  -webkit-transition: width 0.6s ease;
     -moz-transition: width 0.6s ease;
       -o-transition: width 0.6s ease;
          transition: width 0.6s ease;
}

.progress .bar + .bar {
  -webkit-box-shadow: inset 1px 0 0 rgba(0, 0, 0, 0.15), inset 0 -1px 0 rgba(0, 0, 0, 0.15);
     -moz-box-shadow: inset 1px 0 0 rgba(0, 0, 0, 0.15), inset 0 -1px 0 rgba(0, 0, 0, 0.15);
          box-shadow: inset 1px 0 0 rgba(0, 0, 0, 0.15), inset 0 -1px 0 rgba(0, 0, 0, 0.15);
}

.progress-striped .bar {
  background-color: #149bdf;
  background-image: -webkit-gradient(linear, 0 100%, 100% 0, color-stop(0.25, rgba(255, 255, 255, 0.15)), color-stop(0.25, transparent), color-stop(0.5, transparent), color-stop(0.5, rgba(255, 255, 255, 0.15)), color-stop(0.75, rgba(255, 255, 255, 0.15)), color-stop(0.75, transparent), to(transparent));
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -moz-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  -webkit-background-size: 40px 40px;
     -moz-background-size: 40px 40px;
       -o-background-size: 40px 40px;
          background-size: 40px 40px;
}

.progress.active .bar {
  -webkit-animation: progress-bar-stripes 2s linear infinite;
     -moz-animation: progress-bar-stripes 2s linear infinite;
      -ms-animation: progress-bar-stripes 2s linear infinite;
       -o-animation: progress-bar-stripes 2s linear infinite;
          animation: progress-bar-stripes 2s linear infinite;
}

.progress-danger .bar,
.progress .bar-danger {
  background-color: #dd514c;
  background-image: -moz-linear-gradient(top, #ee5f5b, #c43c35);
  background-image: -webkit-gradient(linear, 0 0, 0 100%, from(#ee5f5b), to(#c43c35));
  background-image: -webkit-linear-gradient(top, #ee5f5b, #c43c35);
  background-image: -o-linear-gradient(top, #ee5f5b, #c43c35);
  background-image: linear-gradient(to bottom, #ee5f5b, #c43c35);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#ffee5f5b', endColorstr='#ffc43c35', GradientType=0);
}

.progress-danger.progress-striped .bar,
.progress-striped .bar-danger {
  background-color: #ee5f5b;
  background-image: -webkit-gradient(linear, 0 100%, 100% 0, color-stop(0.25, rgba(255, 255, 255, 0.15)), color-stop(0.25, transparent), color-stop(0.5, transparent), color-stop(0.5, rgba(255, 255, 255, 0.15)), color-stop(0.75, rgba(255, 255, 255, 0.15)), color-stop(0.75, transparent), to(transparent));
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -moz-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}

.progress-success .bar,
.progress .bar-success {
  background-color: #5eb95e;
  background-image: -moz-linear-gradient(top, #62c462, #57a957);
  background-image: -webkit-gradient(linear, 0 0, 0 100%, from(#62c462), to(#57a957));
  background-image: -webkit-linear-gradient(top, #62c462, #57a957);
  background-image: -o-linear-gradient(top, #62c462, #57a957);
  background-image: linear-gradient(to bottom, #62c462, #57a957);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#ff62c462', endColorstr='#ff57a957', GradientType=0);
}

.progress-success.progress-striped .bar,
.progress-striped .bar-success {
  background-color: #62c462;
  background-image: -webkit-gradient(linear, 0 100%, 100% 0, color-stop(0.25, rgba(255, 255, 255, 0.15)), color-stop(0.25, transparent), color-stop(0.5, transparent), color-stop(0.5, rgba(255, 255, 255, 0.15)), color-stop(0.75, rgba(255, 255, 255, 0.15)), color-stop(0.75, transparent), to(transparent));
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -moz-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}

.progress-info .bar,
.progress .bar-info {
  background-color: #4bb1cf;
  background-image: -moz-linear-gradient(top, #5bc0de, #339bb9);
  background-image: -webkit-gradient(linear, 0 0, 0 100%, from(#5bc0de), to(#339bb9));
  background-image: -webkit-linear-gradient(top, #5bc0de, #339bb9);
  background-image: -o-linear-gradient(top, #5bc0de, #339bb9);
  background-image: linear-gradient(to bottom, #5bc0de, #339bb9);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#ff5bc0de', endColorstr='#ff339bb9', GradientType=0);
}

.progress-info.progress-striped .bar,
.progress-striped .bar-info {
  background-color: #5bc0de;
  background-image: -webkit-gradient(linear, 0 100%, 100% 0, color-stop(0.25, rgba(255, 255, 255, 0.15)), color-stop(0.25, transparent), color-stop(0.5, transparent), color-stop(0.5, rgba(255, 255, 255, 0.15)), color-stop(0.75, rgba(255, 255, 255, 0.15)), color-stop(0.75, transparent), to(transparent));
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -moz-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}

.progress-warning .bar,
.progress .bar-warning {
  background-color: #faa732;
  background-image: -moz-linear-gradient(top, #fbb450, #f89406);
  background-image: -webkit-gradient(linear, 0 0, 0 100%, from(#fbb450), to(#f89406));
  background-image: -webkit-linear-gradient(top, #fbb450, #f89406);
  background-image: -o-linear-gradient(top, #fbb450, #f89406);
  background-image: linear-gradient(to bottom, #fbb450, #f89406);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#fffbb450', endColorstr='#fff89406', GradientType=0);
}

.progress-warning.progress-striped .bar,
.progress-striped .bar-warning {
  background-color: #fbb450;
  background-image: -webkit-gradient(linear, 0 100%, 100% 0, color-stop(0.25, rgba(255, 255, 255, 0.15)), color-stop(0.25, transparent), color-stop(0.5, transparent), color-stop(0.5, rgba(255, 255, 255, 0.15)), color-stop(0.75, rgba(255, 255, 255, 0.15)), color-stop(0.75, transparent), to(transparent));
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -moz-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}

.accordion {
  margin-bottom: 20px;
}

.accordion-group {
  margin-bottom: 2px;
  border: 1px solid #e5e5e5;
  -webkit-border-radius: 4px;
     -moz-border-radius: 4px;
          border-radius: 4px;
}

.accordion-heading {
  border-bottom: 0;
}

.accordion-heading .accordion-toggle {
  display: block;
  padding: 8px 15px;
}

.accordion-toggle {
  cursor: pointer;
}

.accordion-inner {
  padding: 9px 15px;
  border-top: 1px solid #e5e5e5;
}

.carousel {
  position: relative;
  margin-bottom: 20px;
  line-height: 1;
}

.carousel-inner {
  position: relative;
  width: 100%;
  overflow: hidden;
}

.carousel-inner > .item {
  position: relative;
  display: none;
  -webkit-transition: 0.6s ease-in-out left;
     -moz-transition: 0.6s ease-in-out left;
       -o-transition: 0.6s ease-in-out left;
          transition: 0.6s ease-in-out left;
}

.carousel-inner > .item > img,
.carousel-inner > .item > a > img {
  display: block;
  line-height: 1;
}

.carousel-inner > .active,
.carousel-inner > .next,
.carousel-inner > .prev {
  display: block;
}

.carousel-inner > .active {
  left: 0;
}

.carousel-inner > .next,
.carousel-inner > .prev {
  position: absolute;
  top: 0;
  width: 100%;
}

.carousel-inner > .next {
  left: 100%;
}

.carousel-inner > .prev {
  left: -100%;
}

.carousel-inner > .next.left,
.carousel-inner > .prev.right {
  left: 0;
}

.carousel-inner > .active.left {
  left: -100%;
}

.carousel-inner > .active.right {
  left: 100%;
}

.carousel-control {
  position: absolute;
  top: 40%;
  left: 15px;
  width: 40px;
  height: 40px;
  margin-top: -20px;
  font-size: 60px;
  font-weight: 100;
  line-height: 30px;
  color: #ffffff;
  text-align: center;
  background: #222222;
  border: 3px solid #ffffff;
  -webkit-border-radius: 23px;
     -moz-border-radius: 23px;
          border-radius: 23px;
  opacity: 0.5;
  filter: alpha(opacity=50);
}

.carousel-control.right {
  right: 15px;
  left: auto;
}

.carousel-control:hover,
.carousel-control:focus {
  color: #ffffff;
  text-decoration: none;
  opacity: 0.9;
  filter: alpha(opacity=90);
}

.carousel-indicators {
  position: absolute;
  top: 15px;
  right: 15px;
  z-index: 5;
  margin: 0;
  list-style: none;
}

.carousel-indicators li {
  display: block;
  float: left;
  width: 10px;
  height: 10px;
  margin-left: 5px;
  text-indent: -999px;
  background-color: #ccc;
  background-color: rgba(255, 255, 255, 0.25);
  border-radius: 5px;
}

.carousel-indicators .active {
  background-color: #fff;
}

.carousel-caption {
  position: absolute;
  right: 0;
  bottom: 0;
  left: 0;
  padding: 15px;
  background: #333333;
  background: rgba(0, 0, 0, 0.75);
}

.carousel-caption h4,
.carousel-caption p {
  line-height: 20px;
  color: #ffffff;
}

.carousel-caption h4 {
  margin: 0 0 5px;
}

.carousel-caption p {
  margin-bottom: 0;
}

.hero-unit {
  padding: 60px;
  margin-bottom: 30px;
  font-size: 18px;
  font-weight: 200;
  line-height: 30px;
  color: inherit;
  background-color: #eeeeee;
  -webkit-border-radius: 6px;
     -moz-border-radius: 6px;
          border-radius: 6px;
}

.hero-unit h1 {
  margin-bottom: 0;
  font-size: 60px;
  line-height: 1;
  letter-spacing: -1px;
  color: inherit;
}

.hero-unit li {
  line-height: 30px;
}

.pull-right {
  float: right;
}

.pull-left {
  float: left;
}

.hide {
  display: none;
}

.show {
  display: block;
}

.invisible {
  visibility: hidden;
}

.affix {
  position: fixed;
}
                                                                                                                                                                                                                                                 master/bootstrap/css/bootstrap.min.css                                                              000644  000767  000024  00000316723 12110524611 021132  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /*!
 * Bootstrap v2.3.0
 *
 * Copyright 2012 Twitter, Inc
 * Licensed under the Apache License v2.0
 * http://www.apache.org/licenses/LICENSE-2.0
 *
 * Designed and built with all the love in the world @twitter by @mdo and @fat.
 */.clearfix{*zoom:1}.clearfix:before,.clearfix:after{display:table;line-height:0;content:""}.clearfix:after{clear:both}.hide-text{font:0/0 a;color:transparent;text-shadow:none;background-color:transparent;border:0}.input-block-level{display:block;width:100%;min-height:30px;-webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box}article,aside,details,figcaption,figure,footer,header,hgroup,nav,section{display:block}audio,canvas,video{display:inline-block;*display:inline;*zoom:1}audio:not([controls]){display:none}html{font-size:100%;-webkit-text-size-adjust:100%;-ms-text-size-adjust:100%}a:focus{outline:thin dotted #333;outline:5px auto -webkit-focus-ring-color;outline-offset:-2px}a:hover,a:active{outline:0}sub,sup{position:relative;font-size:75%;line-height:0;vertical-align:baseline}sup{top:-0.5em}sub{bottom:-0.25em}img{width:auto\9;height:auto;max-width:100%;vertical-align:middle;border:0;-ms-interpolation-mode:bicubic}#map_canvas img,.google-maps img{max-width:none}button,input,select,textarea{margin:0;font-size:100%;vertical-align:middle}button,input{*overflow:visible;line-height:normal}button::-moz-focus-inner,input::-moz-focus-inner{padding:0;border:0}button,html input[type="button"],input[type="reset"],input[type="submit"]{cursor:pointer;-webkit-appearance:button}label,select,button,input[type="button"],input[type="reset"],input[type="submit"],input[type="radio"],input[type="checkbox"]{cursor:pointer}input[type="search"]{-webkit-box-sizing:content-box;-moz-box-sizing:content-box;box-sizing:content-box;-webkit-appearance:textfield}input[type="search"]::-webkit-search-decoration,input[type="search"]::-webkit-search-cancel-button{-webkit-appearance:none}textarea{overflow:auto;vertical-align:top}@media print{*{color:#000!important;text-shadow:none!important;background:transparent!important;box-shadow:none!important}a,a:visited{text-decoration:underline}a[href]:after{content:" (" attr(href) ")"}abbr[title]:after{content:" (" attr(title) ")"}.ir a:after,a[href^="javascript:"]:after,a[href^="#"]:after{content:""}pre,blockquote{border:1px solid #999;page-break-inside:avoid}thead{display:table-header-group}tr,img{page-break-inside:avoid}img{max-width:100%!important}@page{margin:.5cm}p,h2,h3{orphans:3;widows:3}h2,h3{page-break-after:avoid}}body{margin:0;font-family:"Helvetica Neue",Helvetica,Arial,sans-serif;font-size:14px;line-height:20px;color:#333;background-color:#fff}a{color:#08c;text-decoration:none}a:hover,a:focus{color:#005580;text-decoration:underline}.img-rounded{-webkit-border-radius:6px;-moz-border-radius:6px;border-radius:6px}.img-polaroid{padding:4px;background-color:#fff;border:1px solid #ccc;border:1px solid rgba(0,0,0,0.2);-webkit-box-shadow:0 1px 3px rgba(0,0,0,0.1);-moz-box-shadow:0 1px 3px rgba(0,0,0,0.1);box-shadow:0 1px 3px rgba(0,0,0,0.1)}.img-circle{-webkit-border-radius:500px;-moz-border-radius:500px;border-radius:500px}.row{margin-left:-20px;*zoom:1}.row:before,.row:after{display:table;line-height:0;content:""}.row:after{clear:both}[class*="span"]{float:left;min-height:1px;margin-left:20px}.container,.navbar-static-top .container,.navbar-fixed-top .container,.navbar-fixed-bottom .container{width:940px}.span12{width:940px}.span11{width:860px}.span10{width:780px}.span9{width:700px}.span8{width:620px}.span7{width:540px}.span6{width:460px}.span5{width:380px}.span4{width:300px}.span3{width:220px}.span2{width:140px}.span1{width:60px}.offset12{margin-left:980px}.offset11{margin-left:900px}.offset10{margin-left:820px}.offset9{margin-left:740px}.offset8{margin-left:660px}.offset7{margin-left:580px}.offset6{margin-left:500px}.offset5{margin-left:420px}.offset4{margin-left:340px}.offset3{margin-left:260px}.offset2{margin-left:180px}.offset1{margin-left:100px}.row-fluid{width:100%;*zoom:1}.row-fluid:before,.row-fluid:after{display:table;line-height:0;content:""}.row-fluid:after{clear:both}.row-fluid [class*="span"]{display:block;float:left;width:100%;min-height:30px;margin-left:2.127659574468085%;*margin-left:2.074468085106383%;-webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box}.row-fluid [class*="span"]:first-child{margin-left:0}.row-fluid .controls-row [class*="span"]+[class*="span"]{margin-left:2.127659574468085%}.row-fluid .span12{width:100%;*width:99.94680851063829%}.row-fluid .span11{width:91.48936170212765%;*width:91.43617021276594%}.row-fluid .span10{width:82.97872340425532%;*width:82.92553191489361%}.row-fluid .span9{width:74.46808510638297%;*width:74.41489361702126%}.row-fluid .span8{width:65.95744680851064%;*width:65.90425531914893%}.row-fluid .span7{width:57.44680851063829%;*width:57.39361702127659%}.row-fluid .span6{width:48.93617021276595%;*width:48.88297872340425%}.row-fluid .span5{width:40.42553191489362%;*width:40.37234042553192%}.row-fluid .span4{width:31.914893617021278%;*width:31.861702127659576%}.row-fluid .span3{width:23.404255319148934%;*width:23.351063829787233%}.row-fluid .span2{width:14.893617021276595%;*width:14.840425531914894%}.row-fluid .span1{width:6.382978723404255%;*width:6.329787234042553%}.row-fluid .offset12{margin-left:104.25531914893617%;*margin-left:104.14893617021275%}.row-fluid .offset12:first-child{margin-left:102.12765957446808%;*margin-left:102.02127659574467%}.row-fluid .offset11{margin-left:95.74468085106382%;*margin-left:95.6382978723404%}.row-fluid .offset11:first-child{margin-left:93.61702127659574%;*margin-left:93.51063829787232%}.row-fluid .offset10{margin-left:87.23404255319149%;*margin-left:87.12765957446807%}.row-fluid .offset10:first-child{margin-left:85.1063829787234%;*margin-left:84.99999999999999%}.row-fluid .offset9{margin-left:78.72340425531914%;*margin-left:78.61702127659572%}.row-fluid .offset9:first-child{margin-left:76.59574468085106%;*margin-left:76.48936170212764%}.row-fluid .offset8{margin-left:70.2127659574468%;*margin-left:70.10638297872339%}.row-fluid .offset8:first-child{margin-left:68.08510638297872%;*margin-left:67.9787234042553%}.row-fluid .offset7{margin-left:61.70212765957446%;*margin-left:61.59574468085106%}.row-fluid .offset7:first-child{margin-left:59.574468085106375%;*margin-left:59.46808510638297%}.row-fluid .offset6{margin-left:53.191489361702125%;*margin-left:53.085106382978715%}.row-fluid .offset6:first-child{margin-left:51.063829787234035%;*margin-left:50.95744680851063%}.row-fluid .offset5{margin-left:44.68085106382979%;*margin-left:44.57446808510638%}.row-fluid .offset5:first-child{margin-left:42.5531914893617%;*margin-left:42.4468085106383%}.row-fluid .offset4{margin-left:36.170212765957444%;*margin-left:36.06382978723405%}.row-fluid .offset4:first-child{margin-left:34.04255319148936%;*margin-left:33.93617021276596%}.row-fluid .offset3{margin-left:27.659574468085104%;*margin-left:27.5531914893617%}.row-fluid .offset3:first-child{margin-left:25.53191489361702%;*margin-left:25.425531914893618%}.row-fluid .offset2{margin-left:19.148936170212764%;*margin-left:19.04255319148936%}.row-fluid .offset2:first-child{margin-left:17.02127659574468%;*margin-left:16.914893617021278%}.row-fluid .offset1{margin-left:10.638297872340425%;*margin-left:10.53191489361702%}.row-fluid .offset1:first-child{margin-left:8.51063829787234%;*margin-left:8.404255319148938%}[class*="span"].hide,.row-fluid [class*="span"].hide{display:none}[class*="span"].pull-right,.row-fluid [class*="span"].pull-right{float:right}.container{margin-right:auto;margin-left:auto;*zoom:1}.container:before,.container:after{display:table;line-height:0;content:""}.container:after{clear:both}.container-fluid{padding-right:20px;padding-left:20px;*zoom:1}.container-fluid:before,.container-fluid:after{display:table;line-height:0;content:""}.container-fluid:after{clear:both}p{margin:0 0 10px}.lead{margin-bottom:20px;font-size:21px;font-weight:200;line-height:30px}small{font-size:85%}strong{font-weight:bold}em{font-style:italic}cite{font-style:normal}.muted{color:#999}a.muted:hover,a.muted:focus{color:#808080}.text-warning{color:#c09853}a.text-warning:hover,a.text-warning:focus{color:#a47e3c}.text-error{color:#b94a48}a.text-error:hover,a.text-error:focus{color:#953b39}.text-info{color:#3a87ad}a.text-info:hover,a.text-info:focus{color:#2d6987}.text-success{color:#468847}a.text-success:hover,a.text-success:focus{color:#356635}.text-left{text-align:left}.text-right{text-align:right}.text-center{text-align:center}h1,h2,h3,h4,h5,h6{margin:10px 0;font-family:inherit;font-weight:bold;line-height:20px;color:inherit;text-rendering:optimizelegibility}h1 small,h2 small,h3 small,h4 small,h5 small,h6 small{font-weight:normal;line-height:1;color:#999}h1,h2,h3{line-height:40px}h1{font-size:38.5px}h2{font-size:31.5px}h3{font-size:24.5px}h4{font-size:17.5px}h5{font-size:14px}h6{font-size:11.9px}h1 small{font-size:24.5px}h2 small{font-size:17.5px}h3 small{font-size:14px}h4 small{font-size:14px}.page-header{padding-bottom:9px;margin:20px 0 30px;border-bottom:1px solid #eee}ul,ol{padding:0;margin:0 0 10px 25px}ul ul,ul ol,ol ol,ol ul{margin-bottom:0}li{line-height:20px}ul.unstyled,ol.unstyled{margin-left:0;list-style:none}ul.inline,ol.inline{margin-left:0;list-style:none}ul.inline>li,ol.inline>li{display:inline-block;*display:inline;padding-right:5px;padding-left:5px;*zoom:1}dl{margin-bottom:20px}dt,dd{line-height:20px}dt{font-weight:bold}dd{margin-left:10px}.dl-horizontal{*zoom:1}.dl-horizontal:before,.dl-horizontal:after{display:table;line-height:0;content:""}.dl-horizontal:after{clear:both}.dl-horizontal dt{float:left;width:160px;overflow:hidden;clear:left;text-align:right;text-overflow:ellipsis;white-space:nowrap}.dl-horizontal dd{margin-left:180px}hr{margin:20px 0;border:0;border-top:1px solid #eee;border-bottom:1px solid #fff}abbr[title],abbr[data-original-title]{cursor:help;border-bottom:1px dotted #999}abbr.initialism{font-size:90%;text-transform:uppercase}blockquote{padding:0 0 0 15px;margin:0 0 20px;border-left:5px solid #eee}blockquote p{margin-bottom:0;font-size:17.5px;font-weight:300;line-height:1.25}blockquote small{display:block;line-height:20px;color:#999}blockquote small:before{content:'\2014 \00A0'}blockquote.pull-right{float:right;padding-right:15px;padding-left:0;border-right:5px solid #eee;border-left:0}blockquote.pull-right p,blockquote.pull-right small{text-align:right}blockquote.pull-right small:before{content:''}blockquote.pull-right small:after{content:'\00A0 \2014'}q:before,q:after,blockquote:before,blockquote:after{content:""}address{display:block;margin-bottom:20px;font-style:normal;line-height:20px}code,pre{padding:0 3px 2px;font-family:Monaco,Menlo,Consolas,"Courier New",monospace;font-size:12px;color:#333;-webkit-border-radius:3px;-moz-border-radius:3px;border-radius:3px}code{padding:2px 4px;color:#d14;white-space:nowrap;background-color:#f7f7f9;border:1px solid #e1e1e8}pre{display:block;padding:9.5px;margin:0 0 10px;font-size:13px;line-height:20px;word-break:break-all;word-wrap:break-word;white-space:pre;white-space:pre-wrap;background-color:#f5f5f5;border:1px solid #ccc;border:1px solid rgba(0,0,0,0.15);-webkit-border-radius:4px;-moz-border-radius:4px;border-radius:4px}pre.prettyprint{margin-bottom:20px}pre code{padding:0;color:inherit;white-space:pre;white-space:pre-wrap;background-color:transparent;border:0}.pre-scrollable{max-height:340px;overflow-y:scroll}form{margin:0 0 20px}fieldset{padding:0;margin:0;border:0}legend{display:block;width:100%;padding:0;margin-bottom:20px;font-size:21px;line-height:40px;color:#333;border:0;border-bottom:1px solid #e5e5e5}legend small{font-size:15px;color:#999}label,input,button,select,textarea{font-size:14px;font-weight:normal;line-height:20px}input,button,select,textarea{font-family:"Helvetica Neue",Helvetica,Arial,sans-serif}label{display:block;margin-bottom:5px}select,textarea,input[type="text"],input[type="password"],input[type="datetime"],input[type="datetime-local"],input[type="date"],input[type="month"],input[type="time"],input[type="week"],input[type="number"],input[type="email"],input[type="url"],input[type="search"],input[type="tel"],input[type="color"],.uneditable-input{display:inline-block;height:20px;padding:4px 6px;margin-bottom:10px;font-size:14px;line-height:20px;color:#555;vertical-align:middle;-webkit-border-radius:4px;-moz-border-radius:4px;border-radius:4px}input,textarea,.uneditable-input{width:206px}textarea{height:auto}textarea,input[type="text"],input[type="password"],input[type="datetime"],input[type="datetime-local"],input[type="date"],input[type="month"],input[type="time"],input[type="week"],input[type="number"],input[type="email"],input[type="url"],input[type="search"],input[type="tel"],input[type="color"],.uneditable-input{background-color:#fff;border:1px solid #ccc;-webkit-box-shadow:inset 0 1px 1px rgba(0,0,0,0.075);-moz-box-shadow:inset 0 1px 1px rgba(0,0,0,0.075);box-shadow:inset 0 1px 1px rgba(0,0,0,0.075);-webkit-transition:border linear .2s,box-shadow linear .2s;-moz-transition:border linear .2s,box-shadow linear .2s;-o-transition:border linear .2s,box-shadow linear .2s;transition:border linear .2s,box-shadow linear .2s}textarea:focus,input[type="text"]:focus,input[type="password"]:focus,input[type="datetime"]:focus,input[type="datetime-local"]:focus,input[type="date"]:focus,input[type="month"]:focus,input[type="time"]:focus,input[type="week"]:focus,input[type="number"]:focus,input[type="email"]:focus,input[type="url"]:focus,input[type="search"]:focus,input[type="tel"]:focus,input[type="color"]:focus,.uneditable-input:focus{border-color:rgba(82,168,236,0.8);outline:0;outline:thin dotted \9;-webkit-box-shadow:inset 0 1px 1px rgba(0,0,0,0.075),0 0 8px rgba(82,168,236,0.6);-moz-box-shadow:inset 0 1px 1px rgba(0,0,0,0.075),0 0 8px rgba(82,168,236,0.6);box-shadow:inset 0 1px 1px rgba(0,0,0,0.075),0 0 8px rgba(82,168,236,0.6)}input[type="radio"],input[type="checkbox"]{margin:4px 0 0;margin-top:1px \9;*margin-top:0;line-height:normal}input[type="file"],input[type="image"],input[type="submit"],input[type="reset"],input[type="button"],input[type="radio"],input[type="checkbox"]{width:auto}select,input[type="file"]{height:30px;*margin-top:4px;line-height:30px}select{width:220px;background-color:#fff;border:1px solid #ccc}select[multiple],select[size]{height:auto}select:focus,input[type="file"]:focus,input[type="radio"]:focus,input[type="checkbox"]:focus{outline:thin dotted #333;outline:5px auto -webkit-focus-ring-color;outline-offset:-2px}.uneditable-input,.uneditable-textarea{color:#999;cursor:not-allowed;background-color:#fcfcfc;border-color:#ccc;-webkit-box-shadow:inset 0 1px 2px rgba(0,0,0,0.025);-moz-box-shadow:inset 0 1px 2px rgba(0,0,0,0.025);box-shadow:inset 0 1px 2px rgba(0,0,0,0.025)}.uneditable-input{overflow:hidden;white-space:nowrap}.uneditable-textarea{width:auto;height:auto}input:-moz-placeholder,textarea:-moz-placeholder{color:#999}input:-ms-input-placeholder,textarea:-ms-input-placeholder{color:#999}input::-webkit-input-placeholder,textarea::-webkit-input-placeholder{color:#999}.radio,.checkbox{min-height:20px;padding-left:20px}.radio input[type="radio"],.checkbox input[type="checkbox"]{float:left;margin-left:-20px}.controls>.radio:first-child,.controls>.checkbox:first-child{padding-top:5px}.radio.inline,.checkbox.inline{display:inline-block;padding-top:5px;margin-bottom:0;vertical-align:middle}.radio.inline+.radio.inline,.checkbox.inline+.checkbox.inline{margin-left:10px}.input-mini{width:60px}.input-small{width:90px}.input-medium{width:150px}.input-large{width:210px}.input-xlarge{width:270px}.input-xxlarge{width:530px}input[class*="span"],select[class*="span"],textarea[class*="span"],.uneditable-input[class*="span"],.row-fluid input[class*="span"],.row-fluid select[class*="span"],.row-fluid textarea[class*="span"],.row-fluid .uneditable-input[class*="span"]{float:none;margin-left:0}.input-append input[class*="span"],.input-append .uneditable-input[class*="span"],.input-prepend input[class*="span"],.input-prepend .uneditable-input[class*="span"],.row-fluid input[class*="span"],.row-fluid select[class*="span"],.row-fluid textarea[class*="span"],.row-fluid .uneditable-input[class*="span"],.row-fluid .input-prepend [class*="span"],.row-fluid .input-append [class*="span"]{display:inline-block}input,textarea,.uneditable-input{margin-left:0}.controls-row [class*="span"]+[class*="span"]{margin-left:20px}input.span12,textarea.span12,.uneditable-input.span12{width:926px}input.span11,textarea.span11,.uneditable-input.span11{width:846px}input.span10,textarea.span10,.uneditable-input.span10{width:766px}input.span9,textarea.span9,.uneditable-input.span9{width:686px}input.span8,textarea.span8,.uneditable-input.span8{width:606px}input.span7,textarea.span7,.uneditable-input.span7{width:526px}input.span6,textarea.span6,.uneditable-input.span6{width:446px}input.span5,textarea.span5,.uneditable-input.span5{width:366px}input.span4,textarea.span4,.uneditable-input.span4{width:286px}input.span3,textarea.span3,.uneditable-input.span3{width:206px}input.span2,textarea.span2,.uneditable-input.span2{width:126px}input.span1,textarea.span1,.uneditable-input.span1{width:46px}.controls-row{*zoom:1}.controls-row:before,.controls-row:after{display:table;line-height:0;content:""}.controls-row:after{clear:both}.controls-row [class*="span"],.row-fluid .controls-row [class*="span"]{float:left}.controls-row .checkbox[class*="span"],.controls-row .radio[class*="span"]{padding-top:5px}input[disabled],select[disabled],textarea[disabled],input[readonly],select[readonly],textarea[readonly]{cursor:not-allowed;background-color:#eee}input[type="radio"][disabled],input[type="checkbox"][disabled],input[type="radio"][readonly],input[type="checkbox"][readonly]{background-color:transparent}.control-group.warning .control-label,.control-group.warning .help-block,.control-group.warning .help-inline{color:#c09853}.control-group.warning .checkbox,.control-group.warning .radio,.control-group.warning input,.control-group.warning select,.control-group.warning textarea{color:#c09853}.control-group.warning input,.control-group.warning select,.control-group.warning textarea{border-color:#c09853;-webkit-box-shadow:inset 0 1px 1px rgba(0,0,0,0.075);-moz-box-shadow:inset 0 1px 1px rgba(0,0,0,0.075);box-shadow:inset 0 1px 1px rgba(0,0,0,0.075)}.control-group.warning input:focus,.control-group.warning select:focus,.control-group.warning textarea:focus{border-color:#a47e3c;-webkit-box-shadow:inset 0 1px 1px rgba(0,0,0,0.075),0 0 6px #dbc59e;-moz-box-shadow:inset 0 1px 1px rgba(0,0,0,0.075),0 0 6px #dbc59e;box-shadow:inset 0 1px 1px rgba(0,0,0,0.075),0 0 6px #dbc59e}.control-group.warning .input-prepend .add-on,.control-group.warning .input-append .add-on{color:#c09853;background-color:#fcf8e3;border-color:#c09853}.control-group.error .control-label,.control-group.error .help-block,.control-group.error .help-inline{color:#b94a48}.control-group.error .checkbox,.control-group.error .radio,.control-group.error input,.control-group.error select,.control-group.error textarea{color:#b94a48}.control-group.error input,.control-group.error select,.control-group.error textarea{border-color:#b94a48;-webkit-box-shadow:inset 0 1px 1px rgba(0,0,0,0.075);-moz-box-shadow:inset 0 1px 1px rgba(0,0,0,0.075);box-shadow:inset 0 1px 1px rgba(0,0,0,0.075)}.control-group.error input:focus,.control-group.error select:focus,.control-group.error textarea:focus{border-color:#953b39;-webkit-box-shadow:inset 0 1px 1px rgba(0,0,0,0.075),0 0 6px #d59392;-moz-box-shadow:inset 0 1px 1px rgba(0,0,0,0.075),0 0 6px #d59392;box-shadow:inset 0 1px 1px rgba(0,0,0,0.075),0 0 6px #d59392}.control-group.error .input-prepend .add-on,.control-group.error .input-append .add-on{color:#b94a48;background-color:#f2dede;border-color:#b94a48}.control-group.success .control-label,.control-group.success .help-block,.control-group.success .help-inline{color:#468847}.control-group.success .checkbox,.control-group.success .radio,.control-group.success input,.control-group.success select,.control-group.success textarea{color:#468847}.control-group.success input,.control-group.success select,.control-group.success textarea{border-color:#468847;-webkit-box-shadow:inset 0 1px 1px rgba(0,0,0,0.075);-moz-box-shadow:inset 0 1px 1px rgba(0,0,0,0.075);box-shadow:inset 0 1px 1px rgba(0,0,0,0.075)}.control-group.success input:focus,.control-group.success select:focus,.control-group.success textarea:focus{border-color:#356635;-webkit-box-shadow:inset 0 1px 1px rgba(0,0,0,0.075),0 0 6px #7aba7b;-moz-box-shadow:inset 0 1px 1px rgba(0,0,0,0.075),0 0 6px #7aba7b;box-shadow:inset 0 1px 1px rgba(0,0,0,0.075),0 0 6px #7aba7b}.control-group.success .input-prepend .add-on,.control-group.success .input-append .add-on{color:#468847;background-color:#dff0d8;border-color:#468847}.control-group.info .control-label,.control-group.info .help-block,.control-group.info .help-inline{color:#3a87ad}.control-group.info .checkbox,.control-group.info .radio,.control-group.info input,.control-group.info select,.control-group.info textarea{color:#3a87ad}.control-group.info input,.control-group.info select,.control-group.info textarea{border-color:#3a87ad;-webkit-box-shadow:inset 0 1px 1px rgba(0,0,0,0.075);-moz-box-shadow:inset 0 1px 1px rgba(0,0,0,0.075);box-shadow:inset 0 1px 1px rgba(0,0,0,0.075)}.control-group.info input:focus,.control-group.info select:focus,.control-group.info textarea:focus{border-color:#2d6987;-webkit-box-shadow:inset 0 1px 1px rgba(0,0,0,0.075),0 0 6px #7ab5d3;-moz-box-shadow:inset 0 1px 1px rgba(0,0,0,0.075),0 0 6px #7ab5d3;box-shadow:inset 0 1px 1px rgba(0,0,0,0.075),0 0 6px #7ab5d3}.control-group.info .input-prepend .add-on,.control-group.info .input-append .add-on{color:#3a87ad;background-color:#d9edf7;border-color:#3a87ad}input:focus:invalid,textarea:focus:invalid,select:focus:invalid{color:#b94a48;border-color:#ee5f5b}input:focus:invalid:focus,textarea:focus:invalid:focus,select:focus:invalid:focus{border-color:#e9322d;-webkit-box-shadow:0 0 6px #f8b9b7;-moz-box-shadow:0 0 6px #f8b9b7;box-shadow:0 0 6px #f8b9b7}.form-actions{padding:19px 20px 20px;margin-top:20px;margin-bottom:20px;background-color:#f5f5f5;border-top:1px solid #e5e5e5;*zoom:1}.form-actions:before,.form-actions:after{display:table;line-height:0;content:""}.form-actions:after{clear:both}.help-block,.help-inline{color:#595959}.help-block{display:block;margin-bottom:10px}.help-inline{display:inline-block;*display:inline;padding-left:5px;vertical-align:middle;*zoom:1}.input-append,.input-prepend{display:inline-block;margin-bottom:10px;font-size:0;white-space:nowrap;vertical-align:middle}.input-append input,.input-prepend input,.input-append select,.input-prepend select,.input-append .uneditable-input,.input-prepend .uneditable-input,.input-append .dropdown-menu,.input-prepend .dropdown-menu,.input-append .popover,.input-prepend .popover{font-size:14px}.input-append input,.input-prepend input,.input-append select,.input-prepend select,.input-append .uneditable-input,.input-prepend .uneditable-input{position:relative;margin-bottom:0;*margin-left:0;vertical-align:top;-webkit-border-radius:0 4px 4px 0;-moz-border-radius:0 4px 4px 0;border-radius:0 4px 4px 0}.input-append input:focus,.input-prepend input:focus,.input-append select:focus,.input-prepend select:focus,.input-append .uneditable-input:focus,.input-prepend .uneditable-input:focus{z-index:2}.input-append .add-on,.input-prepend .add-on{display:inline-block;width:auto;height:20px;min-width:16px;padding:4px 5px;font-size:14px;font-weight:normal;line-height:20px;text-align:center;text-shadow:0 1px 0 #fff;background-color:#eee;border:1px solid #ccc}.input-append .add-on,.input-prepend .add-on,.input-append .btn,.input-prepend .btn,.input-append .btn-group>.dropdown-toggle,.input-prepend .btn-group>.dropdown-toggle{vertical-align:top;-webkit-border-radius:0;-moz-border-radius:0;border-radius:0}.input-append .active,.input-prepend .active{background-color:#a9dba9;border-color:#46a546}.input-prepend .add-on,.input-prepend .btn{margin-right:-1px}.input-prepend .add-on:first-child,.input-prepend .btn:first-child{-webkit-border-radius:4px 0 0 4px;-moz-border-radius:4px 0 0 4px;border-radius:4px 0 0 4px}.input-append input,.input-append select,.input-append .uneditable-input{-webkit-border-radius:4px 0 0 4px;-moz-border-radius:4px 0 0 4px;border-radius:4px 0 0 4px}.input-append input+.btn-group .btn:last-child,.input-append select+.btn-group .btn:last-child,.input-append .uneditable-input+.btn-group .btn:last-child{-webkit-border-radius:0 4px 4px 0;-moz-border-radius:0 4px 4px 0;border-radius:0 4px 4px 0}.input-append .add-on,.input-append .btn,.input-append .btn-group{margin-left:-1px}.input-append .add-on:last-child,.input-append .btn:last-child,.input-append .btn-group:last-child>.dropdown-toggle{-webkit-border-radius:0 4px 4px 0;-moz-border-radius:0 4px 4px 0;border-radius:0 4px 4px 0}.input-prepend.input-append input,.input-prepend.input-append select,.input-prepend.input-append .uneditable-input{-webkit-border-radius:0;-moz-border-radius:0;border-radius:0}.input-prepend.input-append input+.btn-group .btn,.input-prepend.input-append select+.btn-group .btn,.input-prepend.input-append .uneditable-input+.btn-group .btn{-webkit-border-radius:0 4px 4px 0;-moz-border-radius:0 4px 4px 0;border-radius:0 4px 4px 0}.input-prepend.input-append .add-on:first-child,.input-prepend.input-append .btn:first-child{margin-right:-1px;-webkit-border-radius:4px 0 0 4px;-moz-border-radius:4px 0 0 4px;border-radius:4px 0 0 4px}.input-prepend.input-append .add-on:last-child,.input-prepend.input-append .btn:last-child{margin-left:-1px;-webkit-border-radius:0 4px 4px 0;-moz-border-radius:0 4px 4px 0;border-radius:0 4px 4px 0}.input-prepend.input-append .btn-group:first-child{margin-left:0}input.search-query{padding-right:14px;padding-right:4px \9;padding-left:14px;padding-left:4px \9;margin-bottom:0;-webkit-border-radius:15px;-moz-border-radius:15px;border-radius:15px}.form-search .input-append .search-query,.form-search .input-prepend .search-query{-webkit-border-radius:0;-moz-border-radius:0;border-radius:0}.form-search .input-append .search-query{-webkit-border-radius:14px 0 0 14px;-moz-border-radius:14px 0 0 14px;border-radius:14px 0 0 14px}.form-search .input-append .btn{-webkit-border-radius:0 14px 14px 0;-moz-border-radius:0 14px 14px 0;border-radius:0 14px 14px 0}.form-search .input-prepend .search-query{-webkit-border-radius:0 14px 14px 0;-moz-border-radius:0 14px 14px 0;border-radius:0 14px 14px 0}.form-search .input-prepend .btn{-webkit-border-radius:14px 0 0 14px;-moz-border-radius:14px 0 0 14px;border-radius:14px 0 0 14px}.form-search input,.form-inline input,.form-horizontal input,.form-search textarea,.form-inline textarea,.form-horizontal textarea,.form-search select,.form-inline select,.form-horizontal select,.form-search .help-inline,.form-inline .help-inline,.form-horizontal .help-inline,.form-search .uneditable-input,.form-inline .uneditable-input,.form-horizontal .uneditable-input,.form-search .input-prepend,.form-inline .input-prepend,.form-horizontal .input-prepend,.form-search .input-append,.form-inline .input-append,.form-horizontal .input-append{display:inline-block;*display:inline;margin-bottom:0;vertical-align:middle;*zoom:1}.form-search .hide,.form-inline .hide,.form-horizontal .hide{display:none}.form-search label,.form-inline label,.form-search .btn-group,.form-inline .btn-group{display:inline-block}.form-search .input-append,.form-inline .input-append,.form-search .input-prepend,.form-inline .input-prepend{margin-bottom:0}.form-search .radio,.form-search .checkbox,.form-inline .radio,.form-inline .checkbox{padding-left:0;margin-bottom:0;vertical-align:middle}.form-search .radio input[type="radio"],.form-search .checkbox input[type="checkbox"],.form-inline .radio input[type="radio"],.form-inline .checkbox input[type="checkbox"]{float:left;margin-right:3px;margin-left:0}.control-group{margin-bottom:10px}legend+.control-group{margin-top:20px;-webkit-margin-top-collapse:separate}.form-horizontal .control-group{margin-bottom:20px;*zoom:1}.form-horizontal .control-group:before,.form-horizontal .control-group:after{display:table;line-height:0;content:""}.form-horizontal .control-group:after{clear:both}.form-horizontal .control-label{float:left;width:160px;padding-top:5px;text-align:right}.form-horizontal .controls{*display:inline-block;*padding-left:20px;margin-left:180px;*margin-left:0}.form-horizontal .controls:first-child{*padding-left:180px}.form-horizontal .help-block{margin-bottom:0}.form-horizontal input+.help-block,.form-horizontal select+.help-block,.form-horizontal textarea+.help-block,.form-horizontal .uneditable-input+.help-block,.form-horizontal .input-prepend+.help-block,.form-horizontal .input-append+.help-block{margin-top:10px}.form-horizontal .form-actions{padding-left:180px}table{max-width:100%;background-color:transparent;border-collapse:collapse;border-spacing:0}.table{width:100%;margin-bottom:20px}.table th,.table td{padding:8px;line-height:20px;text-align:left;vertical-align:top;border-top:1px solid #ddd}.table th{font-weight:bold}.table thead th{vertical-align:bottom}.table caption+thead tr:first-child th,.table caption+thead tr:first-child td,.table colgroup+thead tr:first-child th,.table colgroup+thead tr:first-child td,.table thead:first-child tr:first-child th,.table thead:first-child tr:first-child td{border-top:0}.table tbody+tbody{border-top:2px solid #ddd}.table .table{background-color:#fff}.table-condensed th,.table-condensed td{padding:4px 5px}.table-bordered{border:1px solid #ddd;border-collapse:separate;*border-collapse:collapse;border-left:0;-webkit-border-radius:4px;-moz-border-radius:4px;border-radius:4px}.table-bordered th,.table-bordered td{border-left:1px solid #ddd}.table-bordered caption+thead tr:first-child th,.table-bordered caption+tbody tr:first-child th,.table-bordered caption+tbody tr:first-child td,.table-bordered colgroup+thead tr:first-child th,.table-bordered colgroup+tbody tr:first-child th,.table-bordered colgroup+tbody tr:first-child td,.table-bordered thead:first-child tr:first-child th,.table-bordered tbody:first-child tr:first-child th,.table-bordered tbody:first-child tr:first-child td{border-top:0}.table-bordered thead:first-child tr:first-child>th:first-child,.table-bordered tbody:first-child tr:first-child>td:first-child,.table-bordered tbody:first-child tr:first-child>th:first-child{-webkit-border-top-left-radius:4px;border-top-left-radius:4px;-moz-border-radius-topleft:4px}.table-bordered thead:first-child tr:first-child>th:last-child,.table-bordered tbody:first-child tr:first-child>td:last-child,.table-bordered tbody:first-child tr:first-child>th:last-child{-webkit-border-top-right-radius:4px;border-top-right-radius:4px;-moz-border-radius-topright:4px}.table-bordered thead:last-child tr:last-child>th:first-child,.table-bordered tbody:last-child tr:last-child>td:first-child,.table-bordered tbody:last-child tr:last-child>th:first-child,.table-bordered tfoot:last-child tr:last-child>td:first-child,.table-bordered tfoot:last-child tr:last-child>th:first-child{-webkit-border-bottom-left-radius:4px;border-bottom-left-radius:4px;-moz-border-radius-bottomleft:4px}.table-bordered thead:last-child tr:last-child>th:last-child,.table-bordered tbody:last-child tr:last-child>td:last-child,.table-bordered tbody:last-child tr:last-child>th:last-child,.table-bordered tfoot:last-child tr:last-child>td:last-child,.table-bordered tfoot:last-child tr:last-child>th:last-child{-webkit-border-bottom-right-radius:4px;border-bottom-right-radius:4px;-moz-border-radius-bottomright:4px}.table-bordered tfoot+tbody:last-child tr:last-child td:first-child{-webkit-border-bottom-left-radius:0;border-bottom-left-radius:0;-moz-border-radius-bottomleft:0}.table-bordered tfoot+tbody:last-child tr:last-child td:last-child{-webkit-border-bottom-right-radius:0;border-bottom-right-radius:0;-moz-border-radius-bottomright:0}.table-bordered caption+thead tr:first-child th:first-child,.table-bordered caption+tbody tr:first-child td:first-child,.table-bordered colgroup+thead tr:first-child th:first-child,.table-bordered colgroup+tbody tr:first-child td:first-child{-webkit-border-top-left-radius:4px;border-top-left-radius:4px;-moz-border-radius-topleft:4px}.table-bordered caption+thead tr:first-child th:last-child,.table-bordered caption+tbody tr:first-child td:last-child,.table-bordered colgroup+thead tr:first-child th:last-child,.table-bordered colgroup+tbody tr:first-child td:last-child{-webkit-border-top-right-radius:4px;border-top-right-radius:4px;-moz-border-radius-topright:4px}.table-striped tbody>tr:nth-child(odd)>td,.table-striped tbody>tr:nth-child(odd)>th{background-color:#f9f9f9}.table-hover tbody tr:hover>td,.table-hover tbody tr:hover>th{background-color:#f5f5f5}table td[class*="span"],table th[class*="span"],.row-fluid table td[class*="span"],.row-fluid table th[class*="span"]{display:table-cell;float:none;margin-left:0}.table td.span1,.table th.span1{float:none;width:44px;margin-left:0}.table td.span2,.table th.span2{float:none;width:124px;margin-left:0}.table td.span3,.table th.span3{float:none;width:204px;margin-left:0}.table td.span4,.table th.span4{float:none;width:284px;margin-left:0}.table td.span5,.table th.span5{float:none;width:364px;margin-left:0}.table td.span6,.table th.span6{float:none;width:444px;margin-left:0}.table td.span7,.table th.span7{float:none;width:524px;margin-left:0}.table td.span8,.table th.span8{float:none;width:604px;margin-left:0}.table td.span9,.table th.span9{float:none;width:684px;margin-left:0}.table td.span10,.table th.span10{float:none;width:764px;margin-left:0}.table td.span11,.table th.span11{float:none;width:844px;margin-left:0}.table td.span12,.table th.span12{float:none;width:924px;margin-left:0}.table tbody tr.success>td{background-color:#dff0d8}.table tbody tr.error>td{background-color:#f2dede}.table tbody tr.warning>td{background-color:#fcf8e3}.table tbody tr.info>td{background-color:#d9edf7}.table-hover tbody tr.success:hover>td{background-color:#d0e9c6}.table-hover tbody tr.error:hover>td{background-color:#ebcccc}.table-hover tbody tr.warning:hover>td{background-color:#faf2cc}.table-hover tbody tr.info:hover>td{background-color:#c4e3f3}[class^="icon-"],[class*=" icon-"]{display:inline-block;width:14px;height:14px;margin-top:1px;*margin-right:.3em;line-height:14px;vertical-align:text-top;background-image:url("../img/glyphicons-halflings.png");background-position:14px 14px;background-repeat:no-repeat}.icon-white,.nav-pills>.active>a>[class^="icon-"],.nav-pills>.active>a>[class*=" icon-"],.nav-list>.active>a>[class^="icon-"],.nav-list>.active>a>[class*=" icon-"],.navbar-inverse .nav>.active>a>[class^="icon-"],.navbar-inverse .nav>.active>a>[class*=" icon-"],.dropdown-menu>li>a:hover>[class^="icon-"],.dropdown-menu>li>a:focus>[class^="icon-"],.dropdown-menu>li>a:hover>[class*=" icon-"],.dropdown-menu>li>a:focus>[class*=" icon-"],.dropdown-menu>.active>a>[class^="icon-"],.dropdown-menu>.active>a>[class*=" icon-"],.dropdown-submenu:hover>a>[class^="icon-"],.dropdown-submenu:focus>a>[class^="icon-"],.dropdown-submenu:hover>a>[class*=" icon-"],.dropdown-submenu:focus>a>[class*=" icon-"]{background-image:url("../img/glyphicons-halflings-white.png")}.icon-glass{background-position:0 0}.icon-music{background-position:-24px 0}.icon-search{background-position:-48px 0}.icon-envelope{background-position:-72px 0}.icon-heart{background-position:-96px 0}.icon-star{background-position:-120px 0}.icon-star-empty{background-position:-144px 0}.icon-user{background-position:-168px 0}.icon-film{background-position:-192px 0}.icon-th-large{background-position:-216px 0}.icon-th{background-position:-240px 0}.icon-th-list{background-position:-264px 0}.icon-ok{background-position:-288px 0}.icon-remove{background-position:-312px 0}.icon-zoom-in{background-position:-336px 0}.icon-zoom-out{background-position:-360px 0}.icon-off{background-position:-384px 0}.icon-signal{background-position:-408px 0}.icon-cog{background-position:-432px 0}.icon-trash{background-position:-456px 0}.icon-home{background-position:0 -24px}.icon-file{background-position:-24px -24px}.icon-time{background-position:-48px -24px}.icon-road{background-position:-72px -24px}.icon-download-alt{background-position:-96px -24px}.icon-download{background-position:-120px -24px}.icon-upload{background-position:-144px -24px}.icon-inbox{background-position:-168px -24px}.icon-play-circle{background-position:-192px -24px}.icon-repeat{background-position:-216px -24px}.icon-refresh{background-position:-240px -24px}.icon-list-alt{background-position:-264px -24px}.icon-lock{background-position:-287px -24px}.icon-flag{background-position:-312px -24px}.icon-headphones{background-position:-336px -24px}.icon-volume-off{background-position:-360px -24px}.icon-volume-down{background-position:-384px -24px}.icon-volume-up{background-position:-408px -24px}.icon-qrcode{background-position:-432px -24px}.icon-barcode{background-position:-456px -24px}.icon-tag{background-position:0 -48px}.icon-tags{background-position:-25px -48px}.icon-book{background-position:-48px -48px}.icon-bookmark{background-position:-72px -48px}.icon-print{background-position:-96px -48px}.icon-camera{background-position:-120px -48px}.icon-font{background-position:-144px -48px}.icon-bold{background-position:-167px -48px}.icon-italic{background-position:-192px -48px}.icon-text-height{background-position:-216px -48px}.icon-text-width{background-position:-240px -48px}.icon-align-left{background-position:-264px -48px}.icon-align-center{background-position:-288px -48px}.icon-align-right{background-position:-312px -48px}.icon-align-justify{background-position:-336px -48px}.icon-list{background-position:-360px -48px}.icon-indent-left{background-position:-384px -48px}.icon-indent-right{background-position:-408px -48px}.icon-facetime-video{background-position:-432px -48px}.icon-picture{background-position:-456px -48px}.icon-pencil{background-position:0 -72px}.icon-map-marker{background-position:-24px -72px}.icon-adjust{background-position:-48px -72px}.icon-tint{background-position:-72px -72px}.icon-edit{background-position:-96px -72px}.icon-share{background-position:-120px -72px}.icon-check{background-position:-144px -72px}.icon-move{background-position:-168px -72px}.icon-step-backward{background-position:-192px -72px}.icon-fast-backward{background-position:-216px -72px}.icon-backward{background-position:-240px -72px}.icon-play{background-position:-264px -72px}.icon-pause{background-position:-288px -72px}.icon-stop{background-position:-312px -72px}.icon-forward{background-position:-336px -72px}.icon-fast-forward{background-position:-360px -72px}.icon-step-forward{background-position:-384px -72px}.icon-eject{background-position:-408px -72px}.icon-chevron-left{background-position:-432px -72px}.icon-chevron-right{background-position:-456px -72px}.icon-plus-sign{background-position:0 -96px}.icon-minus-sign{background-position:-24px -96px}.icon-remove-sign{background-position:-48px -96px}.icon-ok-sign{background-position:-72px -96px}.icon-question-sign{background-position:-96px -96px}.icon-info-sign{background-position:-120px -96px}.icon-screenshot{background-position:-144px -96px}.icon-remove-circle{background-position:-168px -96px}.icon-ok-circle{background-position:-192px -96px}.icon-ban-circle{background-position:-216px -96px}.icon-arrow-left{background-position:-240px -96px}.icon-arrow-right{background-position:-264px -96px}.icon-arrow-up{background-position:-289px -96px}.icon-arrow-down{background-position:-312px -96px}.icon-share-alt{background-position:-336px -96px}.icon-resize-full{background-position:-360px -96px}.icon-resize-small{background-position:-384px -96px}.icon-plus{background-position:-408px -96px}.icon-minus{background-position:-433px -96px}.icon-asterisk{background-position:-456px -96px}.icon-exclamation-sign{background-position:0 -120px}.icon-gift{background-position:-24px -120px}.icon-leaf{background-position:-48px -120px}.icon-fire{background-position:-72px -120px}.icon-eye-open{background-position:-96px -120px}.icon-eye-close{background-position:-120px -120px}.icon-warning-sign{background-position:-144px -120px}.icon-plane{background-position:-168px -120px}.icon-calendar{background-position:-192px -120px}.icon-random{width:16px;background-position:-216px -120px}.icon-comment{background-position:-240px -120px}.icon-magnet{background-position:-264px -120px}.icon-chevron-up{background-position:-288px -120px}.icon-chevron-down{background-position:-313px -119px}.icon-retweet{background-position:-336px -120px}.icon-shopping-cart{background-position:-360px -120px}.icon-folder-close{width:16px;background-position:-384px -120px}.icon-folder-open{width:16px;background-position:-408px -120px}.icon-resize-vertical{background-position:-432px -119px}.icon-resize-horizontal{background-position:-456px -118px}.icon-hdd{background-position:0 -144px}.icon-bullhorn{background-position:-24px -144px}.icon-bell{background-position:-48px -144px}.icon-certificate{background-position:-72px -144px}.icon-thumbs-up{background-position:-96px -144px}.icon-thumbs-down{background-position:-120px -144px}.icon-hand-right{background-position:-144px -144px}.icon-hand-left{background-position:-168px -144px}.icon-hand-up{background-position:-192px -144px}.icon-hand-down{background-position:-216px -144px}.icon-circle-arrow-right{background-position:-240px -144px}.icon-circle-arrow-left{background-position:-264px -144px}.icon-circle-arrow-up{background-position:-288px -144px}.icon-circle-arrow-down{background-position:-312px -144px}.icon-globe{background-position:-336px -144px}.icon-wrench{background-position:-360px -144px}.icon-tasks{background-position:-384px -144px}.icon-filter{background-position:-408px -144px}.icon-briefcase{background-position:-432px -144px}.icon-fullscreen{background-position:-456px -144px}.dropup,.dropdown{position:relative}.dropdown-toggle{*margin-bottom:-3px}.dropdown-toggle:active,.open .dropdown-toggle{outline:0}.caret{display:inline-block;width:0;height:0;vertical-align:top;border-top:4px solid #000;border-right:4px solid transparent;border-left:4px solid transparent;content:""}.dropdown .caret{margin-top:8px;margin-left:2px}.dropdown-menu{position:absolute;top:100%;left:0;z-index:1000;display:none;float:left;min-width:160px;padding:5px 0;margin:2px 0 0;list-style:none;background-color:#fff;border:1px solid #ccc;border:1px solid rgba(0,0,0,0.2);*border-right-width:2px;*border-bottom-width:2px;-webkit-border-radius:6px;-moz-border-radius:6px;border-radius:6px;-webkit-box-shadow:0 5px 10px rgba(0,0,0,0.2);-moz-box-shadow:0 5px 10px rgba(0,0,0,0.2);box-shadow:0 5px 10px rgba(0,0,0,0.2);-webkit-background-clip:padding-box;-moz-background-clip:padding;background-clip:padding-box}.dropdown-menu.pull-right{right:0;left:auto}.dropdown-menu .divider{*width:100%;height:1px;margin:9px 1px;*margin:-5px 0 5px;overflow:hidden;background-color:#e5e5e5;border-bottom:1px solid #fff}.dropdown-menu>li>a{display:block;padding:3px 20px;clear:both;font-weight:normal;line-height:20px;color:#333;white-space:nowrap}.dropdown-menu>li>a:hover,.dropdown-menu>li>a:focus,.dropdown-submenu:hover>a,.dropdown-submenu:focus>a{color:#fff;text-decoration:none;background-color:#0081c2;background-image:-moz-linear-gradient(top,#08c,#0077b3);background-image:-webkit-gradient(linear,0 0,0 100%,from(#08c),to(#0077b3));background-image:-webkit-linear-gradient(top,#08c,#0077b3);background-image:-o-linear-gradient(top,#08c,#0077b3);background-image:linear-gradient(to bottom,#08c,#0077b3);background-repeat:repeat-x;filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#ff0088cc',endColorstr='#ff0077b3',GradientType=0)}.dropdown-menu>.active>a,.dropdown-menu>.active>a:hover,.dropdown-menu>.active>a:focus{color:#fff;text-decoration:none;background-color:#0081c2;background-image:-moz-linear-gradient(top,#08c,#0077b3);background-image:-webkit-gradient(linear,0 0,0 100%,from(#08c),to(#0077b3));background-image:-webkit-linear-gradient(top,#08c,#0077b3);background-image:-o-linear-gradient(top,#08c,#0077b3);background-image:linear-gradient(to bottom,#08c,#0077b3);background-repeat:repeat-x;outline:0;filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#ff0088cc',endColorstr='#ff0077b3',GradientType=0)}.dropdown-menu>.disabled>a,.dropdown-menu>.disabled>a:hover,.dropdown-menu>.disabled>a:focus{color:#999}.dropdown-menu>.disabled>a:hover,.dropdown-menu>.disabled>a:focus{text-decoration:none;cursor:default;background-color:transparent;background-image:none;filter:progid:DXImageTransform.Microsoft.gradient(enabled=false)}.open{*z-index:1000}.open>.dropdown-menu{display:block}.pull-right>.dropdown-menu{right:0;left:auto}.dropup .caret,.navbar-fixed-bottom .dropdown .caret{border-top:0;border-bottom:4px solid #000;content:""}.dropup .dropdown-menu,.navbar-fixed-bottom .dropdown .dropdown-menu{top:auto;bottom:100%;margin-bottom:1px}.dropdown-submenu{position:relative}.dropdown-submenu>.dropdown-menu{top:0;left:100%;margin-top:-6px;margin-left:-1px;-webkit-border-radius:0 6px 6px 6px;-moz-border-radius:0 6px 6px 6px;border-radius:0 6px 6px 6px}.dropdown-submenu:hover>.dropdown-menu{display:block}.dropup .dropdown-submenu>.dropdown-menu{top:auto;bottom:0;margin-top:0;margin-bottom:-2px;-webkit-border-radius:5px 5px 5px 0;-moz-border-radius:5px 5px 5px 0;border-radius:5px 5px 5px 0}.dropdown-submenu>a:after{display:block;float:right;width:0;height:0;margin-top:5px;margin-right:-10px;border-color:transparent;border-left-color:#ccc;border-style:solid;border-width:5px 0 5px 5px;content:" "}.dropdown-submenu:hover>a:after{border-left-color:#fff}.dropdown-submenu.pull-left{float:none}.dropdown-submenu.pull-left>.dropdown-menu{left:-100%;margin-left:10px;-webkit-border-radius:6px 0 6px 6px;-moz-border-radius:6px 0 6px 6px;border-radius:6px 0 6px 6px}.dropdown .dropdown-menu .nav-header{padding-right:20px;padding-left:20px}.typeahead{z-index:1051;margin-top:2px;-webkit-border-radius:4px;-moz-border-radius:4px;border-radius:4px}.well{min-height:20px;padding:19px;margin-bottom:20px;background-color:#f5f5f5;border:1px solid #e3e3e3;-webkit-border-radius:4px;-moz-border-radius:4px;border-radius:4px;-webkit-box-shadow:inset 0 1px 1px rgba(0,0,0,0.05);-moz-box-shadow:inset 0 1px 1px rgba(0,0,0,0.05);box-shadow:inset 0 1px 1px rgba(0,0,0,0.05)}.well blockquote{border-color:#ddd;border-color:rgba(0,0,0,0.15)}.well-large{padding:24px;-webkit-border-radius:6px;-moz-border-radius:6px;border-radius:6px}.well-small{padding:9px;-webkit-border-radius:3px;-moz-border-radius:3px;border-radius:3px}.fade{opacity:0;-webkit-transition:opacity .15s linear;-moz-transition:opacity .15s linear;-o-transition:opacity .15s linear;transition:opacity .15s linear}.fade.in{opacity:1}.collapse{position:relative;height:0;overflow:hidden;-webkit-transition:height .35s ease;-moz-transition:height .35s ease;-o-transition:height .35s ease;transition:height .35s ease}.collapse.in{height:auto}.close{float:right;font-size:20px;font-weight:bold;line-height:20px;color:#000;text-shadow:0 1px 0 #fff;opacity:.2;filter:alpha(opacity=20)}.close:hover,.close:focus{color:#000;text-decoration:none;cursor:pointer;opacity:.4;filter:alpha(opacity=40)}button.close{padding:0;cursor:pointer;background:transparent;border:0;-webkit-appearance:none}.btn{display:inline-block;*display:inline;padding:4px 12px;margin-bottom:0;*margin-left:.3em;font-size:14px;line-height:20px;color:#333;text-align:center;text-shadow:0 1px 1px rgba(255,255,255,0.75);vertical-align:middle;cursor:pointer;background-color:#f5f5f5;*background-color:#e6e6e6;background-image:-moz-linear-gradient(top,#fff,#e6e6e6);background-image:-webkit-gradient(linear,0 0,0 100%,from(#fff),to(#e6e6e6));background-image:-webkit-linear-gradient(top,#fff,#e6e6e6);background-image:-o-linear-gradient(top,#fff,#e6e6e6);background-image:linear-gradient(to bottom,#fff,#e6e6e6);background-repeat:repeat-x;border:1px solid #ccc;*border:0;border-color:#e6e6e6 #e6e6e6 #bfbfbf;border-color:rgba(0,0,0,0.1) rgba(0,0,0,0.1) rgba(0,0,0,0.25);border-bottom-color:#b3b3b3;-webkit-border-radius:4px;-moz-border-radius:4px;border-radius:4px;filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#ffffffff',endColorstr='#ffe6e6e6',GradientType=0);filter:progid:DXImageTransform.Microsoft.gradient(enabled=false);*zoom:1;-webkit-box-shadow:inset 0 1px 0 rgba(255,255,255,0.2),0 1px 2px rgba(0,0,0,0.05);-moz-box-shadow:inset 0 1px 0 rgba(255,255,255,0.2),0 1px 2px rgba(0,0,0,0.05);box-shadow:inset 0 1px 0 rgba(255,255,255,0.2),0 1px 2px rgba(0,0,0,0.05)}.btn:hover,.btn:focus,.btn:active,.btn.active,.btn.disabled,.btn[disabled]{color:#333;background-color:#e6e6e6;*background-color:#d9d9d9}.btn:active,.btn.active{background-color:#ccc \9}.btn:first-child{*margin-left:0}.btn:hover,.btn:focus{color:#333;text-decoration:none;background-position:0 -15px;-webkit-transition:background-position .1s linear;-moz-transition:background-position .1s linear;-o-transition:background-position .1s linear;transition:background-position .1s linear}.btn:focus{outline:thin dotted #333;outline:5px auto -webkit-focus-ring-color;outline-offset:-2px}.btn.active,.btn:active{background-image:none;outline:0;-webkit-box-shadow:inset 0 2px 4px rgba(0,0,0,0.15),0 1px 2px rgba(0,0,0,0.05);-moz-box-shadow:inset 0 2px 4px rgba(0,0,0,0.15),0 1px 2px rgba(0,0,0,0.05);box-shadow:inset 0 2px 4px rgba(0,0,0,0.15),0 1px 2px rgba(0,0,0,0.05)}.btn.disabled,.btn[disabled]{cursor:default;background-image:none;opacity:.65;filter:alpha(opacity=65);-webkit-box-shadow:none;-moz-box-shadow:none;box-shadow:none}.btn-large{padding:11px 19px;font-size:17.5px;-webkit-border-radius:6px;-moz-border-radius:6px;border-radius:6px}.btn-large [class^="icon-"],.btn-large [class*=" icon-"]{margin-top:4px}.btn-small{padding:2px 10px;font-size:11.9px;-webkit-border-radius:3px;-moz-border-radius:3px;border-radius:3px}.btn-small [class^="icon-"],.btn-small [class*=" icon-"]{margin-top:0}.btn-mini [class^="icon-"],.btn-mini [class*=" icon-"]{margin-top:-1px}.btn-mini{padding:0 6px;font-size:10.5px;-webkit-border-radius:3px;-moz-border-radius:3px;border-radius:3px}.btn-block{display:block;width:100%;padding-right:0;padding-left:0;-webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box}.btn-block+.btn-block{margin-top:5px}input[type="submit"].btn-block,input[type="reset"].btn-block,input[type="button"].btn-block{width:100%}.btn-primary.active,.btn-warning.active,.btn-danger.active,.btn-success.active,.btn-info.active,.btn-inverse.active{color:rgba(255,255,255,0.75)}.btn-primary{color:#fff;text-shadow:0 -1px 0 rgba(0,0,0,0.25);background-color:#006dcc;*background-color:#04c;background-image:-moz-linear-gradient(top,#08c,#04c);background-image:-webkit-gradient(linear,0 0,0 100%,from(#08c),to(#04c));background-image:-webkit-linear-gradient(top,#08c,#04c);background-image:-o-linear-gradient(top,#08c,#04c);background-image:linear-gradient(to bottom,#08c,#04c);background-repeat:repeat-x;border-color:#04c #04c #002a80;border-color:rgba(0,0,0,0.1) rgba(0,0,0,0.1) rgba(0,0,0,0.25);filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#ff0088cc',endColorstr='#ff0044cc',GradientType=0);filter:progid:DXImageTransform.Microsoft.gradient(enabled=false)}.btn-primary:hover,.btn-primary:focus,.btn-primary:active,.btn-primary.active,.btn-primary.disabled,.btn-primary[disabled]{color:#fff;background-color:#04c;*background-color:#003bb3}.btn-primary:active,.btn-primary.active{background-color:#039 \9}.btn-warning{color:#fff;text-shadow:0 -1px 0 rgba(0,0,0,0.25);background-color:#faa732;*background-color:#f89406;background-image:-moz-linear-gradient(top,#fbb450,#f89406);background-image:-webkit-gradient(linear,0 0,0 100%,from(#fbb450),to(#f89406));background-image:-webkit-linear-gradient(top,#fbb450,#f89406);background-image:-o-linear-gradient(top,#fbb450,#f89406);background-image:linear-gradient(to bottom,#fbb450,#f89406);background-repeat:repeat-x;border-color:#f89406 #f89406 #ad6704;border-color:rgba(0,0,0,0.1) rgba(0,0,0,0.1) rgba(0,0,0,0.25);filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#fffbb450',endColorstr='#fff89406',GradientType=0);filter:progid:DXImageTransform.Microsoft.gradient(enabled=false)}.btn-warning:hover,.btn-warning:focus,.btn-warning:active,.btn-warning.active,.btn-warning.disabled,.btn-warning[disabled]{color:#fff;background-color:#f89406;*background-color:#df8505}.btn-warning:active,.btn-warning.active{background-color:#c67605 \9}.btn-danger{color:#fff;text-shadow:0 -1px 0 rgba(0,0,0,0.25);background-color:#da4f49;*background-color:#bd362f;background-image:-moz-linear-gradient(top,#ee5f5b,#bd362f);background-image:-webkit-gradient(linear,0 0,0 100%,from(#ee5f5b),to(#bd362f));background-image:-webkit-linear-gradient(top,#ee5f5b,#bd362f);background-image:-o-linear-gradient(top,#ee5f5b,#bd362f);background-image:linear-gradient(to bottom,#ee5f5b,#bd362f);background-repeat:repeat-x;border-color:#bd362f #bd362f #802420;border-color:rgba(0,0,0,0.1) rgba(0,0,0,0.1) rgba(0,0,0,0.25);filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#ffee5f5b',endColorstr='#ffbd362f',GradientType=0);filter:progid:DXImageTransform.Microsoft.gradient(enabled=false)}.btn-danger:hover,.btn-danger:focus,.btn-danger:active,.btn-danger.active,.btn-danger.disabled,.btn-danger[disabled]{color:#fff;background-color:#bd362f;*background-color:#a9302a}.btn-danger:active,.btn-danger.active{background-color:#942a25 \9}.btn-success{color:#fff;text-shadow:0 -1px 0 rgba(0,0,0,0.25);background-color:#5bb75b;*background-color:#51a351;background-image:-moz-linear-gradient(top,#62c462,#51a351);background-image:-webkit-gradient(linear,0 0,0 100%,from(#62c462),to(#51a351));background-image:-webkit-linear-gradient(top,#62c462,#51a351);background-image:-o-linear-gradient(top,#62c462,#51a351);background-image:linear-gradient(to bottom,#62c462,#51a351);background-repeat:repeat-x;border-color:#51a351 #51a351 #387038;border-color:rgba(0,0,0,0.1) rgba(0,0,0,0.1) rgba(0,0,0,0.25);filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#ff62c462',endColorstr='#ff51a351',GradientType=0);filter:progid:DXImageTransform.Microsoft.gradient(enabled=false)}.btn-success:hover,.btn-success:focus,.btn-success:active,.btn-success.active,.btn-success.disabled,.btn-success[disabled]{color:#fff;background-color:#51a351;*background-color:#499249}.btn-success:active,.btn-success.active{background-color:#408140 \9}.btn-info{color:#fff;text-shadow:0 -1px 0 rgba(0,0,0,0.25);background-color:#49afcd;*background-color:#2f96b4;background-image:-moz-linear-gradient(top,#5bc0de,#2f96b4);background-image:-webkit-gradient(linear,0 0,0 100%,from(#5bc0de),to(#2f96b4));background-image:-webkit-linear-gradient(top,#5bc0de,#2f96b4);background-image:-o-linear-gradient(top,#5bc0de,#2f96b4);background-image:linear-gradient(to bottom,#5bc0de,#2f96b4);background-repeat:repeat-x;border-color:#2f96b4 #2f96b4 #1f6377;border-color:rgba(0,0,0,0.1) rgba(0,0,0,0.1) rgba(0,0,0,0.25);filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#ff5bc0de',endColorstr='#ff2f96b4',GradientType=0);filter:progid:DXImageTransform.Microsoft.gradient(enabled=false)}.btn-info:hover,.btn-info:focus,.btn-info:active,.btn-info.active,.btn-info.disabled,.btn-info[disabled]{color:#fff;background-color:#2f96b4;*background-color:#2a85a0}.btn-info:active,.btn-info.active{background-color:#24748c \9}.btn-inverse{color:#fff;text-shadow:0 -1px 0 rgba(0,0,0,0.25);background-color:#363636;*background-color:#222;background-image:-moz-linear-gradient(top,#444,#222);background-image:-webkit-gradient(linear,0 0,0 100%,from(#444),to(#222));background-image:-webkit-linear-gradient(top,#444,#222);background-image:-o-linear-gradient(top,#444,#222);background-image:linear-gradient(to bottom,#444,#222);background-repeat:repeat-x;border-color:#222 #222 #000;border-color:rgba(0,0,0,0.1) rgba(0,0,0,0.1) rgba(0,0,0,0.25);filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#ff444444',endColorstr='#ff222222',GradientType=0);filter:progid:DXImageTransform.Microsoft.gradient(enabled=false)}.btn-inverse:hover,.btn-inverse:focus,.btn-inverse:active,.btn-inverse.active,.btn-inverse.disabled,.btn-inverse[disabled]{color:#fff;background-color:#222;*background-color:#151515}.btn-inverse:active,.btn-inverse.active{background-color:#080808 \9}button.btn,input[type="submit"].btn{*padding-top:3px;*padding-bottom:3px}button.btn::-moz-focus-inner,input[type="submit"].btn::-moz-focus-inner{padding:0;border:0}button.btn.btn-large,input[type="submit"].btn.btn-large{*padding-top:7px;*padding-bottom:7px}button.btn.btn-small,input[type="submit"].btn.btn-small{*padding-top:3px;*padding-bottom:3px}button.btn.btn-mini,input[type="submit"].btn.btn-mini{*padding-top:1px;*padding-bottom:1px}.btn-link,.btn-link:active,.btn-link[disabled]{background-color:transparent;background-image:none;-webkit-box-shadow:none;-moz-box-shadow:none;box-shadow:none}.btn-link{color:#08c;cursor:pointer;border-color:transparent;-webkit-border-radius:0;-moz-border-radius:0;border-radius:0}.btn-link:hover,.btn-link:focus{color:#005580;text-decoration:underline;background-color:transparent}.btn-link[disabled]:hover,.btn-link[disabled]:focus{color:#333;text-decoration:none}.btn-group{position:relative;display:inline-block;*display:inline;*margin-left:.3em;font-size:0;white-space:nowrap;vertical-align:middle;*zoom:1}.btn-group:first-child{*margin-left:0}.btn-group+.btn-group{margin-left:5px}.btn-toolbar{margin-top:10px;margin-bottom:10px;font-size:0}.btn-toolbar>.btn+.btn,.btn-toolbar>.btn-group+.btn,.btn-toolbar>.btn+.btn-group{margin-left:5px}.btn-group>.btn{position:relative;-webkit-border-radius:0;-moz-border-radius:0;border-radius:0}.btn-group>.btn+.btn{margin-left:-1px}.btn-group>.btn,.btn-group>.dropdown-menu,.btn-group>.popover{font-size:14px}.btn-group>.btn-mini{font-size:10.5px}.btn-group>.btn-small{font-size:11.9px}.btn-group>.btn-large{font-size:17.5px}.btn-group>.btn:first-child{margin-left:0;-webkit-border-bottom-left-radius:4px;border-bottom-left-radius:4px;-webkit-border-top-left-radius:4px;border-top-left-radius:4px;-moz-border-radius-bottomleft:4px;-moz-border-radius-topleft:4px}.btn-group>.btn:last-child,.btn-group>.dropdown-toggle{-webkit-border-top-right-radius:4px;border-top-right-radius:4px;-webkit-border-bottom-right-radius:4px;border-bottom-right-radius:4px;-moz-border-radius-topright:4px;-moz-border-radius-bottomright:4px}.btn-group>.btn.large:first-child{margin-left:0;-webkit-border-bottom-left-radius:6px;border-bottom-left-radius:6px;-webkit-border-top-left-radius:6px;border-top-left-radius:6px;-moz-border-radius-bottomleft:6px;-moz-border-radius-topleft:6px}.btn-group>.btn.large:last-child,.btn-group>.large.dropdown-toggle{-webkit-border-top-right-radius:6px;border-top-right-radius:6px;-webkit-border-bottom-right-radius:6px;border-bottom-right-radius:6px;-moz-border-radius-topright:6px;-moz-border-radius-bottomright:6px}.btn-group>.btn:hover,.btn-group>.btn:focus,.btn-group>.btn:active,.btn-group>.btn.active{z-index:2}.btn-group .dropdown-toggle:active,.btn-group.open .dropdown-toggle{outline:0}.btn-group>.btn+.dropdown-toggle{*padding-top:5px;padding-right:8px;*padding-bottom:5px;padding-left:8px;-webkit-box-shadow:inset 1px 0 0 rgba(255,255,255,0.125),inset 0 1px 0 rgba(255,255,255,0.2),0 1px 2px rgba(0,0,0,0.05);-moz-box-shadow:inset 1px 0 0 rgba(255,255,255,0.125),inset 0 1px 0 rgba(255,255,255,0.2),0 1px 2px rgba(0,0,0,0.05);box-shadow:inset 1px 0 0 rgba(255,255,255,0.125),inset 0 1px 0 rgba(255,255,255,0.2),0 1px 2px rgba(0,0,0,0.05)}.btn-group>.btn-mini+.dropdown-toggle{*padding-top:2px;padding-right:5px;*padding-bottom:2px;padding-left:5px}.btn-group>.btn-small+.dropdown-toggle{*padding-top:5px;*padding-bottom:4px}.btn-group>.btn-large+.dropdown-toggle{*padding-top:7px;padding-right:12px;*padding-bottom:7px;padding-left:12px}.btn-group.open .dropdown-toggle{background-image:none;-webkit-box-shadow:inset 0 2px 4px rgba(0,0,0,0.15),0 1px 2px rgba(0,0,0,0.05);-moz-box-shadow:inset 0 2px 4px rgba(0,0,0,0.15),0 1px 2px rgba(0,0,0,0.05);box-shadow:inset 0 2px 4px rgba(0,0,0,0.15),0 1px 2px rgba(0,0,0,0.05)}.btn-group.open .btn.dropdown-toggle{background-color:#e6e6e6}.btn-group.open .btn-primary.dropdown-toggle{background-color:#04c}.btn-group.open .btn-warning.dropdown-toggle{background-color:#f89406}.btn-group.open .btn-danger.dropdown-toggle{background-color:#bd362f}.btn-group.open .btn-success.dropdown-toggle{background-color:#51a351}.btn-group.open .btn-info.dropdown-toggle{background-color:#2f96b4}.btn-group.open .btn-inverse.dropdown-toggle{background-color:#222}.btn .caret{margin-top:8px;margin-left:0}.btn-large .caret{margin-top:6px}.btn-large .caret{border-top-width:5px;border-right-width:5px;border-left-width:5px}.btn-mini .caret,.btn-small .caret{margin-top:8px}.dropup .btn-large .caret{border-bottom-width:5px}.btn-primary .caret,.btn-warning .caret,.btn-danger .caret,.btn-info .caret,.btn-success .caret,.btn-inverse .caret{border-top-color:#fff;border-bottom-color:#fff}.btn-group-vertical{display:inline-block;*display:inline;*zoom:1}.btn-group-vertical>.btn{display:block;float:none;max-width:100%;-webkit-border-radius:0;-moz-border-radius:0;border-radius:0}.btn-group-vertical>.btn+.btn{margin-top:-1px;margin-left:0}.btn-group-vertical>.btn:first-child{-webkit-border-radius:4px 4px 0 0;-moz-border-radius:4px 4px 0 0;border-radius:4px 4px 0 0}.btn-group-vertical>.btn:last-child{-webkit-border-radius:0 0 4px 4px;-moz-border-radius:0 0 4px 4px;border-radius:0 0 4px 4px}.btn-group-vertical>.btn-large:first-child{-webkit-border-radius:6px 6px 0 0;-moz-border-radius:6px 6px 0 0;border-radius:6px 6px 0 0}.btn-group-vertical>.btn-large:last-child{-webkit-border-radius:0 0 6px 6px;-moz-border-radius:0 0 6px 6px;border-radius:0 0 6px 6px}.alert{padding:8px 35px 8px 14px;margin-bottom:20px;text-shadow:0 1px 0 rgba(255,255,255,0.5);background-color:#fcf8e3;border:1px solid #fbeed5;-webkit-border-radius:4px;-moz-border-radius:4px;border-radius:4px}.alert,.alert h4{color:#c09853}.alert h4{margin:0}.alert .close{position:relative;top:-2px;right:-21px;line-height:20px}.alert-success{color:#468847;background-color:#dff0d8;border-color:#d6e9c6}.alert-success h4{color:#468847}.alert-danger,.alert-error{color:#b94a48;background-color:#f2dede;border-color:#eed3d7}.alert-danger h4,.alert-error h4{color:#b94a48}.alert-info{color:#3a87ad;background-color:#d9edf7;border-color:#bce8f1}.alert-info h4{color:#3a87ad}.alert-block{padding-top:14px;padding-bottom:14px}.alert-block>p,.alert-block>ul{margin-bottom:0}.alert-block p+p{margin-top:5px}.nav{margin-bottom:20px;margin-left:0;list-style:none}.nav>li>a{display:block}.nav>li>a:hover,.nav>li>a:focus{text-decoration:none;background-color:#eee}.nav>li>a>img{max-width:none}.nav>.pull-right{float:right}.nav-header{display:block;padding:3px 15px;font-size:11px;font-weight:bold;line-height:20px;color:#999;text-shadow:0 1px 0 rgba(255,255,255,0.5);text-transform:uppercase}.nav li+.nav-header{margin-top:9px}.nav-list{padding-right:15px;padding-left:15px;margin-bottom:0}.nav-list>li>a,.nav-list .nav-header{margin-right:-15px;margin-left:-15px;text-shadow:0 1px 0 rgba(255,255,255,0.5)}.nav-list>li>a{padding:3px 15px}.nav-list>.active>a,.nav-list>.active>a:hover,.nav-list>.active>a:focus{color:#fff;text-shadow:0 -1px 0 rgba(0,0,0,0.2);background-color:#08c}.nav-list [class^="icon-"],.nav-list [class*=" icon-"]{margin-right:2px}.nav-list .divider{*width:100%;height:1px;margin:9px 1px;*margin:-5px 0 5px;overflow:hidden;background-color:#e5e5e5;border-bottom:1px solid #fff}.nav-tabs,.nav-pills{*zoom:1}.nav-tabs:before,.nav-pills:before,.nav-tabs:after,.nav-pills:after{display:table;line-height:0;content:""}.nav-tabs:after,.nav-pills:after{clear:both}.nav-tabs>li,.nav-pills>li{float:left}.nav-tabs>li>a,.nav-pills>li>a{padding-right:12px;padding-left:12px;margin-right:2px;line-height:14px}.nav-tabs{border-bottom:1px solid #ddd}.nav-tabs>li{margin-bottom:-1px}.nav-tabs>li>a{padding-top:8px;padding-bottom:8px;line-height:20px;border:1px solid transparent;-webkit-border-radius:4px 4px 0 0;-moz-border-radius:4px 4px 0 0;border-radius:4px 4px 0 0}.nav-tabs>li>a:hover,.nav-tabs>li>a:focus{border-color:#eee #eee #ddd}.nav-tabs>.active>a,.nav-tabs>.active>a:hover,.nav-tabs>.active>a:focus{color:#555;cursor:default;background-color:#fff;border:1px solid #ddd;border-bottom-color:transparent}.nav-pills>li>a{padding-top:8px;padding-bottom:8px;margin-top:2px;margin-bottom:2px;-webkit-border-radius:5px;-moz-border-radius:5px;border-radius:5px}.nav-pills>.active>a,.nav-pills>.active>a:hover,.nav-pills>.active>a:focus{color:#fff;background-color:#08c}.nav-stacked>li{float:none}.nav-stacked>li>a{margin-right:0}.nav-tabs.nav-stacked{border-bottom:0}.nav-tabs.nav-stacked>li>a{border:1px solid #ddd;-webkit-border-radius:0;-moz-border-radius:0;border-radius:0}.nav-tabs.nav-stacked>li:first-child>a{-webkit-border-top-right-radius:4px;border-top-right-radius:4px;-webkit-border-top-left-radius:4px;border-top-left-radius:4px;-moz-border-radius-topright:4px;-moz-border-radius-topleft:4px}.nav-tabs.nav-stacked>li:last-child>a{-webkit-border-bottom-right-radius:4px;border-bottom-right-radius:4px;-webkit-border-bottom-left-radius:4px;border-bottom-left-radius:4px;-moz-border-radius-bottomright:4px;-moz-border-radius-bottomleft:4px}.nav-tabs.nav-stacked>li>a:hover,.nav-tabs.nav-stacked>li>a:focus{z-index:2;border-color:#ddd}.nav-pills.nav-stacked>li>a{margin-bottom:3px}.nav-pills.nav-stacked>li:last-child>a{margin-bottom:1px}.nav-tabs .dropdown-menu{-webkit-border-radius:0 0 6px 6px;-moz-border-radius:0 0 6px 6px;border-radius:0 0 6px 6px}.nav-pills .dropdown-menu{-webkit-border-radius:6px;-moz-border-radius:6px;border-radius:6px}.nav .dropdown-toggle .caret{margin-top:6px;border-top-color:#08c;border-bottom-color:#08c}.nav .dropdown-toggle:hover .caret,.nav .dropdown-toggle:focus .caret{border-top-color:#005580;border-bottom-color:#005580}.nav-tabs .dropdown-toggle .caret{margin-top:8px}.nav .active .dropdown-toggle .caret{border-top-color:#fff;border-bottom-color:#fff}.nav-tabs .active .dropdown-toggle .caret{border-top-color:#555;border-bottom-color:#555}.nav>.dropdown.active>a:hover,.nav>.dropdown.active>a:focus{cursor:pointer}.nav-tabs .open .dropdown-toggle,.nav-pills .open .dropdown-toggle,.nav>li.dropdown.open.active>a:hover,.nav>li.dropdown.open.active>a:focus{color:#fff;background-color:#999;border-color:#999}.nav li.dropdown.open .caret,.nav li.dropdown.open.active .caret,.nav li.dropdown.open a:hover .caret,.nav li.dropdown.open a:focus .caret{border-top-color:#fff;border-bottom-color:#fff;opacity:1;filter:alpha(opacity=100)}.tabs-stacked .open>a:hover,.tabs-stacked .open>a:focus{border-color:#999}.tabbable{*zoom:1}.tabbable:before,.tabbable:after{display:table;line-height:0;content:""}.tabbable:after{clear:both}.tab-content{overflow:auto}.tabs-below>.nav-tabs,.tabs-right>.nav-tabs,.tabs-left>.nav-tabs{border-bottom:0}.tab-content>.tab-pane,.pill-content>.pill-pane{display:none}.tab-content>.active,.pill-content>.active{display:block}.tabs-below>.nav-tabs{border-top:1px solid #ddd}.tabs-below>.nav-tabs>li{margin-top:-1px;margin-bottom:0}.tabs-below>.nav-tabs>li>a{-webkit-border-radius:0 0 4px 4px;-moz-border-radius:0 0 4px 4px;border-radius:0 0 4px 4px}.tabs-below>.nav-tabs>li>a:hover,.tabs-below>.nav-tabs>li>a:focus{border-top-color:#ddd;border-bottom-color:transparent}.tabs-below>.nav-tabs>.active>a,.tabs-below>.nav-tabs>.active>a:hover,.tabs-below>.nav-tabs>.active>a:focus{border-color:transparent #ddd #ddd #ddd}.tabs-left>.nav-tabs>li,.tabs-right>.nav-tabs>li{float:none}.tabs-left>.nav-tabs>li>a,.tabs-right>.nav-tabs>li>a{min-width:74px;margin-right:0;margin-bottom:3px}.tabs-left>.nav-tabs{float:left;margin-right:19px;border-right:1px solid #ddd}.tabs-left>.nav-tabs>li>a{margin-right:-1px;-webkit-border-radius:4px 0 0 4px;-moz-border-radius:4px 0 0 4px;border-radius:4px 0 0 4px}.tabs-left>.nav-tabs>li>a:hover,.tabs-left>.nav-tabs>li>a:focus{border-color:#eee #ddd #eee #eee}.tabs-left>.nav-tabs .active>a,.tabs-left>.nav-tabs .active>a:hover,.tabs-left>.nav-tabs .active>a:focus{border-color:#ddd transparent #ddd #ddd;*border-right-color:#fff}.tabs-right>.nav-tabs{float:right;margin-left:19px;border-left:1px solid #ddd}.tabs-right>.nav-tabs>li>a{margin-left:-1px;-webkit-border-radius:0 4px 4px 0;-moz-border-radius:0 4px 4px 0;border-radius:0 4px 4px 0}.tabs-right>.nav-tabs>li>a:hover,.tabs-right>.nav-tabs>li>a:focus{border-color:#eee #eee #eee #ddd}.tabs-right>.nav-tabs .active>a,.tabs-right>.nav-tabs .active>a:hover,.tabs-right>.nav-tabs .active>a:focus{border-color:#ddd #ddd #ddd transparent;*border-left-color:#fff}.nav>.disabled>a{color:#999}.nav>.disabled>a:hover,.nav>.disabled>a:focus{text-decoration:none;cursor:default;background-color:transparent}.navbar{*position:relative;*z-index:2;margin-bottom:20px;overflow:visible}.navbar-inner{min-height:40px;padding-right:20px;padding-left:20px;background-color:#fafafa;background-image:-moz-linear-gradient(top,#fff,#f2f2f2);background-image:-webkit-gradient(linear,0 0,0 100%,from(#fff),to(#f2f2f2));background-image:-webkit-linear-gradient(top,#fff,#f2f2f2);background-image:-o-linear-gradient(top,#fff,#f2f2f2);background-image:linear-gradient(to bottom,#fff,#f2f2f2);background-repeat:repeat-x;border:1px solid #d4d4d4;-webkit-border-radius:4px;-moz-border-radius:4px;border-radius:4px;filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#ffffffff',endColorstr='#fff2f2f2',GradientType=0);*zoom:1;-webkit-box-shadow:0 1px 4px rgba(0,0,0,0.065);-moz-box-shadow:0 1px 4px rgba(0,0,0,0.065);box-shadow:0 1px 4px rgba(0,0,0,0.065)}.navbar-inner:before,.navbar-inner:after{display:table;line-height:0;content:""}.navbar-inner:after{clear:both}.navbar .container{width:auto}.nav-collapse.collapse{height:auto;overflow:visible}.navbar .brand{display:block;float:left;padding:10px 20px 10px;margin-left:-20px;font-size:20px;font-weight:200;color:#777;text-shadow:0 1px 0 #fff}.navbar .brand:hover,.navbar .brand:focus{text-decoration:none}.navbar-text{margin-bottom:0;line-height:40px;color:#777}.navbar-link{color:#777}.navbar-link:hover,.navbar-link:focus{color:#333}.navbar .divider-vertical{height:40px;margin:0 9px;border-right:1px solid #fff;border-left:1px solid #f2f2f2}.navbar .btn,.navbar .btn-group{margin-top:5px}.navbar .btn-group .btn,.navbar .input-prepend .btn,.navbar .input-append .btn,.navbar .input-prepend .btn-group,.navbar .input-append .btn-group{margin-top:0}.navbar-form{margin-bottom:0;*zoom:1}.navbar-form:before,.navbar-form:after{display:table;line-height:0;content:""}.navbar-form:after{clear:both}.navbar-form input,.navbar-form select,.navbar-form .radio,.navbar-form .checkbox{margin-top:5px}.navbar-form input,.navbar-form select,.navbar-form .btn{display:inline-block;margin-bottom:0}.navbar-form input[type="image"],.navbar-form input[type="checkbox"],.navbar-form input[type="radio"]{margin-top:3px}.navbar-form .input-append,.navbar-form .input-prepend{margin-top:5px;white-space:nowrap}.navbar-form .input-append input,.navbar-form .input-prepend input{margin-top:0}.navbar-search{position:relative;float:left;margin-top:5px;margin-bottom:0}.navbar-search .search-query{padding:4px 14px;margin-bottom:0;font-family:"Helvetica Neue",Helvetica,Arial,sans-serif;font-size:13px;font-weight:normal;line-height:1;-webkit-border-radius:15px;-moz-border-radius:15px;border-radius:15px}.navbar-static-top{position:static;margin-bottom:0}.navbar-static-top .navbar-inner{-webkit-border-radius:0;-moz-border-radius:0;border-radius:0}.navbar-fixed-top,.navbar-fixed-bottom{position:fixed;right:0;left:0;z-index:1030;margin-bottom:0}.navbar-fixed-top .navbar-inner,.navbar-static-top .navbar-inner{border-width:0 0 1px}.navbar-fixed-bottom .navbar-inner{border-width:1px 0 0}.navbar-fixed-top .navbar-inner,.navbar-fixed-bottom .navbar-inner{padding-right:0;padding-left:0;-webkit-border-radius:0;-moz-border-radius:0;border-radius:0}.navbar-static-top .container,.navbar-fixed-top .container,.navbar-fixed-bottom .container{width:940px}.navbar-fixed-top{top:0}.navbar-fixed-top .navbar-inner,.navbar-static-top .navbar-inner{-webkit-box-shadow:0 1px 10px rgba(0,0,0,0.1);-moz-box-shadow:0 1px 10px rgba(0,0,0,0.1);box-shadow:0 1px 10px rgba(0,0,0,0.1)}.navbar-fixed-bottom{bottom:0}.navbar-fixed-bottom .navbar-inner{-webkit-box-shadow:0 -1px 10px rgba(0,0,0,0.1);-moz-box-shadow:0 -1px 10px rgba(0,0,0,0.1);box-shadow:0 -1px 10px rgba(0,0,0,0.1)}.navbar .nav{position:relative;left:0;display:block;float:left;margin:0 10px 0 0}.navbar .nav.pull-right{float:right;margin-right:0}.navbar .nav>li{float:left}.navbar .nav>li>a{float:none;padding:10px 15px 10px;color:#777;text-decoration:none;text-shadow:0 1px 0 #fff}.navbar .nav .dropdown-toggle .caret{margin-top:8px}.navbar .nav>li>a:focus,.navbar .nav>li>a:hover{color:#333;text-decoration:none;background-color:transparent}.navbar .nav>.active>a,.navbar .nav>.active>a:hover,.navbar .nav>.active>a:focus{color:#555;text-decoration:none;background-color:#e5e5e5;-webkit-box-shadow:inset 0 3px 8px rgba(0,0,0,0.125);-moz-box-shadow:inset 0 3px 8px rgba(0,0,0,0.125);box-shadow:inset 0 3px 8px rgba(0,0,0,0.125)}.navbar .btn-navbar{display:none;float:right;padding:7px 10px;margin-right:5px;margin-left:5px;color:#fff;text-shadow:0 -1px 0 rgba(0,0,0,0.25);background-color:#ededed;*background-color:#e5e5e5;background-image:-moz-linear-gradient(top,#f2f2f2,#e5e5e5);background-image:-webkit-gradient(linear,0 0,0 100%,from(#f2f2f2),to(#e5e5e5));background-image:-webkit-linear-gradient(top,#f2f2f2,#e5e5e5);background-image:-o-linear-gradient(top,#f2f2f2,#e5e5e5);background-image:linear-gradient(to bottom,#f2f2f2,#e5e5e5);background-repeat:repeat-x;border-color:#e5e5e5 #e5e5e5 #bfbfbf;border-color:rgba(0,0,0,0.1) rgba(0,0,0,0.1) rgba(0,0,0,0.25);filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#fff2f2f2',endColorstr='#ffe5e5e5',GradientType=0);filter:progid:DXImageTransform.Microsoft.gradient(enabled=false);-webkit-box-shadow:inset 0 1px 0 rgba(255,255,255,0.1),0 1px 0 rgba(255,255,255,0.075);-moz-box-shadow:inset 0 1px 0 rgba(255,255,255,0.1),0 1px 0 rgba(255,255,255,0.075);box-shadow:inset 0 1px 0 rgba(255,255,255,0.1),0 1px 0 rgba(255,255,255,0.075)}.navbar .btn-navbar:hover,.navbar .btn-navbar:focus,.navbar .btn-navbar:active,.navbar .btn-navbar.active,.navbar .btn-navbar.disabled,.navbar .btn-navbar[disabled]{color:#fff;background-color:#e5e5e5;*background-color:#d9d9d9}.navbar .btn-navbar:active,.navbar .btn-navbar.active{background-color:#ccc \9}.navbar .btn-navbar .icon-bar{display:block;width:18px;height:2px;background-color:#f5f5f5;-webkit-border-radius:1px;-moz-border-radius:1px;border-radius:1px;-webkit-box-shadow:0 1px 0 rgba(0,0,0,0.25);-moz-box-shadow:0 1px 0 rgba(0,0,0,0.25);box-shadow:0 1px 0 rgba(0,0,0,0.25)}.btn-navbar .icon-bar+.icon-bar{margin-top:3px}.navbar .nav>li>.dropdown-menu:before{position:absolute;top:-7px;left:9px;display:inline-block;border-right:7px solid transparent;border-bottom:7px solid #ccc;border-left:7px solid transparent;border-bottom-color:rgba(0,0,0,0.2);content:''}.navbar .nav>li>.dropdown-menu:after{position:absolute;top:-6px;left:10px;display:inline-block;border-right:6px solid transparent;border-bottom:6px solid #fff;border-left:6px solid transparent;content:''}.navbar-fixed-bottom .nav>li>.dropdown-menu:before{top:auto;bottom:-7px;border-top:7px solid #ccc;border-bottom:0;border-top-color:rgba(0,0,0,0.2)}.navbar-fixed-bottom .nav>li>.dropdown-menu:after{top:auto;bottom:-6px;border-top:6px solid #fff;border-bottom:0}.navbar .nav li.dropdown>a:hover .caret,.navbar .nav li.dropdown>a:focus .caret{border-top-color:#333;border-bottom-color:#333}.navbar .nav li.dropdown.open>.dropdown-toggle,.navbar .nav li.dropdown.active>.dropdown-toggle,.navbar .nav li.dropdown.open.active>.dropdown-toggle{color:#555;background-color:#e5e5e5}.navbar .nav li.dropdown>.dropdown-toggle .caret{border-top-color:#777;border-bottom-color:#777}.navbar .nav li.dropdown.open>.dropdown-toggle .caret,.navbar .nav li.dropdown.active>.dropdown-toggle .caret,.navbar .nav li.dropdown.open.active>.dropdown-toggle .caret{border-top-color:#555;border-bottom-color:#555}.navbar .pull-right>li>.dropdown-menu,.navbar .nav>li>.dropdown-menu.pull-right{right:0;left:auto}.navbar .pull-right>li>.dropdown-menu:before,.navbar .nav>li>.dropdown-menu.pull-right:before{right:12px;left:auto}.navbar .pull-right>li>.dropdown-menu:after,.navbar .nav>li>.dropdown-menu.pull-right:after{right:13px;left:auto}.navbar .pull-right>li>.dropdown-menu .dropdown-menu,.navbar .nav>li>.dropdown-menu.pull-right .dropdown-menu{right:100%;left:auto;margin-right:-1px;margin-left:0;-webkit-border-radius:6px 0 6px 6px;-moz-border-radius:6px 0 6px 6px;border-radius:6px 0 6px 6px}.navbar-inverse .navbar-inner{background-color:#1b1b1b;background-image:-moz-linear-gradient(top,#222,#111);background-image:-webkit-gradient(linear,0 0,0 100%,from(#222),to(#111));background-image:-webkit-linear-gradient(top,#222,#111);background-image:-o-linear-gradient(top,#222,#111);background-image:linear-gradient(to bottom,#222,#111);background-repeat:repeat-x;border-color:#252525;filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#ff222222',endColorstr='#ff111111',GradientType=0)}.navbar-inverse .brand,.navbar-inverse .nav>li>a{color:#999;text-shadow:0 -1px 0 rgba(0,0,0,0.25)}.navbar-inverse .brand:hover,.navbar-inverse .nav>li>a:hover,.navbar-inverse .brand:focus,.navbar-inverse .nav>li>a:focus{color:#fff}.navbar-inverse .brand{color:#999}.navbar-inverse .navbar-text{color:#999}.navbar-inverse .nav>li>a:focus,.navbar-inverse .nav>li>a:hover{color:#fff;background-color:transparent}.navbar-inverse .nav .active>a,.navbar-inverse .nav .active>a:hover,.navbar-inverse .nav .active>a:focus{color:#fff;background-color:#111}.navbar-inverse .navbar-link{color:#999}.navbar-inverse .navbar-link:hover,.navbar-inverse .navbar-link:focus{color:#fff}.navbar-inverse .divider-vertical{border-right-color:#222;border-left-color:#111}.navbar-inverse .nav li.dropdown.open>.dropdown-toggle,.navbar-inverse .nav li.dropdown.active>.dropdown-toggle,.navbar-inverse .nav li.dropdown.open.active>.dropdown-toggle{color:#fff;background-color:#111}.navbar-inverse .nav li.dropdown>a:hover .caret,.navbar-inverse .nav li.dropdown>a:focus .caret{border-top-color:#fff;border-bottom-color:#fff}.navbar-inverse .nav li.dropdown>.dropdown-toggle .caret{border-top-color:#999;border-bottom-color:#999}.navbar-inverse .nav li.dropdown.open>.dropdown-toggle .caret,.navbar-inverse .nav li.dropdown.active>.dropdown-toggle .caret,.navbar-inverse .nav li.dropdown.open.active>.dropdown-toggle .caret{border-top-color:#fff;border-bottom-color:#fff}.navbar-inverse .navbar-search .search-query{color:#fff;background-color:#515151;border-color:#111;-webkit-box-shadow:inset 0 1px 2px rgba(0,0,0,0.1),0 1px 0 rgba(255,255,255,0.15);-moz-box-shadow:inset 0 1px 2px rgba(0,0,0,0.1),0 1px 0 rgba(255,255,255,0.15);box-shadow:inset 0 1px 2px rgba(0,0,0,0.1),0 1px 0 rgba(255,255,255,0.15);-webkit-transition:none;-moz-transition:none;-o-transition:none;transition:none}.navbar-inverse .navbar-search .search-query:-moz-placeholder{color:#ccc}.navbar-inverse .navbar-search .search-query:-ms-input-placeholder{color:#ccc}.navbar-inverse .navbar-search .search-query::-webkit-input-placeholder{color:#ccc}.navbar-inverse .navbar-search .search-query:focus,.navbar-inverse .navbar-search .search-query.focused{padding:5px 15px;color:#333;text-shadow:0 1px 0 #fff;background-color:#fff;border:0;outline:0;-webkit-box-shadow:0 0 3px rgba(0,0,0,0.15);-moz-box-shadow:0 0 3px rgba(0,0,0,0.15);box-shadow:0 0 3px rgba(0,0,0,0.15)}.navbar-inverse .btn-navbar{color:#fff;text-shadow:0 -1px 0 rgba(0,0,0,0.25);background-color:#0e0e0e;*background-color:#040404;background-image:-moz-linear-gradient(top,#151515,#040404);background-image:-webkit-gradient(linear,0 0,0 100%,from(#151515),to(#040404));background-image:-webkit-linear-gradient(top,#151515,#040404);background-image:-o-linear-gradient(top,#151515,#040404);background-image:linear-gradient(to bottom,#151515,#040404);background-repeat:repeat-x;border-color:#040404 #040404 #000;border-color:rgba(0,0,0,0.1) rgba(0,0,0,0.1) rgba(0,0,0,0.25);filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#ff151515',endColorstr='#ff040404',GradientType=0);filter:progid:DXImageTransform.Microsoft.gradient(enabled=false)}.navbar-inverse .btn-navbar:hover,.navbar-inverse .btn-navbar:focus,.navbar-inverse .btn-navbar:active,.navbar-inverse .btn-navbar.active,.navbar-inverse .btn-navbar.disabled,.navbar-inverse .btn-navbar[disabled]{color:#fff;background-color:#040404;*background-color:#000}.navbar-inverse .btn-navbar:active,.navbar-inverse .btn-navbar.active{background-color:#000 \9}.breadcrumb{padding:8px 15px;margin:0 0 20px;list-style:none;background-color:#f5f5f5;-webkit-border-radius:4px;-moz-border-radius:4px;border-radius:4px}.breadcrumb>li{display:inline-block;*display:inline;text-shadow:0 1px 0 #fff;*zoom:1}.breadcrumb>li>.divider{padding:0 5px;color:#ccc}.breadcrumb>.active{color:#999}.pagination{margin:20px 0}.pagination ul{display:inline-block;*display:inline;margin-bottom:0;margin-left:0;-webkit-border-radius:4px;-moz-border-radius:4px;border-radius:4px;*zoom:1;-webkit-box-shadow:0 1px 2px rgba(0,0,0,0.05);-moz-box-shadow:0 1px 2px rgba(0,0,0,0.05);box-shadow:0 1px 2px rgba(0,0,0,0.05)}.pagination ul>li{display:inline}.pagination ul>li>a,.pagination ul>li>span{float:left;padding:4px 12px;line-height:20px;text-decoration:none;background-color:#fff;border:1px solid #ddd;border-left-width:0}.pagination ul>li>a:hover,.pagination ul>li>a:focus,.pagination ul>.active>a,.pagination ul>.active>span{background-color:#f5f5f5}.pagination ul>.active>a,.pagination ul>.active>span{color:#999;cursor:default}.pagination ul>.disabled>span,.pagination ul>.disabled>a,.pagination ul>.disabled>a:hover,.pagination ul>.disabled>a:focus{color:#999;cursor:default;background-color:transparent}.pagination ul>li:first-child>a,.pagination ul>li:first-child>span{border-left-width:1px;-webkit-border-bottom-left-radius:4px;border-bottom-left-radius:4px;-webkit-border-top-left-radius:4px;border-top-left-radius:4px;-moz-border-radius-bottomleft:4px;-moz-border-radius-topleft:4px}.pagination ul>li:last-child>a,.pagination ul>li:last-child>span{-webkit-border-top-right-radius:4px;border-top-right-radius:4px;-webkit-border-bottom-right-radius:4px;border-bottom-right-radius:4px;-moz-border-radius-topright:4px;-moz-border-radius-bottomright:4px}.pagination-centered{text-align:center}.pagination-right{text-align:right}.pagination-large ul>li>a,.pagination-large ul>li>span{padding:11px 19px;font-size:17.5px}.pagination-large ul>li:first-child>a,.pagination-large ul>li:first-child>span{-webkit-border-bottom-left-radius:6px;border-bottom-left-radius:6px;-webkit-border-top-left-radius:6px;border-top-left-radius:6px;-moz-border-radius-bottomleft:6px;-moz-border-radius-topleft:6px}.pagination-large ul>li:last-child>a,.pagination-large ul>li:last-child>span{-webkit-border-top-right-radius:6px;border-top-right-radius:6px;-webkit-border-bottom-right-radius:6px;border-bottom-right-radius:6px;-moz-border-radius-topright:6px;-moz-border-radius-bottomright:6px}.pagination-mini ul>li:first-child>a,.pagination-small ul>li:first-child>a,.pagination-mini ul>li:first-child>span,.pagination-small ul>li:first-child>span{-webkit-border-bottom-left-radius:3px;border-bottom-left-radius:3px;-webkit-border-top-left-radius:3px;border-top-left-radius:3px;-moz-border-radius-bottomleft:3px;-moz-border-radius-topleft:3px}.pagination-mini ul>li:last-child>a,.pagination-small ul>li:last-child>a,.pagination-mini ul>li:last-child>span,.pagination-small ul>li:last-child>span{-webkit-border-top-right-radius:3px;border-top-right-radius:3px;-webkit-border-bottom-right-radius:3px;border-bottom-right-radius:3px;-moz-border-radius-topright:3px;-moz-border-radius-bottomright:3px}.pagination-small ul>li>a,.pagination-small ul>li>span{padding:2px 10px;font-size:11.9px}.pagination-mini ul>li>a,.pagination-mini ul>li>span{padding:0 6px;font-size:10.5px}.pager{margin:20px 0;text-align:center;list-style:none;*zoom:1}.pager:before,.pager:after{display:table;line-height:0;content:""}.pager:after{clear:both}.pager li{display:inline}.pager li>a,.pager li>span{display:inline-block;padding:5px 14px;background-color:#fff;border:1px solid #ddd;-webkit-border-radius:15px;-moz-border-radius:15px;border-radius:15px}.pager li>a:hover,.pager li>a:focus{text-decoration:none;background-color:#f5f5f5}.pager .next>a,.pager .next>span{float:right}.pager .previous>a,.pager .previous>span{float:left}.pager .disabled>a,.pager .disabled>a:hover,.pager .disabled>a:focus,.pager .disabled>span{color:#999;cursor:default;background-color:#fff}.modal-backdrop{position:fixed;top:0;right:0;bottom:0;left:0;z-index:1040;background-color:#000}.modal-backdrop.fade{opacity:0}.modal-backdrop,.modal-backdrop.fade.in{opacity:.8;filter:alpha(opacity=80)}.modal{position:fixed;top:10%;left:50%;z-index:1050;width:560px;margin-left:-280px;background-color:#fff;border:1px solid #999;border:1px solid rgba(0,0,0,0.3);*border:1px solid #999;-webkit-border-radius:6px;-moz-border-radius:6px;border-radius:6px;outline:0;-webkit-box-shadow:0 3px 7px rgba(0,0,0,0.3);-moz-box-shadow:0 3px 7px rgba(0,0,0,0.3);box-shadow:0 3px 7px rgba(0,0,0,0.3);-webkit-background-clip:padding-box;-moz-background-clip:padding-box;background-clip:padding-box}.modal.fade{top:-25%;-webkit-transition:opacity .3s linear,top .3s ease-out;-moz-transition:opacity .3s linear,top .3s ease-out;-o-transition:opacity .3s linear,top .3s ease-out;transition:opacity .3s linear,top .3s ease-out}.modal.fade.in{top:10%}.modal-header{padding:9px 15px;border-bottom:1px solid #eee}.modal-header .close{margin-top:2px}.modal-header h3{margin:0;line-height:30px}.modal-body{position:relative;max-height:400px;padding:15px;overflow-y:auto}.modal-form{margin-bottom:0}.modal-footer{padding:14px 15px 15px;margin-bottom:0;text-align:right;background-color:#f5f5f5;border-top:1px solid #ddd;-webkit-border-radius:0 0 6px 6px;-moz-border-radius:0 0 6px 6px;border-radius:0 0 6px 6px;*zoom:1;-webkit-box-shadow:inset 0 1px 0 #fff;-moz-box-shadow:inset 0 1px 0 #fff;box-shadow:inset 0 1px 0 #fff}.modal-footer:before,.modal-footer:after{display:table;line-height:0;content:""}.modal-footer:after{clear:both}.modal-footer .btn+.btn{margin-bottom:0;margin-left:5px}.modal-footer .btn-group .btn+.btn{margin-left:-1px}.modal-footer .btn-block+.btn-block{margin-left:0}.tooltip{position:absolute;z-index:1030;display:block;font-size:11px;line-height:1.4;opacity:0;filter:alpha(opacity=0);visibility:visible}.tooltip.in{opacity:.8;filter:alpha(opacity=80)}.tooltip.top{padding:5px 0;margin-top:-3px}.tooltip.right{padding:0 5px;margin-left:3px}.tooltip.bottom{padding:5px 0;margin-top:3px}.tooltip.left{padding:0 5px;margin-left:-3px}.tooltip-inner{max-width:200px;padding:8px;color:#fff;text-align:center;text-decoration:none;background-color:#000;-webkit-border-radius:4px;-moz-border-radius:4px;border-radius:4px}.tooltip-arrow{position:absolute;width:0;height:0;border-color:transparent;border-style:solid}.tooltip.top .tooltip-arrow{bottom:0;left:50%;margin-left:-5px;border-top-color:#000;border-width:5px 5px 0}.tooltip.right .tooltip-arrow{top:50%;left:0;margin-top:-5px;border-right-color:#000;border-width:5px 5px 5px 0}.tooltip.left .tooltip-arrow{top:50%;right:0;margin-top:-5px;border-left-color:#000;border-width:5px 0 5px 5px}.tooltip.bottom .tooltip-arrow{top:0;left:50%;margin-left:-5px;border-bottom-color:#000;border-width:0 5px 5px}.popover{position:absolute;top:0;left:0;z-index:1010;display:none;max-width:276px;padding:1px;text-align:left;white-space:normal;background-color:#fff;border:1px solid #ccc;border:1px solid rgba(0,0,0,0.2);-webkit-border-radius:6px;-moz-border-radius:6px;border-radius:6px;-webkit-box-shadow:0 5px 10px rgba(0,0,0,0.2);-moz-box-shadow:0 5px 10px rgba(0,0,0,0.2);box-shadow:0 5px 10px rgba(0,0,0,0.2);-webkit-background-clip:padding-box;-moz-background-clip:padding;background-clip:padding-box}.popover.top{margin-top:-10px}.popover.right{margin-left:10px}.popover.bottom{margin-top:10px}.popover.left{margin-left:-10px}.popover-title{padding:8px 14px;margin:0;font-size:14px;font-weight:normal;line-height:18px;background-color:#f7f7f7;border-bottom:1px solid #ebebeb;-webkit-border-radius:5px 5px 0 0;-moz-border-radius:5px 5px 0 0;border-radius:5px 5px 0 0}.popover-title:empty{display:none}.popover-content{padding:9px 14px}.popover .arrow,.popover .arrow:after{position:absolute;display:block;width:0;height:0;border-color:transparent;border-style:solid}.popover .arrow{border-width:11px}.popover .arrow:after{border-width:10px;content:""}.popover.top .arrow{bottom:-11px;left:50%;margin-left:-11px;border-top-color:#999;border-top-color:rgba(0,0,0,0.25);border-bottom-width:0}.popover.top .arrow:after{bottom:1px;margin-left:-10px;border-top-color:#fff;border-bottom-width:0}.popover.right .arrow{top:50%;left:-11px;margin-top:-11px;border-right-color:#999;border-right-color:rgba(0,0,0,0.25);border-left-width:0}.popover.right .arrow:after{bottom:-10px;left:1px;border-right-color:#fff;border-left-width:0}.popover.bottom .arrow{top:-11px;left:50%;margin-left:-11px;border-bottom-color:#999;border-bottom-color:rgba(0,0,0,0.25);border-top-width:0}.popover.bottom .arrow:after{top:1px;margin-left:-10px;border-bottom-color:#fff;border-top-width:0}.popover.left .arrow{top:50%;right:-11px;margin-top:-11px;border-left-color:#999;border-left-color:rgba(0,0,0,0.25);border-right-width:0}.popover.left .arrow:after{right:1px;bottom:-10px;border-left-color:#fff;border-right-width:0}.thumbnails{margin-left:-20px;list-style:none;*zoom:1}.thumbnails:before,.thumbnails:after{display:table;line-height:0;content:""}.thumbnails:after{clear:both}.row-fluid .thumbnails{margin-left:0}.thumbnails>li{float:left;margin-bottom:20px;margin-left:20px}.thumbnail{display:block;padding:4px;line-height:20px;border:1px solid #ddd;-webkit-border-radius:4px;-moz-border-radius:4px;border-radius:4px;-webkit-box-shadow:0 1px 3px rgba(0,0,0,0.055);-moz-box-shadow:0 1px 3px rgba(0,0,0,0.055);box-shadow:0 1px 3px rgba(0,0,0,0.055);-webkit-transition:all .2s ease-in-out;-moz-transition:all .2s ease-in-out;-o-transition:all .2s ease-in-out;transition:all .2s ease-in-out}a.thumbnail:hover,a.thumbnail:focus{border-color:#08c;-webkit-box-shadow:0 1px 4px rgba(0,105,214,0.25);-moz-box-shadow:0 1px 4px rgba(0,105,214,0.25);box-shadow:0 1px 4px rgba(0,105,214,0.25)}.thumbnail>img{display:block;max-width:100%;margin-right:auto;margin-left:auto}.thumbnail .caption{padding:9px;color:#555}.media,.media-body{overflow:hidden;*overflow:visible;zoom:1}.media,.media .media{margin-top:15px}.media:first-child{margin-top:0}.media-object{display:block}.media-heading{margin:0 0 5px}.media>.pull-left{margin-right:10px}.media>.pull-right{margin-left:10px}.media-list{margin-left:0;list-style:none}.label,.badge{display:inline-block;padding:2px 4px;font-size:11.844px;font-weight:bold;line-height:14px;color:#fff;text-shadow:0 -1px 0 rgba(0,0,0,0.25);white-space:nowrap;vertical-align:baseline;background-color:#999}.label{-webkit-border-radius:3px;-moz-border-radius:3px;border-radius:3px}.badge{padding-right:9px;padding-left:9px;-webkit-border-radius:9px;-moz-border-radius:9px;border-radius:9px}.label:empty,.badge:empty{display:none}a.label:hover,a.label:focus,a.badge:hover,a.badge:focus{color:#fff;text-decoration:none;cursor:pointer}.label-important,.badge-important{background-color:#b94a48}.label-important[href],.badge-important[href]{background-color:#953b39}.label-warning,.badge-warning{background-color:#f89406}.label-warning[href],.badge-warning[href]{background-color:#c67605}.label-success,.badge-success{background-color:#468847}.label-success[href],.badge-success[href]{background-color:#356635}.label-info,.badge-info{background-color:#3a87ad}.label-info[href],.badge-info[href]{background-color:#2d6987}.label-inverse,.badge-inverse{background-color:#333}.label-inverse[href],.badge-inverse[href]{background-color:#1a1a1a}.btn .label,.btn .badge{position:relative;top:-1px}.btn-mini .label,.btn-mini .badge{top:0}@-webkit-keyframes progress-bar-stripes{from{background-position:40px 0}to{background-position:0 0}}@-moz-keyframes progress-bar-stripes{from{background-position:40px 0}to{background-position:0 0}}@-ms-keyframes progress-bar-stripes{from{background-position:40px 0}to{background-position:0 0}}@-o-keyframes progress-bar-stripes{from{background-position:0 0}to{background-position:40px 0}}@keyframes progress-bar-stripes{from{background-position:40px 0}to{background-position:0 0}}.progress{height:20px;margin-bottom:20px;overflow:hidden;background-color:#f7f7f7;background-image:-moz-linear-gradient(top,#f5f5f5,#f9f9f9);background-image:-webkit-gradient(linear,0 0,0 100%,from(#f5f5f5),to(#f9f9f9));background-image:-webkit-linear-gradient(top,#f5f5f5,#f9f9f9);background-image:-o-linear-gradient(top,#f5f5f5,#f9f9f9);background-image:linear-gradient(to bottom,#f5f5f5,#f9f9f9);background-repeat:repeat-x;-webkit-border-radius:4px;-moz-border-radius:4px;border-radius:4px;filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#fff5f5f5',endColorstr='#fff9f9f9',GradientType=0);-webkit-box-shadow:inset 0 1px 2px rgba(0,0,0,0.1);-moz-box-shadow:inset 0 1px 2px rgba(0,0,0,0.1);box-shadow:inset 0 1px 2px rgba(0,0,0,0.1)}.progress .bar{float:left;width:0;height:100%;font-size:12px;color:#fff;text-align:center;text-shadow:0 -1px 0 rgba(0,0,0,0.25);background-color:#0e90d2;background-image:-moz-linear-gradient(top,#149bdf,#0480be);background-image:-webkit-gradient(linear,0 0,0 100%,from(#149bdf),to(#0480be));background-image:-webkit-linear-gradient(top,#149bdf,#0480be);background-image:-o-linear-gradient(top,#149bdf,#0480be);background-image:linear-gradient(to bottom,#149bdf,#0480be);background-repeat:repeat-x;filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#ff149bdf',endColorstr='#ff0480be',GradientType=0);-webkit-box-shadow:inset 0 -1px 0 rgba(0,0,0,0.15);-moz-box-shadow:inset 0 -1px 0 rgba(0,0,0,0.15);box-shadow:inset 0 -1px 0 rgba(0,0,0,0.15);-webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box;-webkit-transition:width .6s ease;-moz-transition:width .6s ease;-o-transition:width .6s ease;transition:width .6s ease}.progress .bar+.bar{-webkit-box-shadow:inset 1px 0 0 rgba(0,0,0,0.15),inset 0 -1px 0 rgba(0,0,0,0.15);-moz-box-shadow:inset 1px 0 0 rgba(0,0,0,0.15),inset 0 -1px 0 rgba(0,0,0,0.15);box-shadow:inset 1px 0 0 rgba(0,0,0,0.15),inset 0 -1px 0 rgba(0,0,0,0.15)}.progress-striped .bar{background-color:#149bdf;background-image:-webkit-gradient(linear,0 100%,100% 0,color-stop(0.25,rgba(255,255,255,0.15)),color-stop(0.25,transparent),color-stop(0.5,transparent),color-stop(0.5,rgba(255,255,255,0.15)),color-stop(0.75,rgba(255,255,255,0.15)),color-stop(0.75,transparent),to(transparent));background-image:-webkit-linear-gradient(45deg,rgba(255,255,255,0.15) 25%,transparent 25%,transparent 50%,rgba(255,255,255,0.15) 50%,rgba(255,255,255,0.15) 75%,transparent 75%,transparent);background-image:-moz-linear-gradient(45deg,rgba(255,255,255,0.15) 25%,transparent 25%,transparent 50%,rgba(255,255,255,0.15) 50%,rgba(255,255,255,0.15) 75%,transparent 75%,transparent);background-image:-o-linear-gradient(45deg,rgba(255,255,255,0.15) 25%,transparent 25%,transparent 50%,rgba(255,255,255,0.15) 50%,rgba(255,255,255,0.15) 75%,transparent 75%,transparent);background-image:linear-gradient(45deg,rgba(255,255,255,0.15) 25%,transparent 25%,transparent 50%,rgba(255,255,255,0.15) 50%,rgba(255,255,255,0.15) 75%,transparent 75%,transparent);-webkit-background-size:40px 40px;-moz-background-size:40px 40px;-o-background-size:40px 40px;background-size:40px 40px}.progress.active .bar{-webkit-animation:progress-bar-stripes 2s linear infinite;-moz-animation:progress-bar-stripes 2s linear infinite;-ms-animation:progress-bar-stripes 2s linear infinite;-o-animation:progress-bar-stripes 2s linear infinite;animation:progress-bar-stripes 2s linear infinite}.progress-danger .bar,.progress .bar-danger{background-color:#dd514c;background-image:-moz-linear-gradient(top,#ee5f5b,#c43c35);background-image:-webkit-gradient(linear,0 0,0 100%,from(#ee5f5b),to(#c43c35));background-image:-webkit-linear-gradient(top,#ee5f5b,#c43c35);background-image:-o-linear-gradient(top,#ee5f5b,#c43c35);background-image:linear-gradient(to bottom,#ee5f5b,#c43c35);background-repeat:repeat-x;filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#ffee5f5b',endColorstr='#ffc43c35',GradientType=0)}.progress-danger.progress-striped .bar,.progress-striped .bar-danger{background-color:#ee5f5b;background-image:-webkit-gradient(linear,0 100%,100% 0,color-stop(0.25,rgba(255,255,255,0.15)),color-stop(0.25,transparent),color-stop(0.5,transparent),color-stop(0.5,rgba(255,255,255,0.15)),color-stop(0.75,rgba(255,255,255,0.15)),color-stop(0.75,transparent),to(transparent));background-image:-webkit-linear-gradient(45deg,rgba(255,255,255,0.15) 25%,transparent 25%,transparent 50%,rgba(255,255,255,0.15) 50%,rgba(255,255,255,0.15) 75%,transparent 75%,transparent);background-image:-moz-linear-gradient(45deg,rgba(255,255,255,0.15) 25%,transparent 25%,transparent 50%,rgba(255,255,255,0.15) 50%,rgba(255,255,255,0.15) 75%,transparent 75%,transparent);background-image:-o-linear-gradient(45deg,rgba(255,255,255,0.15) 25%,transparent 25%,transparent 50%,rgba(255,255,255,0.15) 50%,rgba(255,255,255,0.15) 75%,transparent 75%,transparent);background-image:linear-gradient(45deg,rgba(255,255,255,0.15) 25%,transparent 25%,transparent 50%,rgba(255,255,255,0.15) 50%,rgba(255,255,255,0.15) 75%,transparent 75%,transparent)}.progress-success .bar,.progress .bar-success{background-color:#5eb95e;background-image:-moz-linear-gradient(top,#62c462,#57a957);background-image:-webkit-gradient(linear,0 0,0 100%,from(#62c462),to(#57a957));background-image:-webkit-linear-gradient(top,#62c462,#57a957);background-image:-o-linear-gradient(top,#62c462,#57a957);background-image:linear-gradient(to bottom,#62c462,#57a957);background-repeat:repeat-x;filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#ff62c462',endColorstr='#ff57a957',GradientType=0)}.progress-success.progress-striped .bar,.progress-striped .bar-success{background-color:#62c462;background-image:-webkit-gradient(linear,0 100%,100% 0,color-stop(0.25,rgba(255,255,255,0.15)),color-stop(0.25,transparent),color-stop(0.5,transparent),color-stop(0.5,rgba(255,255,255,0.15)),color-stop(0.75,rgba(255,255,255,0.15)),color-stop(0.75,transparent),to(transparent));background-image:-webkit-linear-gradient(45deg,rgba(255,255,255,0.15) 25%,transparent 25%,transparent 50%,rgba(255,255,255,0.15) 50%,rgba(255,255,255,0.15) 75%,transparent 75%,transparent);background-image:-moz-linear-gradient(45deg,rgba(255,255,255,0.15) 25%,transparent 25%,transparent 50%,rgba(255,255,255,0.15) 50%,rgba(255,255,255,0.15) 75%,transparent 75%,transparent);background-image:-o-linear-gradient(45deg,rgba(255,255,255,0.15) 25%,transparent 25%,transparent 50%,rgba(255,255,255,0.15) 50%,rgba(255,255,255,0.15) 75%,transparent 75%,transparent);background-image:linear-gradient(45deg,rgba(255,255,255,0.15) 25%,transparent 25%,transparent 50%,rgba(255,255,255,0.15) 50%,rgba(255,255,255,0.15) 75%,transparent 75%,transparent)}.progress-info .bar,.progress .bar-info{background-color:#4bb1cf;background-image:-moz-linear-gradient(top,#5bc0de,#339bb9);background-image:-webkit-gradient(linear,0 0,0 100%,from(#5bc0de),to(#339bb9));background-image:-webkit-linear-gradient(top,#5bc0de,#339bb9);background-image:-o-linear-gradient(top,#5bc0de,#339bb9);background-image:linear-gradient(to bottom,#5bc0de,#339bb9);background-repeat:repeat-x;filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#ff5bc0de',endColorstr='#ff339bb9',GradientType=0)}.progress-info.progress-striped .bar,.progress-striped .bar-info{background-color:#5bc0de;background-image:-webkit-gradient(linear,0 100%,100% 0,color-stop(0.25,rgba(255,255,255,0.15)),color-stop(0.25,transparent),color-stop(0.5,transparent),color-stop(0.5,rgba(255,255,255,0.15)),color-stop(0.75,rgba(255,255,255,0.15)),color-stop(0.75,transparent),to(transparent));background-image:-webkit-linear-gradient(45deg,rgba(255,255,255,0.15) 25%,transparent 25%,transparent 50%,rgba(255,255,255,0.15) 50%,rgba(255,255,255,0.15) 75%,transparent 75%,transparent);background-image:-moz-linear-gradient(45deg,rgba(255,255,255,0.15) 25%,transparent 25%,transparent 50%,rgba(255,255,255,0.15) 50%,rgba(255,255,255,0.15) 75%,transparent 75%,transparent);background-image:-o-linear-gradient(45deg,rgba(255,255,255,0.15) 25%,transparent 25%,transparent 50%,rgba(255,255,255,0.15) 50%,rgba(255,255,255,0.15) 75%,transparent 75%,transparent);background-image:linear-gradient(45deg,rgba(255,255,255,0.15) 25%,transparent 25%,transparent 50%,rgba(255,255,255,0.15) 50%,rgba(255,255,255,0.15) 75%,transparent 75%,transparent)}.progress-warning .bar,.progress .bar-warning{background-color:#faa732;background-image:-moz-linear-gradient(top,#fbb450,#f89406);background-image:-webkit-gradient(linear,0 0,0 100%,from(#fbb450),to(#f89406));background-image:-webkit-linear-gradient(top,#fbb450,#f89406);background-image:-o-linear-gradient(top,#fbb450,#f89406);background-image:linear-gradient(to bottom,#fbb450,#f89406);background-repeat:repeat-x;filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#fffbb450',endColorstr='#fff89406',GradientType=0)}.progress-warning.progress-striped .bar,.progress-striped .bar-warning{background-color:#fbb450;background-image:-webkit-gradient(linear,0 100%,100% 0,color-stop(0.25,rgba(255,255,255,0.15)),color-stop(0.25,transparent),color-stop(0.5,transparent),color-stop(0.5,rgba(255,255,255,0.15)),color-stop(0.75,rgba(255,255,255,0.15)),color-stop(0.75,transparent),to(transparent));background-image:-webkit-linear-gradient(45deg,rgba(255,255,255,0.15) 25%,transparent 25%,transparent 50%,rgba(255,255,255,0.15) 50%,rgba(255,255,255,0.15) 75%,transparent 75%,transparent);background-image:-moz-linear-gradient(45deg,rgba(255,255,255,0.15) 25%,transparent 25%,transparent 50%,rgba(255,255,255,0.15) 50%,rgba(255,255,255,0.15) 75%,transparent 75%,transparent);background-image:-o-linear-gradient(45deg,rgba(255,255,255,0.15) 25%,transparent 25%,transparent 50%,rgba(255,255,255,0.15) 50%,rgba(255,255,255,0.15) 75%,transparent 75%,transparent);background-image:linear-gradient(45deg,rgba(255,255,255,0.15) 25%,transparent 25%,transparent 50%,rgba(255,255,255,0.15) 50%,rgba(255,255,255,0.15) 75%,transparent 75%,transparent)}.accordion{margin-bottom:20px}.accordion-group{margin-bottom:2px;border:1px solid #e5e5e5;-webkit-border-radius:4px;-moz-border-radius:4px;border-radius:4px}.accordion-heading{border-bottom:0}.accordion-heading .accordion-toggle{display:block;padding:8px 15px}.accordion-toggle{cursor:pointer}.accordion-inner{padding:9px 15px;border-top:1px solid #e5e5e5}.carousel{position:relative;margin-bottom:20px;line-height:1}.carousel-inner{position:relative;width:100%;overflow:hidden}.carousel-inner>.item{position:relative;display:none;-webkit-transition:.6s ease-in-out left;-moz-transition:.6s ease-in-out left;-o-transition:.6s ease-in-out left;transition:.6s ease-in-out left}.carousel-inner>.item>img,.carousel-inner>.item>a>img{display:block;line-height:1}.carousel-inner>.active,.carousel-inner>.next,.carousel-inner>.prev{display:block}.carousel-inner>.active{left:0}.carousel-inner>.next,.carousel-inner>.prev{position:absolute;top:0;width:100%}.carousel-inner>.next{left:100%}.carousel-inner>.prev{left:-100%}.carousel-inner>.next.left,.carousel-inner>.prev.right{left:0}.carousel-inner>.active.left{left:-100%}.carousel-inner>.active.right{left:100%}.carousel-control{position:absolute;top:40%;left:15px;width:40px;height:40px;margin-top:-20px;font-size:60px;font-weight:100;line-height:30px;color:#fff;text-align:center;background:#222;border:3px solid #fff;-webkit-border-radius:23px;-moz-border-radius:23px;border-radius:23px;opacity:.5;filter:alpha(opacity=50)}.carousel-control.right{right:15px;left:auto}.carousel-control:hover,.carousel-control:focus{color:#fff;text-decoration:none;opacity:.9;filter:alpha(opacity=90)}.carousel-indicators{position:absolute;top:15px;right:15px;z-index:5;margin:0;list-style:none}.carousel-indicators li{display:block;float:left;width:10px;height:10px;margin-left:5px;text-indent:-999px;background-color:#ccc;background-color:rgba(255,255,255,0.25);border-radius:5px}.carousel-indicators .active{background-color:#fff}.carousel-caption{position:absolute;right:0;bottom:0;left:0;padding:15px;background:#333;background:rgba(0,0,0,0.75)}.carousel-caption h4,.carousel-caption p{line-height:20px;color:#fff}.carousel-caption h4{margin:0 0 5px}.carousel-caption p{margin-bottom:0}.hero-unit{padding:60px;margin-bottom:30px;font-size:18px;font-weight:200;line-height:30px;color:inherit;background-color:#eee;-webkit-border-radius:6px;-moz-border-radius:6px;border-radius:6px}.hero-unit h1{margin-bottom:0;font-size:60px;line-height:1;letter-spacing:-1px;color:inherit}.hero-unit li{line-height:30px}.pull-right{float:right}.pull-left{float:left}.hide{display:none}.show{display:block}.invisible{visibility:hidden}.affix{position:fixed}
                                             master/css/                                                                                         000755  000767  000024  00000000000 12152167061 013600  5                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         master/css/UserSetup.css                                                                            000644  000767  000024  00000000652 12170066275 016261  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         html {
  background-color: #FFFFFF;
}
body {
  background: transparent;
}
.container-fluid {
  padding: 5px;
  background: #B7E3E4;
}
.container div .well .form-horizontal .control-group .controls select.select-primary-outcome {
  width: 100%;
}
.container-fluid.container-fluid-footer {
  padding: 20px;
  background: #FAA61A;
}
.light-grey {
  background-color: #808080;
}
.dotted_underline {
   border-bottom: 1px dotted;
}                                                                                      master/datepicker/                                                                                  000755  000767  000024  00000000000 12136504245 015124  5                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         master/datepicker/build/                                                                            000755  000767  000024  00000000000 12136504245 016223  5                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         master/datepicker/css/                                                                              000755  000767  000024  00000000000 12136504245 015714  5                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         master/datepicker/js/                                                                               000755  000767  000024  00000000000 12136504245 015540  5                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         master/datepicker/less/                                                                             000755  000767  000024  00000000000 12136504245 016072  5                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         master/datepicker/less/datepicker.less                                                              000644  000767  000024  00000010355 12136504245 021101  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /*!
 * Datepicker for Bootstrap
 *
 * Copyright 2012 Stefan Petre
 * Improvements by Andrew Rowls
 * Licensed under the Apache License v2.0
 * http://www.apache.org/licenses/LICENSE-2.0
 *
 */

.datepicker {
	padding: 4px;
	.border-radius(4px);
	&-inline {
		width: 220px;
	}
	direction: ltr;
	&&-rtl {
		direction: rtl;
		table tr td span {
			float: right;
		}
	}
	&-dropdown {
		top: 0;
		left: 0;
		&:before {
			content: '';
			display: inline-block;
			border-left:   7px solid transparent;
			border-right:  7px solid transparent;
			border-bottom: 7px solid #ccc;
			border-bottom-color: rgba(0,0,0,.2);
			position: absolute;
			top: -7px;
			left: 6px;
		}
		&:after {
			content: '';
			display: inline-block;
			border-left:   6px solid transparent;
			border-right:  6px solid transparent;
			border-bottom: 6px solid @white;
			position: absolute;
			top: -6px;
			left: 7px;
		}
	}
	>div {
		display: none;
	}
	&.days div.datepicker-days {
		display: block;
	}
	&.months div.datepicker-months {
		display: block;
	}
	&.years div.datepicker-years {
		display: block;
	}
	table{
		margin: 0;
	}
	td,
	th{
		text-align: center;
		width: 20px;
		height: 20px;
		.border-radius(4px);

		border: none;
	}
	// Inline display inside a table presents some problems with
	// border and background colors.
	.table-striped & table tr {
		td, th {
			background-color:transparent;
		}
	}
	table tr td {
		&.day:hover {
			background: @grayLighter;
			cursor: pointer;
		}
		&.old,
		&.new {
			color: @grayLight;
		}
		&.disabled,
		&.disabled:hover {
			background: none;
			color: @grayLight;
			cursor: default;
		}
		&.today,
		&.today:hover,
		&.today.disabled,
		&.today.disabled:hover {
			@todayBackground: lighten(@orange, 30%);
			.buttonBackground(@todayBackground, spin(@todayBackground, 20));
			color: #000 !important;
		}
		&.range,
		&.range:hover,
		&.range.disabled,
		&.range.disabled:hover {
			background:@grayLighter;
			.border-radius(0);
		}
		&.range.today,
		&.range.today:hover,
		&.range.today.disabled,
		&.range.today.disabled:hover {
			@todayBackground: mix(@orange, @grayLighter);
			.buttonBackground(@todayBackground, spin(@todayBackground, 20));
			.border-radius(0);
		}
		&.selected,
		&.selected:hover,
		&.selected.disabled,
		&.selected.disabled:hover {
			.buttonBackground(lighten(@grayLight, 10), darken(@grayLight, 10));
			color: #fff;
			text-shadow: 0 -1px 0 rgba(0,0,0,.25);
		}
		&.active,
		&.active:hover,
		&.active.disabled,
		&.active.disabled:hover {
			.buttonBackground(@btnPrimaryBackground, spin(@btnPrimaryBackground, 20));
			color: #fff;
			text-shadow: 0 -1px 0 rgba(0,0,0,.25);
		}
		span {
			display: block;
			width: 23%;
			height: 54px;
			line-height: 54px;
			float: left;
			margin: 1%;
			cursor: pointer;
			.border-radius(4px);
			&:hover {
				background: @grayLighter;
			}
			&.disabled,
			&.disabled:hover {
				background:none;
				color: @grayLight;
				cursor: default;
			}
			&.active,
			&.active:hover,
			&.active.disabled,
			&.active.disabled:hover {
				.buttonBackground(@btnPrimaryBackground, spin(@btnPrimaryBackground, 20));
				color: #fff;
				text-shadow: 0 -1px 0 rgba(0,0,0,.25);
			}
			&.old {
				color: @grayLight;
			}
		}
	}

	th.datepicker-switch {
		width: 145px;
	}

	thead tr:first-child th,
	tfoot tr:first-child th {
		cursor: pointer;
		&:hover{
			background: @grayLighter;
		}
	}
	/*.dow {
		border-top: 1px solid #ddd !important;
	}*/

	// Basic styling for calendar-week cells
	.cw {
		font-size: 10px;
		width: 12px;
		padding: 0 2px 0 5px;
		vertical-align: middle;
	}
	thead tr:first-child th.cw {
		cursor: default;
		background-color: transparent;
	}
}
.input-append,
.input-prepend {
	&.date {
		.add-on i {
			display: block;
			cursor: pointer;
			width: 16px;
			height: 16px;
		}
	}
}
.input-daterange {
	input {
		text-align:center;
	}
	input:first-child {
		.border-radius(3px 0 0 3px);
	}
	input:last-child {
		.border-radius(0 3px 3px 0);
	}
	.add-on {
		display: inline-block;
		width: auto;
		min-width: 16px;
		height: @baseLineHeight;
		padding: 4px 5px;
		font-weight: normal;
		line-height: @baseLineHeight;
		text-align: center;
		text-shadow: 0 1px 0 @white;
		vertical-align: middle;
		background-color: @grayLighter;
		border: 1px solid #ccc;
		margin-left:-5px;
		margin-right:-5px;
	}
}
                                                                                                                                                                                                                                                                                   master/datepicker/js/bootstrap-datepicker.js                                                        000644  000767  000024  00000105326 12136504245 022233  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /* =========================================================
 * bootstrap-datepicker.js
 * http://www.eyecon.ro/bootstrap-datepicker
 * =========================================================
 * Copyright 2012 Stefan Petre
 * Improvements by Andrew Rowls
 *
 * Licensed under the Apache License, Version 2.0 (the "License");
 * you may not use this file except in compliance with the License.
 * You may obtain a copy of the License at
 *
 * http://www.apache.org/licenses/LICENSE-2.0
 *
 * Unless required by applicable law or agreed to in writing, software
 * distributed under the License is distributed on an "AS IS" BASIS,
 * WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 * See the License for the specific language governing permissions and
 * limitations under the License.
 * ========================================================= */

!function( $ ) {

	function UTCDate(){
		return new Date(Date.UTC.apply(Date, arguments));
	}
	function UTCToday(){
		var today = new Date();
		return UTCDate(today.getUTCFullYear(), today.getUTCMonth(), today.getUTCDate());
	}

	// Picker object

	var Datepicker = function(element, options) {
		var that = this;

		this.element = $(element);
		this.language = options.language||this.element.data('date-language')||"en";
		this.language = this.language in dates ? this.language : this.language.split('-')[0]; //Check if "de-DE" style date is available, if not language should fallback to 2 letter code eg "de"
		this.language = this.language in dates ? this.language : "en";
		this.isRTL = dates[this.language].rtl||false;
		this.format = DPGlobal.parseFormat(options.format||this.element.data('date-format')||dates[this.language].format||'mm/dd/yyyy');
		this.isInline = false;
		this.isInput = this.element.is('input');
		this.component = this.element.is('.date') ? this.element.find('.add-on, .btn') : false;
		this.hasInput = this.component && this.element.find('input').length;
		if(this.component && this.component.length === 0)
			this.component = false;

		this.forceParse = true;
		if ('forceParse' in options) {
			this.forceParse = options.forceParse;
		} else if ('dateForceParse' in this.element.data()) {
			this.forceParse = this.element.data('date-force-parse');
		}

		this.picker = $(DPGlobal.template);
		this._buildEvents();
		this._attachEvents();

		if(this.isInline) {
			this.picker.addClass('datepicker-inline').appendTo(this.element);
		} else {
			this.picker.addClass('datepicker-dropdown dropdown-menu');
		}
		if (this.isRTL){
			this.picker.addClass('datepicker-rtl');
			this.picker.find('.prev i, .next i')
						.toggleClass('icon-arrow-left icon-arrow-right');
		}

		this.autoclose = false;
		if ('autoclose' in options) {
			this.autoclose = options.autoclose;
		} else if ('dateAutoclose' in this.element.data()) {
			this.autoclose = this.element.data('date-autoclose');
		}

		this.keyboardNavigation = true;
		if ('keyboardNavigation' in options) {
			this.keyboardNavigation = options.keyboardNavigation;
		} else if ('dateKeyboardNavigation' in this.element.data()) {
			this.keyboardNavigation = this.element.data('date-keyboard-navigation');
		}

		this.viewMode = this.startViewMode = 0;
		switch(options.startView || this.element.data('date-start-view')){
			case 2:
			case 'decade':
				this.viewMode = this.startViewMode = 2;
				break;
			case 1:
			case 'year':
				this.viewMode = this.startViewMode = 1;
				break;
		}

		this.minViewMode = options.minViewMode||this.element.data('date-min-view-mode')||0;
		if (typeof this.minViewMode === 'string') {
			switch (this.minViewMode) {
				case 'months':
					this.minViewMode = 1;
					break;
				case 'years':
					this.minViewMode = 2;
					break;
				default:
					this.minViewMode = 0;
					break;
			}
		}

		this.viewMode = this.startViewMode = Math.max(this.startViewMode, this.minViewMode);

		this.todayBtn = (options.todayBtn||this.element.data('date-today-btn')||false);
		this.todayHighlight = (options.todayHighlight||this.element.data('date-today-highlight')||false);

		this.calendarWeeks = false;
		if ('calendarWeeks' in options) {
			this.calendarWeeks = options.calendarWeeks;
		} else if ('dateCalendarWeeks' in this.element.data()) {
			this.calendarWeeks = this.element.data('date-calendar-weeks');
		}
		if (this.calendarWeeks)
			this.picker.find('tfoot th.today')
						.attr('colspan', function(i, val){
							return parseInt(val) + 1;
						});

		this._allow_update = false;

		this.weekStart = ((options.weekStart||this.element.data('date-weekstart')||dates[this.language].weekStart||0) % 7);
		this.weekEnd = ((this.weekStart + 6) % 7);
		this.startDate = -Infinity;
		this.endDate = Infinity;
		this.daysOfWeekDisabled = [];
		this.setStartDate(options.startDate||this.element.data('date-startdate'));
		this.setEndDate(options.endDate||this.element.data('date-enddate'));
		this.setDaysOfWeekDisabled(options.daysOfWeekDisabled||this.element.data('date-days-of-week-disabled'));
		this.fillDow();
		this.fillMonths();
		this.setRange(options.range);

		this._allow_update = true;

		this.update();
		this.showMode();

		if(this.isInline) {
			this.show();
		}
	};

	Datepicker.prototype = {
		constructor: Datepicker,

		_events: [],
		_secondaryEvents: [],
		_applyEvents: function(evs){
			for (var i=0, el, ev; i<evs.length; i++){
				el = evs[i][0];
				ev = evs[i][1];
				el.on(ev);
			}
		},
		_unapplyEvents: function(evs){
			for (var i=0, el, ev; i<evs.length; i++){
				el = evs[i][0];
				ev = evs[i][1];
				el.off(ev);
			}
		},
		_buildEvents: function(){
			if (this.isInput) { // single input
				this._events = [
					[this.element, {
						focus: $.proxy(this.show, this),
						keyup: $.proxy(this.update, this),
						keydown: $.proxy(this.keydown, this)
					}]
				];
			}
			else if (this.component && this.hasInput){ // component: input + button
				this._events = [
					// For components that are not readonly, allow keyboard nav
					[this.element.find('input'), {
						focus: $.proxy(this.show, this),
						keyup: $.proxy(this.update, this),
						keydown: $.proxy(this.keydown, this)
					}],
					[this.component, {
						click: $.proxy(this.show, this)
					}]
				];
			}
			else if (this.element.is('div')) {  // inline datepicker
				this.isInline = true;
			}
			else {
				this._events = [
					[this.element, {
						click: $.proxy(this.show, this)
					}]
				];
			}

			this._secondaryEvents = [
				[this.picker, {
					click: $.proxy(this.click, this)
				}],
				[$(window), {
					resize: $.proxy(this.place, this)
				}],
				[$(document), {
					mousedown: $.proxy(function (e) {
						// Clicked outside the datepicker, hide it
						if ($(e.target).closest('.datepicker.datepicker-inline, .datepicker.datepicker-dropdown').length === 0) {
							this.hide();
						}
					}, this)
				}]
			];
		},
		_attachEvents: function(){
			this._detachEvents();
			this._applyEvents(this._events);
		},
		_detachEvents: function(){
			this._unapplyEvents(this._events);
		},
		_attachSecondaryEvents: function(){
			this._detachSecondaryEvents();
			this._applyEvents(this._secondaryEvents);
		},
		_detachSecondaryEvents: function(){
			this._unapplyEvents(this._secondaryEvents);
		},

		show: function(e) {
			if (!this.isInline)
				this.picker.appendTo('body');
			this.picker.show();
			this.height = this.component ? this.component.outerHeight() : this.element.outerHeight();
			this.place();
			this._attachSecondaryEvents();
			if (e) {
				e.preventDefault();
			}
			this.element.trigger({
				type: 'show',
				date: this.date
			});
		},

		hide: function(e){
			if(this.isInline) return;
			if (!this.picker.is(':visible')) return;
			this.picker.hide().detach();
			this._detachSecondaryEvents();
			this.viewMode = this.startViewMode;
			this.showMode();

			if (
				this.forceParse &&
				(
					this.isInput && this.element.val() ||
					this.hasInput && this.element.find('input').val()
				)
			)
				this.setValue();
			this.element.trigger({
				type: 'hide',
				date: this.date
			});
		},

		remove: function() {
			this.hide();
			this._detachEvents();
			this._detachSecondaryEvents();
			this.picker.remove();
			delete this.element.data().datepicker;
			if (!this.isInput) {
				delete this.element.data().date;
			}
		},

		getDate: function() {
			var d = this.getUTCDate();
			return new Date(d.getTime() + (d.getTimezoneOffset()*60000));
		},

		getUTCDate: function() {
			return this.date;
		},

		setDate: function(d) {
			this.setUTCDate(new Date(d.getTime() - (d.getTimezoneOffset()*60000)));
		},

		setUTCDate: function(d) {
			this.date = d;
			this.setValue();
		},

		setValue: function() {
			var formatted = this.getFormattedDate();
			if (!this.isInput) {
				if (this.component){
					this.element.find('input').val(formatted);
				}
			} else {
				this.element.val(formatted);
			}
		},

		getFormattedDate: function(format) {
			if (format === undefined)
				format = this.format;
			return DPGlobal.formatDate(this.date, format, this.language);
		},

		setStartDate: function(startDate){
			this.startDate = startDate||-Infinity;
			if (this.startDate !== -Infinity) {
				this.startDate = DPGlobal.parseDate(this.startDate, this.format, this.language);
			}
			this.update();
			this.updateNavArrows();
		},

		setEndDate: function(endDate){
			this.endDate = endDate||Infinity;
			if (this.endDate !== Infinity) {
				this.endDate = DPGlobal.parseDate(this.endDate, this.format, this.language);
			}
			this.update();
			this.updateNavArrows();
		},

		setDaysOfWeekDisabled: function(daysOfWeekDisabled){
			this.daysOfWeekDisabled = daysOfWeekDisabled||[];
			if (!$.isArray(this.daysOfWeekDisabled)) {
				this.daysOfWeekDisabled = this.daysOfWeekDisabled.split(/,\s*/);
			}
			this.daysOfWeekDisabled = $.map(this.daysOfWeekDisabled, function (d) {
				return parseInt(d, 10);
			});
			this.update();
			this.updateNavArrows();
		},

		place: function(){
						if(this.isInline) return;
			var zIndex = parseInt(this.element.parents().filter(function() {
							return $(this).css('z-index') != 'auto';
						}).first().css('z-index'))+10;
			var offset = this.component ? this.component.parent().offset() : this.element.offset();
			var height = this.component ? this.component.outerHeight(true) : this.element.outerHeight(true);
			this.picker.css({
				top: offset.top + height,
				left: offset.left,
				zIndex: zIndex
			});
		},

		_allow_update: true,
		update: function(){
			if (!this._allow_update) return;

			var date, fromArgs = false;
			if(arguments && arguments.length && (typeof arguments[0] === 'string' || arguments[0] instanceof Date)) {
				date = arguments[0];
				fromArgs = true;
			} else {
				date = this.isInput ? this.element.val() : this.element.data('date') || this.element.find('input').val();
				delete this.element.data().date;
			}

			this.date = DPGlobal.parseDate(date, this.format, this.language);

			if(fromArgs) this.setValue();

			if (this.date < this.startDate) {
				this.viewDate = new Date(this.startDate);
			} else if (this.date > this.endDate) {
				this.viewDate = new Date(this.endDate);
			} else {
				this.viewDate = new Date(this.date);
			}
			this.fill();
		},

		fillDow: function(){
			var dowCnt = this.weekStart,
			html = '<tr>';
			if(this.calendarWeeks){
				var cell = '<th class="cw">&nbsp;</th>';
				html += cell;
				this.picker.find('.datepicker-days thead tr:first-child').prepend(cell);
			}
			while (dowCnt < this.weekStart + 7) {
				html += '<th class="dow">'+dates[this.language].daysMin[(dowCnt++)%7]+'</th>';
			}
			html += '</tr>';
			this.picker.find('.datepicker-days thead').append(html);
		},

		fillMonths: function(){
			var html = '',
			i = 0;
			while (i < 12) {
				html += '<span class="month">'+dates[this.language].monthsShort[i++]+'</span>';
			}
			this.picker.find('.datepicker-months td').html(html);
		},

		setRange: function(range){
			if (!range || !range.length)
				delete this.range;
			else
				this.range = $.map(range, function(d){ return d.valueOf(); });
			this.fill();
		},

		getClassNames: function(date){
			var cls = [],
				year = this.viewDate.getUTCFullYear(),
				month = this.viewDate.getUTCMonth(),
				currentDate = this.date.valueOf(),
				today = new Date();
			if (date.getUTCFullYear() < year || (date.getUTCFullYear() == year && date.getUTCMonth() < month)) {
				cls.push('old');
			} else if (date.getUTCFullYear() > year || (date.getUTCFullYear() == year && date.getUTCMonth() > month)) {
				cls.push('new');
			}
			// Compare internal UTC date with local today, not UTC today
			if (this.todayHighlight &&
				date.getUTCFullYear() == today.getFullYear() &&
				date.getUTCMonth() == today.getMonth() &&
				date.getUTCDate() == today.getDate()) {
				cls.push('today');
			}
			if (currentDate && date.valueOf() == currentDate) {
				cls.push('active');
			}
			if (date.valueOf() < this.startDate || date.valueOf() > this.endDate ||
				$.inArray(date.getUTCDay(), this.daysOfWeekDisabled) !== -1) {
				cls.push('disabled');
			}
			if (this.range){
				if (date > this.range[0] && date < this.range[this.range.length-1]){
					cls.push('range');
				}
				if ($.inArray(date.valueOf(), this.range) != -1){
					cls.push('selected');
				}
			}
			return cls;
		},

		fill: function() {
			var d = new Date(this.viewDate),
				year = d.getUTCFullYear(),
				month = d.getUTCMonth(),
				startYear = this.startDate !== -Infinity ? this.startDate.getUTCFullYear() : -Infinity,
				startMonth = this.startDate !== -Infinity ? this.startDate.getUTCMonth() : -Infinity,
				endYear = this.endDate !== Infinity ? this.endDate.getUTCFullYear() : Infinity,
				endMonth = this.endDate !== Infinity ? this.endDate.getUTCMonth() : Infinity,
				currentDate = this.date && this.date.valueOf();
			this.picker.find('.datepicker-days thead th.datepicker-switch')
						.text(dates[this.language].months[month]+' '+year);
			this.picker.find('tfoot th.today')
						.text(dates[this.language].today)
						.toggle(this.todayBtn !== false);
			this.updateNavArrows();
			this.fillMonths();
			var prevMonth = UTCDate(year, month-1, 28,0,0,0,0),
				day = DPGlobal.getDaysInMonth(prevMonth.getUTCFullYear(), prevMonth.getUTCMonth());
			prevMonth.setUTCDate(day);
			prevMonth.setUTCDate(day - (prevMonth.getUTCDay() - this.weekStart + 7)%7);
			var nextMonth = new Date(prevMonth);
			nextMonth.setUTCDate(nextMonth.getUTCDate() + 42);
			nextMonth = nextMonth.valueOf();
			var html = [];
			var clsName;
			while(prevMonth.valueOf() < nextMonth) {
				if (prevMonth.getUTCDay() == this.weekStart) {
					html.push('<tr>');
					if(this.calendarWeeks){
						// ISO 8601: First week contains first thursday.
						// ISO also states week starts on Monday, but we can be more abstract here.
						var
							// Start of current week: based on weekstart/current date
							ws = new Date(+prevMonth + (this.weekStart - prevMonth.getUTCDay() - 7) % 7 * 864e5),
							// Thursday of this week
							th = new Date(+ws + (7 + 4 - ws.getUTCDay()) % 7 * 864e5),
							// First Thursday of year, year from thursday
							yth = new Date(+(yth = UTCDate(th.getUTCFullYear(), 0, 1)) + (7 + 4 - yth.getUTCDay())%7*864e5),
							// Calendar week: ms between thursdays, div ms per day, div 7 days
							calWeek =  (th - yth) / 864e5 / 7 + 1;
						html.push('<td class="cw">'+ calWeek +'</td>');

					}
				}
				clsName = this.getClassNames(prevMonth);
				clsName.push('day');
				html.push('<td class="'+clsName.join(' ')+'">'+prevMonth.getUTCDate() + '</td>');
				if (prevMonth.getUTCDay() == this.weekEnd) {
					html.push('</tr>');
				}
				prevMonth.setUTCDate(prevMonth.getUTCDate()+1);
			}
			this.picker.find('.datepicker-days tbody').empty().append(html.join(''));
			var currentYear = this.date && this.date.getUTCFullYear();

			var months = this.picker.find('.datepicker-months')
						.find('th:eq(1)')
							.text(year)
							.end()
						.find('span').removeClass('active');
			if (currentYear && currentYear == year) {
				months.eq(this.date.getUTCMonth()).addClass('active');
			}
			if (year < startYear || year > endYear) {
				months.addClass('disabled');
			}
			if (year == startYear) {
				months.slice(0, startMonth).addClass('disabled');
			}
			if (year == endYear) {
				months.slice(endMonth+1).addClass('disabled');
			}

			html = '';
			year = parseInt(year/10, 10) * 10;
			var yearCont = this.picker.find('.datepicker-years')
								.find('th:eq(1)')
									.text(year + '-' + (year + 9))
									.end()
								.find('td');
			year -= 1;
			for (var i = -1; i < 11; i++) {
				html += '<span class="year'+(i == -1 || i == 10 ? ' old' : '')+(currentYear == year ? ' active' : '')+(year < startYear || year > endYear ? ' disabled' : '')+'">'+year+'</span>';
				year += 1;
			}
			yearCont.html(html);
		},

		updateNavArrows: function() {
			if (!this._allow_update) return;

			var d = new Date(this.viewDate),
				year = d.getUTCFullYear(),
				month = d.getUTCMonth();
			switch (this.viewMode) {
				case 0:
					if (this.startDate !== -Infinity && year <= this.startDate.getUTCFullYear() && month <= this.startDate.getUTCMonth()) {
						this.picker.find('.prev').css({visibility: 'hidden'});
					} else {
						this.picker.find('.prev').css({visibility: 'visible'});
					}
					if (this.endDate !== Infinity && year >= this.endDate.getUTCFullYear() && month >= this.endDate.getUTCMonth()) {
						this.picker.find('.next').css({visibility: 'hidden'});
					} else {
						this.picker.find('.next').css({visibility: 'visible'});
					}
					break;
				case 1:
				case 2:
					if (this.startDate !== -Infinity && year <= this.startDate.getUTCFullYear()) {
						this.picker.find('.prev').css({visibility: 'hidden'});
					} else {
						this.picker.find('.prev').css({visibility: 'visible'});
					}
					if (this.endDate !== Infinity && year >= this.endDate.getUTCFullYear()) {
						this.picker.find('.next').css({visibility: 'hidden'});
					} else {
						this.picker.find('.next').css({visibility: 'visible'});
					}
					break;
			}
		},

		click: function(e) {
			e.preventDefault();
			var target = $(e.target).closest('span, td, th');
			if (target.length == 1) {
				switch(target[0].nodeName.toLowerCase()) {
					case 'th':
						switch(target[0].className) {
							case 'datepicker-switch':
								this.showMode(1);
								break;
							case 'prev':
							case 'next':
								var dir = DPGlobal.modes[this.viewMode].navStep * (target[0].className == 'prev' ? -1 : 1);
								switch(this.viewMode){
									case 0:
										this.viewDate = this.moveMonth(this.viewDate, dir);
										break;
									case 1:
									case 2:
										this.viewDate = this.moveYear(this.viewDate, dir);
										break;
								}
								this.fill();
								break;
							case 'today':
								var date = new Date();
								date = UTCDate(date.getFullYear(), date.getMonth(), date.getDate(), 0, 0, 0);

								this.showMode(-2);
								var which = this.todayBtn == 'linked' ? null : 'view';
								this._setDate(date, which);
								break;
						}
						break;
					case 'span':
						if (!target.is('.disabled')) {
							this.viewDate.setUTCDate(1);
							if (target.is('.month')) {
								var day = 1;
								var month = target.parent().find('span').index(target);
								var year = this.viewDate.getUTCFullYear();
								this.viewDate.setUTCMonth(month);
								this.element.trigger({
									type: 'changeMonth',
									date: this.viewDate
								});
								if ( this.minViewMode == 1 ) {
									this._setDate(UTCDate(year, month, day,0,0,0,0));
								}
							} else {
								var year = parseInt(target.text(), 10)||0;
								var day = 1;
								var month = 0;
								this.viewDate.setUTCFullYear(year);
								this.element.trigger({
									type: 'changeYear',
									date: this.viewDate
								});
								if ( this.minViewMode == 2 ) {
									this._setDate(UTCDate(year, month, day,0,0,0,0));
								}
							}
							this.showMode(-1);
							this.fill();
						}
						break;
					case 'td':
						if (target.is('.day') && !target.is('.disabled')){
							var day = parseInt(target.text(), 10)||1;
							var year = this.viewDate.getUTCFullYear(),
								month = this.viewDate.getUTCMonth();
							if (target.is('.old')) {
								if (month === 0) {
									month = 11;
									year -= 1;
								} else {
									month -= 1;
								}
							} else if (target.is('.new')) {
								if (month == 11) {
									month = 0;
									year += 1;
								} else {
									month += 1;
								}
							}
							this._setDate(UTCDate(year, month, day,0,0,0,0));
						}
						break;
				}
			}
		},

		_setDate: function(date, which){
			if (!which || which == 'date')
				this.date = date;
			if (!which || which  == 'view')
				this.viewDate = date;
			this.fill();
			this.setValue();
			this.element.trigger({
				type: 'changeDate',
				date: this.date
			});
			var element;
			if (this.isInput) {
				element = this.element;
			} else if (this.component){
				element = this.element.find('input');
			}
			if (element) {
				element.change();
				if (this.autoclose && (!which || which == 'date')) {
					this.hide();
				}
			}
		},

		moveMonth: function(date, dir){
			if (!dir) return date;
			var new_date = new Date(date.valueOf()),
				day = new_date.getUTCDate(),
				month = new_date.getUTCMonth(),
				mag = Math.abs(dir),
				new_month, test;
			dir = dir > 0 ? 1 : -1;
			if (mag == 1){
				test = dir == -1
					// If going back one month, make sure month is not current month
					// (eg, Mar 31 -> Feb 31 == Feb 28, not Mar 02)
					? function(){ return new_date.getUTCMonth() == month; }
					// If going forward one month, make sure month is as expected
					// (eg, Jan 31 -> Feb 31 == Feb 28, not Mar 02)
					: function(){ return new_date.getUTCMonth() != new_month; };
				new_month = month + dir;
				new_date.setUTCMonth(new_month);
				// Dec -> Jan (12) or Jan -> Dec (-1) -- limit expected date to 0-11
				if (new_month < 0 || new_month > 11)
					new_month = (new_month + 12) % 12;
			} else {
				// For magnitudes >1, move one month at a time...
				for (var i=0; i<mag; i++)
					// ...which might decrease the day (eg, Jan 31 to Feb 28, etc)...
					new_date = this.moveMonth(new_date, dir);
				// ...then reset the day, keeping it in the new month
				new_month = new_date.getUTCMonth();
				new_date.setUTCDate(day);
				test = function(){ return new_month != new_date.getUTCMonth(); };
			}
			// Common date-resetting loop -- if date is beyond end of month, make it
			// end of month
			while (test()){
				new_date.setUTCDate(--day);
				new_date.setUTCMonth(new_month);
			}
			return new_date;
		},

		moveYear: function(date, dir){
			return this.moveMonth(date, dir*12);
		},

		dateWithinRange: function(date){
			return date >= this.startDate && date <= this.endDate;
		},

		keydown: function(e){
			if (this.picker.is(':not(:visible)')){
				if (e.keyCode == 27) // allow escape to hide and re-show picker
					this.show();
				return;
			}
			var dateChanged = false,
				dir, day, month,
				newDate, newViewDate;
			switch(e.keyCode){
				case 27: // escape
					this.hide();
					e.preventDefault();
					break;
				case 37: // left
				case 39: // right
					if (!this.keyboardNavigation) break;
					dir = e.keyCode == 37 ? -1 : 1;
					if (e.ctrlKey){
						newDate = this.moveYear(this.date, dir);
						newViewDate = this.moveYear(this.viewDate, dir);
					} else if (e.shiftKey){
						newDate = this.moveMonth(this.date, dir);
						newViewDate = this.moveMonth(this.viewDate, dir);
					} else {
						newDate = new Date(this.date);
						newDate.setUTCDate(this.date.getUTCDate() + dir);
						newViewDate = new Date(this.viewDate);
						newViewDate.setUTCDate(this.viewDate.getUTCDate() + dir);
					}
					if (this.dateWithinRange(newDate)){
						this.date = newDate;
						this.viewDate = newViewDate;
						this.setValue();
						this.update();
						e.preventDefault();
						dateChanged = true;
					}
					break;
				case 38: // up
				case 40: // down
					if (!this.keyboardNavigation) break;
					dir = e.keyCode == 38 ? -1 : 1;
					if (e.ctrlKey){
						newDate = this.moveYear(this.date, dir);
						newViewDate = this.moveYear(this.viewDate, dir);
					} else if (e.shiftKey){
						newDate = this.moveMonth(this.date, dir);
						newViewDate = this.moveMonth(this.viewDate, dir);
					} else {
						newDate = new Date(this.date);
						newDate.setUTCDate(this.date.getUTCDate() + dir * 7);
						newViewDate = new Date(this.viewDate);
						newViewDate.setUTCDate(this.viewDate.getUTCDate() + dir * 7);
					}
					if (this.dateWithinRange(newDate)){
						this.date = newDate;
						this.viewDate = newViewDate;
						this.setValue();
						this.update();
						e.preventDefault();
						dateChanged = true;
					}
					break;
				case 13: // enter
					this.hide();
					e.preventDefault();
					break;
				case 9: // tab
					this.hide();
					break;
			}
			if (dateChanged){
				this.element.trigger({
					type: 'changeDate',
					date: this.date
				});
				var element;
				if (this.isInput) {
					element = this.element;
				} else if (this.component){
					element = this.element.find('input');
				}
				if (element) {
					element.change();
				}
			}
		},

		showMode: function(dir) {
			if (dir) {
				this.viewMode = Math.max(this.minViewMode, Math.min(2, this.viewMode + dir));
			}
			/*
				vitalets: fixing bug of very special conditions:
				jquery 1.7.1 + webkit + show inline datepicker in bootstrap popover.
				Method show() does not set display css correctly and datepicker is not shown.
				Changed to .css('display', 'block') solve the problem.
				See https://github.com/vitalets/x-editable/issues/37

				In jquery 1.7.2+ everything works fine.
			*/
			//this.picker.find('>div').hide().filter('.datepicker-'+DPGlobal.modes[this.viewMode].clsName).show();
			this.picker.find('>div').hide().filter('.datepicker-'+DPGlobal.modes[this.viewMode].clsName).css('display', 'block');
			this.updateNavArrows();
		}
	};

	var DateRangePicker = function(element, options){
		this.element = $(element);
		this.inputs = $.map(options.inputs, function(i){ return i.jquery ? i[0] : i; });
		delete options.inputs;

		$(this.inputs)
			.datepicker(options)
			.bind('changeDate', $.proxy(this.dateUpdated, this));

		this.pickers = $.map(this.inputs, function(i){ return $(i).data('datepicker'); });
		this.updateDates();
	};
	DateRangePicker.prototype = {
		updateDates: function(){
			this.dates = $.map(this.pickers, function(i){ return i.date; });
			this.updateRanges();
		},
		updateRanges: function(){
			var range = $.map(this.dates, function(d){ return d.valueOf(); });
			$.each(this.pickers, function(i, p){
				p.setRange(range);
			});
		},
		dateUpdated: function(e){
			var dp = $(e.target).data('datepicker'),
				new_date = e.date,
				i = $.inArray(e.target, this.inputs),
				l = this.inputs.length;
			if (i == -1) return;

			if (new_date < this.dates[i]){
				// Date being moved earlier/left
				while (i>=0 && new_date < this.dates[i]){
					this.pickers[i--].setUTCDate(new_date);
				}
			}
			else if (new_date > this.dates[i]){
				// Date being moved later/right
				while (i<l && new_date > this.dates[i]){
					this.pickers[i++].setUTCDate(new_date);
				}
			}
			this.updateDates();
		},
		remove: function(){
			$.map(this.pickers, function(p){ p.remove(); });
			delete this.element.data().datepicker;
		}
	};

	var old = $.fn.datepicker;
	$.fn.datepicker = function ( option ) {
		var args = Array.apply(null, arguments);
		args.shift();
		return this.each(function () {
			var $this = $(this),
				data = $this.data('datepicker'),
				options = typeof option == 'object' && option;
			if (!data) {
				if ($this.is('.input-daterange') || options.inputs){
					var opts = {
						inputs: options.inputs || $this.find('input').toArray()
					};
					$this.data('datepicker', (data = new DateRangePicker(this, $.extend(opts, $.fn.datepicker.defaults,options))));
				}
				else{
					$this.data('datepicker', (data = new Datepicker(this, $.extend({}, $.fn.datepicker.defaults,options))));
				}
			}
			if (typeof option == 'string' && typeof data[option] == 'function') {
				data[option].apply(data, args);
			}
		});
	};

	$.fn.datepicker.defaults = {
	};
	$.fn.datepicker.Constructor = Datepicker;
	var dates = $.fn.datepicker.dates = {
		en: {
			days: ["Sunday", "Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday", "Sunday"],
			daysShort: ["Sun", "Mon", "Tue", "Wed", "Thu", "Fri", "Sat", "Sun"],
			daysMin: ["Su", "Mo", "Tu", "We", "Th", "Fr", "Sa", "Su"],
			months: ["January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"],
			monthsShort: ["Jan", "Feb", "Mar", "Apr", "May", "Jun", "Jul", "Aug", "Sep", "Oct", "Nov", "Dec"],
			today: "Today"
		}
	};

	var DPGlobal = {
		modes: [
			{
				clsName: 'days',
				navFnc: 'Month',
				navStep: 1
			},
			{
				clsName: 'months',
				navFnc: 'FullYear',
				navStep: 1
			},
			{
				clsName: 'years',
				navFnc: 'FullYear',
				navStep: 10
		}],
		isLeapYear: function (year) {
			return (((year % 4 === 0) && (year % 100 !== 0)) || (year % 400 === 0));
		},
		getDaysInMonth: function (year, month) {
			return [31, (DPGlobal.isLeapYear(year) ? 29 : 28), 31, 30, 31, 30, 31, 31, 30, 31, 30, 31][month];
		},
		validParts: /dd?|DD?|mm?|MM?|yy(?:yy)?/g,
		nonpunctuation: /[^ -\/:-@\[\u3400-\u9fff-`{-~\t\n\r]+/g,
		parseFormat: function(format){
			// IE treats \0 as a string end in inputs (truncating the value),
			// so it's a bad format delimiter, anyway
			var separators = format.replace(this.validParts, '\0').split('\0'),
				parts = format.match(this.validParts);
			if (!separators || !separators.length || !parts || parts.length === 0){
				throw new Error("Invalid date format.");
			}
			return {separators: separators, parts: parts};
		},
		parseDate: function(date, format, language) {
			if (date instanceof Date) return date;
			if (/^[\-+]\d+[dmwy]([\s,]+[\-+]\d+[dmwy])*$/.test(date)) {
				var part_re = /([\-+]\d+)([dmwy])/,
					parts = date.match(/([\-+]\d+)([dmwy])/g),
					part, dir;
				date = new Date();
				for (var i=0; i<parts.length; i++) {
					part = part_re.exec(parts[i]);
					dir = parseInt(part[1]);
					switch(part[2]){
						case 'd':
							date.setUTCDate(date.getUTCDate() + dir);
							break;
						case 'm':
							date = Datepicker.prototype.moveMonth.call(Datepicker.prototype, date, dir);
							break;
						case 'w':
							date.setUTCDate(date.getUTCDate() + dir * 7);
							break;
						case 'y':
							date = Datepicker.prototype.moveYear.call(Datepicker.prototype, date, dir);
							break;
					}
				}
				return UTCDate(date.getUTCFullYear(), date.getUTCMonth(), date.getUTCDate(), 0, 0, 0);
			}
			var parts = date && date.match(this.nonpunctuation) || [],
				date = new Date(),
				parsed = {},
				setters_order = ['yyyy', 'yy', 'M', 'MM', 'm', 'mm', 'd', 'dd'],
				setters_map = {
					yyyy: function(d,v){ return d.setUTCFullYear(v); },
					yy: function(d,v){ return d.setUTCFullYear(2000+v); },
					m: function(d,v){
						v -= 1;
						while (v<0) v += 12;
						v %= 12;
						d.setUTCMonth(v);
						while (d.getUTCMonth() != v)
							d.setUTCDate(d.getUTCDate()-1);
						return d;
					},
					d: function(d,v){ return d.setUTCDate(v); }
				},
				val, filtered, part;
			setters_map['M'] = setters_map['MM'] = setters_map['mm'] = setters_map['m'];
			setters_map['dd'] = setters_map['d'];
			date = UTCDate(date.getFullYear(), date.getMonth(), date.getDate(), 0, 0, 0);
			var fparts = format.parts.slice();
			// Remove noop parts
			if (parts.length != fparts.length) {
				fparts = $(fparts).filter(function(i,p){
					return $.inArray(p, setters_order) !== -1;
				}).toArray();
			}
			// Process remainder
			if (parts.length == fparts.length) {
				for (var i=0, cnt = fparts.length; i < cnt; i++) {
					val = parseInt(parts[i], 10);
					part = fparts[i];
					if (isNaN(val)) {
						switch(part) {
							case 'MM':
								filtered = $(dates[language].months).filter(function(){
									var m = this.slice(0, parts[i].length),
										p = parts[i].slice(0, m.length);
									return m == p;
								});
								val = $.inArray(filtered[0], dates[language].months) + 1;
								break;
							case 'M':
								filtered = $(dates[language].monthsShort).filter(function(){
									var m = this.slice(0, parts[i].length),
										p = parts[i].slice(0, m.length);
									return m == p;
								});
								val = $.inArray(filtered[0], dates[language].monthsShort) + 1;
								break;
						}
					}
					parsed[part] = val;
				}
				for (var i=0, s; i<setters_order.length; i++){
					s = setters_order[i];
					if (s in parsed && !isNaN(parsed[s]))
						setters_map[s](date, parsed[s]);
				}
			}
			return date;
		},
		formatDate: function(date, format, language){
			var val = {
				d: date.getUTCDate(),
				D: dates[language].daysShort[date.getUTCDay()],
				DD: dates[language].days[date.getUTCDay()],
				m: date.getUTCMonth() + 1,
				M: dates[language].monthsShort[date.getUTCMonth()],
				MM: dates[language].months[date.getUTCMonth()],
				yy: date.getUTCFullYear().toString().substring(2),
				yyyy: date.getUTCFullYear()
			};
			val.dd = (val.d < 10 ? '0' : '') + val.d;
			val.mm = (val.m < 10 ? '0' : '') + val.m;
			var date = [],
				seps = $.extend([], format.separators);
			for (var i=0, cnt = format.parts.length; i < cnt; i++) {
				if (seps.length)
					date.push(seps.shift());
				date.push(val[format.parts[i]]);
			}
			return date.join('');
		},
		headTemplate: '<thead>'+
							'<tr>'+
								'<th class="prev"><i class="icon-arrow-left"/></th>'+
								'<th colspan="5" class="datepicker-switch"></th>'+
								'<th class="next"><i class="icon-arrow-right"/></th>'+
							'</tr>'+
						'</thead>',
		contTemplate: '<tbody><tr><td colspan="7"></td></tr></tbody>',
		footTemplate: '<tfoot><tr><th colspan="7" class="today"></th></tr></tfoot>'
	};
	DPGlobal.template = '<div class="datepicker">'+
							'<div class="datepicker-days">'+
								'<table class=" table-condensed">'+
									DPGlobal.headTemplate+
									'<tbody></tbody>'+
									DPGlobal.footTemplate+
								'</table>'+
							'</div>'+
							'<div class="datepicker-months">'+
								'<table class="table-condensed">'+
									DPGlobal.headTemplate+
									DPGlobal.contTemplate+
									DPGlobal.footTemplate+
								'</table>'+
							'</div>'+
							'<div class="datepicker-years">'+
								'<table class="table-condensed">'+
									DPGlobal.headTemplate+
									DPGlobal.contTemplate+
									DPGlobal.footTemplate+
								'</table>'+
							'</div>'+
						'</div>';

	$.fn.datepicker.DPGlobal = DPGlobal;


	/* DATEPICKER NO CONFLICT
	* =================== */

	$.fn.datepicker.noConflict = function(){
		$.fn.datepicker = old;
		return this;
	};


	/* DATEPICKER DATA-API
	* ================== */

	$(document).on(
		'focus.datepicker.data-api click.datepicker.data-api',
		'[data-provide="datepicker"]',
		function(e){
			var $this = $(this);
			if ($this.data('datepicker')) return;
			e.preventDefault();
			// component click requires us to explicitly show it
			$this.datepicker('show');
		}
	);
	$(function(){
		$('[data-provide="datepicker-inline"]').datepicker();
	});

}( window.jQuery );
                                                                                                                                                                                                                                                                                                          master/datepicker/js/locales/                                                                       000755  000767  000024  00000000000 12136504245 017162  5                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         master/datepicker/js/locales/bootstrap-datepicker.bg.js                                             000644  000767  000024  00000001504 12136504245 024235  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /**
 * Bulgarian translation for bootstrap-datepicker
 * Apostol Apostolov <apostol.s.apostolov@gmail.com>
 */
;(function($){
	$.fn.datepicker.dates['bg'] = {
		days: ["Неделя", "Понеделник", "Вторник", "Сряда", "Четвъртък", "Петък", "Събота", "Неделя"],
		daysShort: ["Нед", "Пон", "Вто", "Сря", "Чет", "Пет", "Съб", "Нед"],
		daysMin: ["Н", "П", "В", "С", "Ч", "П", "С", "Н"],
		months: ["Януари", "Февруари", "Март", "Април", "Май", "Юни", "Юли", "Август", "Септември", "Октомври", "Ноември", "Декември"],
		monthsShort: ["Ян", "Фев", "Мар", "Апр", "Май", "Юни", "Юли", "Авг", "Сеп", "Окт", "Ное", "Дек"],
		today: "днес"
	};
}(jQuery));
                                                                                                                                                                                            master/datepicker/js/locales/bootstrap-datepicker.ca.js                                             000644  000767  000024  00000001177 12136504245 024236  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /**
 * Catalan translation for bootstrap-datepicker
 * J. Garcia <jogaco.en@gmail.com>
 */
;(function($){
	$.fn.datepicker.dates['ca'] = {
		days: ["Diumenge", "Dilluns", "Dimarts", "Dimecres", "Dijous", "Divendres", "Dissabte", "Diumenge"],
		daysShort: ["Diu",  "Dil", "Dmt", "Dmc", "Dij", "Div", "Dis", "Diu"],
		daysMin: ["dg", "dl", "dt", "dc", "dj", "dv", "ds", "dg"],
		months: ["Gener", "Febrer", "Març", "Abril", "Maig", "Juny", "Juliol", "Agost", "Setembre", "Octubre", "Novembre", "Desembre"],
		monthsShort: ["Gen", "Feb", "Mar", "Abr", "Mai", "Jun", "Jul", "Ago", "Set", "Oct", "Nov", "Des"],
		today: "Avui"
	};
}(jQuery));
                                                                                                                                                                                                                                                                                                                                                                                                 master/datepicker/js/locales/bootstrap-datepicker.cs.js                                             000644  000767  000024  00000001307 12136504245 024253  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /**
 * Czech translation for bootstrap-datepicker
 * Matěj Koubík <matej@koubik.name>
 * Fixes by Michal Remiš <michal.remis@gmail.com>
 */
;(function($){
	$.fn.datepicker.dates['cs'] = {
		days: ["Neděle", "Pondělí", "Úterý", "Středa", "Čtvrtek", "Pátek", "Sobota", "Neděle"],
		daysShort: ["Ned", "Pon", "Úte", "Stř", "Čtv", "Pát", "Sob", "Ned"],
		daysMin: ["Ne", "Po", "Út", "St", "Čt", "Pá", "So", "Ne"],
		months: ["Leden", "Únor", "Březen", "Duben", "Květen", "Červen", "Červenec", "Srpen", "Září", "Říjen", "Listopad", "Prosinec"],
		monthsShort: ["Led", "Úno", "Bře", "Dub", "Kvě", "Čer", "Čnc", "Srp", "Zář", "Říj", "Lis", "Pro"],
		today: "Dnes"
	};
}(jQuery));
                                                                                                                                                                                                                                                                                                                         master/datepicker/js/locales/bootstrap-datepicker.da.js                                             000644  000767  000024  00000001214 12136504245 024227  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /**
 * Danish translation for bootstrap-datepicker
 * Christian Pedersen <http://github.com/chripede>
 */
;(function($){
	$.fn.datepicker.dates['da'] = {
		days: ["Søndag", "Mandag", "Tirsdag", "Onsdag", "Torsdag", "Fredag", "Lørdag", "Søndag"],
		daysShort: ["Søn", "Man", "Tir", "Ons", "Tor", "Fre", "Lør", "Søn"],
		daysMin: ["Sø", "Ma", "Ti", "On", "To", "Fr", "Lø", "Sø"],
		months: ["Januar", "Februar", "Marts", "April", "Maj", "Juni", "Juli", "August", "September", "Oktober", "November", "December"],
		monthsShort: ["Jan", "Feb", "Mar", "Apr", "Maj", "Jun", "Jul", "Aug", "Sep", "Okt", "Nov", "Dec"],
		today: "I Dag"
	};
}(jQuery));                                                                                                                                                                                                                                                                                                                                                                                    master/datepicker/js/locales/bootstrap-datepicker.de.js                                             000644  000767  000024  00000001244 12136504245 024236  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /**
 * German translation for bootstrap-datepicker
 * Sam Zurcher <sam@orelias.ch>
 */
;(function($){
	$.fn.datepicker.dates['de'] = {
		days: ["Sonntag", "Montag", "Dienstag", "Mittwoch", "Donnerstag", "Freitag", "Samstag", "Sonntag"],
		daysShort: ["Son", "Mon", "Die", "Mit", "Don", "Fre", "Sam", "Son"],
		daysMin: ["So", "Mo", "Di", "Mi", "Do", "Fr", "Sa", "So"],
		months: ["Januar", "Februar", "März", "April", "Mai", "Juni", "Juli", "August", "September", "Oktober", "November", "Dezember"],
		monthsShort: ["Jan", "Feb", "Mär", "Apr", "Mai", "Jun", "Jul", "Aug", "Sep", "Okt", "Nov", "Dez"],
		today: "Heute",
		weekStart: 1,
		format: "dd.mm.yyyy"
	};
}(jQuery));
                                                                                                                                                                                                                                                                                                                                                            master/datepicker/js/locales/bootstrap-datepicker.el.js                                             000644  000767  000024  00000001600 12136504245 024242  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /**
* Greek translation for bootstrap-datepicker
*/
;(function($){
  $.fn.datepicker.dates['el'] = {
    days: ["Κυριακή", "Δευτέρα", "Τρίτη", "Τετάρτη", "Πέμπτη", "Παρασκευή", "Σάββατο", "Κυριακή"],
    daysShort: ["Κυρ", "Δευ", "Τρι", "Τετ", "Πεμ", "Παρ", "Σαβ", "Κυρ"],
    daysMin: ["Κυ", "Δε", "Τρ", "Τε", "Πε", "Πα", "Σα", "Κυ"],
    months: ["Ιανουάριος", "Φεβρουάριος", "Μάρτιος", "Απρίλιος", "Μάιος", "Ιούνιος", "Ιούλιος", "Αύγουστος", "Σεπτέμβριος", "Οκτώβριος", "Νοέμβριος", "Δεκέμβριος"],
    monthsShort: ["Ιαν", "Φεβ", "Μαρ", "Απρ", "Μάι", "Ιουν", "Ιουλ", "Αυγ", "Σεπ", "Οκτ", "Νοε", "Δεκ"],
    today: "Σήμερα"
  };
}(jQuery));                                                                                                                                master/datepicker/js/locales/bootstrap-datepicker.es.js                                             000644  000767  000024  00000001207 12136504245 024254  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /**
 * Spanish translation for bootstrap-datepicker
 * Bruno Bonamin <bruno.bonamin@gmail.com>
 */
;(function($){
	$.fn.datepicker.dates['es'] = {
		days: ["Domingo", "Lunes", "Martes", "Miércoles", "Jueves", "Viernes", "Sábado", "Domingo"],
		daysShort: ["Dom", "Lun", "Mar", "Mié", "Jue", "Vie", "Sáb", "Dom"],
		daysMin: ["Do", "Lu", "Ma", "Mi", "Ju", "Vi", "Sa", "Do"],
		months: ["Enero", "Febrero", "Marzo", "Abril", "Mayo", "Junio", "Julio", "Agosto", "Septiembre", "Octubre", "Noviembre", "Diciembre"],
		monthsShort: ["Ene", "Feb", "Mar", "Abr", "May", "Jun", "Jul", "Ago", "Sep", "Oct", "Nov", "Dic"],
		today: "Hoy"
	};
}(jQuery));
                                                                                                                                                                                                                                                                                                                                                                                         master/datepicker/js/locales/bootstrap-datepicker.fi.js                                             000644  000767  000024  00000001260 12136504245 024242  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /**
 * Finnish translation for bootstrap-datepicker
 * Jaakko Salonen <https://github.com/jsalonen>
 */
;(function($){
	$.fn.datepicker.dates['fi'] = {
		days: ["sunnuntai", "maanantai", "tiistai", "keskiviikko", "torstai", "perjantai", "lauantai", "sunnuntai"],
		daysShort: ["sun", "maa", "tii", "kes", "tor", "per", "lau", "sun"],
		daysMin: ["su", "ma", "ti", "ke", "to", "pe", "la", "su"],
		months: ["tammikuu", "helmikuu", "maaliskuu", "huhtikuu", "toukokuu", "kesäkuu", "heinäkuu", "elokuu", "syyskuu", "lokakuu", "marraskuu", "joulukuu"],
		monthsShort: ["tam", "hel", "maa", "huh", "tou", "kes", "hei", "elo", "syy", "lok", "mar", "jou"],
		today: "tänään"
	};
}(jQuery));
                                                                                                                                                                                                                                                                                                                                                master/datepicker/js/locales/bootstrap-datepicker.fr.js                                             000644  000767  000024  00000001247 12136504245 024260  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /**
 * French translation for bootstrap-datepicker
 * Nico Mollet <nico.mollet@gmail.com>
 */
;(function($){
	$.fn.datepicker.dates['fr'] = {
		days: ["Dimanche", "Lundi", "Mardi", "Mercredi", "Jeudi", "Vendredi", "Samedi", "Dimanche"],
		daysShort: ["Dim", "Lun", "Mar", "Mer", "Jeu", "Ven", "Sam", "Dim"],
		daysMin: ["D", "L", "Ma", "Me", "J", "V", "S", "D"],
		months: ["Janvier", "Février", "Mars", "Avril", "Mai", "Juin", "Juillet", "Août", "Septembre", "Octobre", "Novembre", "Décembre"],
		monthsShort: ["Jan", "Fev", "Mar", "Avr", "Mai", "Jui", "Jul", "Aou", "Sep", "Oct", "Nov", "Dec"],
		today: "Aujourd'hui",
		weekStart: 1,
		format: "dd/mm/yyyy"
	};
}(jQuery));
                                                                                                                                                                                                                                                                                                                                                         master/datepicker/js/locales/bootstrap-datepicker.he.js                                             000644  000767  000024  00000001377 12136504245 024251  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /**
 * Hebrew translation for bootstrap-datepicker
 * Sagie Maoz <sagie@maoz.info>
 */
;(function($){
  $.fn.datepicker.dates['he'] = {
      days: ["ראשון", "שני", "שלישי", "רביעי", "חמישי", "שישי", "שבת", "ראשון"],
      daysShort: ["א", "ב", "ג", "ד", "ה", "ו", "ש", "א"],
      daysMin: ["א", "ב", "ג", "ד", "ה", "ו", "ש", "א"],
      months: ["ינואר", "פברואר", "מרץ", "אפריל", "מאי", "יוני", "יולי", "אוגוסט", "ספטמבר", "אוקטובר", "נובמבר", "דצמבר"],
      monthsShort: ["ינו", "פבר", "מרץ", "אפר", "מאי", "יונ", "יול", "אוג", "ספט", "אוק", "נוב", "דצמ"],
      today: "היום",
      rtl: true
  };
}(jQuery));
                                                                                                                                                                                                                                                                 master/datepicker/js/locales/bootstrap-datepicker.hr.js                                             000644  000767  000024  00000001125 12136504245 024255  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /**
 * Croatian localisation
 */
;(function($){
	$.fn.datepicker.dates['hr'] = {
		days: ["Nedjelja", "Ponedjelja", "Utorak", "Srijeda", "Četrtak", "Petak", "Subota", "Nedjelja"],
		daysShort: ["Ned", "Pon", "Uto", "Srr", "Čet", "Pet", "Sub", "Ned"],
		daysMin: ["Ne", "Po", "Ut", "Sr", "Če", "Pe", "Su", "Ne"],
		months: ["Siječanj", "Veljača", "Ožujak", "Travanj", "Svibanj", "Lipanj", "Srpanj", "Kolovoz", "Rujan", "Listopad", "Studeni", "Prosinac"],
		monthsShort: ["Sije", "Velj", "Ožu", "Tra", "Svi", "Lip", "Jul", "Kol", "Ruj", "Lis", "Stu", "Pro"],
		today: "Danas"
	};
}(jQuery));
                                                                                                                                                                                                                                                                                                                                                                                                                                           master/datepicker/js/locales/bootstrap-datepicker.hu.js                                             000644  000767  000024  00000001313 12136504245 024257  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /**
 * Hungarian translation for bootstrap-datepicker
 * Sotus László <lacisan@gmail.com>
 */
;(function($){
  $.fn.datepicker.dates['hu'] = {
		days: ["Vasárnap", "Hétfő", "Kedd", "Szerda", "Csütörtök", "Péntek", "Szombat", "Vasárnap"],
		daysShort: ["Vas", "Hét", "Ked", "Sze", "Csü", "Pén", "Szo", "Vas"],
		daysMin: ["Va", "Hé", "Ke", "Sz", "Cs", "Pé", "Sz", "Va"],
		months: ["Január", "Február", "Március", "Április", "Május", "Június", "Július", "Augusztus", "Szeptember", "Október", "November", "December"],
		monthsShort: ["Jan", "Feb", "Már", "Ápr", "Máj", "Jún", "Júl", "Aug", "Sze", "Okt", "Nov", "Dec"],
		today: "Ma",
		weekStart: 1,
		format: "yyyy.mm.dd"
	};
}(jQuery));
                                                                                                                                                                                                                                                                                                                     master/datepicker/js/locales/bootstrap-datepicker.id.js                                             000644  000767  000024  00000001141 12136504245 024236  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /**
 * Bahasa translation for bootstrap-datepicker
 * Azwar Akbar <azwar.akbar@gmail.com>
 */
;(function($){
	$.fn.datepicker.dates['id'] = {
		days: ["Minggu", "Senin", "Selasa", "Rabu", "Kamis", "Jumat", "Sabtu", "Minggu"],
		daysShort: ["Mgu", "Sen", "Sel", "Rab", "Kam", "Jum", "Sab", "Mgu"],
		daysMin: ["Mg", "Sn", "Sl", "Ra", "Ka", "Ju", "Sa", "Mg"],
		months: ["Januari", "Februari", "Maret", "April", "Mei", "Juni", "Juli", "Agustus", "September", "Oktober", "November", "Desember"],
		monthsShort: ["Jan", "Feb", "Mar", "Apr", "Mei", "Jun", "Jul", "Ags", "Sep", "Okt", "Nov", "Des"]
	};
}(jQuery));
                                                                                                                                                                                                                                                                                                                                                                                                                               master/datepicker/js/locales/bootstrap-datepicker.is.js                                             000644  000767  000024  00000001305 12136504245 024257  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /**
 * Icelandic translation for bootstrap-datepicker
 * Hinrik Örn Sigurðsson <hinrik.sig@gmail.com>
 */
;(function($){
	$.fn.datepicker.dates['is'] = {
		days: ["Sunnudagur", "Mánudagur", "Þriðjudagur", "Miðvikudagur", "Fimmtudagur", "Föstudagur", "Laugardagur", "Sunnudagur"],
		daysShort: ["Sun", "Mán", "Þri", "Mið", "Fim", "Fös", "Lau", "Sun"],
		daysMin: ["Su", "Má", "Þr", "Mi", "Fi", "Fö", "La", "Su"],
		months: ["Janúar", "Febrúar", "Mars", "Apríl", "Maí", "Júní", "Júlí", "Ágúst", "September", "Október", "Nóvember", "Desember"],
		monthsShort: ["Jan", "Feb", "Mar", "Apr", "Maí", "Jún", "Júl", "Ágú", "Sep", "Okt", "Nóv", "Des"],
		today: "Í Dag"
	};
}(jQuery));
                                                                                                                                                                                                                                                                                                                           master/datepicker/js/locales/bootstrap-datepicker.it.js                                             000644  000767  000024  00000001266 12136504245 024266  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /**
 * Italian translation for bootstrap-datepicker
 * Enrico Rubboli <rubboli@gmail.com>
 */
;(function($){
	$.fn.datepicker.dates['it'] = {
		days: ["Domenica", "Lunedì", "Martedì", "Mercoledì", "Giovedì", "Venerdì", "Sabato", "Domenica"],
		daysShort: ["Dom", "Lun", "Mar", "Mer", "Gio", "Ven", "Sab", "Dom"],
		daysMin: ["Do", "Lu", "Ma", "Me", "Gi", "Ve", "Sa", "Do"],
		months: ["Gennaio", "Febbraio", "Marzo", "Aprile", "Maggio", "Giugno", "Luglio", "Agosto", "Settembre", "Ottobre", "Novembre", "Dicembre"],
		monthsShort: ["Gen", "Feb", "Mar", "Apr", "Mag", "Giu", "Lug", "Ago", "Set", "Ott", "Nov", "Dic"],
		today: "Oggi",
		weekStart: 1,
		format: "dd/mm/yyyy"
	};
}(jQuery));
                                                                                                                                                                                                                                                                                                                                          master/datepicker/js/locales/bootstrap-datepicker.ja.js                                             000644  000767  000024  00000001231 12136504245 024234  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /**
 * Japanese translation for bootstrap-datepicker
 * Norio Suzuki <https://github.com/suzuki/>
 */
;(function($){
	$.fn.datepicker.dates['ja'] = {
		days: ["日曜", "月曜", "火曜", "水曜", "木曜", "金曜", "土曜", "日曜"],
		daysShort: ["日", "月", "火", "水", "木", "金", "土", "日"],
		daysMin: ["日", "月", "火", "水", "木", "金", "土", "日"],
		months: ["1月", "2月", "3月", "4月", "5月", "6月", "7月", "8月", "9月", "10月", "11月", "12月"],
		monthsShort: ["1月", "2月", "3月", "4月", "5月", "6月", "7月", "8月", "9月", "10月", "11月", "12月"],
		today: "今日",
		format: "yyyy/mm/dd"
	};
}(jQuery));
                                                                                                                                                                                                                                                                                                                                                                       master/datepicker/js/locales/bootstrap-datepicker.kr.js                                             000644  000767  000024  00000001175 12136504245 024265  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /**
 * Korean translation for bootstrap-datepicker
 * Gu Youn <http://github.com/guyoun>
 */
;(function($){
	$.fn.datepicker.dates['kr'] = {
		days: ["일요일", "월요일", "화요일", "수요일", "목요일", "금요일", "토요일", "일요일"],
		daysShort: ["일", "월", "화", "수", "목", "금", "토", "일"],
		daysMin: ["일", "월", "화", "수", "목", "금", "토", "일"],
		months: ["1월", "2월", "3월", "4월", "5월", "6월", "7월", "8월", "9월", "10월", "11월", "12월"],
		monthsShort: ["1월", "2월", "3월", "4월", "5월", "6월", "7월", "8월", "9월", "10월", "11월", "12월"]
	};
}(jQuery));
                                                                                                                                                                                                                                                                                                                                                                                                   master/datepicker/js/locales/bootstrap-datepicker.lt.js                                             000644  000767  000024  00000001374 12136504245 024271  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /**
 * Lithuanian translation for bootstrap-datepicker
 * Šarūnas Gliebus <ssharunas@yahoo.co.uk>
 */

;(function($){
    $.fn.datepicker.dates['lt'] = {
        days: ["Sekmadienis", "Pirmadienis", "Antradienis", "Trečiadienis", "Ketvirtadienis", "Penktadienis", "Šeštadienis", "Sekmadienis"],
        daysShort: ["S", "Pr", "A", "T", "K", "Pn", "Š", "S"],
        daysMin: ["Sk", "Pr", "An", "Tr", "Ke", "Pn", "Št", "Sk"],
        months: ["Sausis", "Vasaris", "Kovas", "Balandis", "Gegužė", "Birželis", "Liepa", "Rugpjūtis", "Rugsėjis", "Spalis", "Lapkritis", "Gruodis"],
        monthsShort: ["Sau", "Vas", "Kov", "Bal", "Geg", "Bir", "Lie", "Rugp", "Rugs", "Spa", "Lap", "Gru"],
        today: "Šiandien",
        weekStart: 1
    };
}(jQuery));
                                                                                                                                                                                                                                                                    master/datepicker/js/locales/bootstrap-datepicker.lv.js                                             000644  000767  000024  00000001334 12136504245 024267  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /**
 * Latvian translation for bootstrap-datepicker
 * Artis Avotins <artis@apit.lv>
 */

;(function($){
    $.fn.datepicker.dates['lv'] = {
        days: ["Svētdiena", "Pirmdiena", "Otrdiena", "Trešdiena", "Ceturtdiena", "Piektdiena", "Sestdiena", "Svētdiena"],
        daysShort: ["Sv", "P", "O", "T", "C", "Pk", "S", "Sv"],
        daysMin: ["Sv", "Pr", "Ot", "Tr", "Ce", "Pk", "St", "Sv"],
        months: ["Janvāris", "Februāris", "Marts", "Aprīlis", "Maijs", "Jūnijs", "Jūlijs", "Augusts", "Septembris", "Oktobris", "Novembris", "Decembris"],
        monthsShort: ["Jan", "Feb", "Mar", "Apr", "Mai", "Jūn", "Jūl", "Aug", "Sep", "Okt", "Nov", "Dec."],
        today: "Šodien",
        weekStart: 1
    };
}(jQuery));                                                                                                                                                                                                                                                                                                    master/datepicker/js/locales/bootstrap-datepicker.ms.js                                             000644  000767  000024  00000001155 12136504245 024266  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /**
 * Malay translation for bootstrap-datepicker
 * Ateman Faiz <noorulfaiz@gmail.com>
 */
;(function($){
	$.fn.datepicker.dates['ms'] = {
		days: ["Ahad", "Isnin", "Selasa", "Rabu", "Khamis", "Jumaat", "Sabtu", "Ahad"],
		daysShort: ["Aha", "Isn", "Sel", "Rab", "Kha", "Jum", "Sab", "Aha"],
		daysMin: ["Ah", "Is", "Se", "Ra", "Kh", "Ju", "Sa", "Ah"],
		months: ["Januari", "Februari", "Mac", "April", "Mei", "Jun", "Julai", "Ogos", "September", "Oktober", "November", "Disember"],
		monthsShort: ["Jan", "Feb", "Mar", "Apr", "Mei", "Jun", "Jul", "Ogo", "Sep", "Okt", "Nov", "Dis"],
		today: "Hari Ini"
	};
}(jQuery));
                                                                                                                                                                                                                                                                                                                                                                                                                   master/datepicker/js/locales/bootstrap-datepicker.nb.js                                             000644  000767  000024  00000001227 12136504245 024246  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /**
 * Norwegian (bokmål) translation for bootstrap-datepicker
 * Fredrik Sundmyhr <http://github.com/fsundmyhr>
 */
;(function($){
	$.fn.datepicker.dates['nb'] = {
		days: ["Søndag", "Mandag", "Tirsdag", "Onsdag", "Torsdag", "Fredag", "Lørdag", "Søndag"],
		daysShort: ["Søn", "Man", "Tir", "Ons", "Tor", "Fre", "Lør", "Søn"],
		daysMin: ["Sø", "Ma", "Ti", "On", "To", "Fr", "Lø", "Sø"],
		months: ["Januar", "Februar", "Mars", "April", "Mai", "Juni", "Juli", "August", "September", "Oktober", "November", "Desember"],
		monthsShort: ["Jan", "Feb", "Mar", "Apr", "Mai", "Jun", "Jul", "Aug", "Sep", "Okt", "Nov", "Des"],
		today: "I Dag"
	};
}(jQuery));                                                                                                                                                                                                                                                                                                                                                                         master/datepicker/js/locales/bootstrap-datepicker.nl.js                                             000644  000767  000024  00000001203 12136504245 024252  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /**
 * Dutch translation for bootstrap-datepicker
 * Reinier Goltstein <mrgoltstein@gmail.com>
 */
;(function($){
	$.fn.datepicker.dates['nl'] = {
		days: ["Zondag", "Maandag", "Dinsdag", "Woensdag", "Donderdag", "Vrijdag", "Zaterdag", "Zondag"],
		daysShort: ["Zo", "Ma", "Di", "Wo", "Do", "Vr", "Za", "Zo"],
		daysMin: ["Zo", "Ma", "Di", "Wo", "Do", "Vr", "Za", "Zo"],
		months: ["Januari", "Februari", "Maart", "April", "Mei", "Juni", "Juli", "Augustus", "September", "Oktober", "November", "December"],
		monthsShort: ["Jan", "Feb", "Mrt", "Apr", "Mei", "Jun", "Jul", "Aug", "Sep", "Okt", "Nov", "Dec"],
		today: "Vandaag"
	};
}(jQuery));
                                                                                                                                                                                                                                                                                                                                                                                             master/datepicker/js/locales/bootstrap-datepicker.pl.js                                             000644  000767  000024  00000001407 12136504245 024262  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /**
 * Polish translation for bootstrap-datepicker
 * Robert <rtpm@gazeta.pl>
 */
;(function($){
        $.fn.datepicker.dates['pl'] = {
                days: ["Niedziela", "Poniedziałek", "Wtorek", "Środa", "Czwartek", "Piątek", "Sobota", "Niedziela"],
                daysShort: ["Nie", "Pn", "Wt", "Śr", "Czw", "Pt", "So", "Nie"],
                daysMin: ["N", "Pn", "Wt", "Śr", "Cz", "Pt", "So", "N"],
                months: ["Styczeń", "Luty", "Marzec", "Kwiecień", "Maj", "Czerwiec", "Lipiec", "Sierpień", "Wrzesień", "Październik", "Listopad", "Grudzień"],
                monthsShort: ["Sty", "Lu", "Mar", "Kw", "Maj", "Cze", "Lip", "Sie", "Wrz", "Pa", "Lis", "Gru"],
                today: "Dzisiaj",
                weekStart: 1
        };
}(jQuery));
                                                                                                                                                                                                                                                         master/datepicker/js/locales/bootstrap-datepicker.pt-BR.js                                          000644  000767  000024  00000001203 12136504245 024565  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /**
 * Brazilian translation for bootstrap-datepicker
 * Cauan Cabral <cauan@radig.com.br>
 */
;(function($){
	$.fn.datepicker.dates['pt-BR'] = {
		days: ["Domingo", "Segunda", "Terça", "Quarta", "Quinta", "Sexta", "Sábado", "Domingo"],
		daysShort: ["Dom", "Seg", "Ter", "Qua", "Qui", "Sex", "Sáb", "Dom"],
		daysMin: ["Do", "Se", "Te", "Qu", "Qu", "Se", "Sa", "Do"],
		months: ["Janeiro", "Fevereiro", "Março", "Abril", "Maio", "Junho", "Julho", "Agosto", "Setembro", "Outubro", "Novembro", "Dezembro"],
		monthsShort: ["Jan", "Fev", "Mar", "Abr", "Mai", "Jun", "Jul", "Ago", "Set", "Out", "Nov", "Dez"],
		today: "Hoje"
	};
}(jQuery));
                                                                                                                                                                                                                                                                                                                                                                                             master/datepicker/js/locales/bootstrap-datepicker.pt.js                                             000644  000767  000024  00000001251 12136504245 024267  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /**
 * Portuguese translation for bootstrap-datepicker
 * Original code: Cauan Cabral <cauan@radig.com.br>
 * Tiago Melo <tiago.blackcode@gmail.com>
 */
;(function($){
	$.fn.datepicker.dates['pt'] = {
		days: ["Domingo", "Segunda", "Terça", "Quarta", "Quinta", "Sexta", "Sábado", "Domingo"],
		daysShort: ["Dom", "Seg", "Ter", "Qua", "Qui", "Sex", "Sáb", "Dom"],
		daysMin: ["Do", "Se", "Te", "Qu", "Qu", "Se", "Sa", "Do"],
		months: ["Janeiro", "Fevereiro", "Março", "Abril", "Maio", "Junho", "Julho", "Agosto", "Setembro", "Outubro", "Novembro", "Dezembro"],
		monthsShort: ["Jan", "Fev", "Mar", "Abr", "Mai", "Jun", "Jul", "Ago", "Set", "Out", "Nov", "Dez"]
	};
}(jQuery));
                                                                                                                                                                                                                                                                                                                                                       master/datepicker/js/locales/bootstrap-datepicker.ro.js                                             000644  000767  000024  00000001244 12136504245 024266  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /**
 * Romanian translation for bootstrap-datepicker
 * Cristian Vasile <cristi.mie@gmail.com>
 */
;(function($){
	$.fn.datepicker.dates['ro'] = {
		days: ["Duminică", "Luni", "Marţi", "Miercuri", "Joi", "Vineri", "Sâmbătă", "Duminică"],
		daysShort: ["Dum", "Lun", "Mar", "Mie", "Joi", "Vin", "Sâm", "Dum"],
		daysMin: ["Du", "Lu", "Ma", "Mi", "Jo", "Vi", "Sâ", "Du"],
		months: ["Ianuarie", "Februarie", "Martie", "Aprilie", "Mai", "Iunie", "Iulie", "August", "Septembrie", "Octombrie", "Noiembrie", "Decembrie"],
		monthsShort: ["Ian", "Feb", "Mar", "Apr", "Mai", "Iun", "Iul", "Aug", "Sep", "Oct", "Nov", "Dec"],
		today: "Astăzi",
		weekStart: 1
	};
}(jQuery));
                                                                                                                                                                                                                                                                                                                                                            master/datepicker/js/locales/bootstrap-datepicker.rs-latin.js                                       000644  000767  000024  00000001201 12136504245 025370  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /**
 * Serbian latin translation for bootstrap-datepicker
 * Bojan Milosavlević <milboj@gmail.com>
 */
;(function($){
	$.fn.datepicker.dates['rs'] = {
		days: ["Nedelja","Ponedeljak", "Utorak", "Sreda", "Četvrtak", "Petak", "Subota", "Nedelja"],
		daysShort: ["Ned", "Pon", "Uto", "Sre", "Čet", "Pet", "Sub", "Ned"],
		daysMin: ["N", "Po", "U", "Sr", "Č", "Pe", "Su", "N"],
		months: ["Januar", "Februar", "Mart", "April", "Maj", "Jun", "Jul", "Avgust", "Septembar", "Oktobar", "Novembar", "Decembar"],
		monthsShort: ["Jan", "Feb", "Mar", "Apr", "Maj", "Jun", "Jul", "Avg", "Sep", "Okt", "Nov", "Dec"],
		today: "Danas"
	};
}(jQuery));
                                                                                                                                                                                                                                                                                                                                                                                               master/datepicker/js/locales/bootstrap-datepicker.rs.js                                             000644  000767  000024  00000001503 12136504245 024270  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /**
 * Serbian cyrillic translation for bootstrap-datepicker
 * Bojan Milosavlević <milboj@gmail.com>
 */
;(function($){
	$.fn.datepicker.dates['rs'] = {
		days: ["Недеља","Понедељак", "Уторак", "Среда", "Четвртак", "Петак", "Субота", "Недеља"],
		daysShort: ["Нед", "Пон", "Уто", "Сре", "Чет", "Пет", "Суб", "Нед"],
		daysMin: ["Н", "По", "У", "Ср", "Ч", "Пе", "Су", "Н"],
		months: ["Јануар", "Фебруар", "Март", "Април", "Мај", "Јун", "Јул", "Август", "Септембар", "Октобар", "Новембар", "Децембар"],
		monthsShort: ["Јан", "Феб", "Мар", "Апр", "Мај", "Јун", "Јул", "Авг", "Сеп", "Окт", "Нов", "Дец"],
		today: "Данас"
	};
}(jQuery));
                                                                                                                                                                                             master/datepicker/js/locales/bootstrap-datepicker.ru.js                                             000644  000767  000024  00000001542 12136504245 024275  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /**
 * Russian translation for bootstrap-datepicker
 * Victor Taranenko <darwin@snowdale.com>
 */
;(function($){
	$.fn.datepicker.dates['ru'] = {
		days: ["Воскресенье", "Понедельник", "Вторник", "Среда", "Четверг", "Пятница", "Суббота", "Воскресенье"],
		daysShort: ["Вск", "Пнд", "Втр", "Срд", "Чтв", "Птн", "Суб", "Вск"],
		daysMin: ["Вс", "Пн", "Вт", "Ср", "Чт", "Пт", "Сб", "Вс"],
		months: ["Январь", "Февраль", "Март", "Апрель", "Май", "Июнь", "Июль", "Август", "Сентябрь", "Октябрь", "Ноябрь", "Декабрь"],
		monthsShort: ["Янв", "Фев", "Мар", "Апр", "Май", "Июн", "Июл", "Авг", "Сен", "Окт", "Ноя", "Дек"],
		today: "Сегодня"
	};
}(jQuery));                                                                                                                                                              master/datepicker/js/locales/bootstrap-datepicker.sk.js                                             000644  000767  000024  00000001265 12136504245 024266  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /**
 * Slovak translation for bootstrap-datepicker
 * Marek Lichtner <marek@licht.sk>
 * Fixes by Michal Remiš <michal.remis@gmail.com>
 */
;(function($){
	$.fn.datepicker.dates["sk"] = {
		days: ["Nedeľa", "Pondelok", "Utorok", "Streda", "Štvrtok", "Piatok", "Sobota", "Nedeľa"],
		daysShort: ["Ned", "Pon", "Uto", "Str", "Štv", "Pia", "Sob", "Ned"],
		daysMin: ["Ne", "Po", "Ut", "St", "Št", "Pia", "So", "Ne"],
		months: ["Január", "Február", "Marec", "Apríl", "Máj", "Jún", "Júl", "August", "September", "Október", "November", "December"],
		monthsShort: ["Jan", "Feb", "Mar", "Apr", "Máj", "Jún", "Júl", "Aug", "Sep", "Okt", "Nov", "Dec"],
		today: "Dnes"
	};
}(jQuery));
                                                                                                                                                                                                                                                                                                                                           master/datepicker/js/locales/bootstrap-datepicker.sl.js                                             000644  000767  000024  00000001204 12136504245 024260  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /**
 * Slovene translation for bootstrap-datepicker
 * Gregor Rudolf <gregor.rudolf@gmail.com>
 */
;(function($){
	$.fn.datepicker.dates['sl'] = {
		days: ["Nedelja", "Ponedeljek", "Torek", "Sreda", "Četrtek", "Petek", "Sobota", "Nedelja"],
		daysShort: ["Ned", "Pon", "Tor", "Sre", "Čet", "Pet", "Sob", "Ned"],
		daysMin: ["Ne", "Po", "To", "Sr", "Če", "Pe", "So", "Ne"],
		months: ["Januar", "Februar", "Marec", "April", "Maj", "Junij", "Julij", "Avgust", "September", "Oktober", "November", "December"],
		monthsShort: ["Jan", "Feb", "Mar", "Apr", "Maj", "Jun", "Jul", "Avg", "Sep", "Okt", "Nov", "Dec"],
		today: "Danes"
	};
}(jQuery));
                                                                                                                                                                                                                                                                                                                                                                                            master/datepicker/js/locales/bootstrap-datepicker.sv.js                                             000644  000767  000024  00000001212 12136504245 024271  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /**
 * Swedish translation for bootstrap-datepicker
 * Patrik Ragnarsson <patrik@starkast.net>
 */
;(function($){
	$.fn.datepicker.dates['sv'] = {
		days: ["Söndag", "Måndag", "Tisdag", "Onsdag", "Torsdag", "Fredag", "Lördag", "Söndag"],
		daysShort: ["Sön", "Mån", "Tis", "Ons", "Tor", "Fre", "Lör", "Sön"],
		daysMin: ["Sö", "Må", "Ti", "On", "To", "Fr", "Lö", "Sö"],
		months: ["Januari", "Februari", "Mars", "April", "Maj", "Juni", "Juli", "Augusti", "September", "Oktober", "November", "December"],
		monthsShort: ["Jan", "Feb", "Mar", "Apr", "Maj", "Jun", "Jul", "Aug", "Sep", "Okt", "Nov", "Dec"],
		today: "I Dag"
	};
}(jQuery));
                                                                                                                                                                                                                                                                                                                                                                                      master/datepicker/js/locales/bootstrap-datepicker.sw.js                                             000644  000767  000024  00000001405 12136504245 024276  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /**
 * Swahili translation for bootstrap-datepicker
 * Edwin Mugendi <https://github.com/edwinmugendi>
 * Source: http://scriptsource.org/cms/scripts/page.php?item_id=entry_detail&uid=xnfaqyzcku
 */
;(function($){
    $.fn.datepicker.dates['sw'] = {
        days: ["Jumapili", "Jumatatu", "Jumanne", "Jumatano", "Alhamisi", "Ijumaa", "Jumamosi", "Jumapili"],
        daysShort: ["J2", "J3", "J4", "J5", "Alh", "Ij", "J1", "J2"],
        daysMin: ["2", "3", "4", "5", "A", "I", "1", "2"],
        months: ["Januari", "Februari", "Machi", "Aprili", "Mei", "Juni", "Julai", "Agosti", "Septemba", "Oktoba", "Novemba", "Desemba"],
        monthsShort: ["Jan", "Feb", "Mac", "Apr", "Mei", "Jun", "Jul", "Ago", "Sep", "Okt", "Nov", "Des"],
        today: "Leo"
    };
}(jQuery));
                                                                                                                                                                                                                                                           master/datepicker/js/locales/bootstrap-datepicker.th.js                                             000644  000767  000024  00000001760 12136504245 024264  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /**
 * Thai translation for bootstrap-datepicker
 * Suchau Jiraprapot <seroz24@gmail.com>
 */
;(function($){
	$.fn.datepicker.dates['th'] = {
		days: ["อาทิตย์", "จันทร์", "อังคาร", "พุธ", "พฤหัส", "ศุกร์", "เสาร์", "อาทิตย์"],
		daysShort: ["อา", "จ", "อ", "พ", "พฤ", "ศ", "ส", "อา"],
		daysMin: ["อา", "จ", "อ", "พ", "พฤ", "ศ", "ส", "อา"],
		months: ["มกราคม", "กุมภาพันธ์", "มีนาคม", "เมษายน", "พฤษภาคม", "มิถุนายน", "กรกฎาคม", "สิงหาคม", "กันยายน", "ตุลาคม", "พฤศจิกายน", "ธันวาคม"],
		monthsShort: ["ม.ค.", "ก.พ.", "มี.ค.", "เม.ย.", "พ.ค.", "มิ.ย.", "ก.ค.", "ส.ค.", "ก.ย.", "ต.ค.", "พ.ย.", "ธ.ค."],
		today: "วันนี้"
	};
}(jQuery));
                master/datepicker/js/locales/bootstrap-datepicker.tr.js                                             000644  000767  000024  00000001207 12136504245 024272  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /**
 * Turkish translation for bootstrap-datepicker
 * Serkan Algur <kaisercrazy_2@hotmail.com>
 */
;(function($){
	$.fn.datepicker.dates['tr'] = {
		days: ["Pazar", "Pazartesi", "Salı", "Çarşamba", "Perşembe", "Cuma", "Cumartesi", "Pazar"],
		daysShort: ["Pz", "Pzt", "Sal", "Çrş", "Prş", "Cu", "Cts", "Pz"],
		daysMin: ["Pz", "Pzt", "Sa", "Çr", "Pr", "Cu", "Ct", "Pz"],
		months: ["Ocak", "Şubat", "Mart", "Nisan", "Mayıs", "Haziran", "Temmuz", "Ağustos", "Eylül", "Ekim", "Kasım", "Aralık"],
		monthsShort: ["Oca", "Şub", "Mar", "Nis", "May", "Haz", "Tem", "Ağu", "Eyl", "Eki", "Kas", "Ara"],
		today: "Bugün"
	};
}(jQuery));

                                                                                                                                                                                                                                                                                                                                                                                         master/datepicker/js/locales/bootstrap-datepicker.uk.js                                             000644  000767  000024  00000001571 12136504245 024270  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /**
 * Ukrainian translation for bootstrap-datepicker
 * Andrey Vityuk <andrey [dot] vityuk [at] gmail.com>
 */
;(function($){
	$.fn.datepicker.dates['uk'] = {
		days: ["Неділя", "Понеділок", "Вівторок", "Середа", "Четвер", "П'ятниця", "Субота", "Неділя"],
		daysShort: ["Нед", "Пнд", "Втр", "Срд", "Чтв", "Птн", "Суб", "Нед"],
		daysMin: ["Нд", "Пн", "Вт", "Ср", "Чт", "Пт", "Сб", "Нд"],
		months: ["Січень", "Лютий", "Березень", "Квітень", "Травень", "Червень", "Липень", "Серпень", "Вересень", "Жовтень", "Листопад", "Грудень"],
		monthsShort: ["Січ", "Лют", "Бер", "Кві", "Тра", "Чер", "Лип", "Сер", "Вер", "Жов", "Лис", "Гру"],
		today: "Сьогодні"
	};
}(jQuery));                                                                                                                                       master/datepicker/js/locales/bootstrap-datepicker.zh-CN.js                                          000644  000767  000024  00000001364 12136504245 024570  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /**
 * Simplified Chinese translation for bootstrap-datepicker
 * Yuan Cheung <advanimal@gmail.com>
 */
;(function($){
	$.fn.datepicker.dates['zh-CN'] = {
				days: ["星期日", "星期一", "星期二", "星期三", "星期四", "星期五", "星期六", "星期日"],
			daysShort: ["周日", "周一", "周二", "周三", "周四", "周五", "周六", "周日"],
			daysMin:  ["日", "一", "二", "三", "四", "五", "六", "日"],
			months: ["一月", "二月", "三月", "四月", "五月", "六月", "七月", "八月", "九月", "十月", "十一月", "十二月"],
			monthsShort: ["一月", "二月", "三月", "四月", "五月", "六月", "七月", "八月", "九月", "十月", "十一月", "十二月"],
			today: "今日"
	};
}(jQuery));
                                                                                                                                                                                                                                                                            master/datepicker/js/locales/bootstrap-datepicker.zh-TW.js                                          000644  000767  000024  00000001346 12136504245 024622  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /**
 * Traditional Chinese translation for bootstrap-datepicker
 * Rung-Sheng Jang <daniel@i-trend.co.cc>
 */
;(function($){
	$.fn.datepicker.dates['zh-TW'] = {
				days: ["星期日", "星期一", "星期二", "星期三", "星期四", "星期五", "星期六", "星期日"],
			daysShort: ["周日", "周一", "周二", "周三", "周四", "周五", "周六", "周日"],
			daysMin:  ["日", "一", "二", "三", "四", "五", "六", "日"],
			months: ["一月", "二月", "三月", "四月", "五月", "六月", "七月", "八月", "九月", "十月", "十一月", "十二月"],
			monthsShort: ["一月", "二月", "三月", "四月", "五月", "六月", "七月", "八月", "九月", "十月", "十一月", "十二月"]
	};
}(jQuery));
                                                                                                                                                                                                                                                                                          master/datepicker/css/datepicker.css                                                                000644  000767  000024  00000037434 12136504245 020554  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /*!
 * Datepicker for Bootstrap
 *
 * Copyright 2012 Stefan Petre
 * Improvements by Andrew Rowls
 * Licensed under the Apache License v2.0
 * http://www.apache.org/licenses/LICENSE-2.0
 *
 */
.datepicker {
  padding: 4px;
  -webkit-border-radius: 4px;
  -moz-border-radius: 4px;
  border-radius: 4px;
  direction: ltr;
  /*.dow {
		border-top: 1px solid #ddd !important;
	}*/

}
.datepicker-inline {
  width: 220px;
}
.datepicker.datepicker-rtl {
  direction: rtl;
}
.datepicker.datepicker-rtl table tr td span {
  float: right;
}
.datepicker-dropdown {
  top: 0;
  left: 0;
}
.datepicker-dropdown:before {
  content: '';
  display: inline-block;
  border-left: 7px solid transparent;
  border-right: 7px solid transparent;
  border-bottom: 7px solid #ccc;
  border-bottom-color: rgba(0, 0, 0, 0.2);
  position: absolute;
  top: -7px;
  left: 6px;
}
.datepicker-dropdown:after {
  content: '';
  display: inline-block;
  border-left: 6px solid transparent;
  border-right: 6px solid transparent;
  border-bottom: 6px solid #ffffff;
  position: absolute;
  top: -6px;
  left: 7px;
}
.datepicker > div {
  display: none;
}
.datepicker.days div.datepicker-days {
  display: block;
}
.datepicker.months div.datepicker-months {
  display: block;
}
.datepicker.years div.datepicker-years {
  display: block;
}
.datepicker table {
  margin: 0;
}
.datepicker td,
.datepicker th {
  text-align: center;
  width: 20px;
  height: 20px;
  -webkit-border-radius: 4px;
  -moz-border-radius: 4px;
  border-radius: 4px;
  border: none;
}
.table-striped .datepicker table tr td,
.table-striped .datepicker table tr th {
  background-color: transparent;
}
.datepicker table tr td.day:hover {
  background: #eeeeee;
  cursor: pointer;
}
.datepicker table tr td.old,
.datepicker table tr td.new {
  color: #999999;
}
.datepicker table tr td.disabled,
.datepicker table tr td.disabled:hover {
  background: none;
  color: #999999;
  cursor: default;
}
.datepicker table tr td.today,
.datepicker table tr td.today:hover,
.datepicker table tr td.today.disabled,
.datepicker table tr td.today.disabled:hover {
  background-color: #fde19a;
  background-image: -moz-linear-gradient(top, #fdd49a, #fdf59a);
  background-image: -ms-linear-gradient(top, #fdd49a, #fdf59a);
  background-image: -webkit-gradient(linear, 0 0, 0 100%, from(#fdd49a), to(#fdf59a));
  background-image: -webkit-linear-gradient(top, #fdd49a, #fdf59a);
  background-image: -o-linear-gradient(top, #fdd49a, #fdf59a);
  background-image: linear-gradient(top, #fdd49a, #fdf59a);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#fdd49a', endColorstr='#fdf59a', GradientType=0);
  border-color: #fdf59a #fdf59a #fbed50;
  border-color: rgba(0, 0, 0, 0.1) rgba(0, 0, 0, 0.1) rgba(0, 0, 0, 0.25);
  filter: progid:DXImageTransform.Microsoft.gradient(enabled=false);
  color: #000 !important;
}
.datepicker table tr td.today:hover,
.datepicker table tr td.today:hover:hover,
.datepicker table tr td.today.disabled:hover,
.datepicker table tr td.today.disabled:hover:hover,
.datepicker table tr td.today:active,
.datepicker table tr td.today:hover:active,
.datepicker table tr td.today.disabled:active,
.datepicker table tr td.today.disabled:hover:active,
.datepicker table tr td.today.active,
.datepicker table tr td.today:hover.active,
.datepicker table tr td.today.disabled.active,
.datepicker table tr td.today.disabled:hover.active,
.datepicker table tr td.today.disabled,
.datepicker table tr td.today:hover.disabled,
.datepicker table tr td.today.disabled.disabled,
.datepicker table tr td.today.disabled:hover.disabled,
.datepicker table tr td.today[disabled],
.datepicker table tr td.today:hover[disabled],
.datepicker table tr td.today.disabled[disabled],
.datepicker table tr td.today.disabled:hover[disabled] {
  background-color: #fdf59a;
}
.datepicker table tr td.today:active,
.datepicker table tr td.today:hover:active,
.datepicker table tr td.today.disabled:active,
.datepicker table tr td.today.disabled:hover:active,
.datepicker table tr td.today.active,
.datepicker table tr td.today:hover.active,
.datepicker table tr td.today.disabled.active,
.datepicker table tr td.today.disabled:hover.active {
  background-color: #fbf069 \9;
}
.datepicker table tr td.range,
.datepicker table tr td.range:hover,
.datepicker table tr td.range.disabled,
.datepicker table tr td.range.disabled:hover {
  background: #eeeeee;
  -webkit-border-radius: 0;
  -moz-border-radius: 0;
  border-radius: 0;
}
.datepicker table tr td.range.today,
.datepicker table tr td.range.today:hover,
.datepicker table tr td.range.today.disabled,
.datepicker table tr td.range.today.disabled:hover {
  background-color: #f3d17a;
  background-image: -moz-linear-gradient(top, #f3c17a, #f3e97a);
  background-image: -ms-linear-gradient(top, #f3c17a, #f3e97a);
  background-image: -webkit-gradient(linear, 0 0, 0 100%, from(#f3c17a), to(#f3e97a));
  background-image: -webkit-linear-gradient(top, #f3c17a, #f3e97a);
  background-image: -o-linear-gradient(top, #f3c17a, #f3e97a);
  background-image: linear-gradient(top, #f3c17a, #f3e97a);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#f3c17a', endColorstr='#f3e97a', GradientType=0);
  border-color: #f3e97a #f3e97a #edde34;
  border-color: rgba(0, 0, 0, 0.1) rgba(0, 0, 0, 0.1) rgba(0, 0, 0, 0.25);
  filter: progid:DXImageTransform.Microsoft.gradient(enabled=false);
  -webkit-border-radius: 0;
  -moz-border-radius: 0;
  border-radius: 0;
}
.datepicker table tr td.range.today:hover,
.datepicker table tr td.range.today:hover:hover,
.datepicker table tr td.range.today.disabled:hover,
.datepicker table tr td.range.today.disabled:hover:hover,
.datepicker table tr td.range.today:active,
.datepicker table tr td.range.today:hover:active,
.datepicker table tr td.range.today.disabled:active,
.datepicker table tr td.range.today.disabled:hover:active,
.datepicker table tr td.range.today.active,
.datepicker table tr td.range.today:hover.active,
.datepicker table tr td.range.today.disabled.active,
.datepicker table tr td.range.today.disabled:hover.active,
.datepicker table tr td.range.today.disabled,
.datepicker table tr td.range.today:hover.disabled,
.datepicker table tr td.range.today.disabled.disabled,
.datepicker table tr td.range.today.disabled:hover.disabled,
.datepicker table tr td.range.today[disabled],
.datepicker table tr td.range.today:hover[disabled],
.datepicker table tr td.range.today.disabled[disabled],
.datepicker table tr td.range.today.disabled:hover[disabled] {
  background-color: #f3e97a;
}
.datepicker table tr td.range.today:active,
.datepicker table tr td.range.today:hover:active,
.datepicker table tr td.range.today.disabled:active,
.datepicker table tr td.range.today.disabled:hover:active,
.datepicker table tr td.range.today.active,
.datepicker table tr td.range.today:hover.active,
.datepicker table tr td.range.today.disabled.active,
.datepicker table tr td.range.today.disabled:hover.active {
  background-color: #efe24b \9;
}
.datepicker table tr td.selected,
.datepicker table tr td.selected:hover,
.datepicker table tr td.selected.disabled,
.datepicker table tr td.selected.disabled:hover {
  background-color: #9e9e9e;
  background-image: -moz-linear-gradient(top, #b3b3b3, #808080);
  background-image: -ms-linear-gradient(top, #b3b3b3, #808080);
  background-image: -webkit-gradient(linear, 0 0, 0 100%, from(#b3b3b3), to(#808080));
  background-image: -webkit-linear-gradient(top, #b3b3b3, #808080);
  background-image: -o-linear-gradient(top, #b3b3b3, #808080);
  background-image: linear-gradient(top, #b3b3b3, #808080);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#b3b3b3', endColorstr='#808080', GradientType=0);
  border-color: #808080 #808080 #595959;
  border-color: rgba(0, 0, 0, 0.1) rgba(0, 0, 0, 0.1) rgba(0, 0, 0, 0.25);
  filter: progid:DXImageTransform.Microsoft.gradient(enabled=false);
  color: #fff;
  text-shadow: 0 -1px 0 rgba(0, 0, 0, 0.25);
}
.datepicker table tr td.selected:hover,
.datepicker table tr td.selected:hover:hover,
.datepicker table tr td.selected.disabled:hover,
.datepicker table tr td.selected.disabled:hover:hover,
.datepicker table tr td.selected:active,
.datepicker table tr td.selected:hover:active,
.datepicker table tr td.selected.disabled:active,
.datepicker table tr td.selected.disabled:hover:active,
.datepicker table tr td.selected.active,
.datepicker table tr td.selected:hover.active,
.datepicker table tr td.selected.disabled.active,
.datepicker table tr td.selected.disabled:hover.active,
.datepicker table tr td.selected.disabled,
.datepicker table tr td.selected:hover.disabled,
.datepicker table tr td.selected.disabled.disabled,
.datepicker table tr td.selected.disabled:hover.disabled,
.datepicker table tr td.selected[disabled],
.datepicker table tr td.selected:hover[disabled],
.datepicker table tr td.selected.disabled[disabled],
.datepicker table tr td.selected.disabled:hover[disabled] {
  background-color: #808080;
}
.datepicker table tr td.selected:active,
.datepicker table tr td.selected:hover:active,
.datepicker table tr td.selected.disabled:active,
.datepicker table tr td.selected.disabled:hover:active,
.datepicker table tr td.selected.active,
.datepicker table tr td.selected:hover.active,
.datepicker table tr td.selected.disabled.active,
.datepicker table tr td.selected.disabled:hover.active {
  background-color: #666666 \9;
}
.datepicker table tr td.active,
.datepicker table tr td.active:hover,
.datepicker table tr td.active.disabled,
.datepicker table tr td.active.disabled:hover {
  background-color: #006dcc;
  background-image: -moz-linear-gradient(top, #0088cc, #0044cc);
  background-image: -ms-linear-gradient(top, #0088cc, #0044cc);
  background-image: -webkit-gradient(linear, 0 0, 0 100%, from(#0088cc), to(#0044cc));
  background-image: -webkit-linear-gradient(top, #0088cc, #0044cc);
  background-image: -o-linear-gradient(top, #0088cc, #0044cc);
  background-image: linear-gradient(top, #0088cc, #0044cc);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#0088cc', endColorstr='#0044cc', GradientType=0);
  border-color: #0044cc #0044cc #002a80;
  border-color: rgba(0, 0, 0, 0.1) rgba(0, 0, 0, 0.1) rgba(0, 0, 0, 0.25);
  filter: progid:DXImageTransform.Microsoft.gradient(enabled=false);
  color: #fff;
  text-shadow: 0 -1px 0 rgba(0, 0, 0, 0.25);
}
.datepicker table tr td.active:hover,
.datepicker table tr td.active:hover:hover,
.datepicker table tr td.active.disabled:hover,
.datepicker table tr td.active.disabled:hover:hover,
.datepicker table tr td.active:active,
.datepicker table tr td.active:hover:active,
.datepicker table tr td.active.disabled:active,
.datepicker table tr td.active.disabled:hover:active,
.datepicker table tr td.active.active,
.datepicker table tr td.active:hover.active,
.datepicker table tr td.active.disabled.active,
.datepicker table tr td.active.disabled:hover.active,
.datepicker table tr td.active.disabled,
.datepicker table tr td.active:hover.disabled,
.datepicker table tr td.active.disabled.disabled,
.datepicker table tr td.active.disabled:hover.disabled,
.datepicker table tr td.active[disabled],
.datepicker table tr td.active:hover[disabled],
.datepicker table tr td.active.disabled[disabled],
.datepicker table tr td.active.disabled:hover[disabled] {
  background-color: #0044cc;
}
.datepicker table tr td.active:active,
.datepicker table tr td.active:hover:active,
.datepicker table tr td.active.disabled:active,
.datepicker table tr td.active.disabled:hover:active,
.datepicker table tr td.active.active,
.datepicker table tr td.active:hover.active,
.datepicker table tr td.active.disabled.active,
.datepicker table tr td.active.disabled:hover.active {
  background-color: #003399 \9;
}
.datepicker table tr td span {
  display: block;
  width: 23%;
  height: 54px;
  line-height: 54px;
  float: left;
  margin: 1%;
  cursor: pointer;
  -webkit-border-radius: 4px;
  -moz-border-radius: 4px;
  border-radius: 4px;
}
.datepicker table tr td span:hover {
  background: #eeeeee;
}
.datepicker table tr td span.disabled,
.datepicker table tr td span.disabled:hover {
  background: none;
  color: #999999;
  cursor: default;
}
.datepicker table tr td span.active,
.datepicker table tr td span.active:hover,
.datepicker table tr td span.active.disabled,
.datepicker table tr td span.active.disabled:hover {
  background-color: #006dcc;
  background-image: -moz-linear-gradient(top, #0088cc, #0044cc);
  background-image: -ms-linear-gradient(top, #0088cc, #0044cc);
  background-image: -webkit-gradient(linear, 0 0, 0 100%, from(#0088cc), to(#0044cc));
  background-image: -webkit-linear-gradient(top, #0088cc, #0044cc);
  background-image: -o-linear-gradient(top, #0088cc, #0044cc);
  background-image: linear-gradient(top, #0088cc, #0044cc);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#0088cc', endColorstr='#0044cc', GradientType=0);
  border-color: #0044cc #0044cc #002a80;
  border-color: rgba(0, 0, 0, 0.1) rgba(0, 0, 0, 0.1) rgba(0, 0, 0, 0.25);
  filter: progid:DXImageTransform.Microsoft.gradient(enabled=false);
  color: #fff;
  text-shadow: 0 -1px 0 rgba(0, 0, 0, 0.25);
}
.datepicker table tr td span.active:hover,
.datepicker table tr td span.active:hover:hover,
.datepicker table tr td span.active.disabled:hover,
.datepicker table tr td span.active.disabled:hover:hover,
.datepicker table tr td span.active:active,
.datepicker table tr td span.active:hover:active,
.datepicker table tr td span.active.disabled:active,
.datepicker table tr td span.active.disabled:hover:active,
.datepicker table tr td span.active.active,
.datepicker table tr td span.active:hover.active,
.datepicker table tr td span.active.disabled.active,
.datepicker table tr td span.active.disabled:hover.active,
.datepicker table tr td span.active.disabled,
.datepicker table tr td span.active:hover.disabled,
.datepicker table tr td span.active.disabled.disabled,
.datepicker table tr td span.active.disabled:hover.disabled,
.datepicker table tr td span.active[disabled],
.datepicker table tr td span.active:hover[disabled],
.datepicker table tr td span.active.disabled[disabled],
.datepicker table tr td span.active.disabled:hover[disabled] {
  background-color: #0044cc;
}
.datepicker table tr td span.active:active,
.datepicker table tr td span.active:hover:active,
.datepicker table tr td span.active.disabled:active,
.datepicker table tr td span.active.disabled:hover:active,
.datepicker table tr td span.active.active,
.datepicker table tr td span.active:hover.active,
.datepicker table tr td span.active.disabled.active,
.datepicker table tr td span.active.disabled:hover.active {
  background-color: #003399 \9;
}
.datepicker table tr td span.old {
  color: #999999;
}
.datepicker th.datepicker-switch {
  width: 145px;
}
.datepicker thead tr:first-child th,
.datepicker tfoot tr:first-child th {
  cursor: pointer;
}
.datepicker thead tr:first-child th:hover,
.datepicker tfoot tr:first-child th:hover {
  background: #eeeeee;
}
.datepicker .cw {
  font-size: 10px;
  width: 12px;
  padding: 0 2px 0 5px;
  vertical-align: middle;
}
.datepicker thead tr:first-child th.cw {
  cursor: default;
  background-color: transparent;
}
.input-append.date .add-on i,
.input-prepend.date .add-on i {
  display: block;
  cursor: pointer;
  width: 16px;
  height: 16px;
}
.input-daterange input {
  text-align: center;
}
.input-daterange input:first-child {
  -webkit-border-radius: 3px 0 0 3px;
  -moz-border-radius: 3px 0 0 3px;
  border-radius: 3px 0 0 3px;
}
.input-daterange input:last-child {
  -webkit-border-radius: 0 3px 3px 0;
  -moz-border-radius: 0 3px 3px 0;
  border-radius: 0 3px 3px 0;
}
.input-daterange .add-on {
  display: inline-block;
  width: auto;
  min-width: 16px;
  height: 18px;
  padding: 4px 5px;
  font-weight: normal;
  line-height: 18px;
  text-align: center;
  text-shadow: 0 1px 0 #ffffff;
  vertical-align: middle;
  background-color: #eeeeee;
  border: 1px solid #ccc;
  margin-left: -5px;
  margin-right: -5px;
}
                                                                                                                                                                                                                                    master/datepicker/build/build.less                                                                  000644  000767  000024  00000004405 12136504245 020215  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         // Datepicker .less buildfile.  Includes select mixins/variables from bootstrap
// and imports the included datepicker.less to output a minimal datepicker.css
//
// Usage:
//     lessc build.less datepicker.css
//
// Variables and mixins copied from bootstrap 2.0.2

// Variables
@grayLight:             #999;
@grayLighter:           #eee;
@white:                 #fff;
@linkColor:             #08c;
@btnPrimaryBackground:  @linkColor;
@orange:                #f89406;
@baseLineHeight:        18px;

// Mixins

// Border Radius
.border-radius(@radius: 5px) {
  -webkit-border-radius: @radius;
     -moz-border-radius: @radius;
          border-radius: @radius;
}

// Button backgrounds
.buttonBackground(@startColor, @endColor) {
  .gradientBar(@startColor, @endColor);
  .reset-filter();
  &:hover, &:active, &.active, &.disabled, &[disabled] {
    background-color: @endColor;
  }
  &:active,
  &.active {
    background-color: darken(@endColor, 10%) e("\9");
  }
}

// Reset filters for IE
.reset-filter() {
  filter: progid:DXImageTransform.Microsoft.gradient(enabled = false);
}

// Gradient Bar Colors for buttons and alerts
.gradientBar(@primaryColor, @secondaryColor) {
  #gradient > .vertical(@primaryColor, @secondaryColor);
  border-color: @secondaryColor @secondaryColor darken(@secondaryColor, 15%);
  border-color: rgba(0,0,0,.1) rgba(0,0,0,.1) fadein(rgba(0,0,0,.1), 15%);
}

// Gradients
#gradient {
  .vertical(@startColor: #555, @endColor: #333) {
    background-color: mix(@startColor, @endColor, 60%);
    background-image: -moz-linear-gradient(top, @startColor, @endColor); // FF 3.6+
    background-image: -ms-linear-gradient(top, @startColor, @endColor); // IE10
    background-image: -webkit-gradient(linear, 0 0, 0 100%, from(@startColor), to(@endColor)); // Safari 4+, Chrome 2+
    background-image: -webkit-linear-gradient(top, @startColor, @endColor); // Safari 5.1+, Chrome 10+
    background-image: -o-linear-gradient(top, @startColor, @endColor); // Opera 11.10
    background-image: linear-gradient(top, @startColor, @endColor); // The standard
    background-repeat: repeat-x;
    filter: e(%("progid:DXImageTransform.Microsoft.gradient(startColorstr='%d', endColorstr='%d', GradientType=0)",@startColor,@endColor)); // IE9 and down
  }
}

@import "../less/datepicker.less";
                                                                                                                                                                                                                                                           master/datepicker/build/build_standalone.less                                                       000644  000767  000024  00000003604 12136504245 022425  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         // Datepicker standalone .less buildfile.  Includes all necessary mixins/variables/rules from bootstrap
// and imports the included datepicker.less to output a minimal standalone datepicker.css
//
// Usage:
//     lessc build_standalone.less datepicker.css
//
// Variables, mixins, and rules copied from bootstrap 2.0.2

@import "build.less";

// Dropdown css

@zindexDropdown:                1000;
@grayDark:                      #333;
@baseLineHeight:                18px;
@tableBackground:               transparent; // overall background-color
@dropdownBackground:            @white;
@dropdownBorder:                rgba(0,0,0,.2);
@dropdownLinkColor:             @grayDark;
@dropdownLinkColorHover:        @white;
@dropdownLinkBackgroundHover:   @linkColor;

// Drop shadows
.box-shadow(@shadow) {
  -webkit-box-shadow: @shadow;
     -moz-box-shadow: @shadow;
          box-shadow: @shadow;
}

// The dropdown menu (ul)
// ----------------------
.datepicker.dropdown-menu {
  position: absolute;
  top: 100%;
  left: 0;
  z-index: @zindexDropdown;
  float: left;
  display: none; // none by default, but block on "open" of the menu
  min-width: 160px;
  list-style: none;
  background-color: @dropdownBackground;
  border: 1px solid #ccc;
  border: 1px solid rgba(0,0,0,.2);
  .border-radius(5px);
  .box-shadow(0 5px 10px rgba(0,0,0,.2));
  -webkit-background-clip: padding-box;
     -moz-background-clip: padding;
          background-clip: padding-box;
  *border-right-width: 2px;
  *border-bottom-width: 2px;

  // Normally inherited from bootstrap's `body`
  color: #333333;
  font-family: "Helvetica Neue",Helvetica,Arial,sans-serif;
  font-size:13px;
  line-height: @baseLineHeight;

  th, td {
    padding: 4px 5px;
  }
}

// Alternative arrows
// May require `charset="UTF-8"` in your `<link>` tag
.datepicker {
  .prev, .next {font-style:normal;}
  .prev:after {content:"«";}
  .next:after {content:"»";}
}
                                                                                                                            master/images/                                                                                      000755  000767  000024  00000000000 12152167061 014255  5                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         master/images/omh_logo-white.png                                                                    000644  000767  000024  00000041641 12152167061 017712  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         �PNG

   IHDR  D      M�c�   	pHYs     ��   tEXtSoftware Adobe ImageReadyq�e<  C.IDATx���?�Y�'�/�Y����l�`Y�k/�c�M�)9��j}V�t�X0hɜ�+���'H�" �[t�^`oX`�R��1�C2Od���<@�=S�/N�q"�/OD|w     %�M     �B 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    C 
    ���;X6Ϳ��{Xn��NS}�Y�~��.�߮��/K5����kmx�  `x����k�"v/�e��<�|��x��H%)���6|����M^7�X���r�������׆7�   �'eRz�,ON|�w�e�Fm�u~��P�YJ�}�i���^��Z  ��DY��^��A��RU���k�����{~ݏ��SІgM�8�k�T�   08�(K��tj��ߣ�@��Ǚ�O|�����u��yS#��Ū�y   �Q�(P)z:���������ϩ�9�uZ��4w+�ś6P��C�F+   �D �Ҍ@�������c�0��f9nc=7�����   p��,�TT���z%�X��ah4��M�=��㽎u��   0*3DY�S�t��]��M���ZK�)Z��ahێ�c�ߺ���������;�ⱗ~0S   � e	�	�>��]�ӵF���ڠ]¥�����z_��Oj×M{t	���[�WM�����6�2E  �#�(s�5�JA�e<P�6��_tx��B�:������),�ux�e�.��6��S��-��6����BQ   �@ ʜu�N��y
�~������utC�n����Y�	�;[t)��1����n��L(
   �����T��Ǜ��{(Z����Y����r�{(:U-N��  ���<s4U ���,�����&P�k��������秬�*�\�>   ��͔T��凢uL;�p��j�
�(   �J ʜ�!�jձ�P��y�j��PtN�X�P   z#e.�@��X^(ZǼ�;��Pt��X�P   z!e�@��XN(Z�<o³�PtεX�P   N&ejs�Zu�?�c�w$_B(��Z�B(
   '�2�%P�:���1�0�5�PtI�X�P   �&e*K
�Zu�/�cahk���k�
�(   E ��@��O(Zǲ��֜B�%�bBQ   �L �ؖ@��>�c�ahk��j�
�(   t"eLk�ZuL�ֱ�0�5e(��Z�B(
   پ����
�a���:�}U<L���iaT�C���c8�,���ڸ=������6   �wf�2�x]������f�ֱ��k̙�kC�*��}�{  �4f�2����|��}U;S�����z����ck�c�.;�   �0C���hkC�:��)ZG�B9S��04�"��p�<   �1C������[r ���~g��Q�u!��)ZRzl���i#   X=3DRe��I����̛��9S��0����t�[   (��i���Zݭlݫ8m�h�~�Lђ��8���  �Q��}X~�xܟ"��8KS�q�h��ֱ�h�0t�mFv��   ,�@��\=,?x�����ۡ�n��|X�U�ǯ9muE�K��?f>~�ah�yX~?�M[  ����(C�f<檀v���5E����5E�1�������>��n  `��%��ܻBڢ�n�h�R��V�P4G)a�~r��  `��a���ڤ��B����V��hiah��}<��(   �'e*7�s�������>B���֡�mtM   ��@�!��2��6u����N	EKC�[�  @���������a����})м8�yQn��;   �7Q����T��N}�߄@t_��|}����dn�   ��2�]�cJ����#��}E�ڹyX���'�sK����  �tQ��sZn��TǇ���C�S��Vɡ��w�Q   VO �rB����I����RC�>��V��h�6��}  �vQ�r�A/���w��/m�����JEsnBu��  `��%�7W�C�����ᱥ��]����Yr��n�����)�   @ �Pr�4Ktͧ���-��a���s�=�������Y�g>g���Yf�\   ���{��Pn�𬴏�8{mm3�����{��zX^wx���9krL�j����Y��g��_c-vi�?�k�  P 3DR��5��K�}JھF�3EOC���m�;S�K�.��   �Q�v�g�&k��W��a�*ʛ)�G��ę�]��O���   �Q�v���5�Ϋ��0�}͒f���F�7S�k�kC  (�@��������.9����0t��KE�C[���]�����)   J�yƒ�`�"�K;e�����}U����!��}k>}�M�    �@���5��c�0�U��Bѱ��5ע0   29e�����:�C��\���c��k�Ea(   t eLk
��?��5��S��k�Ea(   t$elk��.��KE�C�R��P   8�@�),9��c�0t��,1�C��Z�  ���Le�AT�	C�?ӒB�9��K�Ea(   �@ ʔ�D�1�0t��-!�c��Z�  ���Lm	AT�C�?�C�9��K�Ea(   �@ ��9��c�a��g�c(��0t�(  ��D��9Qu,'���s
E��ε��   �#�(s2� ��兡��}���йբ0   z&en�Dձ�0t�E��Υ��   0 �(s4eU�����u�"]C:u-
C  ` Q�j� �������tL(zv��U��0t�Z�  ����٘AT�C�׭k(�µ��s6����:���]��P   �w���Z��:$�c�a�*�.>�c�y�|�Λ������.)���   0�(K1TXTGah���hߖ�Y��P   �S�Y�!NY���0�]�&|����CԢ0   F$eI���(/�_�)B�5��}ע0   F&ei���(7�o�1Cѷ��0��Z�  �\C��:6L�a�Υ&=�=~~X.����b��UC  `tQ��k������v�|X~��u��ɋ���ӫ�n��   �#�̳d]OY0�m�\��ay���}h�/�>�Q�'�  @��e���WR�%�x<���Ц�rBСkQ
   ��}Q���_��ǐt󅿥6�5�բ0   "eMN���̡��   0 �(ksl%e�Z�?���9��a��!  ���A�2��6�otD�k�   ��*o��5u�7����/��)�@��I;����s�E����	Гv�����T�  p��>���o
l���(�@�5���|�DяS�e���Ms����y�sR-�5�t��7  @���EǇ�-A����j���ay�������>�𾩭�\kb�E������������� F �����{z-A��+U��j�g���f��a���hm�	0{���ՁǤ�|��uy���% ����K��{~�6�:׼d�;U�etS���/1L���J��o� ��5   %��dutC���Es���5M����il������ǝ.�>,�C0
 p���t���-��8e����[x�C�:��+�,s�1ah[O[�X�ˇ�"��6�P�`��Y� ��kX3DY�:�C�t��m��G?=�6�	C�b�Λ:x�
C���N��_5�  �Q�����Ж �S����r�Y��q�ڇ�  �6Q�����Ж �c������&�G���:�����-]�����>[���ۿo����c=kj  X�e)��/m�A�M��#y�Cբ�ɩ��%�]|����s^�-]O�O��Kf�
  0kf��i��w�2;�\C��jQ�|ɇ�/���]߯{�,��k�5����x�B  ,�@���c�0�%�␡�P��n�k�B�&��[7q\0*  M ʜ���ahKšZ:U��s��з�)��S����yBQ  `���U����Q|�_d>��0T-��n����H/c�����"o����KWj  X"�(sT��a�~0�A�k��0T-.�E��y�|��3�ܩ~6k.}�3_9  �$Q榎��Ж ����w��+��/��}?P��Qs�2�4�u  X�(s��S�����(�x�Pa�Z\n��h�л�C�P4]R⥯  X
�(sQ�|���CA�Z����P��,��w��1�0t��5����  � e�@znahK��f�0T-.�&��S7S�<�ؚ��Yo�   X�?h&V�|���C��ț��Q�9���U��ǉ�_�8_�M{r���"�\
p�x�f;�-`�Λe�3[�8�m�{���ڶ�o��n����k���6�}ִæ��Jg{m�~��ޘ����vo�؟�~�W����Vr���^��m���F�+��n���d̉@�)�������P`�(�8]��k�Y?oc�7 J��s<��\>,UOmZe�W��^6�·���_�ei�g�z��Ł��{�}hֻ��������ڠ��o�ڠ$U�m���&�����/�����gM]4�����0��4��ck%y�W�������'��>>_KZ���M�qҩ.'n��{K���M���`a�����
L��儡���D^��o8����}��e���f`�䃿�ٟf<����0��Y��en'��vx�\-`[�4���{|��k��?>��n���we�r��o�?c`~���Ǟ��"NF���y�Sۼk^�f��#g{�s,c�ޡ�jkhU�<��5�6��ܾ��̶=�'���:�9{�����wmw����i��=�Ǜ���|l�¹�(s��%�pǒkqn��Z��`"���Vp�We>n.��h��Uσ��}�5Ù���Mӷ������^7��r���^���6x�����J/���Ǻ�K��z�f{HAb�!���5�pC���6u�:��^4�r3��F�����Y���n����Q=�}&��7����_�O��#�G��@��ձ�0�%�*��:�R-�cP�S?W+X�T;�zj�!m����@��n:����w4D��A�_���1g#|�����箚���SH���6�r{�����W����~�~Þ����1���f���tL����˒���#���G��"eLu,?m	�ʩŹ�j~l-n�Ao�9�ZN���xLPN5{��V�<���18�6���?�Ի���c�����-���?������*�1��������6v8�K���R�?���1q��;��sZ���H��L?����*���Q�ݹ�%=���3�ʙMr��u�ɬ�)�*�@�t ?�,�M󽼘�&�}��l�71�,�o��[�����>��}�뉶���Hu��~V�׼��.q�]�cĵ�;�����LF �� �ˌ�%��-AԲ\����ck�Y�{��R��C���n�r�S��=�=& I�˻�ei��즮!���6n���F
?5�������B��:�O�h��=���(����?zG�δ��YO}�ǦN�L����:I��_����7}��������Y�έ�s��O�_�V����&``��;�%���6������\�k�-�:����;�w���M^)���?k��3�O�SX7������md����y|��n��m�tޡ׽�Vf��k�e[e�o��/�>"wU=Q�y���o>�m|}F����2�|��~hJm�c�vw���8oھk���v�u^gn�{}��Wja�l]>��f;��"g]�]����wz��Z��B=_D~��lo�1���eUr|��^o�>��g�y��+6���z��g�^n���f�~9�>����_9��|֏v=����a8���ː��}�j��z���vX�s�1�r���ܭ��R�i}7��6�iے���^����l�w�k>�ّ��j^����������?����|�݉�յ.��>��4������߬��1m�鰿n�l�=�/����ێ�i;�����}�Xr��!����w�kj�~�KRO��k�V���:;r��r���r�mt��]u��=�:�x�5f�,N�gH�W��k�-qf�纞�lV޸�r~�^���Sj1�
{�D:�9-�f�럳nC����H�[�~n��SnlU73~���!��C���Yk��S|���)���S���?u`ݫ��l�o�5��s�J��������+��Ǧݎi�]�w�б>�}���/8�6o�����9���s�a����)���^�1s{��#��ϻf[�4�]�_��1�̫p��\}�O��mb�.��G��(C��!��𷙃����s����ݮ�s�߇�}u��D�Uκݿ����N��+�|�pݮ�;�_/#�T̷=�iw����x싘�&Km�q�S�w��/
ؿ�O7�:u��S�*O��?���̪���2����tϹI5�s�n_��߇l3k�����Oא�c���T�.�̧�2s��+}���㙻�� ��%u���ey�C��݈�Á���<�fR��	C??�ȩE�����κ}�ޯ�c���"?L~�~C���}��f�b�[e��T3~�Пu�u�2������������=��O���e�d�I��c���ڹk�hU�6��>3��4&�o����T��_3�.�@�!<r:�˕��]f�T*�������!�6s;3p��,���,�� ۑ?ӛ.�|{�E���]��N�G؞/2�O'ȼp��:�v���m{u����a�}�Uf��o>���mCOҸ��'��6+
��>Ùs������9��pr�y��s���M���ڕO��]�Q�C���w�~�p�L�Cפ�ÇrS���w�R�o�߯���ϛ~��k�n��_���p���5�o����0B_�j>�&�2pg��oC�?.��2�zH������O���~���F�r���X�ջ�{x��]���>�K?ڎ��{�AD�*,xe��Wm���P�2��D!�eƁh��Z��6�Y����|���CL3�e�]
j� ﺇm8�1�k����I3��_�b� �����w��ao�5'�^׻��_u�^���]s��}F�y�������o�㆏���==�oYۏ*u��Ol/L��H���~T �`�2�r~��i��8|��_���j񐍒��N��d��V�D�]��f9�&zg�w�2�qc��I�~3�:�eÔ�o��=�7~�83g�����T�7���*��a��6���TZ_��1�,\̨&���@��ۂ�㦇��8�=|?k���g��_]�`7���f������`�2��_N���̽C��T}燔ҟ�u��.�n�1�9?zo�)���b�Y�C>���/MΏ���?���.�ob��P�!��裂�����8N�γ�k���l�{��1�q��ˌǜrJ����	�����3\��8��2x�G|��ׇC��4�r<r��W��Ǥ���8o\4�)Μ�ه��@��@��`y:�
[_!k<p�Ï�`��l��+C꧲�ig��L��˳���9��Ǹ?�ٯ�W�1�̷��
�E��sُ�@(��/�_��q9�ϒJ3��yN=�����o9���v#��n����@�=�;��oc�3g�{�x)��Ҝ��&�������@��:����C��^�L�Ya�kP�`�O�����̾��f�l3�a�Y�7��d���T5p���w3�L�`��<73����B �/��o7��A�A0���y�3=����b�l�~J�鳙�@R��z���gX)�|�����s�/͝�q;�{Ǌ���y^��܎���2�+��p��d�{�^�����Y6Ϳg_�޾4;����]��~�S���}s e��їQF z�qзS2��i�m!�tP�T-�f���m�Xs܇��>9�5�-�����́�M�����B���~��B��)L���l�m�~���)���h>��޿�ה�ϡ�aN�g���C7��
i����e2펽�Z�zj/>��2�l��?X��)�������w3Y�C�é��X�7s��fN�=ԱD��3-��ay�����~����������\)OF>^��2C�!����i�{Q�N�2�1��eP�f-=k
oV��`��x�p����_d3aM}�i��N���̞�׃�s�].��},qތ��8��I�̈@������D�X�/Bi���<�ZKt�q�W7�k��:���6�:۵�;TW�Xo ���߆�aܒ�;�A�b����<]P���>��>���3��a�x�1)�Y���m�G�T�Sc��x����x<]��v⓾O�^�`3��J��RO7C`���:�� �Q�t���M3��X�u�#/\���3����&�Xn���ZL��:�qB8�UN�����q��6�17օY�_�4I��5��c������_گo���R���]����"DR
��uB���� ���ϓ��1x�eD�V�i^wh�I�$:m<]۱^���\��F���& �d<�%�|��\�8N�4㢴lc�k�|�S�R�;	~����f��k���ZP-V����C�u��]��ˌ~���#o3S���v��."oB@��%��f?V��6v�q�e��=,�ǳ� f�Q�v��s~�\��.ah��f�NS�OW^��3���x����<&͈�ĺ �������_�}����w�A00���[3?.�O:���,�� Jm���z��e�8`RQ��9��	�DuC߄�Lᮩſf>~���>k�0��R��H��/c=��&�n�5����ۧ�~��1@'��ܮ|s.[��i��HN�g��K:e�k�f�TJb��VZ������)�wن�ՙu�Y��^f<��H��9fs�盎}V�	P���[J���E汣0(�@���1������R�\��ZL�]��J)�"7T�\��n"�4��������g�x�k�ѹ��o�2���*�Z��X�'eLu�'�:&Me�U�}�B:���]fmW���q��`:4�蘙8��������Ǭ���Y�Ke�N ��Q�P�8UC� wP��K���y�:��ץ��mf�F}һ>'}/g6C��q���������46�)�tQ�P�r�(a�Z�K-V!���ț%��%���ȟ:��]̨��
Ds���}���Ǥ� ��>�R � e*ip�� J��R�UC��2�q?��«��~�b����ɀv������Ah:e�CO�P��˷\�tݟ���c����B ʔ�XN%U�s��*��stӴun��/h�x���M�M�>�r��N����>�ؗ�cR
D]rd\�h fC ��s���jq.�X�0t���*�.�O�>�|���js*?Nܖ��v:�rW�>����zg��Q=��\D�ˠ{�A�0T-Υ����]�6�{(ZG~�sw���?�ل�}Ȼ�h���=�4���f�7��*S �)�]�Z_�(`V���enA�0T-Υ��.�u�:߆��n�a軙p��aUZ��mz���{ӆ�u��
��]�����3�>{�s�}�F�Swl3��k�R0#Q�6�K%U�s��*��Ks��	9R�[�#T���,��04ͺ�ӵ�ƾ�E��^eL��\i��6�qcϖ=k�����x�u�g�>���j��4��x��;����;��#�¬D��t02u%e.������s��	;<�U��l&��)Ľ��(E�ns���
E�l��=O�ꪝy<V(zּߋϾ��p�`��~x��^~a��㸛�ǌ5����j�r.��8fD ������(a(s��*��K����K(�N%����$m�>��^�N}�Џ���g������_3��v��g��)�_��]|9H��V�\
��e<n�sR?����w_��ae�l�1.5ӆ��
������1�K%A���U�Q�P�R�UC��6���I�-�kL��>۶��~�n�����������@�6��{p��x����1̥r�i_����g�����>�Y��rl��?~���b�{�������]�]�����u}VX����A3!e��/��2�ZL����86}��~o���S?�±]tB#>����v��@�Ҭ�)�Ȧy��vh�68j�2�S�K����f��k�9�d	��]�_��i�����&ϛ�J��~���|����Н���ӯ���&�ow�~�
�b�^	D���C:��2�Z�B�F����|���.��y���{�~c�v����9xN�)���+����6�13��m��lɧM��w���qZ��#�FS����.�g;E3 �����������_u�_�n�����r��/�[h��ۏ�5�߰��qF���8���6��}c]?�<n"9�x!G{S͛�N�_iӪyͻ�X����M��v,�A��{圝�MC�����Y{Mѫ���{�~�6���x�����%��?Ƨ����w�}~���!�	��Y�]�a)��Y>4�q��ޠl��#����MX��\�">Q�~�Y�=7{c��8�����>m�Ӻ^6��ӏ?�O�/�n�	7��,�>bۼǡ�m�2Y�����
r����p�I �Z^r�(a(s��*��%hg�]7u4�;��39�Ю��~ㆧGX�ƜE{��ˮ�{pٮ;���v �Xn�PV
Z�������'ͱ�~������/���m�u�|�Olj0oN�gi/}��,e.�X�0�4)�����˹z���K���]�y�L���c�p׼���}�=C�%��)þ��:�8�����	��~<k��!ߔ�ǩ���M�O �^N���̥���*�'i���#��c��|�m�w�ޘ�f����`����O1�+~n��;�7��,�_'�������?���r��'�+ �@���`����̥����mc�`�]S˛ȻC�ܷ��~����d粏�j��1gʦv�c��F�:�5���������{㒱��e��a�V���.:���	DY�k���0�y����P��M�ߤ`������{��y�zE����fྋO�h�8륽V���c��v������!�ѴoOA�&D�b�Q7��� �b=?����ꩦ� 艛*��L�,���-e�Z�7^[Z�]<�(HK�9�������f�r]�`��n�6M���v������8k�(-/N|ͷM�\����y]Rb)��/�56�w��Z?��L��6����k�����߽�Q�u�n��.O�\��f��=�q_������fR�{5�{SǏ{�S�������|w�X�4�{���	C�K-
C���6�A�Y��������]w�f�������C�0G�v�~�{����]�f�+�l���|�M�6���(��@�������o{���������7�� ������7���{��i�"_���"e-��'��2�Z�R���  �sQ֢��/Z-e.�(  ��DY�:����̥��   0 �(kS?,�:>�?�0�aj�?t|�a(   J �ڤS�/��/����Ч�a��:>�_��w�   �A ʚ�0�&�����!��?Uc%�   ��&`%N	C[�7�V����m��l���m<^f�f���.�j   �����V`��C��~S����o;�i�1U��\?,�B�.���_��(U�~;t��  �c8e���;MJ=e��� �/ˋ#��������{�~���uϯ��y   �@�%�����]R��� 4�yO{z��~)�,�����W�   0�(K�5M������=J����ԧ���x���f�mXE�0�MS�j   & e��	C��xӟ:Q��^?��>�T���{[�*����^��E   �@��9%m�Qv����d>�'����P����P�   ��$}���:��Κ6|6�{�)���0��Z  �I�A�}�����77�jgTVm�S���x�ۦM���u}�6�6��DU���Z�   0�����s7D������9&��7]��1���l��y��N���Bѡk��Z��>��l��  C �����XouL���rٱS0Zw�����U#k�E   ��@�9+mU�� �k��Y���/}gsEǮ�5�"   ̂@��;mU�� j�prm��T5��Z  ��p�y�h�04�cw��2�lo��>��s��|Ӆ�k�E   ��(s3eڪc�A�fh�!�b��K�E   ��(s2�0�U�2��9����P�������Z  �Y�2s
C[u,+���;��V1�kw.�  `������V���|#�%��U��FFK�E   �5�(S�sڪc�A��꾄P�����}�   �'eJKC[u�3�ZBښs(Z���й�"   ,�@��,)m�1� jIahk��h�	C�Z�   �Q���0�U�<��%���9��U,/�[-  ��Dے��V�QKC[sE�Xn:�Z  ���2�5���:�	�����E�X~:u-  �"	D˚��V�Qk
C[S��U�'��  `������
-y�XW�����5��S���Ւj1���.
  ��D����<�KC[U��=k=����\�Z`�   �ќ2��.b�ahR�0�,��F{�|e����b   P3DR�S���୤0t����;Yk-:u  �b�!ʐ��В�Ф�~f���F�;S��2�Ю�x��  �Q�Te<fMah���Bђ��V�h��R���Z�)�qO���,   J��y���xL
�R��[iT�=�K�jo��0t߱��yC�]?,/<�mE  (�@����8��[~����[E�`�??,�2�kC[]C���������04�<,���t]   ��S�����S�wU@;����ya���z��0���u=u�  ���2�4���ǤSx�
i�:����������9J	C[9?@lu_   ��@�!�g<溰6���P��0��g(ZZM�|<��  ���2��:NEKC[}��%�����F�  ��	DB��]�mS�q��0��SBђ��P?    eg������S����!�ڗB����]i7   (�@�!�.��7���y�.� תzX~9�y���n�s�  @��!gڶж�yX����C(�T��#��$�E7�  ��	DBN Zb U��ah��P�����V���YF���   X;�(C�9e�*�M�x3�Pj(�j�uO�Ub(�2�1;�   k'e(��=�T��u���JE��/m��^d<�F�  ��	D�u�c.h�:��Џ˫�]J(ZE�0�{X�g>��P4����?��   @ �Pr��7km����n���a���{�=��[��a����>�<,W=m�   �x����k�r���!) �W��i}�����^��{X��Om������=,]�6�c�!
  @�eH���K�W�����0�}��g�Vqz |e�������   (���&�f�&k�)�>��a�*ʛ)��:�8S��:�
  @1�ehU<L9�>S��~���5K�)ZE�pi3E���?�0  ���!���r-q�h��}�����g���%����)$^�ͤ   ��������0YR(�e�N	٪Xo(:ֺ�9=f�6�8�   ��y�R�c��k)���1Nھ�O��b��w����
C  (�@�1U��P�������\S(Z���^���x�(   8�@��U��P�������^C(Z�t� XK(*  ���L��e��uL���%��UL=ԥ���P   8�@��T��P������ϲ�P����j���0   �$eJU,+�c>a��gZR(Z�|����BQa(   �@ �ԪXF(Z�����϶�P����������P   8�@�9�bޡh�C�?�C�*�����
C  �Q梊y��u�?���sE��ښk(*  ��D��*��ֱ�0t�3�)�b9ahkn��0   z$en��G(Z������>�P��兡�����P   �@�9�b�P��冡��0e(Z�r���ԡ�0    e��?MT�C[i]�E�X~ښ*�  �@��Y�Cы#�k��Z��V�CѴNgG��e�'m��<���C
   ��2wUtE��0i����]�c��� ��n�hj�]�.���i�W�g	ah�P�/�m�h[�a(   ���{��ԑ?{��«�x�v͒l�qFh�7��{��5�@U�m�f���mx���)�;k�/-O;����}]Oe�V-�5�x��ԋ#����"   LF ʒ��=���*���}[j�:6U�   0N�gI��v�|��@������-=M��>�  `F�,M㇢k��&]Cښ*�  ���,Qㅢk�������aMah�Eߎ�~B
   '��T���S���7k�n��r�c�~~��������J�<���]y-  �h�,�U<�D�z~���Լ�n�m�k����?\~׼v]@-^>,����6PN��M   N�.��6C��'�F
������)�=��Y���:����Z��6<�.������Z  ��DY�M<ΦKKN8������YxT�cȜ�1'}�׆;��ߜ��3�   � e��Ϳ)�:k�;]�1ͺۅ�.ǦYΚv���n���Z���&  ��	D   �b��    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(    P�(  ��ǎ    ��� ��    ��    6�(    �!D   �!
    lQ    `C�    B    ��    ��    6�(    �!D   �!
    lQ    `C�    B    ��    �F 5Jp9c;L?    IEND�B`�                                                                                               master/index.html                                                                                   000644  000767  000024  00000203052 12176751667 015030  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         <!DOCTYPE HTML>
<html>
  <head>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <!--  The above meta tag must immediately follow the head element (no empty newlines) for IE7 to render in 'standards mode  -->
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1" />
    
    <!-- The title at the top of the page. -->
    <title>Trialist Setup</title>
    
    <!-- JSON because IE<8 -->
    <script src="https://ajax.cdnjs.com/ajax/libs/json2/20110223/json2.min.js">
    </script>
    
    <!-- Le HTML5 shim, for IE6-8 support of HTML5 elements -->
    <!--[if lt IE 9]>
        <script src="https://html5shim.googlecode.com/svn/trunk/html5.js"></script>
    <![endif]-->
    
    <!-- jQuery stuff -->
    <script src="js/jquery-1.9.0.min.js"></script>
    <script src="js/jquery.cookie.js"></script>
    
    <!-- Less stuff -->
    <script src="js/less-1.3.3.min.js"></script>
    
    <!-- Bootstrap stuff -->
    <link href="https://fonts.googleapis.com/css?family=Limelight|Flamenco|Federo|Yesteryear|Josefin Sans|Spinnaker|Sansita One|Handlee|Droid Sans|Oswald:400,300,700" media="screen" rel="stylesheet" type="text/css" />
    <link href="bootstrap/css/bootstrap.min.css" media="screen" rel="stylesheet" type="text/css" />
    <link href="bootstrap/css/bootstrap-responsive.min.css" media="screen" rel="stylesheet" type="text/css" />
    <link href="bootstrap/less/dropdowns.less" rel="stylesheet/less" />
    <link href="bootstrap/less/sprites.less" rel="stylesheet/less" />
    <script src="bootstrap/js/bootstrap.min.js"></script>
    
    <!-- DatePicker stuff -->
    <link href="datepicker/css/datepicker.css" rel="stylesheet" type="text/css" />
    <link href="datepicker/build/build.less" rel="stylesheet/less" />
    <link href="datepicker/build/build_standalone.less" rel="stylesheet/less" />
    <link href="datepicker/less/datepicker.less" rel="stylesheet/less" />
    <script src="datepicker/js/bootstrap-datepicker.js"></script>
    
    <!-- CSS Stuff -->
    <link href="css/UserSetup.css" media="screen" rel="stylesheet" type="text/css" />
        
    <!-- Wicked Good XPath -->
    <script src="js/wgxpath.install.js"></script>
  </head>
  
  <body>
    <!-- 
        This JavaScript should be run before any of the page is rendered. 
     -->
    <script type="text/javascript">
        /**
         * Retrieves a cookie's value.
         */
        function getCookie(name)
        {
            var i,x,y,ARRcookies=document.cookie.split(";");
            for(i = 0; i < ARRcookies.length; i++)
            {
                x=ARRcookies[i].substr(0,ARRcookies[i].indexOf("="));
                y=ARRcookies[i].substr(ARRcookies[i].indexOf("=")+1);
                x=x.replace(/^\s+|\s+$/g,"");
                if (x == name)
                {
                    return unescape(y);
                }
            }
        }
        
        /**
         * Redirects the user to the login page.
         */
        function redirectToLogin() {
            <!--
            $.cookie('trialist_redirect', '/trialist', {path: '/'});
            document.location = "/";
            //-->
        }
        
        /**
         * Retrieves the authentication token cookie or redirects the user to
         * the login page.
         *
         * @return The user's authentication token or null if no authentication
         *         token exists.
         */
        function getAuthToken() {
            // Attempt to retrieve the authentication token.
            var authToken = getCookie("auth_token");
            
            // If the token is missing, redirect the user back to the login
            // page.
            if(
                (authToken === null) ||
                (typeof authToken === "undefined") ||
                (authToken === ""))
            {
                // Set the authentication token to null;
                authToken = null;
                
                // Send the user to the login page.
                redirectToLogin();
            }
                        
            // Return whatever we have as the authentication token.
            return authToken;
        }
        
        // Check for the authentication token before loading the page. If it
        // doesn't exist, we will be redirected to the homepage before any of
        // the UI elements are rendered.
        getAuthToken();
        
        // Install the Wicked Good XPath library.
        wgxpath.install();
    </script>
    <script type="text/javascript">
        // Expire the redirect cookie once a successful login occurs.
        // This cannot happen in the above script tag because the browser 
        // can continue executing that JavaScript after the redirect to /
        // has occurred.
        $.cookie('trialist_redirect', '/trialist', { path: '/', expires: new Date() });
    </script>
	<div class="container">
		<div style="box-shadow: 1px 0px 4px 0 #E0E0E0;">
			<div style="box-shadow: -1px 0px 4px 0 #E0E0E0;">

				<div id="alertModal" class="modal hide fade">
					<div class="modal-header">
						<button type="button" class="close" data-dismiss="modal"
							aria-hidden="true">&times;</button>
						<h3 id="alertHeader"></h3>
					</div>
					<div class="modal-body">
						<div class="alertInfo"></div>
					</div>
				</div>
				
				<div class="container-fluid">
				    <div class="row-fluid">
				      <div class="span5"><h1>Trialist Participant Setup</h1></div>
				      <div class="span2"></div>
						<div class="span5">
							<div class="row-fluid">
								<div class="btn-toolbar pull-right">
									<div class="btn-group">
										<button class="btn btn-inverse"
											style="background: #738077; color: white;" id="help">Information
											About Prescribing Opioids</button>
									</div>
									<div class="btn-group">
										<button class="btn btn-inverse" id="logout">Logout</button>
									</div>
								</div>
							</div>
							<div class="row-fluid">
							    <div class="pull-right">
							        <small><i class="icon-question-sign" style="padding-left: 5px;"></i><a href="mailto:trialist-setup-help@ohmage.org">trialist-setup-help@ohmage.org</a></small>
							    </div>
							</div>
						</div>
					</div>
				</div>

				<div id="helpArea" class="well">
					<h3>General Principles when prescribing opioids for chronic
						pain</h3>
					<ul>
						<li>Use the lowest possible effective dose when opioid
							analgesics are considered for the management of pain.</li>
						<li>When switching opioids, find an equivalent dose based on
							the patient's current dosage and consider a reduction for
							incomplete cross tolerance (see hyperlink below for opioid
							equianalgesic dosages).</li>
						<li>To assess for opioid misuse or addiction, consider using
							targeted history or validated screening tools (see hyperlink
							below for paper questionnaires).</li>
						<li>Prescribers are advised to access a prescription
							monitoring program (PMP) to ensure that patients are not involved
							in doctor shopping (see hyperlink below for California’s
							Prescription Drug Monitoring Program (CURES).</li>
						<li>When feasible, avoid simultaneous prescribing of opioid
							analgesics and benzodiazepines. This combination raises the risk
							of inadvertent overdose.</li>
						<li>Because of its added depressant effects, tramadol should
							be prescribed with caution for those patients whose medical
							condition requires the concomitant administration of sedatives,
							tranquilizers, muscle relaxants, antidepressants, or other CNS
							depressant drugs.</li>
						<li>Provide information about opioid analgesics to patients
							receiving a prescription, such as the risks of overdose and
							dependence/ addiction, as well as safe storage and proper
							disposal of unused medications (see hyperlink below for patient
							instructions).</li>
					</ul>
					
					<h3>Online references for safe opioid prescribing</h3>
					<table class="table table-bordered"
						style="table-layout: fixed; width: 100%; word-wrap: break-word;">
						<tr>
							<th colspan="2">Opioid safety and risk management</th>
						</tr>
						<tr>
							<td>Balancing Pain Management and Prescription Opioid Abuse</td>
							<td><a
								href="http://www.cdc.gov/primarycare/materials/opoidabuse/index.html">http://www.cdc.gov/primarycare/materials/opoidabuse/index.html</a></td>
						</tr>
						<tr>
							<td>Preventing misuse and adverse events</td>
							<td><a href="http://pain-topics.org/opioid_rx/safety.php">http://pain-topics.org/opioid_rx/safety.php</a></td>
						</tr>
						<tr>
							<th>Opioid drug interactions</th>
							<td><a
								href="https://www.painedu.org/tools/drug_drug_interactions.asp">https://www.painedu.org/tools/drug_drug_interactions.asp</a></td>
						</tr>
						<tr>
							<th>Opioid equianalgesic dosages</th>
							<td><a href="http://www.globalrph.com/narcoticonv.htm">http://www.globalrph.com/narcoticonv.htm</a></td>
						</tr>
						<tr>
							<th>Opioid side effects</th>
							<td><a href="http://www.medscape.org/viewarticle/573016">http://www.medscape.org/viewarticle/573016</a></td>
						</tr>
						<tr>
							<th colspan="2">Paper questionnaires for screening before
								starting opioids</th>
						</tr>
						<tr>
							<td>Screener and Opioid Assessment for Patients with Pain
								(SOAPP)</td>
							<td><a href="http://www.painedu.org/soapp.asp">http://www.painedu.org/soapp.asp</a></td>
						</tr>
						<tr>
							<td>Opioid Risk Tool (ORT)</td>
							<td><a
								href="http://www.partnersagainstpain.com/printouts/Opioid_Risk_Tool.pdf">http://www.partnersagainstpain.com/printouts/Opioid_Risk_Tool.pdf</a>
						</tr>
						<tr>
							<th colspan="2">Paper questionnaires for monitoring during
								long-term opioid therapy</th>
						</tr>
						<tr>
							<td>Pain Assessment and Documentation Tool (PADT)</td>
							<td><a
								href="http://www.ucdenver.edu/academics/colleges/PublicHealth/research/centers/maperc/online/Documents/Pain Assessment Documentation Tool %28PADT%29.pdf">http://www.ucdenver.edu/academics/colleges/PublicHealth/research/centers/maperc/online/Documents/Pain
									Assessment Documentation Tool %28PADT%29.pdf</a></td>
						</tr>
						<tr>
							<td>Current Opioid Misuse Measure (COMM)</td>
							<td><a href="http://www.painedu.org/soapp.asp">http://www.painedu.org/soapp.asp</a></td>
						</tr>
						<tr>
							<th colspan="2">Patient instructions</th>
						</tr>
						<tr>
							<td>A Guide to Safe Use of Pain Medicine</td>
							<td><a
								href="http://www.fda.gov/downloads/ForConsumers/ConsumerUpdates/ucm095742.pdf">http://www.fda.gov/downloads/ForConsumers/ConsumerUpdates/ucm095742.pdf</a></td>
						</tr>
						<tr>
							<td>Disposal of medications</td>
							<td><a
								href="http://www.fda.gov/drugs/resourcesforyou/consumers/buyingusingmedicinesafely/ensuringsafeuseofmedicine/safedisposalofmedicines/ucm186187.htm">http://www.fda.gov/drugs/resourcesforyou/consumers/buyingusingmedicinesafely/ensuringsafeuseofmedicine/safedisposalofmedicines/ucm186187.htm</a></td>
						</tr>
						<tr>
							<th>Prescription Drug Monitoring Program</th>
							<td><a href="https://pmp.doj.ca.gov/pdmp/index.do">https://pmp.doj.ca.gov/pdmp/index.do</a></td>
						</tr>
						<tr>
							<th colspan="2">Urine drug testing</th>
						</tr>
						<tr>
							<td>Urine Drug Testing: Current Recommendations and Best
								Practices See Table 5 for immunoassay cross-reactions (false
								positives)</td>
							<td><a
								href="http://www.painphysicianjournal.com/2012/july/2012;15;ES119-ES133.pdf">http://www.painphysicianjournal.com/2012/july/2012;15;ES119-ES133.pdf</a></td>
						</tr>
					</table>
				</div>

				<div class="light-grey row-fluid" style="margin-bottom: 0px;">
					<form class="form-horizontal" action="#">
						<h4 class="heading" style="padding-left: 10px; color: white;">
							Patient Information</h4>
					</form>
			    </div>
				<div class="well" style="margin: 0px;">
					<form class="form-horizontal" action="#">
						<div class="control-group">
							<label class="control-label">Patient's Login:</label>
							<div class="controls">
								<select id="selectUser">
								</select> 
							</div>
						</div>
					</form>
				</div>

				<div class="light-grey row-fluid" style="margin-bottom: 0px;">
					<form class="form-horizontal" action="#">
						<h4 class="heading heading-shaddow" style="padding-left: 10px; color: white;">
						  Study Protocol
						</h4>
					</form>
			    </div>
			    
			    
				<div class="well" style="margin: 0px;">
                    
					<form class="form-horizontal" action="#">
						<div class="control-group">
							<label class="control-label"><span class="dotted_underline" title="A treatment or treatments to be used in the personalized trial.">Regimen A:</span></label>
							<div id="regimenA" class="controls"></div>
						</div>
					</form>
					<form class="form-horizontal" action="#">
						<div class="control-group">
							<label class="control-label"><span class="dotted_underline" title="Treatment or treatments to be compared to the Regimen A selections.">Regimen B:</span></label>
							<div id="regimenB" class="controls"></div>
						</div>
					</form>
					
					<hr/>
					   
					<form class="form-horizontal" action="#">
                        <div class="control-group">
                        <div class="controls">
                            <span>Do you intend to prescribe or continue any pain treatments in addition to the ones selected above?</span>
                            <div>
	                            <label class="radio inline">
	                            <input type="radio" name="extraTreatmentRadios" id="extraTreatmentRadios1" value="yes">Yes
	                            </label>
	                            <label class="radio inline">
	                            <input type="radio" name="extraTreatmentRadios" id="extraTreatmentRadios2" value="no">No
	                            </label>
	                       </div>
	                       <div class="row" style="margin: 10px;"><span class="extraTreatmentNotification"></span></div>
                            </div>
                        </div>
                    </form>
					
					<hr/>
					
					<form class="form-horizontal" action="#">
						<div class="control-group">
							<label class="control-label"><span class="dotted_underline" title="The day the personalized trial starts.">Study Start Date:</span></label>
							<div class="controls">
								<div class="input-append date datepicker" id="startDatePicker"
									data-date-format="yyyy-mm-dd">
									<input id="startDate" size="16" type="text" readonly><span
										class="add-on"><i class="icon-th"></i></span>
								</div>
							</div>
						</div>
					</form>
					
					<form class="form-horizontal" action="#">
						<div class="control-group">
							<label class="control-label"><span class="dotted_underline" title="The number of weeks to be spent on each Regimen. At the end of the period, a switch to the next Regimen occurs.">Period Length:</span></label>
							<div class="controls">
								<select id="regimenDuration">
								</select>
							</div>
						</div>
					</form>
					<form class="form-horizontal" action="#">
						<div class="control-group">
							<label class="control-label"><span class="dotted_underline" title="The number of times for a full cycle to complete (one cycle is Regimen A followed by Regimen B, or Regimen B followed by Regimen A).">Number of Cycles:</span></label>
							<div class="controls">
								<select id="regimenCycles">
								</select>
								<span class="regimenCyclesEndDate" style="margin-left: 10px;"></span>
							</div>
						</div>
					</form>
				</div>


                <div class="light-grey row-fluid" style="margin-bottom: 0px;">
                    <form class="form-horizontal" action="#">
                        <h4 class="heading" style="padding-left: 10px; color: white;">
                            Mandatory Outcomes
                        </h4>
                    </form>
                </div>
                
                <div class="well" style="margin: 0px;">
                
                    <span>These are outcomes that will be tracked by every participant in the study.</span>
                    <div class="container" style="padding: 20px 20px 0px 20px;">
                    <ul>
                      <li>A daily questionnaire about pain intensity and interferences.</li>
                      <li>A daily question about the previous night's sleep.</li>
                      <li>A daily question about how tired-out you felt in the past day.</li>
                      <li>A daily question about how drowsy you felt for the current day.</li>
                      <li>A daily question about problems moving your bowels.</li>
                    </ul>
                   </div>
                
                <hr />
                
                <div>
	                <form class="form-horizontal" action="#">
	                        <span class="help-block" style="color: #000000;">
	                       Pain medicines can sometimes affect our thinking or concentration. Please select one of the 
	                       following questions about your thinking or concentration to track every day.
	                        </span>
	
	                        <div style="padding: 20px;">
	                            <select style="width: 80%" id="cognitiveFunction">
	                            </select>
	                        </div>
	                </form>
                </div>
              

                </div>


				<div class="light-grey row-fluid" style="margin-bottom: 0px;">
					<form class="form-horizontal" action="#">
						<h4 class="heading" style="padding-left: 10px; color: white;">
							Optional Neuropathic Pain Outcome
						</h4>
					</form>
				</div>
				
				
				<div class="well" style="padding: 10px;">
                   					
		        <form class="form-horizontal" action="#">

                   <div style="margin-left: 20px;">
                       <div><span>Does the patient have pain accompanied by burning, pins and needles, 
                            itching, or a sensitive or unpleasant sensation on the skin?</span></div>
                       <div>
                           <label class="radio inline">
                           <input type="radio" name="neuropathicRadios" id="neuropathicRadios1" value="yes">Yes
                           </label>
                           <label class="radio inline">
                           <input type="radio" name="neuropathicRadios" id="neuropathicRadios2" value="no">No
                           </label>
                      </div>

                 </div>
               </form>
                 
					
				</div>

				<div class="row-fluid">
					<div class="span4"></div>
					<div class="span4" style="padding: 20px;">
						<button id="create" class="btn btn-large"
							type="button" style="background: #B7E3E4;" onclick="create()">Create and Assign
							Protocol</button>
					</div>
				</div>
                
				<div class="row-fluid"
					style="background: #808080; padding-bottom: 3px; margin: 0px;">
					<div class="pull-right">
					    <img src="images/omh_logo-white.png" style="height: 91px; width: 225px;" alt="Open mHealth Logo" />
					</div>
				</div>

			</div>
		</div>
	</div>
	<!--
        The page ends with all of the JavaScript which will speed up how
        quickly the page is rendered and shouldn't even be run until after all
        of the UI elements have been setup.
     -->
    <script type="text/javascript">
    
					// Extend the Array prototype to contain an indexOf function.
					if (!Array.prototype.indexOf) {
						Array.prototype.indexOf = function(needle) {
							for ( var i = 0; i < this.length; i++) {
								if (this[i] === needle) {
									return i;
								}
							}
							return -1;
						};
					}
					// Extend the Array prototype to contain an equivalency function.
					if (!Array.prototype.equivalent) {
						Array.prototype.equivalent = function(other) {
							if (typeof other === "undefined") {
								return false;
							}
							if (other === null) {
								return false;
							}
							if (this.length !== other.length) {
								return false;
							}
							for ( var i = 0; i < this.length; i++) {
								if (other.indexOf(this[i]) === -1) {
									return false;
								}
							}
							return true;
						};
					}
					
					 $(document).ready(function () {
		                $("span").tooltip({
		                  'selector': '',
		                  'placement': 'top',
		                  'trigger' : 'hover'
		                });
			        });
					
					// The list of radio buttons refrencing the regimen.
					var REGIMEN_RADIOS = [];

					// The maximum random value allowed, which should be set when reading
					// the campaign's contents.
					var MAX_RANDOM;

					// The list of required survey IDs.
					var REQUIRED_PROMPT_IDS = [ 'averagePainIntensity',
							'enjoymentOfLife', 'generalActivity', 'fatiguePrompt', 
							'drowsinessPrompt', 'constipationPrompt', 'sleepDisturbancePrompt', 'notesAboutToday'];
					
					var PROMPT_IDS_COGNITIVE_FUNCTION = [
							'cognitiveFunctionSlowThinkingPrompt',
							'cognitiveFunctionFoggyThinkingPrompt',
							'cognitiveFunctionTroubleConcentratingPrompt',
							'cognitiveFunctionWorkingHarderPrompt' ];
					
					var PROMPT_IDS_NEUROPATHIC_PAIN = ['experiencePain',
					        'painSharpness', 'painHotness', 'painSensitivity'];
					
					var SURVEY_ID_ADHERENCE = 'adherence';
					var PROMPT_ID_ADHERENCE = 'adherencePrompt';
					
					// The list of optional survey ID elements, which should be added when
					// reading the campaign's contents.
					var OPTIONAL_SURVEY_ID_ELEMENTS = [];

					// Create a list of allowed regimen combinations. Each index in the
					// list corresponds to the key for that choice. Each value is an array
					// of allowed keys.
					// 0 - No treatment
                    // 1 - Tylenol
                    // 2 - NSAID
                    // 3 - Codeine
                    // 4 - Tramadol
                    // 5 - Hydrocodone
                    // 6 - Oxycodone
                    // 7 - CAM
					var ALLOWED_REGIMEN_COMBINATIONS = [
							[ ],
							[ "2", "4", "7" ],
							[ "1", "2", "3", "4", "5", "6", "7" ],
							[ "2", "7" ],
							[ "1", "2", "7" ],
							[ "2", "7" ],
							[ "2", "7" ],
							[ "1", "2", "3", "4", "5", "6" ] ];
				
					// The Trialist class' unique identifier.
					var CLASS_ID = "urn:class:Trialist";

					// The Trialist campaign's unique identifier.
					var CAMPAIGN_ID = "urn:campaign:trialist";
					// The ID of the survey that contains all of the setup prompts.
					var SETUP_SURVEY_ID = "setup";
					// The ID of the survey that contains the prompts in the main user survey
                    var MAIN_SURVEY_ID = "main";
					
					// The prompt IDs from the setup survey.
					var PROMPT_ID_REGIMEN_A = "regimenA";
					var PROMPT_ID_REGIMEN_B = "regimenB";
					var PROMPT_ID_START_DATE = "startDate";
					var PROMPT_ID_REGIMEN_DURATION = "regimenDuration";
					var PROMPT_ID_REGIMEN_CYCLES = "numberComparisonCycles";
					var PROMPT_ID_RANDOM = "random";
					var PROMPT_ID_RANDOM_AS_TEXT = "randomAsText";
					var PROMPT_ID_COGNITIVE_FUNCTION = "cognitiveFunction";
					var PROMPT_ID_NEUROPATHIC_PAIN_TAKEN = "neuropathicPainTaken";
					var PROMPT_ID_USER_SELECTED = "userSelected";
					var PROMPT_ID_EXTRA_TREATMENT = "extraTreatment";
					
					// The list of checkboxes for each regimen.
					var CHECKBOX_REGIMEN_A = [];
					var CHECKBOX_REGIMEN_B = [];
					
					// Global array for the user list
                    var usernames = new Array();
					
					// Variable to hold the end date value
					// because it is calculated in an anonymous
					// function
					var endDateValue;
					var endDateAsDate;
					var startDateAsDate;

					// Connect the help button with its functionality.
					$("#help").click(function() {
						var helpArea = $("#helpArea");
						if (helpVisible) {
							helpArea.fadeOut(200);
							helpVisible = false;
						} else {
							helpArea.fadeIn(200);
							helpVisible = true;
						}
					});
					$("#helpArea").fadeOut(0);
					var helpVisible = false;

					// Connect the logout button with its functionality.
					$("#logout").click(function() {
						$.post("/app/user/logout", {
							"client" : "Trialist"
						}, function() {
							window.location = "/";
						});
					});

					// Setup the date picker.
					$('#startDatePicker').datepicker();
					$('#startDatePicker').change(updateCycles);

					$('#regimenDuration').change(updateCycles);
					$('#regimenCycles').change(updateCycles);
					$('#extraTreatmentRadios1').change(showExtraTreatmentText);
					$('#extraTreatmentRadios2').change(showExtraTreatmentText);

					// Populate the page's UI elements.
					try {
						getUsers();
						filterUsers();
						getCampaignDefinition();
					} catch (e) {
						alertUser("Error", "An unknown error occurred: " + e);
					}
				    
					
					function setDateValues(start, end) {
						endDateAsDate = new Date(end);
						startDateAsDate = new Date(start);
						endDateValue = end.toString();
					}
					
					/**
					 * Converts an XML string into a DOM object.
					 */
					function convertXmlStringToDomObject(xml) {
						var xmlDoc = null;
					    
						if(isIE()) {
							xmlDoc = new ActiveXObject("Microsoft.XMLDOM");
                            xmlDoc.async = false;
                            xmlDoc.loadXML(xml);
						} 
						else {
							var parser = new DOMParser();
                            xmlDoc = parser.parseFromString(xml, "text/xml");
						}

						return xmlDoc;
					}

					/**
					 * Runs the document.evaluate() method based on the current browser.
					 */
					function evaluateXpath(root, node, expression) {
						
						var result;
						
						if(isIE()) {
							result = node.selectNodes(expression);
						}
						else {
							result = root.evaluate(expression, node, null,
                                    XPathResult.ANY_TYPE, null);
						}
						
						return result;
					}

					/**
					 * Returns the next element from a list of elements.
					 */
					function nextElement(node) {
						if(isIE()) {
							return node.nextNode();
						}
						else {
							return node.iterateNext();
						}
					}

					/**
					 * Returns the text for the node.
					 */
					function elementValue(node) {
						 if(isIE()) {
							 return node.text; 
						 } 
						 else {
							 return node.textContent; 
						 }
					}

					/**
					 * Because IE8 won't even bother with ISO 8601. Microsoft, what is your
					 * problem!?
					 */
					function parseISO8601(dateStringInRange) {
						var isoExp = /^\s*(\d{4})-(\d\d)-(\d\d)\s*$/, date = new Date(NaN), month, parts = isoExp.exec(dateStringInRange);

						if (parts) {
							month = +parts[2];
							date.setFullYear(parts[1], month - 1, parts[3]);
							if (month != date.getMonth() + 1) {
								date.setTime(NaN);
							}
						}
						return date;
					}
				    
					/**
					 * Check for IE :(
					 */
					function isIE() {
						return (window.DOMParser === undefined) 
						  || (navigator.userAgent.indexOf("MSIE 9") != -1)
						  || (navigator.userAgent.indexOf("MSIE 10") != -1);
					}
					
					
					/**
					 * randomUUID.js - Version 1.0
					 *
					 * Copyright 2008, Robert Kieffer
					 *
					 * This software is made available under the terms of the Open Software License
					 * v3.0 (available here: http://www.opensource.org/licenses/osl-3.0.php )
					 *
					 * The latest version of this file can be found at:
					 * http://www.broofa.com/Tools/randomUUID.js
					 *
					 * For more information, or to comment on this, please go to:
					 * http://www.broofa.com/blog/?p=151
					 *
					 * Create and return a "version 4" RFC-4122 UUID string.
					 */
					function randomUUID() {
						var s = [], itoh = '0123456789ABCDEF';

						// Make array of random hex digits. The UUID only has 32 digits in it, but we
						// allocate an extra items to make room for the '-'s we'll be inserting.
						for ( var i = 0; i < 36; i++)
							s[i] = Math.floor(Math.random() * 0x10);

						// Conform to RFC-4122, section 4.4
						s[14] = 4; // Set 4 high bits of time_high field to version
						s[19] = (s[19] & 0x3) | 0x8; // Specify 2 high bits of clock sequence

						// Convert to hex chars
						for ( var i = 0; i < 36; i++)
							s[i] = itoh.charAt(s[i]);

						// Insert '-'s
						s[8] = s[13] = s[18] = s[23] = '-';

						return s.join('');
					}

					/**
					 * Uses some UI element to alert the user that something has happened.
					 */
					function alertUser(header, info, isHtml) {
						$("#alertHeader").text(header);
						if(isHtml !== undefined) {
						     $("div.alertInfo").html('<p>' + info + '</p>');
						} else {
							$("div.alertInfo").html(info);
						}
						$("#alertModal").modal('show');
					}

					/**
					 * Updates the number of cycles by adding dates to the values.
					 */
					function updateCycles() {
						// Get the start date.
						var startDateValue = $('#startDate').val();
						// If it hasn't been selected, bail out.
						if ((startDateValue === undefined) || (startDateValue === null) || (startDateValue === '')) {
							return;
						}
						var startDate = parseISO8601(startDateValue);
						
						// Get index of the duration select
						// .text() will return the contents of the select
						var durationIndex = $("#regimenDuration option:selected").val(); 
						// If it hasn't been selected, bail out.
						if ((durationIndex === undefined) || (durationIndex === null) || (durationIndex === '')) {
							return;
						}
						
						// If nothing was selected, we will want to reset it after we
						// update the options.
						var regimenCyclesIndex = $("#regimenCycles option:selected").val();
						
						var notSelected = (regimenCyclesIndex === undefined);
												
						// Reset the choice if it was nothing.
						if (notSelected) {
							$("#regimenCycles").prop("selectedIndex", -1);
							$("span.regimenCyclesEndDate").text("");
						}
						else {
							
							// NOTE: if the XML values have changed for the duration
							// or cycles, this code will need to be updated.
							// FIXME using the <value> attribute for the property in the XML
							
							var duration = -1;
							var regimenCycles = -1;
							
							// This is the duration for each 'leg' of an AB pair
							// E.g., 14 days on A and 14 days on B
							
							if(durationIndex == 0) {
								duration = 2; // days
							} else if(durationIndex == 1) {
								duration = 7;
							} else if(durationIndex == 2) {
								duration = 14;
							}
							
						    if(regimenCyclesIndex == 0) {
                                regimenCycles = 2; 
                            } else if(regimenCyclesIndex == 1) {
                            	regimenCycles = 3;
                            } else if(regimenCyclesIndex == 2) {
                            	regimenCycles = 4;
                            }
							
						    var millis = duration * 2 * regimenCycles * 24 * 60 * 60 * 1000;
						    
						    var endDateValue = new Date();
						    endDateValue.setTime(startDate.getTime() + millis + (startDate.getTimezoneOffset() * 60 * 1000));
						    
						    $("span.regimenCyclesEndDate").html("<i class=\"icon-arrow-right\"></i>&nbsp;Your study will end on " + endDateValue.toDateString() + ".");
						    
						    setDateValues(startDate, endDateValue);
						}
					}
					
					function showExtraTreatmentText() {
						if($("#extraTreatmentRadios1").is(":checked")) {
							$("span.extraTreatmentNotification").html("<i class=\"icon-arrow-right\"></i>&nbsp;Please communicate this information to the PREEMPT Study Research Assistant (RA). If the RA is not <strong>immediately</strong> available, UCDMC clinicians should page study investigator Richard Kravitz, MD, 916.816.6431 (UCDMC).  VA providers should call Barth Wilsey, MD, 916.402.2270.  They will speak with you and personally record the information.");	
						} 
						else {
							$("span.extraTreatmentNotification").html("");
						}
					}

					/**
					 * Retrieves the list of users visible to this user via their classes.
					 *
					 * @return A JSON array of the users.
					 */
					function getUsers() {
						// Build the failure function.
						var failure = function() {
							alertUser("Error Retrieving Users",
									"There was an error retrieving the list of users.");
						}
						// Build the success function.
						var success = function(data) {
							try {
								// Check that we indicated success.
								if (data['result'] === "success") {
									
									// Iterate over all of the classes.
									for ( var currClassId in data['data']) {
										// We are only concerned with the Trialist class.
										if (currClassId !== CLASS_ID) {
											continue;
										}

										// Get the current class object.
										var classObject = data['data'][currClassId];
										
										// Iterate over all of the users in the current class.
										for ( var user in classObject['users']) {
											
											if(classObject['users'][user] === 'restricted') {
												usernames.push(user);
											}
										}
										
										usernames.sort();
									}
								} else {
									var failureObject = data['errors'][0];
									if (failureObject['code'] === "0200") {
										redirectToLogin();
									} else {
										throw "Error reading the data: "
												+ failureObject['text'];
									}
								}
							} catch (e) {
								alertUser("Error Loading Users",
										"There was an error loading the list of users: "
												+ e);
							}
						}

						// Build the parameters and make the class read request.
						var authToken = getAuthToken();
						if (authToken != null) {
							var parameters = {
								"client" : "TrialistWeb",
								"auth_token" : authToken,
								"class_urn_list" : CLASS_ID
							};
							$.post("/app/class/read", parameters, success)
									.fail(failure);
						}
					}
					
					
					/**
					 * Filter out users based on previously submitted survey responses.
					 */
                    function filterUsers() {
                        
                        // Build the failure function.
                        var failure = function() {
                            alertUser("Server Communication Error",
                                    "There was an error while communicating with the server.");
                        }
                        // Build the success function.
                        var success = function(data) {
	                        try {
	                            // Check that we indicated success.
	                            if (data['result'] === "success") {
	                                    
	                                    // Get the participants so users cannot be added to
	                                    // to the study twice.
	                                    var dataArray = data['data']; // an array of anonymous objects
	                                    var participants = new Array(); 
	                                    
	                                    for(var i = 0; i < dataArray.length; i++) {
	                                    	participants.push(dataArray[i]['responses']['userSelected']['prompt_response']);
	                                    }
	                                    
	                                    var length = usernames.length;
	                                    
	                                    // Connect to the list of users element in the HTML.
	                                    var userListElement = $("#selectUser");
	                                
	                                    for(var i = 0; i < length; i++) {
	                                        
	                                        if(participants.indexOf(usernames[i]) == -1) {
	                                            userListElement
	                                              .append("<option value=\"" + usernames[i] + "\">"
	                                                    + usernames[i]
	                                                    + "</option>");
	                                        }
	                                    }
	                                    
	                                    // Reset the selected index to -1, so that the user must explicitly
	                                    // choose an option.
	                                    userListElement.prop('selectedIndex', -1);
	                                    
	                            } else {
	                               
	                            	var failureObject = data['errors'][0];
	                                if (failureObject['code'] === "0200") {
	                                    redirectToLogin();
	                                } else {
	                                    throw "Error reading the data: "
	                                            + failureObject['text'];
	                                }
	                            }
	                        } catch (e) {
	                            alertUser("Error Populating the Page",
	                                    "There was an error populating the page: "
	                                            + e.toString());
	                        }
                        }

                        // Build the parameters and make the request.
                        var authToken = getAuthToken();
                        if (authToken != null) {
                            var parameters = {
                                "client" : "TrialistWeb",
                                "auth_token" : authToken,
                                "campaign_urn" : CAMPAIGN_ID,
                                "output_format" : "json-rows",
                                "prompt_id_list" : "userSelected",
                                "user_list" : "urn:ohmage:special:all",
                                "column_list" : "urn:ohmage:prompt:response"
                            };
                            $.post("/app/survey_response/read", parameters, success,
                                    "json").fail(failure);
                        }
                    }
					
					/**
					 * Get the campaign definition.
					 */
					function getCampaignDefinition() {
						
						// Build the failure function.
						var failure = function() {
							alertUser("Server Communication Error",
									"There was an error while communicating with the server.");
						}
						// Build the success function.
						var success = function(data) {
							try {
								// Check that we indicated success.
								if (data['result'] === "success") {
									// Iterate over all of the campaigns.
									for ( var currCampaignId in data['data']) {
										// We are only concerned with the Trialist
										// campaign.
										if (currCampaignId !== CAMPAIGN_ID) {
											continue;
										}
											
										// Get a handle for all of the necessary objects.
										var regimenA = $("#regimenA");
										var regimenB = $("#regimenB");
										var regimenDuration = $("#regimenDuration");
										var regimenCycles = $("#regimenCycles");

										var cognitiveFunction = $("#cognitiveFunction");

										// Get the Trialist campaign XML.
										var xml = data['data'][currCampaignId]['xml'];
										var xmlObject = convertXmlStringToDomObject(xml);

										// Get the configuration surveys.
										var setupSurveys = evaluateXpath(
												xmlObject, xmlObject,
												'/campaign/surveys/survey[id="'
														+ SETUP_SURVEY_ID
														+ '"]');

										// Get the single configuration survey.
										var setupSurvey = nextElement(setupSurveys);
										if (setupSurvey === null) {
											throw "The setup survey is missing.";
										}
										
										// Populate the regimen HTML select.
										setupRegimenLists(xmlObject,
												setupSurvey, regimenA, regimenB)

										// Populate the duration.
										createSelectOptionsFromPromptProperties(
												xmlObject, setupSurvey,
												PROMPT_ID_REGIMEN_DURATION,
												regimenDuration);

										// Populate the number of cycles.
										createSelectOptionsFromPromptProperties(
												xmlObject, setupSurvey,
												PROMPT_ID_REGIMEN_CYCLES,
												regimenCycles,
												OPTIONAL_SURVEY_ID_ELEMENTS);

										// Populate the number of cycles.
										MAX_RANDOM = 2; // getNumChoices(xmlObject,setupSurvey, PROMPT_ID_RANDOM);

										// Create a choice for the cognitive functioning outcome.
										populateSelectFromSingleItemSurveys(xmlObject,
												PROMPT_IDS_COGNITIVE_FUNCTION,
												cognitiveFunction);
									}
								} else {
									var failureObject = data['errors'][0];
									if (failureObject['code'] === "0200") {
										redirectToLogin();
									} else {
										throw "Error reading the data: "
												+ failureObject['text'];
									}
								}
							} catch (e) {
								alertUser("Error Populating the Page",
										"There was an error populating the page: "
												+ e.toString());
							}
						}

						// Build the parameters and make the request.
						var authToken = getAuthToken();
						if (authToken != null) {
							var parameters = {
								"client" : "TrialistWeb",
								"auth_token" : authToken,
								"campaign_urn_list" : CAMPAIGN_ID,
								"output_format" : "long"
							};
							$.post("/app/campaign/read", parameters, success,
									"json").fail(failure);
						}
					}

					/**
					 * Populate the two regimen checkbox groups.
					 */
					function setupRegimenLists(root, survey, divA, divB) {
						var properties, index;

						// Get the list of properties for regimen list A.
						properties = getPropertiesFromPrompt(root, survey,
								PROMPT_ID_REGIMEN_A);
						// Populate the checkboxes for regimen list A.
						CHECKBOX_REGIMEN_A = CHECKBOX_REGIMEN_A
								.concat(populateCheckboxFromProperties(root,
										divA, properties, 'A'));

						// Get the list of properties for regimen list B.
						properties = getPropertiesFromPrompt(root, survey,
								PROMPT_ID_REGIMEN_B);
						// Populate the checkboxes for regimen list B.
						CHECKBOX_REGIMEN_B = CHECKBOX_REGIMEN_B
								.concat(populateCheckboxFromProperties(root,
										divB, properties, 'B'));
					}

					/**
					 * Finds a specific prompt in a survey and populates the given HTML
					 * select with the properties of this prompt. This prompt must be a
					 * [custom] single or multi choice prompt.
					 */
					function createSelectOptionsFromPromptProperties(root,
							survey, promptId, select) {
						// Get the properties for the given prompt in the given survey.
						var properties = getPropertiesFromPrompt(root, survey,
								promptId);

						// Using the properties, populate the HTML select.
						populateSelectFromProperties(root, select, properties);
					}

					/**
					 * Drills down on a survey to find the given prompt. Then, it drills
					 * down on the prompt to get its properties. Those properties XML
					 * elements are returned.
					 *
					 * @param survey An XML element referencing the survey.
					 *
					 * @param promptId The prompt ID whose properties are desired.
					 *
					 * @return An XML object that references all of the "property" tags.
					 */
					function getPropertiesFromPrompt(root, survey, promptId) {
						// Get the prompt elements.
						var prompts = evaluateXpath(root, survey,
								'.//prompt[id="' + promptId + '"]');

						// Get the singular prompt element.
						var prompt = nextElement(prompts);
						if (prompt === null) {
							throw "The " + promptId + " prompt is missing.";
						}

						// Get the prompt's properties.
						var properties = evaluateXpath(root, prompt,
								'.//property');

						// Return the list of properties.
						return properties;
					}

					/**
					 * Populates a HTML select tag with the given single choice prompt
					 * properties.
					 */
					function populateSelectFromProperties(root, select,
							properties) {
						var currProperty = null;
						var result = [];
						while ((currProperty = nextElement(properties)) !== null) {
							// XPath to the key element.
							var keyElements = evaluateXpath(root, currProperty,
									'./key');

							// Get the key element.
							var keyElement = nextElement(keyElements);
							if (keyElement === null) {
								throw "The property is missing its key.";
							}

							// Get the key value.
							var key = elementValue(keyElement);

							// XPath to the label element.
							var labelElements = evaluateXpath(root,
									currProperty, './label');

							// Get the label element.
							var labelElement = nextElement(labelElements);
							if (labelElement === null) {
								throw "The property is missing its label: "
										+ key;
							}

							// Get the label value.
							var label = elementValue(labelElement);

							// XPath to the value element.
							var value = null;
							var valueElements = evaluateXpath(root,
									currProperty, './value');
							// Get the label element.
							var valueElement = nextElement(valueElements);
							// If it exists, set it.
							if (valueElement !== null) {
								value = elementValue(valueElement);
							}

							// Create the checkbox.
							var checkbox = $('<option value="'
									+ key
									+ ((value === null) ? ''
											: ('" data-value="' + value))
									+ '">' + label + '</option>');

							// Add the value to the select's choices.
							select.append(checkbox);
						}

						// Reset the selected index to -1, so that the user must explicitly
						// choose an option.
						select.prop('selectedIndex', -1);

						return result;
					}

					/**
					 * Creates a series of checkboxes for a DIV based on the properties
					 * from a prompt.
					 * 
					 * Returns a list containing the generated checkboxes.
					 */
					function populateCheckboxFromProperties(root, div,
							properties, spanIdPrefix) {
						var currProperty = null;
						var result = [];
						var first = true;
						
						while ((currProperty = nextElement(properties)) !== null) {
							if(first === true && spanIdPrefix === 'A') {
								first = false;
								continue;
							}
							
							// XPath to the key element.
							var keyElements = evaluateXpath(root, currProperty,
									'./key');

							// Get the key element.
							var keyElement = nextElement(keyElements);
							if (keyElement === null) {
								throw "The property is missing its key.";
							}

							// Get the key value.
							var key = elementValue(keyElement);

							// XPath to the label element.
							var labelElements = evaluateXpath(root,
									currProperty, './label');

							// Get the label element.
							var labelElement = nextElement(labelElements);
							if (labelElement === null) {
								throw "The property is missing its label: "
										+ key;
							}

							// Get the label value.
							var label = elementValue(labelElement);

							// Create the checkbox.
							var checkbox = $('<input type="checkbox" value="' + key + '">');

							// Save the checkbox.
							result.push(checkbox);

							// Build the entire checkbox option.
							var entireOption = $(
									'<label class="checkbox"></label>').append(
									checkbox).append(
									'<span class="regimen' + spanIdPrefix + key + '">' + label + '</span>');

							// Add the entire option to the div.
							div.append(entireOption);
						}

						return result;
					}

					/**
					 * Populates a HTML select tag with prompt text for the given single-item surveys. 
					 */
					function populateSelectFromSingleItemSurveys(root, promptIds, select) {
						// Cycles through the prompt IDs.
						for ( var i = 0; i < promptIds.length; i++) {
							// Get the prompt ID.
							var promptId = promptIds[i];

							// Get the prompt XML nodes.
							// FIXME: This might break on FF and IE
							var promptNodes = evaluateXpath(root, root,
									'/campaign/surveys/survey[id="' + MAIN_SURVEY_ID
											+ '"]' + '/contentList/prompt[id="' + promptId + '"]');

							// Get the prompt XML nodes.
							var currPrompt = nextElement(promptNodes);
							if (currPrompt === null) {
								throw "The prompt does not exist: " + promptId;
							}

							// XPath to the text element.
							var textElements = evaluateXpath(root, currPrompt, './promptText');

							// Get the name element.
							var textElement = nextElement(textElements);
							if (textElement === null) {
								throw "The prompt is missing its text.";
							}

							// Get the name value.
							var text = elementValue(textElement);

							// Add the value to the select's choices.
							select.append('<option value="' + promptId + '">' + text + '</option>');
						}

						// Reset the selected index to -1, so that the user must explicitly
						// choose an option.
						select.prop('selectedIndex', -1);
					}

					/**
					 * Makes the call to the campaign assignment API.
					 */
					function create() {
						try {
							
							// Get the HTML element used to select the user.
							var username = $("#selectUser").val();

							if (username === null) {
                                alertUser("No Patient Login Selected",
                                        "Please choose a patient login.");
                                return;
                            }
							
							// Cycle through the first regimens, find the ones that are
							// checked, and save them.
							var regimenAs = [];
							for ( var i = 0; i < CHECKBOX_REGIMEN_A.length; i++) {
								// Get the current regimen radio.
								var regimenRadio = CHECKBOX_REGIMEN_A[i];

								// If it is checked, set it as the regimen response value. 
								if (regimenRadio.is(":checked")) {
									regimenAs.push(regimenRadio.val());
								}
							}
							// If none were selected, alert the user.
							if (regimenAs.length === 0) {
								alertUser("No First Regimen Selected",
										"Please choose a first regimen.");
								return;
							}
							// Guarantee that no illegal association was made.
							var index = 0;
							while (index < regimenAs.length) {
								// Get the allowed values for the currently selected
								// regimen.
								var allowedValues = ALLOWED_REGIMEN_COMBINATIONS[regimenAs[index]];

								// Cycle through the other regimens to be sure they are in
								// the list.
								var i = index + 1;
								while (i < regimenAs.length) {
									// Verify that it is in the list.
									if (allowedValues.indexOf(regimenAs[i]) === -1) {
										alertUser(
												"Regimen Combination Not Medically Indicated ",
												"In the first regimen section, multiple "
														+ "regimens were combined that were not "
														+ "allowed to be combined.");
										return;
									}

									// Step.
									i = i + 1;
								}

								// Step the index.
								index = index + 1;
							}

							// Cycle through the second regimens, find the ones that are
							// checked, and save them.
							var regimenBs = [];
							for ( var i = 0; i < CHECKBOX_REGIMEN_B.length; i++) {
								// Get the current regimen radio.
								var regimenRadio = CHECKBOX_REGIMEN_B[i];

								// If it is checked, set it as the regimen response value. 
								if (regimenRadio.is(":checked")) {
									regimenBs.push(regimenRadio.val());
								}
							}
							if (regimenBs.length === 0) {
								alertUser("No Second Regimen Selected",
										"Please choose a second regimen.");
								return;
							}
							// Guarantee that no illegal association was made.
							index = 0;
							while (index < regimenBs.length) {
								// Get the allowed values for the currently selected
								// regimen.
								var allowedValues = ALLOWED_REGIMEN_COMBINATIONS[regimenBs[index]];

								// Cycle through the other regimens to be sure they are in
								// the list.
								var i = index + 1;
								while (i < regimenBs.length) {
									// Verify that it is in the list.
									if (allowedValues.indexOf(regimenBs[i]) === -1) {
										alertUser(
												"Regimen Combination Not Medically Indicated ",
												"In the second regimen section, multiple "
														+ "regimens were combined that were not "
														+ "allowed to be combined.");
										return;
									}

									// Step.
									i = i + 1;
								}

								// Step the index.
								index = index + 1;
							}

							// Make sure the two regimens are not equal.
							if (regimenAs.equivalent(regimenBs)) {
								alertUser("Equivalent Regimens",
										"The first and second regimen lists are the same.");
								return;
							}
							
	                        // Make sure yes or no was selected 
                            var isPrescribingAdditionalOrContinuingTreatments = 0;
                             
                            if($("#extraTreatmentRadios1").is(":checked")) {  
                                isPrescribingAdditionalOrContinuingTreatments = 1;
                                
                            } else if( ! $("#extraTreatmentRadios2").is(":checked")) {
                                alertUser("No Extra Treatment Option Selected",
                                "Please choose Yes or No for prescribing or continuing pain treatments.");
                                return;
                            }

							// Get the start date.
							var startDate = $("#startDate").val();
							if ((startDate === null) || (startDate === "")) {
								alertUser("No Start Date",
										"Please choose a start date.");
								return;
							}

							var today = new Date();
							today.setUTCHours(0);
							today.setUTCMinutes(0);
							today.setUTCSeconds(0);
							today.setUTCMilliseconds(0);
							
							if(startDateAsDate.valueOf() < today.valueOf()) {
								alertUser("Invalid Start Date",
                                "Please choose a start date that is not in the past.");
							    return;
							}
							
							// A trial can not be longer than 12 weeks (84 days)
							// A simpler version of this is to just disallow the selection
							// of a two week period with 4 cycles.
							
							// First, clear out the time portion of each date
							
							startDateAsDate.setUTCHours(0);
                            startDateAsDate.setUTCMinutes(0);
                            startDateAsDate.setUTCSeconds(0);
                            startDateAsDate.setUTCMilliseconds(0);
							
                            endDateAsDate.setUTCHours(0);
                            endDateAsDate.setUTCMinutes(0);
                            endDateAsDate.setUTCSeconds(0);
                            endDateAsDate.setUTCMilliseconds(0);
                            
							var startTime = startDateAsDate.getTime();
							var endTime = endDateAsDate.getTime();
							
							// Check the difference
							
							var eightyFourDaysInMillis = 84 * 24 * 60 * 60 * 1000;
							
							if((endTime - startTime) > eightyFourDaysInMillis) {
								alertUser("Invalid Trial Length",
                                "A trial cannot be longer than 12 weeks. Please choose a shorter period length or a fewer number of cycles.");
                                return;
							} 
							
							startDate = startDate + " 00:00:00";
							
							// Account for the local timezone when displaying the dates back to the user.
							startDateAsDate.setTime(startDateAsDate.getTime() + (startDateAsDate.getTimezoneOffset() * 60 * 1000));
							endDateAsDate.setTime(endDateAsDate.getTime() + (endDateAsDate.getTimezoneOffset() * 60 * 1000));
							
							// Get the regimen duration value.
							var regimenDuration = $("#regimenDuration").val();
							if (regimenDuration === null) {
								alertUser("No Length Selected",
										"Please choose a period length.");
								return;
							}

							// Get the number of regimen cycles.
							var regimenCycles = $("#regimenCycles").val();
							if (regimenCycles === null) {
								alertUser("No Cycles Selected",
										"Please choose a number of cycles.");
								return;
							}
							
                            var actualRegimenCycles = -1;
                            
                            if(regimenCycles == 0) {
                                actualRegimenCycles = 2; 
                            } else if(regimenCycles == 1) {
                                actualRegimenCycles = 3;
                            } else if(regimenCycles == 2) {
                                actualRegimenCycles = 4;
                            }

							// Generate a random value for the pattern.
							
							var randoms = [];
							
							for(var i = 0; i < actualRegimenCycles; i++) {
								randoms.push(Math.floor(Math.random() * 1000 * MAX_RANDOM) % MAX_RANDOM);
							}
							
							// Generate the random regimen plan as a text string in case people want it in the future
							
							var randomsArray = [];
							for(var i = 0; i < randoms.length; i++) {
								if(randoms[i] == 0) {
									randomsArray.push('AB');	
								} else {
									randomsArray.push('BA');
								}
							}
							
							var randomsAsText = randomsArray.toString();
							
							// Pad with zeros to make the binary math work
							
							if(randoms.length < 3) {
								for(var i = 0; i < (3 - randoms.length ); i++) {
									randoms.push(0);
								}
							}
							
							// 0 == AB
							// 1 == BA
							
							var random = 0;
							
							for(var i = 0; i < randoms.length; i++) {
							     if(i == 0) {
							    	 if(randoms[i] == 1) {
							    		 random = random + 1;
							    	 }
							     }
							     if(i == 1) {
                                     if(randoms[i] == 1) {
                                         random = random + 2;
                                     }
                                 }
							     if(i == 2) {
                                     if(randoms[i] == 1) {
                                         random = random + 4;
                                     }
                                 }
							}
														
							// Get the primary outcome text.
							var cognitiveFunction = $("#cognitiveFunction").val();
							
							if (cognitiveFunction === null) {
								alertUser("No Cognitive Function Outcome Selected",
										"Please choose a cognitive function outcome.");
								return;
							}

							// Get the list of required survey IDs.
							var promptIds = REQUIRED_PROMPT_IDS.slice();
							// Ensure that a cognitive function was selected.
							var cognitiveFunction = $("#cognitiveFunction").val();
							if ((cognitiveFunction === null) || (cognitiveFunction === "")) {
								alertUser("No Cognitive Outcome Function Selected",
										"Please choose a cognitive function outcome.");
								return;
							}
							promptIds.push(cognitiveFunction);
							
							// Make sure yes or no was selected
							var isNeuropathicPain = 0;
							 
						    if ($("#neuropathicRadios1").is(":checked")) {	
								isNeuropathicPain = 1;
								for(var i = 0; i < PROMPT_IDS_NEUROPATHIC_PAIN.length; i++) {
									promptIds.push(PROMPT_IDS_NEUROPATHIC_PAIN[i]);	
								}
							} else if( ! $("#neuropathicRadios2").is(":checked")) {
								alertUser("No Neuropathic Pain Option Selected",
                                "Please choose Yes Or No for the neuropathic pain option.");
							    return;
							}
						    
							// Build the survey response.
							var surveyResponse = {
								"survey_key" : randomUUID(),
								"time" : (new Date()).getTime(),
								"timezone" : "+00:00",
								"location_status" : "unavailable",
								"survey_id" : SETUP_SURVEY_ID,
								"survey_launch_context" : {
									"launch_time" : (new Date()).getTime(),
									"launch_timezone" : "+00:00",
									"active_triggers" : []
								},
								"responses" : [
										{
											"prompt_id" : PROMPT_ID_REGIMEN_A,
											"value" : regimenAs
										},
										{
											"prompt_id" : PROMPT_ID_REGIMEN_B,
											"value" : regimenBs
										},
										{
											"prompt_id" : PROMPT_ID_START_DATE,
											"value" : startDate
										},
										{
											"prompt_id" : PROMPT_ID_REGIMEN_DURATION,
											"value" : regimenDuration
										},
										{
											"prompt_id" : PROMPT_ID_REGIMEN_CYCLES,
											"value" : regimenCycles
										},
										{
											"prompt_id" : PROMPT_ID_RANDOM,
											"value" : random
										},
										{
											"prompt_id" : PROMPT_ID_RANDOM_AS_TEXT,
											"value" : randomsAsText
										},
										{
											"prompt_id" : PROMPT_ID_COGNITIVE_FUNCTION,
											"value" : cognitiveFunction
										},
										{
											"prompt_id" : PROMPT_ID_NEUROPATHIC_PAIN_TAKEN,
											"value" : isNeuropathicPain
										},
										{
                                            "prompt_id" : PROMPT_ID_EXTRA_TREATMENT,
                                            "value" : isPrescribingAdditionalOrContinuingTreatments
                                        },
										{
                                            "prompt_id" : PROMPT_ID_USER_SELECTED,
                                            "value" : username
                                        }]
							};

							// The survey responses must be an array.
							var surveyResponses = [ surveyResponse ];

							// Create the failure function.
							var failure = function() {
								alertUser("Creation Failure",
										"The server returned an unexpected error.");
							}
							// Create the success function.
							var success = function(data) {
								// Check that we indicated success.
								if (data['result'] === "success") {
									
									var regimenAString = new String();
									var regimenBString = new String();
									
									var first = true;
									
									for(var i = 0; i < regimenAs.length; i++) {
										if(first) {
											first = false;
										} else {
											regimenAString = regimenAString + '; ';	
										}
										
										regimenAString = regimenAString + $("span.regimenA" + regimenAs[i]).text();
									}
									
									first = true;
                                    for(var i = 0; i < regimenBs.length; i++) {
                                    	if(first) {
                                            first = false;
                                        } else {
                                            regimenBString = regimenBString + '; ';  
                                        }
                                    	
                                        regimenBString = regimenBString + $(("span.regimenB" + regimenBs[i])).text();
                                    }
                                                                        
                                    var durationInDays = -1;
                                    
                                    if(regimenDuration == 0) {
                                        durationInDays = 2;
                                    } else if(regimenDuration == 1) {
                                        durationInDays = 7;
                                    } else if(regimenDuration == 2) {
                                        durationInDays = 14;
                                    }
                                    
									var tablePreamble = '<table class="table table-striped table-bordered">'
									var patientRow = '<tr><td>Patient Login</td><td>' + username + '</td></tr>';
									var regimenARow = '<tr><td>Regimen A</td><td>' + regimenAString + '</td></tr>';
									var regimenBRow = '<tr><td>Regimen B</td><td>' + regimenBString + '</td></tr>';
									var periodLengthRow = '<tr><td>Period Length</td><td>' + durationInDays + ' days</td></tr>';
									var numberOfCyclesRow = '<tr><td>Number of Cycles</td><td>' + actualRegimenCycles + '</td></tr>';
									var startDateRow = '<tr><td>Start Date</td><td>' + startDateAsDate.toDateString() + '</td></tr>';
									var endDateRow = '<tr><td>End Date</td><td>' + endDateAsDate.toDateString() + '</td></tr></table>';
									
									var table = tablePreamble + patientRow + regimenARow + regimenBRow 
									    + periodLengthRow + numberOfCyclesRow + startDateRow + endDateRow;
									
									alertUser("Success",
											  "<strong>The phone app for Trialist is ready to go! Welcome to the PREEMPT study.</strong>" + table, true)
									
								} else {
									var failureObject = data['errors'][0];
									if (failureObject['code'] === "0200") {
										redirectToLogin();
									} else {
										alertUser("Error",
												"There was an error setting up the user: "
														+ failureObject['text']);
									}
								}
							}

							// Submit the request.
							var authToken = getAuthToken();
							if (authToken != null) {
 
								// Create the parameters list.
								var parameters = {
									"client" : "TrialistWeb",
									"auth_token" : authToken,
									"username" : username,
									"class_urn" : CLASS_ID,
									"campaign_urn" : CAMPAIGN_ID,
									"survey_prompt_map" : JSON.stringify([
									    {
									    	"survey_id": MAIN_SURVEY_ID,
									        "prompt_ids": promptIds  
									    },
									    {
									    	"survey_id" : SURVEY_ID_ADHERENCE,
									    	"prompt_ids" : [ PROMPT_ID_ADHERENCE ]
									    }
									 	
									]),
									"surveys" : JSON.stringify(surveyResponses)
								};
								
								// Make the request.
							 	$.post("/app/campaign/assign", parameters,
										success).fail(failure); 
							}
						} catch (e) {
							alertUser("Error",
									"There was an error setting up the user: "
											+ e);
						}
					}
				</script>
  </body>
</html>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      master/js/                                                                                          000755  000767  000024  00000000000 12171067413 013425  5                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         master/js/jquery-1.9.0.min.js                                                                       000644  000767  000024  00000265614 12110524611 016534  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /*! jQuery v1.9.0 | (c) 2005, 2012 jQuery Foundation, Inc. | jquery.org/license */(function(e,t){"use strict";function n(e){var t=e.length,n=st.type(e);return st.isWindow(e)?!1:1===e.nodeType&&t?!0:"array"===n||"function"!==n&&(0===t||"number"==typeof t&&t>0&&t-1 in e)}function r(e){var t=Tt[e]={};return st.each(e.match(lt)||[],function(e,n){t[n]=!0}),t}function i(e,n,r,i){if(st.acceptData(e)){var o,a,s=st.expando,u="string"==typeof n,l=e.nodeType,c=l?st.cache:e,f=l?e[s]:e[s]&&s;if(f&&c[f]&&(i||c[f].data)||!u||r!==t)return f||(l?e[s]=f=K.pop()||st.guid++:f=s),c[f]||(c[f]={},l||(c[f].toJSON=st.noop)),("object"==typeof n||"function"==typeof n)&&(i?c[f]=st.extend(c[f],n):c[f].data=st.extend(c[f].data,n)),o=c[f],i||(o.data||(o.data={}),o=o.data),r!==t&&(o[st.camelCase(n)]=r),u?(a=o[n],null==a&&(a=o[st.camelCase(n)])):a=o,a}}function o(e,t,n){if(st.acceptData(e)){var r,i,o,a=e.nodeType,u=a?st.cache:e,l=a?e[st.expando]:st.expando;if(u[l]){if(t&&(r=n?u[l]:u[l].data)){st.isArray(t)?t=t.concat(st.map(t,st.camelCase)):t in r?t=[t]:(t=st.camelCase(t),t=t in r?[t]:t.split(" "));for(i=0,o=t.length;o>i;i++)delete r[t[i]];if(!(n?s:st.isEmptyObject)(r))return}(n||(delete u[l].data,s(u[l])))&&(a?st.cleanData([e],!0):st.support.deleteExpando||u!=u.window?delete u[l]:u[l]=null)}}}function a(e,n,r){if(r===t&&1===e.nodeType){var i="data-"+n.replace(Nt,"-$1").toLowerCase();if(r=e.getAttribute(i),"string"==typeof r){try{r="true"===r?!0:"false"===r?!1:"null"===r?null:+r+""===r?+r:wt.test(r)?st.parseJSON(r):r}catch(o){}st.data(e,n,r)}else r=t}return r}function s(e){var t;for(t in e)if(("data"!==t||!st.isEmptyObject(e[t]))&&"toJSON"!==t)return!1;return!0}function u(){return!0}function l(){return!1}function c(e,t){do e=e[t];while(e&&1!==e.nodeType);return e}function f(e,t,n){if(t=t||0,st.isFunction(t))return st.grep(e,function(e,r){var i=!!t.call(e,r,e);return i===n});if(t.nodeType)return st.grep(e,function(e){return e===t===n});if("string"==typeof t){var r=st.grep(e,function(e){return 1===e.nodeType});if(Wt.test(t))return st.filter(t,r,!n);t=st.filter(t,r)}return st.grep(e,function(e){return st.inArray(e,t)>=0===n})}function p(e){var t=zt.split("|"),n=e.createDocumentFragment();if(n.createElement)for(;t.length;)n.createElement(t.pop());return n}function d(e,t){return e.getElementsByTagName(t)[0]||e.appendChild(e.ownerDocument.createElement(t))}function h(e){var t=e.getAttributeNode("type");return e.type=(t&&t.specified)+"/"+e.type,e}function g(e){var t=nn.exec(e.type);return t?e.type=t[1]:e.removeAttribute("type"),e}function m(e,t){for(var n,r=0;null!=(n=e[r]);r++)st._data(n,"globalEval",!t||st._data(t[r],"globalEval"))}function y(e,t){if(1===t.nodeType&&st.hasData(e)){var n,r,i,o=st._data(e),a=st._data(t,o),s=o.events;if(s){delete a.handle,a.events={};for(n in s)for(r=0,i=s[n].length;i>r;r++)st.event.add(t,n,s[n][r])}a.data&&(a.data=st.extend({},a.data))}}function v(e,t){var n,r,i;if(1===t.nodeType){if(n=t.nodeName.toLowerCase(),!st.support.noCloneEvent&&t[st.expando]){r=st._data(t);for(i in r.events)st.removeEvent(t,i,r.handle);t.removeAttribute(st.expando)}"script"===n&&t.text!==e.text?(h(t).text=e.text,g(t)):"object"===n?(t.parentNode&&(t.outerHTML=e.outerHTML),st.support.html5Clone&&e.innerHTML&&!st.trim(t.innerHTML)&&(t.innerHTML=e.innerHTML)):"input"===n&&Zt.test(e.type)?(t.defaultChecked=t.checked=e.checked,t.value!==e.value&&(t.value=e.value)):"option"===n?t.defaultSelected=t.selected=e.defaultSelected:("input"===n||"textarea"===n)&&(t.defaultValue=e.defaultValue)}}function b(e,n){var r,i,o=0,a=e.getElementsByTagName!==t?e.getElementsByTagName(n||"*"):e.querySelectorAll!==t?e.querySelectorAll(n||"*"):t;if(!a)for(a=[],r=e.childNodes||e;null!=(i=r[o]);o++)!n||st.nodeName(i,n)?a.push(i):st.merge(a,b(i,n));return n===t||n&&st.nodeName(e,n)?st.merge([e],a):a}function x(e){Zt.test(e.type)&&(e.defaultChecked=e.checked)}function T(e,t){if(t in e)return t;for(var n=t.charAt(0).toUpperCase()+t.slice(1),r=t,i=Nn.length;i--;)if(t=Nn[i]+n,t in e)return t;return r}function w(e,t){return e=t||e,"none"===st.css(e,"display")||!st.contains(e.ownerDocument,e)}function N(e,t){for(var n,r=[],i=0,o=e.length;o>i;i++)n=e[i],n.style&&(r[i]=st._data(n,"olddisplay"),t?(r[i]||"none"!==n.style.display||(n.style.display=""),""===n.style.display&&w(n)&&(r[i]=st._data(n,"olddisplay",S(n.nodeName)))):r[i]||w(n)||st._data(n,"olddisplay",st.css(n,"display")));for(i=0;o>i;i++)n=e[i],n.style&&(t&&"none"!==n.style.display&&""!==n.style.display||(n.style.display=t?r[i]||"":"none"));return e}function C(e,t,n){var r=mn.exec(t);return r?Math.max(0,r[1]-(n||0))+(r[2]||"px"):t}function k(e,t,n,r,i){for(var o=n===(r?"border":"content")?4:"width"===t?1:0,a=0;4>o;o+=2)"margin"===n&&(a+=st.css(e,n+wn[o],!0,i)),r?("content"===n&&(a-=st.css(e,"padding"+wn[o],!0,i)),"margin"!==n&&(a-=st.css(e,"border"+wn[o]+"Width",!0,i))):(a+=st.css(e,"padding"+wn[o],!0,i),"padding"!==n&&(a+=st.css(e,"border"+wn[o]+"Width",!0,i)));return a}function E(e,t,n){var r=!0,i="width"===t?e.offsetWidth:e.offsetHeight,o=ln(e),a=st.support.boxSizing&&"border-box"===st.css(e,"boxSizing",!1,o);if(0>=i||null==i){if(i=un(e,t,o),(0>i||null==i)&&(i=e.style[t]),yn.test(i))return i;r=a&&(st.support.boxSizingReliable||i===e.style[t]),i=parseFloat(i)||0}return i+k(e,t,n||(a?"border":"content"),r,o)+"px"}function S(e){var t=V,n=bn[e];return n||(n=A(e,t),"none"!==n&&n||(cn=(cn||st("<iframe frameborder='0' width='0' height='0'/>").css("cssText","display:block !important")).appendTo(t.documentElement),t=(cn[0].contentWindow||cn[0].contentDocument).document,t.write("<!doctype html><html><body>"),t.close(),n=A(e,t),cn.detach()),bn[e]=n),n}function A(e,t){var n=st(t.createElement(e)).appendTo(t.body),r=st.css(n[0],"display");return n.remove(),r}function j(e,t,n,r){var i;if(st.isArray(t))st.each(t,function(t,i){n||kn.test(e)?r(e,i):j(e+"["+("object"==typeof i?t:"")+"]",i,n,r)});else if(n||"object"!==st.type(t))r(e,t);else for(i in t)j(e+"["+i+"]",t[i],n,r)}function D(e){return function(t,n){"string"!=typeof t&&(n=t,t="*");var r,i=0,o=t.toLowerCase().match(lt)||[];if(st.isFunction(n))for(;r=o[i++];)"+"===r[0]?(r=r.slice(1)||"*",(e[r]=e[r]||[]).unshift(n)):(e[r]=e[r]||[]).push(n)}}function L(e,n,r,i){function o(u){var l;return a[u]=!0,st.each(e[u]||[],function(e,u){var c=u(n,r,i);return"string"!=typeof c||s||a[c]?s?!(l=c):t:(n.dataTypes.unshift(c),o(c),!1)}),l}var a={},s=e===$n;return o(n.dataTypes[0])||!a["*"]&&o("*")}function H(e,n){var r,i,o=st.ajaxSettings.flatOptions||{};for(r in n)n[r]!==t&&((o[r]?e:i||(i={}))[r]=n[r]);return i&&st.extend(!0,e,i),e}function M(e,n,r){var i,o,a,s,u=e.contents,l=e.dataTypes,c=e.responseFields;for(o in c)o in r&&(n[c[o]]=r[o]);for(;"*"===l[0];)l.shift(),i===t&&(i=e.mimeType||n.getResponseHeader("Content-Type"));if(i)for(o in u)if(u[o]&&u[o].test(i)){l.unshift(o);break}if(l[0]in r)a=l[0];else{for(o in r){if(!l[0]||e.converters[o+" "+l[0]]){a=o;break}s||(s=o)}a=a||s}return a?(a!==l[0]&&l.unshift(a),r[a]):t}function q(e,t){var n,r,i,o,a={},s=0,u=e.dataTypes.slice(),l=u[0];if(e.dataFilter&&(t=e.dataFilter(t,e.dataType)),u[1])for(n in e.converters)a[n.toLowerCase()]=e.converters[n];for(;i=u[++s];)if("*"!==i){if("*"!==l&&l!==i){if(n=a[l+" "+i]||a["* "+i],!n)for(r in a)if(o=r.split(" "),o[1]===i&&(n=a[l+" "+o[0]]||a["* "+o[0]])){n===!0?n=a[r]:a[r]!==!0&&(i=o[0],u.splice(s--,0,i));break}if(n!==!0)if(n&&e["throws"])t=n(t);else try{t=n(t)}catch(c){return{state:"parsererror",error:n?c:"No conversion from "+l+" to "+i}}}l=i}return{state:"success",data:t}}function _(){try{return new e.XMLHttpRequest}catch(t){}}function F(){try{return new e.ActiveXObject("Microsoft.XMLHTTP")}catch(t){}}function O(){return setTimeout(function(){Qn=t}),Qn=st.now()}function B(e,t){st.each(t,function(t,n){for(var r=(rr[t]||[]).concat(rr["*"]),i=0,o=r.length;o>i;i++)if(r[i].call(e,t,n))return})}function P(e,t,n){var r,i,o=0,a=nr.length,s=st.Deferred().always(function(){delete u.elem}),u=function(){if(i)return!1;for(var t=Qn||O(),n=Math.max(0,l.startTime+l.duration-t),r=n/l.duration||0,o=1-r,a=0,u=l.tweens.length;u>a;a++)l.tweens[a].run(o);return s.notifyWith(e,[l,o,n]),1>o&&u?n:(s.resolveWith(e,[l]),!1)},l=s.promise({elem:e,props:st.extend({},t),opts:st.extend(!0,{specialEasing:{}},n),originalProperties:t,originalOptions:n,startTime:Qn||O(),duration:n.duration,tweens:[],createTween:function(t,n){var r=st.Tween(e,l.opts,t,n,l.opts.specialEasing[t]||l.opts.easing);return l.tweens.push(r),r},stop:function(t){var n=0,r=t?l.tweens.length:0;if(i)return this;for(i=!0;r>n;n++)l.tweens[n].run(1);return t?s.resolveWith(e,[l,t]):s.rejectWith(e,[l,t]),this}}),c=l.props;for(R(c,l.opts.specialEasing);a>o;o++)if(r=nr[o].call(l,e,c,l.opts))return r;return B(l,c),st.isFunction(l.opts.start)&&l.opts.start.call(e,l),st.fx.timer(st.extend(u,{elem:e,anim:l,queue:l.opts.queue})),l.progress(l.opts.progress).done(l.opts.done,l.opts.complete).fail(l.opts.fail).always(l.opts.always)}function R(e,t){var n,r,i,o,a;for(n in e)if(r=st.camelCase(n),i=t[r],o=e[n],st.isArray(o)&&(i=o[1],o=e[n]=o[0]),n!==r&&(e[r]=o,delete e[n]),a=st.cssHooks[r],a&&"expand"in a){o=a.expand(o),delete e[r];for(n in o)n in e||(e[n]=o[n],t[n]=i)}else t[r]=i}function W(e,t,n){var r,i,o,a,s,u,l,c,f,p=this,d=e.style,h={},g=[],m=e.nodeType&&w(e);n.queue||(c=st._queueHooks(e,"fx"),null==c.unqueued&&(c.unqueued=0,f=c.empty.fire,c.empty.fire=function(){c.unqueued||f()}),c.unqueued++,p.always(function(){p.always(function(){c.unqueued--,st.queue(e,"fx").length||c.empty.fire()})})),1===e.nodeType&&("height"in t||"width"in t)&&(n.overflow=[d.overflow,d.overflowX,d.overflowY],"inline"===st.css(e,"display")&&"none"===st.css(e,"float")&&(st.support.inlineBlockNeedsLayout&&"inline"!==S(e.nodeName)?d.zoom=1:d.display="inline-block")),n.overflow&&(d.overflow="hidden",st.support.shrinkWrapBlocks||p.done(function(){d.overflow=n.overflow[0],d.overflowX=n.overflow[1],d.overflowY=n.overflow[2]}));for(r in t)if(o=t[r],Zn.exec(o)){if(delete t[r],u=u||"toggle"===o,o===(m?"hide":"show"))continue;g.push(r)}if(a=g.length){s=st._data(e,"fxshow")||st._data(e,"fxshow",{}),"hidden"in s&&(m=s.hidden),u&&(s.hidden=!m),m?st(e).show():p.done(function(){st(e).hide()}),p.done(function(){var t;st._removeData(e,"fxshow");for(t in h)st.style(e,t,h[t])});for(r=0;a>r;r++)i=g[r],l=p.createTween(i,m?s[i]:0),h[i]=s[i]||st.style(e,i),i in s||(s[i]=l.start,m&&(l.end=l.start,l.start="width"===i||"height"===i?1:0))}}function $(e,t,n,r,i){return new $.prototype.init(e,t,n,r,i)}function I(e,t){var n,r={height:e},i=0;for(t=t?1:0;4>i;i+=2-t)n=wn[i],r["margin"+n]=r["padding"+n]=e;return t&&(r.opacity=r.width=e),r}function z(e){return st.isWindow(e)?e:9===e.nodeType?e.defaultView||e.parentWindow:!1}var X,U,V=e.document,Y=e.location,J=e.jQuery,G=e.$,Q={},K=[],Z="1.9.0",et=K.concat,tt=K.push,nt=K.slice,rt=K.indexOf,it=Q.toString,ot=Q.hasOwnProperty,at=Z.trim,st=function(e,t){return new st.fn.init(e,t,X)},ut=/[+-]?(?:\d*\.|)\d+(?:[eE][+-]?\d+|)/.source,lt=/\S+/g,ct=/^[\s\uFEFF\xA0]+|[\s\uFEFF\xA0]+$/g,ft=/^(?:(<[\w\W]+>)[^>]*|#([\w-]*))$/,pt=/^<(\w+)\s*\/?>(?:<\/\1>|)$/,dt=/^[\],:{}\s]*$/,ht=/(?:^|:|,)(?:\s*\[)+/g,gt=/\\(?:["\\\/bfnrt]|u[\da-fA-F]{4})/g,mt=/"[^"\\\r\n]*"|true|false|null|-?(?:\d+\.|)\d+(?:[eE][+-]?\d+|)/g,yt=/^-ms-/,vt=/-([\da-z])/gi,bt=function(e,t){return t.toUpperCase()},xt=function(){V.addEventListener?(V.removeEventListener("DOMContentLoaded",xt,!1),st.ready()):"complete"===V.readyState&&(V.detachEvent("onreadystatechange",xt),st.ready())};st.fn=st.prototype={jquery:Z,constructor:st,init:function(e,n,r){var i,o;if(!e)return this;if("string"==typeof e){if(i="<"===e.charAt(0)&&">"===e.charAt(e.length-1)&&e.length>=3?[null,e,null]:ft.exec(e),!i||!i[1]&&n)return!n||n.jquery?(n||r).find(e):this.constructor(n).find(e);if(i[1]){if(n=n instanceof st?n[0]:n,st.merge(this,st.parseHTML(i[1],n&&n.nodeType?n.ownerDocument||n:V,!0)),pt.test(i[1])&&st.isPlainObject(n))for(i in n)st.isFunction(this[i])?this[i](n[i]):this.attr(i,n[i]);return this}if(o=V.getElementById(i[2]),o&&o.parentNode){if(o.id!==i[2])return r.find(e);this.length=1,this[0]=o}return this.context=V,this.selector=e,this}return e.nodeType?(this.context=this[0]=e,this.length=1,this):st.isFunction(e)?r.ready(e):(e.selector!==t&&(this.selector=e.selector,this.context=e.context),st.makeArray(e,this))},selector:"",length:0,size:function(){return this.length},toArray:function(){return nt.call(this)},get:function(e){return null==e?this.toArray():0>e?this[this.length+e]:this[e]},pushStack:function(e){var t=st.merge(this.constructor(),e);return t.prevObject=this,t.context=this.context,t},each:function(e,t){return st.each(this,e,t)},ready:function(e){return st.ready.promise().done(e),this},slice:function(){return this.pushStack(nt.apply(this,arguments))},first:function(){return this.eq(0)},last:function(){return this.eq(-1)},eq:function(e){var t=this.length,n=+e+(0>e?t:0);return this.pushStack(n>=0&&t>n?[this[n]]:[])},map:function(e){return this.pushStack(st.map(this,function(t,n){return e.call(t,n,t)}))},end:function(){return this.prevObject||this.constructor(null)},push:tt,sort:[].sort,splice:[].splice},st.fn.init.prototype=st.fn,st.extend=st.fn.extend=function(){var e,n,r,i,o,a,s=arguments[0]||{},u=1,l=arguments.length,c=!1;for("boolean"==typeof s&&(c=s,s=arguments[1]||{},u=2),"object"==typeof s||st.isFunction(s)||(s={}),l===u&&(s=this,--u);l>u;u++)if(null!=(e=arguments[u]))for(n in e)r=s[n],i=e[n],s!==i&&(c&&i&&(st.isPlainObject(i)||(o=st.isArray(i)))?(o?(o=!1,a=r&&st.isArray(r)?r:[]):a=r&&st.isPlainObject(r)?r:{},s[n]=st.extend(c,a,i)):i!==t&&(s[n]=i));return s},st.extend({noConflict:function(t){return e.$===st&&(e.$=G),t&&e.jQuery===st&&(e.jQuery=J),st},isReady:!1,readyWait:1,holdReady:function(e){e?st.readyWait++:st.ready(!0)},ready:function(e){if(e===!0?!--st.readyWait:!st.isReady){if(!V.body)return setTimeout(st.ready);st.isReady=!0,e!==!0&&--st.readyWait>0||(U.resolveWith(V,[st]),st.fn.trigger&&st(V).trigger("ready").off("ready"))}},isFunction:function(e){return"function"===st.type(e)},isArray:Array.isArray||function(e){return"array"===st.type(e)},isWindow:function(e){return null!=e&&e==e.window},isNumeric:function(e){return!isNaN(parseFloat(e))&&isFinite(e)},type:function(e){return null==e?e+"":"object"==typeof e||"function"==typeof e?Q[it.call(e)]||"object":typeof e},isPlainObject:function(e){if(!e||"object"!==st.type(e)||e.nodeType||st.isWindow(e))return!1;try{if(e.constructor&&!ot.call(e,"constructor")&&!ot.call(e.constructor.prototype,"isPrototypeOf"))return!1}catch(n){return!1}var r;for(r in e);return r===t||ot.call(e,r)},isEmptyObject:function(e){var t;for(t in e)return!1;return!0},error:function(e){throw Error(e)},parseHTML:function(e,t,n){if(!e||"string"!=typeof e)return null;"boolean"==typeof t&&(n=t,t=!1),t=t||V;var r=pt.exec(e),i=!n&&[];return r?[t.createElement(r[1])]:(r=st.buildFragment([e],t,i),i&&st(i).remove(),st.merge([],r.childNodes))},parseJSON:function(n){return e.JSON&&e.JSON.parse?e.JSON.parse(n):null===n?n:"string"==typeof n&&(n=st.trim(n),n&&dt.test(n.replace(gt,"@").replace(mt,"]").replace(ht,"")))?Function("return "+n)():(st.error("Invalid JSON: "+n),t)},parseXML:function(n){var r,i;if(!n||"string"!=typeof n)return null;try{e.DOMParser?(i=new DOMParser,r=i.parseFromString(n,"text/xml")):(r=new ActiveXObject("Microsoft.XMLDOM"),r.async="false",r.loadXML(n))}catch(o){r=t}return r&&r.documentElement&&!r.getElementsByTagName("parsererror").length||st.error("Invalid XML: "+n),r},noop:function(){},globalEval:function(t){t&&st.trim(t)&&(e.execScript||function(t){e.eval.call(e,t)})(t)},camelCase:function(e){return e.replace(yt,"ms-").replace(vt,bt)},nodeName:function(e,t){return e.nodeName&&e.nodeName.toLowerCase()===t.toLowerCase()},each:function(e,t,r){var i,o=0,a=e.length,s=n(e);if(r){if(s)for(;a>o&&(i=t.apply(e[o],r),i!==!1);o++);else for(o in e)if(i=t.apply(e[o],r),i===!1)break}else if(s)for(;a>o&&(i=t.call(e[o],o,e[o]),i!==!1);o++);else for(o in e)if(i=t.call(e[o],o,e[o]),i===!1)break;return e},trim:at&&!at.call("\ufeff\u00a0")?function(e){return null==e?"":at.call(e)}:function(e){return null==e?"":(e+"").replace(ct,"")},makeArray:function(e,t){var r=t||[];return null!=e&&(n(Object(e))?st.merge(r,"string"==typeof e?[e]:e):tt.call(r,e)),r},inArray:function(e,t,n){var r;if(t){if(rt)return rt.call(t,e,n);for(r=t.length,n=n?0>n?Math.max(0,r+n):n:0;r>n;n++)if(n in t&&t[n]===e)return n}return-1},merge:function(e,n){var r=n.length,i=e.length,o=0;if("number"==typeof r)for(;r>o;o++)e[i++]=n[o];else for(;n[o]!==t;)e[i++]=n[o++];return e.length=i,e},grep:function(e,t,n){var r,i=[],o=0,a=e.length;for(n=!!n;a>o;o++)r=!!t(e[o],o),n!==r&&i.push(e[o]);return i},map:function(e,t,r){var i,o=0,a=e.length,s=n(e),u=[];if(s)for(;a>o;o++)i=t(e[o],o,r),null!=i&&(u[u.length]=i);else for(o in e)i=t(e[o],o,r),null!=i&&(u[u.length]=i);return et.apply([],u)},guid:1,proxy:function(e,n){var r,i,o;return"string"==typeof n&&(r=e[n],n=e,e=r),st.isFunction(e)?(i=nt.call(arguments,2),o=function(){return e.apply(n||this,i.concat(nt.call(arguments)))},o.guid=e.guid=e.guid||st.guid++,o):t},access:function(e,n,r,i,o,a,s){var u=0,l=e.length,c=null==r;if("object"===st.type(r)){o=!0;for(u in r)st.access(e,n,u,r[u],!0,a,s)}else if(i!==t&&(o=!0,st.isFunction(i)||(s=!0),c&&(s?(n.call(e,i),n=null):(c=n,n=function(e,t,n){return c.call(st(e),n)})),n))for(;l>u;u++)n(e[u],r,s?i:i.call(e[u],u,n(e[u],r)));return o?e:c?n.call(e):l?n(e[0],r):a},now:function(){return(new Date).getTime()}}),st.ready.promise=function(t){if(!U)if(U=st.Deferred(),"complete"===V.readyState)setTimeout(st.ready);else if(V.addEventListener)V.addEventListener("DOMContentLoaded",xt,!1),e.addEventListener("load",st.ready,!1);else{V.attachEvent("onreadystatechange",xt),e.attachEvent("onload",st.ready);var n=!1;try{n=null==e.frameElement&&V.documentElement}catch(r){}n&&n.doScroll&&function i(){if(!st.isReady){try{n.doScroll("left")}catch(e){return setTimeout(i,50)}st.ready()}}()}return U.promise(t)},st.each("Boolean Number String Function Array Date RegExp Object Error".split(" "),function(e,t){Q["[object "+t+"]"]=t.toLowerCase()}),X=st(V);var Tt={};st.Callbacks=function(e){e="string"==typeof e?Tt[e]||r(e):st.extend({},e);var n,i,o,a,s,u,l=[],c=!e.once&&[],f=function(t){for(n=e.memory&&t,i=!0,u=a||0,a=0,s=l.length,o=!0;l&&s>u;u++)if(l[u].apply(t[0],t[1])===!1&&e.stopOnFalse){n=!1;break}o=!1,l&&(c?c.length&&f(c.shift()):n?l=[]:p.disable())},p={add:function(){if(l){var t=l.length;(function r(t){st.each(t,function(t,n){var i=st.type(n);"function"===i?e.unique&&p.has(n)||l.push(n):n&&n.length&&"string"!==i&&r(n)})})(arguments),o?s=l.length:n&&(a=t,f(n))}return this},remove:function(){return l&&st.each(arguments,function(e,t){for(var n;(n=st.inArray(t,l,n))>-1;)l.splice(n,1),o&&(s>=n&&s--,u>=n&&u--)}),this},has:function(e){return st.inArray(e,l)>-1},empty:function(){return l=[],this},disable:function(){return l=c=n=t,this},disabled:function(){return!l},lock:function(){return c=t,n||p.disable(),this},locked:function(){return!c},fireWith:function(e,t){return t=t||[],t=[e,t.slice?t.slice():t],!l||i&&!c||(o?c.push(t):f(t)),this},fire:function(){return p.fireWith(this,arguments),this},fired:function(){return!!i}};return p},st.extend({Deferred:function(e){var t=[["resolve","done",st.Callbacks("once memory"),"resolved"],["reject","fail",st.Callbacks("once memory"),"rejected"],["notify","progress",st.Callbacks("memory")]],n="pending",r={state:function(){return n},always:function(){return i.done(arguments).fail(arguments),this},then:function(){var e=arguments;return st.Deferred(function(n){st.each(t,function(t,o){var a=o[0],s=st.isFunction(e[t])&&e[t];i[o[1]](function(){var e=s&&s.apply(this,arguments);e&&st.isFunction(e.promise)?e.promise().done(n.resolve).fail(n.reject).progress(n.notify):n[a+"With"](this===r?n.promise():this,s?[e]:arguments)})}),e=null}).promise()},promise:function(e){return null!=e?st.extend(e,r):r}},i={};return r.pipe=r.then,st.each(t,function(e,o){var a=o[2],s=o[3];r[o[1]]=a.add,s&&a.add(function(){n=s},t[1^e][2].disable,t[2][2].lock),i[o[0]]=function(){return i[o[0]+"With"](this===i?r:this,arguments),this},i[o[0]+"With"]=a.fireWith}),r.promise(i),e&&e.call(i,i),i},when:function(e){var t,n,r,i=0,o=nt.call(arguments),a=o.length,s=1!==a||e&&st.isFunction(e.promise)?a:0,u=1===s?e:st.Deferred(),l=function(e,n,r){return function(i){n[e]=this,r[e]=arguments.length>1?nt.call(arguments):i,r===t?u.notifyWith(n,r):--s||u.resolveWith(n,r)}};if(a>1)for(t=Array(a),n=Array(a),r=Array(a);a>i;i++)o[i]&&st.isFunction(o[i].promise)?o[i].promise().done(l(i,r,o)).fail(u.reject).progress(l(i,n,t)):--s;return s||u.resolveWith(r,o),u.promise()}}),st.support=function(){var n,r,i,o,a,s,u,l,c,f,p=V.createElement("div");if(p.setAttribute("className","t"),p.innerHTML="  <link/><table></table><a href='/a'>a</a><input type='checkbox'/>",r=p.getElementsByTagName("*"),i=p.getElementsByTagName("a")[0],!r||!i||!r.length)return{};o=V.createElement("select"),a=o.appendChild(V.createElement("option")),s=p.getElementsByTagName("input")[0],i.style.cssText="top:1px;float:left;opacity:.5",n={getSetAttribute:"t"!==p.className,leadingWhitespace:3===p.firstChild.nodeType,tbody:!p.getElementsByTagName("tbody").length,htmlSerialize:!!p.getElementsByTagName("link").length,style:/top/.test(i.getAttribute("style")),hrefNormalized:"/a"===i.getAttribute("href"),opacity:/^0.5/.test(i.style.opacity),cssFloat:!!i.style.cssFloat,checkOn:!!s.value,optSelected:a.selected,enctype:!!V.createElement("form").enctype,html5Clone:"<:nav></:nav>"!==V.createElement("nav").cloneNode(!0).outerHTML,boxModel:"CSS1Compat"===V.compatMode,deleteExpando:!0,noCloneEvent:!0,inlineBlockNeedsLayout:!1,shrinkWrapBlocks:!1,reliableMarginRight:!0,boxSizingReliable:!0,pixelPosition:!1},s.checked=!0,n.noCloneChecked=s.cloneNode(!0).checked,o.disabled=!0,n.optDisabled=!a.disabled;try{delete p.test}catch(d){n.deleteExpando=!1}s=V.createElement("input"),s.setAttribute("value",""),n.input=""===s.getAttribute("value"),s.value="t",s.setAttribute("type","radio"),n.radioValue="t"===s.value,s.setAttribute("checked","t"),s.setAttribute("name","t"),u=V.createDocumentFragment(),u.appendChild(s),n.appendChecked=s.checked,n.checkClone=u.cloneNode(!0).cloneNode(!0).lastChild.checked,p.attachEvent&&(p.attachEvent("onclick",function(){n.noCloneEvent=!1}),p.cloneNode(!0).click());for(f in{submit:!0,change:!0,focusin:!0})p.setAttribute(l="on"+f,"t"),n[f+"Bubbles"]=l in e||p.attributes[l].expando===!1;return p.style.backgroundClip="content-box",p.cloneNode(!0).style.backgroundClip="",n.clearCloneStyle="content-box"===p.style.backgroundClip,st(function(){var r,i,o,a="padding:0;margin:0;border:0;display:block;box-sizing:content-box;-moz-box-sizing:content-box;-webkit-box-sizing:content-box;",s=V.getElementsByTagName("body")[0];s&&(r=V.createElement("div"),r.style.cssText="border:0;width:0;height:0;position:absolute;top:0;left:-9999px;margin-top:1px",s.appendChild(r).appendChild(p),p.innerHTML="<table><tr><td></td><td>t</td></tr></table>",o=p.getElementsByTagName("td"),o[0].style.cssText="padding:0;margin:0;border:0;display:none",c=0===o[0].offsetHeight,o[0].style.display="",o[1].style.display="none",n.reliableHiddenOffsets=c&&0===o[0].offsetHeight,p.innerHTML="",p.style.cssText="box-sizing:border-box;-moz-box-sizing:border-box;-webkit-box-sizing:border-box;padding:1px;border:1px;display:block;width:4px;margin-top:1%;position:absolute;top:1%;",n.boxSizing=4===p.offsetWidth,n.doesNotIncludeMarginInBodyOffset=1!==s.offsetTop,e.getComputedStyle&&(n.pixelPosition="1%"!==(e.getComputedStyle(p,null)||{}).top,n.boxSizingReliable="4px"===(e.getComputedStyle(p,null)||{width:"4px"}).width,i=p.appendChild(V.createElement("div")),i.style.cssText=p.style.cssText=a,i.style.marginRight=i.style.width="0",p.style.width="1px",n.reliableMarginRight=!parseFloat((e.getComputedStyle(i,null)||{}).marginRight)),p.style.zoom!==t&&(p.innerHTML="",p.style.cssText=a+"width:1px;padding:1px;display:inline;zoom:1",n.inlineBlockNeedsLayout=3===p.offsetWidth,p.style.display="block",p.innerHTML="<div></div>",p.firstChild.style.width="5px",n.shrinkWrapBlocks=3!==p.offsetWidth,s.style.zoom=1),s.removeChild(r),r=p=o=i=null)}),r=o=u=a=i=s=null,n}();var wt=/(?:\{[\s\S]*\}|\[[\s\S]*\])$/,Nt=/([A-Z])/g;st.extend({cache:{},expando:"jQuery"+(Z+Math.random()).replace(/\D/g,""),noData:{embed:!0,object:"clsid:D27CDB6E-AE6D-11cf-96B8-444553540000",applet:!0},hasData:function(e){return e=e.nodeType?st.cache[e[st.expando]]:e[st.expando],!!e&&!s(e)},data:function(e,t,n){return i(e,t,n,!1)},removeData:function(e,t){return o(e,t,!1)},_data:function(e,t,n){return i(e,t,n,!0)},_removeData:function(e,t){return o(e,t,!0)},acceptData:function(e){var t=e.nodeName&&st.noData[e.nodeName.toLowerCase()];return!t||t!==!0&&e.getAttribute("classid")===t}}),st.fn.extend({data:function(e,n){var r,i,o=this[0],s=0,u=null;if(e===t){if(this.length&&(u=st.data(o),1===o.nodeType&&!st._data(o,"parsedAttrs"))){for(r=o.attributes;r.length>s;s++)i=r[s].name,i.indexOf("data-")||(i=st.camelCase(i.substring(5)),a(o,i,u[i]));st._data(o,"parsedAttrs",!0)}return u}return"object"==typeof e?this.each(function(){st.data(this,e)}):st.access(this,function(n){return n===t?o?a(o,e,st.data(o,e)):null:(this.each(function(){st.data(this,e,n)}),t)},null,n,arguments.length>1,null,!0)},removeData:function(e){return this.each(function(){st.removeData(this,e)})}}),st.extend({queue:function(e,n,r){var i;return e?(n=(n||"fx")+"queue",i=st._data(e,n),r&&(!i||st.isArray(r)?i=st._data(e,n,st.makeArray(r)):i.push(r)),i||[]):t},dequeue:function(e,t){t=t||"fx";var n=st.queue(e,t),r=n.length,i=n.shift(),o=st._queueHooks(e,t),a=function(){st.dequeue(e,t)};"inprogress"===i&&(i=n.shift(),r--),o.cur=i,i&&("fx"===t&&n.unshift("inprogress"),delete o.stop,i.call(e,a,o)),!r&&o&&o.empty.fire()},_queueHooks:function(e,t){var n=t+"queueHooks";return st._data(e,n)||st._data(e,n,{empty:st.Callbacks("once memory").add(function(){st._removeData(e,t+"queue"),st._removeData(e,n)})})}}),st.fn.extend({queue:function(e,n){var r=2;return"string"!=typeof e&&(n=e,e="fx",r--),r>arguments.length?st.queue(this[0],e):n===t?this:this.each(function(){var t=st.queue(this,e,n);st._queueHooks(this,e),"fx"===e&&"inprogress"!==t[0]&&st.dequeue(this,e)})},dequeue:function(e){return this.each(function(){st.dequeue(this,e)})},delay:function(e,t){return e=st.fx?st.fx.speeds[e]||e:e,t=t||"fx",this.queue(t,function(t,n){var r=setTimeout(t,e);n.stop=function(){clearTimeout(r)}})},clearQueue:function(e){return this.queue(e||"fx",[])},promise:function(e,n){var r,i=1,o=st.Deferred(),a=this,s=this.length,u=function(){--i||o.resolveWith(a,[a])};for("string"!=typeof e&&(n=e,e=t),e=e||"fx";s--;)r=st._data(a[s],e+"queueHooks"),r&&r.empty&&(i++,r.empty.add(u));return u(),o.promise(n)}});var Ct,kt,Et=/[\t\r\n]/g,St=/\r/g,At=/^(?:input|select|textarea|button|object)$/i,jt=/^(?:a|area)$/i,Dt=/^(?:checked|selected|autofocus|autoplay|async|controls|defer|disabled|hidden|loop|multiple|open|readonly|required|scoped)$/i,Lt=/^(?:checked|selected)$/i,Ht=st.support.getSetAttribute,Mt=st.support.input;st.fn.extend({attr:function(e,t){return st.access(this,st.attr,e,t,arguments.length>1)},removeAttr:function(e){return this.each(function(){st.removeAttr(this,e)})},prop:function(e,t){return st.access(this,st.prop,e,t,arguments.length>1)},removeProp:function(e){return e=st.propFix[e]||e,this.each(function(){try{this[e]=t,delete this[e]}catch(n){}})},addClass:function(e){var t,n,r,i,o,a=0,s=this.length,u="string"==typeof e&&e;if(st.isFunction(e))return this.each(function(t){st(this).addClass(e.call(this,t,this.className))});if(u)for(t=(e||"").match(lt)||[];s>a;a++)if(n=this[a],r=1===n.nodeType&&(n.className?(" "+n.className+" ").replace(Et," "):" ")){for(o=0;i=t[o++];)0>r.indexOf(" "+i+" ")&&(r+=i+" ");n.className=st.trim(r)}return this},removeClass:function(e){var t,n,r,i,o,a=0,s=this.length,u=0===arguments.length||"string"==typeof e&&e;if(st.isFunction(e))return this.each(function(t){st(this).removeClass(e.call(this,t,this.className))});if(u)for(t=(e||"").match(lt)||[];s>a;a++)if(n=this[a],r=1===n.nodeType&&(n.className?(" "+n.className+" ").replace(Et," "):"")){for(o=0;i=t[o++];)for(;r.indexOf(" "+i+" ")>=0;)r=r.replace(" "+i+" "," ");n.className=e?st.trim(r):""}return this},toggleClass:function(e,t){var n=typeof e,r="boolean"==typeof t;return st.isFunction(e)?this.each(function(n){st(this).toggleClass(e.call(this,n,this.className,t),t)}):this.each(function(){if("string"===n)for(var i,o=0,a=st(this),s=t,u=e.match(lt)||[];i=u[o++];)s=r?s:!a.hasClass(i),a[s?"addClass":"removeClass"](i);else("undefined"===n||"boolean"===n)&&(this.className&&st._data(this,"__className__",this.className),this.className=this.className||e===!1?"":st._data(this,"__className__")||"")})},hasClass:function(e){for(var t=" "+e+" ",n=0,r=this.length;r>n;n++)if(1===this[n].nodeType&&(" "+this[n].className+" ").replace(Et," ").indexOf(t)>=0)return!0;return!1},val:function(e){var n,r,i,o=this[0];{if(arguments.length)return i=st.isFunction(e),this.each(function(r){var o,a=st(this);1===this.nodeType&&(o=i?e.call(this,r,a.val()):e,null==o?o="":"number"==typeof o?o+="":st.isArray(o)&&(o=st.map(o,function(e){return null==e?"":e+""})),n=st.valHooks[this.type]||st.valHooks[this.nodeName.toLowerCase()],n&&"set"in n&&n.set(this,o,"value")!==t||(this.value=o))});if(o)return n=st.valHooks[o.type]||st.valHooks[o.nodeName.toLowerCase()],n&&"get"in n&&(r=n.get(o,"value"))!==t?r:(r=o.value,"string"==typeof r?r.replace(St,""):null==r?"":r)}}}),st.extend({valHooks:{option:{get:function(e){var t=e.attributes.value;return!t||t.specified?e.value:e.text}},select:{get:function(e){for(var t,n,r=e.options,i=e.selectedIndex,o="select-one"===e.type||0>i,a=o?null:[],s=o?i+1:r.length,u=0>i?s:o?i:0;s>u;u++)if(n=r[u],!(!n.selected&&u!==i||(st.support.optDisabled?n.disabled:null!==n.getAttribute("disabled"))||n.parentNode.disabled&&st.nodeName(n.parentNode,"optgroup"))){if(t=st(n).val(),o)return t;a.push(t)}return a},set:function(e,t){var n=st.makeArray(t);return st(e).find("option").each(function(){this.selected=st.inArray(st(this).val(),n)>=0}),n.length||(e.selectedIndex=-1),n}}},attr:function(e,n,r){var i,o,a,s=e.nodeType;if(e&&3!==s&&8!==s&&2!==s)return e.getAttribute===t?st.prop(e,n,r):(a=1!==s||!st.isXMLDoc(e),a&&(n=n.toLowerCase(),o=st.attrHooks[n]||(Dt.test(n)?kt:Ct)),r===t?o&&a&&"get"in o&&null!==(i=o.get(e,n))?i:(e.getAttribute!==t&&(i=e.getAttribute(n)),null==i?t:i):null!==r?o&&a&&"set"in o&&(i=o.set(e,r,n))!==t?i:(e.setAttribute(n,r+""),r):(st.removeAttr(e,n),t))},removeAttr:function(e,t){var n,r,i=0,o=t&&t.match(lt);if(o&&1===e.nodeType)for(;n=o[i++];)r=st.propFix[n]||n,Dt.test(n)?!Ht&&Lt.test(n)?e[st.camelCase("default-"+n)]=e[r]=!1:e[r]=!1:st.attr(e,n,""),e.removeAttribute(Ht?n:r)},attrHooks:{type:{set:function(e,t){if(!st.support.radioValue&&"radio"===t&&st.nodeName(e,"input")){var n=e.value;return e.setAttribute("type",t),n&&(e.value=n),t}}}},propFix:{tabindex:"tabIndex",readonly:"readOnly","for":"htmlFor","class":"className",maxlength:"maxLength",cellspacing:"cellSpacing",cellpadding:"cellPadding",rowspan:"rowSpan",colspan:"colSpan",usemap:"useMap",frameborder:"frameBorder",contenteditable:"contentEditable"},prop:function(e,n,r){var i,o,a,s=e.nodeType;if(e&&3!==s&&8!==s&&2!==s)return a=1!==s||!st.isXMLDoc(e),a&&(n=st.propFix[n]||n,o=st.propHooks[n]),r!==t?o&&"set"in o&&(i=o.set(e,r,n))!==t?i:e[n]=r:o&&"get"in o&&null!==(i=o.get(e,n))?i:e[n]},propHooks:{tabIndex:{get:function(e){var n=e.getAttributeNode("tabindex");return n&&n.specified?parseInt(n.value,10):At.test(e.nodeName)||jt.test(e.nodeName)&&e.href?0:t}}}}),kt={get:function(e,n){var r=st.prop(e,n),i="boolean"==typeof r&&e.getAttribute(n),o="boolean"==typeof r?Mt&&Ht?null!=i:Lt.test(n)?e[st.camelCase("default-"+n)]:!!i:e.getAttributeNode(n);return o&&o.value!==!1?n.toLowerCase():t},set:function(e,t,n){return t===!1?st.removeAttr(e,n):Mt&&Ht||!Lt.test(n)?e.setAttribute(!Ht&&st.propFix[n]||n,n):e[st.camelCase("default-"+n)]=e[n]=!0,n}},Mt&&Ht||(st.attrHooks.value={get:function(e,n){var r=e.getAttributeNode(n);return st.nodeName(e,"input")?e.defaultValue:r&&r.specified?r.value:t
},set:function(e,n,r){return st.nodeName(e,"input")?(e.defaultValue=n,t):Ct&&Ct.set(e,n,r)}}),Ht||(Ct=st.valHooks.button={get:function(e,n){var r=e.getAttributeNode(n);return r&&("id"===n||"name"===n||"coords"===n?""!==r.value:r.specified)?r.value:t},set:function(e,n,r){var i=e.getAttributeNode(r);return i||e.setAttributeNode(i=e.ownerDocument.createAttribute(r)),i.value=n+="","value"===r||n===e.getAttribute(r)?n:t}},st.attrHooks.contenteditable={get:Ct.get,set:function(e,t,n){Ct.set(e,""===t?!1:t,n)}},st.each(["width","height"],function(e,n){st.attrHooks[n]=st.extend(st.attrHooks[n],{set:function(e,r){return""===r?(e.setAttribute(n,"auto"),r):t}})})),st.support.hrefNormalized||(st.each(["href","src","width","height"],function(e,n){st.attrHooks[n]=st.extend(st.attrHooks[n],{get:function(e){var r=e.getAttribute(n,2);return null==r?t:r}})}),st.each(["href","src"],function(e,t){st.propHooks[t]={get:function(e){return e.getAttribute(t,4)}}})),st.support.style||(st.attrHooks.style={get:function(e){return e.style.cssText||t},set:function(e,t){return e.style.cssText=t+""}}),st.support.optSelected||(st.propHooks.selected=st.extend(st.propHooks.selected,{get:function(e){var t=e.parentNode;return t&&(t.selectedIndex,t.parentNode&&t.parentNode.selectedIndex),null}})),st.support.enctype||(st.propFix.enctype="encoding"),st.support.checkOn||st.each(["radio","checkbox"],function(){st.valHooks[this]={get:function(e){return null===e.getAttribute("value")?"on":e.value}}}),st.each(["radio","checkbox"],function(){st.valHooks[this]=st.extend(st.valHooks[this],{set:function(e,n){return st.isArray(n)?e.checked=st.inArray(st(e).val(),n)>=0:t}})});var qt=/^(?:input|select|textarea)$/i,_t=/^key/,Ft=/^(?:mouse|contextmenu)|click/,Ot=/^(?:focusinfocus|focusoutblur)$/,Bt=/^([^.]*)(?:\.(.+)|)$/;st.event={global:{},add:function(e,n,r,i,o){var a,s,u,l,c,f,p,d,h,g,m,y=3!==e.nodeType&&8!==e.nodeType&&st._data(e);if(y){for(r.handler&&(a=r,r=a.handler,o=a.selector),r.guid||(r.guid=st.guid++),(l=y.events)||(l=y.events={}),(s=y.handle)||(s=y.handle=function(e){return st===t||e&&st.event.triggered===e.type?t:st.event.dispatch.apply(s.elem,arguments)},s.elem=e),n=(n||"").match(lt)||[""],c=n.length;c--;)u=Bt.exec(n[c])||[],h=m=u[1],g=(u[2]||"").split(".").sort(),p=st.event.special[h]||{},h=(o?p.delegateType:p.bindType)||h,p=st.event.special[h]||{},f=st.extend({type:h,origType:m,data:i,handler:r,guid:r.guid,selector:o,needsContext:o&&st.expr.match.needsContext.test(o),namespace:g.join(".")},a),(d=l[h])||(d=l[h]=[],d.delegateCount=0,p.setup&&p.setup.call(e,i,g,s)!==!1||(e.addEventListener?e.addEventListener(h,s,!1):e.attachEvent&&e.attachEvent("on"+h,s))),p.add&&(p.add.call(e,f),f.handler.guid||(f.handler.guid=r.guid)),o?d.splice(d.delegateCount++,0,f):d.push(f),st.event.global[h]=!0;e=null}},remove:function(e,t,n,r,i){var o,a,s,u,l,c,f,p,d,h,g,m=st.hasData(e)&&st._data(e);if(m&&(u=m.events)){for(t=(t||"").match(lt)||[""],l=t.length;l--;)if(s=Bt.exec(t[l])||[],d=g=s[1],h=(s[2]||"").split(".").sort(),d){for(f=st.event.special[d]||{},d=(r?f.delegateType:f.bindType)||d,p=u[d]||[],s=s[2]&&RegExp("(^|\\.)"+h.join("\\.(?:.*\\.|)")+"(\\.|$)"),a=o=p.length;o--;)c=p[o],!i&&g!==c.origType||n&&n.guid!==c.guid||s&&!s.test(c.namespace)||r&&r!==c.selector&&("**"!==r||!c.selector)||(p.splice(o,1),c.selector&&p.delegateCount--,f.remove&&f.remove.call(e,c));a&&!p.length&&(f.teardown&&f.teardown.call(e,h,m.handle)!==!1||st.removeEvent(e,d,m.handle),delete u[d])}else for(d in u)st.event.remove(e,d+t[l],n,r,!0);st.isEmptyObject(u)&&(delete m.handle,st._removeData(e,"events"))}},trigger:function(n,r,i,o){var a,s,u,l,c,f,p,d=[i||V],h=n.type||n,g=n.namespace?n.namespace.split("."):[];if(s=u=i=i||V,3!==i.nodeType&&8!==i.nodeType&&!Ot.test(h+st.event.triggered)&&(h.indexOf(".")>=0&&(g=h.split("."),h=g.shift(),g.sort()),c=0>h.indexOf(":")&&"on"+h,n=n[st.expando]?n:new st.Event(h,"object"==typeof n&&n),n.isTrigger=!0,n.namespace=g.join("."),n.namespace_re=n.namespace?RegExp("(^|\\.)"+g.join("\\.(?:.*\\.|)")+"(\\.|$)"):null,n.result=t,n.target||(n.target=i),r=null==r?[n]:st.makeArray(r,[n]),p=st.event.special[h]||{},o||!p.trigger||p.trigger.apply(i,r)!==!1)){if(!o&&!p.noBubble&&!st.isWindow(i)){for(l=p.delegateType||h,Ot.test(l+h)||(s=s.parentNode);s;s=s.parentNode)d.push(s),u=s;u===(i.ownerDocument||V)&&d.push(u.defaultView||u.parentWindow||e)}for(a=0;(s=d[a++])&&!n.isPropagationStopped();)n.type=a>1?l:p.bindType||h,f=(st._data(s,"events")||{})[n.type]&&st._data(s,"handle"),f&&f.apply(s,r),f=c&&s[c],f&&st.acceptData(s)&&f.apply&&f.apply(s,r)===!1&&n.preventDefault();if(n.type=h,!(o||n.isDefaultPrevented()||p._default&&p._default.apply(i.ownerDocument,r)!==!1||"click"===h&&st.nodeName(i,"a")||!st.acceptData(i)||!c||!i[h]||st.isWindow(i))){u=i[c],u&&(i[c]=null),st.event.triggered=h;try{i[h]()}catch(m){}st.event.triggered=t,u&&(i[c]=u)}return n.result}},dispatch:function(e){e=st.event.fix(e);var n,r,i,o,a,s=[],u=nt.call(arguments),l=(st._data(this,"events")||{})[e.type]||[],c=st.event.special[e.type]||{};if(u[0]=e,e.delegateTarget=this,!c.preDispatch||c.preDispatch.call(this,e)!==!1){for(s=st.event.handlers.call(this,e,l),n=0;(o=s[n++])&&!e.isPropagationStopped();)for(e.currentTarget=o.elem,r=0;(a=o.handlers[r++])&&!e.isImmediatePropagationStopped();)(!e.namespace_re||e.namespace_re.test(a.namespace))&&(e.handleObj=a,e.data=a.data,i=((st.event.special[a.origType]||{}).handle||a.handler).apply(o.elem,u),i!==t&&(e.result=i)===!1&&(e.preventDefault(),e.stopPropagation()));return c.postDispatch&&c.postDispatch.call(this,e),e.result}},handlers:function(e,n){var r,i,o,a,s=[],u=n.delegateCount,l=e.target;if(u&&l.nodeType&&(!e.button||"click"!==e.type))for(;l!=this;l=l.parentNode||this)if(l.disabled!==!0||"click"!==e.type){for(i=[],r=0;u>r;r++)a=n[r],o=a.selector+" ",i[o]===t&&(i[o]=a.needsContext?st(o,this).index(l)>=0:st.find(o,this,null,[l]).length),i[o]&&i.push(a);i.length&&s.push({elem:l,handlers:i})}return n.length>u&&s.push({elem:this,handlers:n.slice(u)}),s},fix:function(e){if(e[st.expando])return e;var t,n,r=e,i=st.event.fixHooks[e.type]||{},o=i.props?this.props.concat(i.props):this.props;for(e=new st.Event(r),t=o.length;t--;)n=o[t],e[n]=r[n];return e.target||(e.target=r.srcElement||V),3===e.target.nodeType&&(e.target=e.target.parentNode),e.metaKey=!!e.metaKey,i.filter?i.filter(e,r):e},props:"altKey bubbles cancelable ctrlKey currentTarget eventPhase metaKey relatedTarget shiftKey target timeStamp view which".split(" "),fixHooks:{},keyHooks:{props:"char charCode key keyCode".split(" "),filter:function(e,t){return null==e.which&&(e.which=null!=t.charCode?t.charCode:t.keyCode),e}},mouseHooks:{props:"button buttons clientX clientY fromElement offsetX offsetY pageX pageY screenX screenY toElement".split(" "),filter:function(e,n){var r,i,o,a=n.button,s=n.fromElement;return null==e.pageX&&null!=n.clientX&&(r=e.target.ownerDocument||V,i=r.documentElement,o=r.body,e.pageX=n.clientX+(i&&i.scrollLeft||o&&o.scrollLeft||0)-(i&&i.clientLeft||o&&o.clientLeft||0),e.pageY=n.clientY+(i&&i.scrollTop||o&&o.scrollTop||0)-(i&&i.clientTop||o&&o.clientTop||0)),!e.relatedTarget&&s&&(e.relatedTarget=s===e.target?n.toElement:s),e.which||a===t||(e.which=1&a?1:2&a?3:4&a?2:0),e}},special:{load:{noBubble:!0},click:{trigger:function(){return st.nodeName(this,"input")&&"checkbox"===this.type&&this.click?(this.click(),!1):t}},focus:{trigger:function(){if(this!==V.activeElement&&this.focus)try{return this.focus(),!1}catch(e){}},delegateType:"focusin"},blur:{trigger:function(){return this===V.activeElement&&this.blur?(this.blur(),!1):t},delegateType:"focusout"},beforeunload:{postDispatch:function(e){e.result!==t&&(e.originalEvent.returnValue=e.result)}}},simulate:function(e,t,n,r){var i=st.extend(new st.Event,n,{type:e,isSimulated:!0,originalEvent:{}});r?st.event.trigger(i,null,t):st.event.dispatch.call(t,i),i.isDefaultPrevented()&&n.preventDefault()}},st.removeEvent=V.removeEventListener?function(e,t,n){e.removeEventListener&&e.removeEventListener(t,n,!1)}:function(e,n,r){var i="on"+n;e.detachEvent&&(e[i]===t&&(e[i]=null),e.detachEvent(i,r))},st.Event=function(e,n){return this instanceof st.Event?(e&&e.type?(this.originalEvent=e,this.type=e.type,this.isDefaultPrevented=e.defaultPrevented||e.returnValue===!1||e.getPreventDefault&&e.getPreventDefault()?u:l):this.type=e,n&&st.extend(this,n),this.timeStamp=e&&e.timeStamp||st.now(),this[st.expando]=!0,t):new st.Event(e,n)},st.Event.prototype={isDefaultPrevented:l,isPropagationStopped:l,isImmediatePropagationStopped:l,preventDefault:function(){var e=this.originalEvent;this.isDefaultPrevented=u,e&&(e.preventDefault?e.preventDefault():e.returnValue=!1)},stopPropagation:function(){var e=this.originalEvent;this.isPropagationStopped=u,e&&(e.stopPropagation&&e.stopPropagation(),e.cancelBubble=!0)},stopImmediatePropagation:function(){this.isImmediatePropagationStopped=u,this.stopPropagation()}},st.each({mouseenter:"mouseover",mouseleave:"mouseout"},function(e,t){st.event.special[e]={delegateType:t,bindType:t,handle:function(e){var n,r=this,i=e.relatedTarget,o=e.handleObj;return(!i||i!==r&&!st.contains(r,i))&&(e.type=o.origType,n=o.handler.apply(this,arguments),e.type=t),n}}}),st.support.submitBubbles||(st.event.special.submit={setup:function(){return st.nodeName(this,"form")?!1:(st.event.add(this,"click._submit keypress._submit",function(e){var n=e.target,r=st.nodeName(n,"input")||st.nodeName(n,"button")?n.form:t;r&&!st._data(r,"submitBubbles")&&(st.event.add(r,"submit._submit",function(e){e._submit_bubble=!0}),st._data(r,"submitBubbles",!0))}),t)},postDispatch:function(e){e._submit_bubble&&(delete e._submit_bubble,this.parentNode&&!e.isTrigger&&st.event.simulate("submit",this.parentNode,e,!0))},teardown:function(){return st.nodeName(this,"form")?!1:(st.event.remove(this,"._submit"),t)}}),st.support.changeBubbles||(st.event.special.change={setup:function(){return qt.test(this.nodeName)?(("checkbox"===this.type||"radio"===this.type)&&(st.event.add(this,"propertychange._change",function(e){"checked"===e.originalEvent.propertyName&&(this._just_changed=!0)}),st.event.add(this,"click._change",function(e){this._just_changed&&!e.isTrigger&&(this._just_changed=!1),st.event.simulate("change",this,e,!0)})),!1):(st.event.add(this,"beforeactivate._change",function(e){var t=e.target;qt.test(t.nodeName)&&!st._data(t,"changeBubbles")&&(st.event.add(t,"change._change",function(e){!this.parentNode||e.isSimulated||e.isTrigger||st.event.simulate("change",this.parentNode,e,!0)}),st._data(t,"changeBubbles",!0))}),t)},handle:function(e){var n=e.target;return this!==n||e.isSimulated||e.isTrigger||"radio"!==n.type&&"checkbox"!==n.type?e.handleObj.handler.apply(this,arguments):t},teardown:function(){return st.event.remove(this,"._change"),!qt.test(this.nodeName)}}),st.support.focusinBubbles||st.each({focus:"focusin",blur:"focusout"},function(e,t){var n=0,r=function(e){st.event.simulate(t,e.target,st.event.fix(e),!0)};st.event.special[t]={setup:function(){0===n++&&V.addEventListener(e,r,!0)},teardown:function(){0===--n&&V.removeEventListener(e,r,!0)}}}),st.fn.extend({on:function(e,n,r,i,o){var a,s;if("object"==typeof e){"string"!=typeof n&&(r=r||n,n=t);for(s in e)this.on(s,n,r,e[s],o);return this}if(null==r&&null==i?(i=n,r=n=t):null==i&&("string"==typeof n?(i=r,r=t):(i=r,r=n,n=t)),i===!1)i=l;else if(!i)return this;return 1===o&&(a=i,i=function(e){return st().off(e),a.apply(this,arguments)},i.guid=a.guid||(a.guid=st.guid++)),this.each(function(){st.event.add(this,e,i,r,n)})},one:function(e,t,n,r){return this.on(e,t,n,r,1)},off:function(e,n,r){var i,o;if(e&&e.preventDefault&&e.handleObj)return i=e.handleObj,st(e.delegateTarget).off(i.namespace?i.origType+"."+i.namespace:i.origType,i.selector,i.handler),this;if("object"==typeof e){for(o in e)this.off(o,n,e[o]);return this}return(n===!1||"function"==typeof n)&&(r=n,n=t),r===!1&&(r=l),this.each(function(){st.event.remove(this,e,r,n)})},bind:function(e,t,n){return this.on(e,null,t,n)},unbind:function(e,t){return this.off(e,null,t)},delegate:function(e,t,n,r){return this.on(t,e,n,r)},undelegate:function(e,t,n){return 1===arguments.length?this.off(e,"**"):this.off(t,e||"**",n)},trigger:function(e,t){return this.each(function(){st.event.trigger(e,t,this)})},triggerHandler:function(e,n){var r=this[0];return r?st.event.trigger(e,n,r,!0):t},hover:function(e,t){return this.mouseenter(e).mouseleave(t||e)}}),st.each("blur focus focusin focusout load resize scroll unload click dblclick mousedown mouseup mousemove mouseover mouseout mouseenter mouseleave change select submit keydown keypress keyup error contextmenu".split(" "),function(e,t){st.fn[t]=function(e,n){return arguments.length>0?this.on(t,null,e,n):this.trigger(t)},_t.test(t)&&(st.event.fixHooks[t]=st.event.keyHooks),Ft.test(t)&&(st.event.fixHooks[t]=st.event.mouseHooks)}),function(e,t){function n(e){return ht.test(e+"")}function r(){var e,t=[];return e=function(n,r){return t.push(n+=" ")>C.cacheLength&&delete e[t.shift()],e[n]=r}}function i(e){return e[P]=!0,e}function o(e){var t=L.createElement("div");try{return e(t)}catch(n){return!1}finally{t=null}}function a(e,t,n,r){var i,o,a,s,u,l,c,d,h,g;if((t?t.ownerDocument||t:R)!==L&&D(t),t=t||L,n=n||[],!e||"string"!=typeof e)return n;if(1!==(s=t.nodeType)&&9!==s)return[];if(!M&&!r){if(i=gt.exec(e))if(a=i[1]){if(9===s){if(o=t.getElementById(a),!o||!o.parentNode)return n;if(o.id===a)return n.push(o),n}else if(t.ownerDocument&&(o=t.ownerDocument.getElementById(a))&&O(t,o)&&o.id===a)return n.push(o),n}else{if(i[2])return Q.apply(n,K.call(t.getElementsByTagName(e),0)),n;if((a=i[3])&&W.getByClassName&&t.getElementsByClassName)return Q.apply(n,K.call(t.getElementsByClassName(a),0)),n}if(W.qsa&&!q.test(e)){if(c=!0,d=P,h=t,g=9===s&&e,1===s&&"object"!==t.nodeName.toLowerCase()){for(l=f(e),(c=t.getAttribute("id"))?d=c.replace(vt,"\\$&"):t.setAttribute("id",d),d="[id='"+d+"'] ",u=l.length;u--;)l[u]=d+p(l[u]);h=dt.test(e)&&t.parentNode||t,g=l.join(",")}if(g)try{return Q.apply(n,K.call(h.querySelectorAll(g),0)),n}catch(m){}finally{c||t.removeAttribute("id")}}}return x(e.replace(at,"$1"),t,n,r)}function s(e,t){for(var n=e&&t&&e.nextSibling;n;n=n.nextSibling)if(n===t)return-1;return e?1:-1}function u(e){return function(t){var n=t.nodeName.toLowerCase();return"input"===n&&t.type===e}}function l(e){return function(t){var n=t.nodeName.toLowerCase();return("input"===n||"button"===n)&&t.type===e}}function c(e){return i(function(t){return t=+t,i(function(n,r){for(var i,o=e([],n.length,t),a=o.length;a--;)n[i=o[a]]&&(n[i]=!(r[i]=n[i]))})})}function f(e,t){var n,r,i,o,s,u,l,c=X[e+" "];if(c)return t?0:c.slice(0);for(s=e,u=[],l=C.preFilter;s;){(!n||(r=ut.exec(s)))&&(r&&(s=s.slice(r[0].length)||s),u.push(i=[])),n=!1,(r=lt.exec(s))&&(n=r.shift(),i.push({value:n,type:r[0].replace(at," ")}),s=s.slice(n.length));for(o in C.filter)!(r=pt[o].exec(s))||l[o]&&!(r=l[o](r))||(n=r.shift(),i.push({value:n,type:o,matches:r}),s=s.slice(n.length));if(!n)break}return t?s.length:s?a.error(e):X(e,u).slice(0)}function p(e){for(var t=0,n=e.length,r="";n>t;t++)r+=e[t].value;return r}function d(e,t,n){var r=t.dir,i=n&&"parentNode"===t.dir,o=I++;return t.first?function(t,n,o){for(;t=t[r];)if(1===t.nodeType||i)return e(t,n,o)}:function(t,n,a){var s,u,l,c=$+" "+o;if(a){for(;t=t[r];)if((1===t.nodeType||i)&&e(t,n,a))return!0}else for(;t=t[r];)if(1===t.nodeType||i)if(l=t[P]||(t[P]={}),(u=l[r])&&u[0]===c){if((s=u[1])===!0||s===N)return s===!0}else if(u=l[r]=[c],u[1]=e(t,n,a)||N,u[1]===!0)return!0}}function h(e){return e.length>1?function(t,n,r){for(var i=e.length;i--;)if(!e[i](t,n,r))return!1;return!0}:e[0]}function g(e,t,n,r,i){for(var o,a=[],s=0,u=e.length,l=null!=t;u>s;s++)(o=e[s])&&(!n||n(o,r,i))&&(a.push(o),l&&t.push(s));return a}function m(e,t,n,r,o,a){return r&&!r[P]&&(r=m(r)),o&&!o[P]&&(o=m(o,a)),i(function(i,a,s,u){var l,c,f,p=[],d=[],h=a.length,m=i||b(t||"*",s.nodeType?[s]:s,[]),y=!e||!i&&t?m:g(m,p,e,s,u),v=n?o||(i?e:h||r)?[]:a:y;if(n&&n(y,v,s,u),r)for(l=g(v,d),r(l,[],s,u),c=l.length;c--;)(f=l[c])&&(v[d[c]]=!(y[d[c]]=f));if(i){if(o||e){if(o){for(l=[],c=v.length;c--;)(f=v[c])&&l.push(y[c]=f);o(null,v=[],l,u)}for(c=v.length;c--;)(f=v[c])&&(l=o?Z.call(i,f):p[c])>-1&&(i[l]=!(a[l]=f))}}else v=g(v===a?v.splice(h,v.length):v),o?o(null,a,v,u):Q.apply(a,v)})}function y(e){for(var t,n,r,i=e.length,o=C.relative[e[0].type],a=o||C.relative[" "],s=o?1:0,u=d(function(e){return e===t},a,!0),l=d(function(e){return Z.call(t,e)>-1},a,!0),c=[function(e,n,r){return!o&&(r||n!==j)||((t=n).nodeType?u(e,n,r):l(e,n,r))}];i>s;s++)if(n=C.relative[e[s].type])c=[d(h(c),n)];else{if(n=C.filter[e[s].type].apply(null,e[s].matches),n[P]){for(r=++s;i>r&&!C.relative[e[r].type];r++);return m(s>1&&h(c),s>1&&p(e.slice(0,s-1)).replace(at,"$1"),n,r>s&&y(e.slice(s,r)),i>r&&y(e=e.slice(r)),i>r&&p(e))}c.push(n)}return h(c)}function v(e,t){var n=0,r=t.length>0,o=e.length>0,s=function(i,s,u,l,c){var f,p,d,h=[],m=0,y="0",v=i&&[],b=null!=c,x=j,T=i||o&&C.find.TAG("*",c&&s.parentNode||s),w=$+=null==x?1:Math.E;for(b&&(j=s!==L&&s,N=n);null!=(f=T[y]);y++){if(o&&f){for(p=0;d=e[p];p++)if(d(f,s,u)){l.push(f);break}b&&($=w,N=++n)}r&&((f=!d&&f)&&m--,i&&v.push(f))}if(m+=y,r&&y!==m){for(p=0;d=t[p];p++)d(v,h,s,u);if(i){if(m>0)for(;y--;)v[y]||h[y]||(h[y]=G.call(l));h=g(h)}Q.apply(l,h),b&&!i&&h.length>0&&m+t.length>1&&a.uniqueSort(l)}return b&&($=w,j=x),v};return r?i(s):s}function b(e,t,n){for(var r=0,i=t.length;i>r;r++)a(e,t[r],n);return n}function x(e,t,n,r){var i,o,a,s,u,l=f(e);if(!r&&1===l.length){if(o=l[0]=l[0].slice(0),o.length>2&&"ID"===(a=o[0]).type&&9===t.nodeType&&!M&&C.relative[o[1].type]){if(t=C.find.ID(a.matches[0].replace(xt,Tt),t)[0],!t)return n;e=e.slice(o.shift().value.length)}for(i=pt.needsContext.test(e)?-1:o.length-1;i>=0&&(a=o[i],!C.relative[s=a.type]);i--)if((u=C.find[s])&&(r=u(a.matches[0].replace(xt,Tt),dt.test(o[0].type)&&t.parentNode||t))){if(o.splice(i,1),e=r.length&&p(o),!e)return Q.apply(n,K.call(r,0)),n;break}}return S(e,l)(r,t,M,n,dt.test(e)),n}function T(){}var w,N,C,k,E,S,A,j,D,L,H,M,q,_,F,O,B,P="sizzle"+-new Date,R=e.document,W={},$=0,I=0,z=r(),X=r(),U=r(),V=typeof t,Y=1<<31,J=[],G=J.pop,Q=J.push,K=J.slice,Z=J.indexOf||function(e){for(var t=0,n=this.length;n>t;t++)if(this[t]===e)return t;return-1},et="[\\x20\\t\\r\\n\\f]",tt="(?:\\\\.|[\\w-]|[^\\x00-\\xa0])+",nt=tt.replace("w","w#"),rt="([*^$|!~]?=)",it="\\["+et+"*("+tt+")"+et+"*(?:"+rt+et+"*(?:(['\"])((?:\\\\.|[^\\\\])*?)\\3|("+nt+")|)|)"+et+"*\\]",ot=":("+tt+")(?:\\(((['\"])((?:\\\\.|[^\\\\])*?)\\3|((?:\\\\.|[^\\\\()[\\]]|"+it.replace(3,8)+")*)|.*)\\)|)",at=RegExp("^"+et+"+|((?:^|[^\\\\])(?:\\\\.)*)"+et+"+$","g"),ut=RegExp("^"+et+"*,"+et+"*"),lt=RegExp("^"+et+"*([\\x20\\t\\r\\n\\f>+~])"+et+"*"),ct=RegExp(ot),ft=RegExp("^"+nt+"$"),pt={ID:RegExp("^#("+tt+")"),CLASS:RegExp("^\\.("+tt+")"),NAME:RegExp("^\\[name=['\"]?("+tt+")['\"]?\\]"),TAG:RegExp("^("+tt.replace("w","w*")+")"),ATTR:RegExp("^"+it),PSEUDO:RegExp("^"+ot),CHILD:RegExp("^:(only|first|last|nth|nth-last)-(child|of-type)(?:\\("+et+"*(even|odd|(([+-]|)(\\d*)n|)"+et+"*(?:([+-]|)"+et+"*(\\d+)|))"+et+"*\\)|)","i"),needsContext:RegExp("^"+et+"*[>+~]|:(even|odd|eq|gt|lt|nth|first|last)(?:\\("+et+"*((?:-\\d)?\\d*)"+et+"*\\)|)(?=[^-]|$)","i")},dt=/[\x20\t\r\n\f]*[+~]/,ht=/\{\s*\[native code\]\s*\}/,gt=/^(?:#([\w-]+)|(\w+)|\.([\w-]+))$/,mt=/^(?:input|select|textarea|button)$/i,yt=/^h\d$/i,vt=/'|\\/g,bt=/\=[\x20\t\r\n\f]*([^'"\]]*)[\x20\t\r\n\f]*\]/g,xt=/\\([\da-fA-F]{1,6}[\x20\t\r\n\f]?|.)/g,Tt=function(e,t){var n="0x"+t-65536;return n!==n?t:0>n?String.fromCharCode(n+65536):String.fromCharCode(55296|n>>10,56320|1023&n)};try{K.call(H.childNodes,0)[0].nodeType}catch(wt){K=function(e){for(var t,n=[];t=this[e];e++)n.push(t);return n}}E=a.isXML=function(e){var t=e&&(e.ownerDocument||e).documentElement;return t?"HTML"!==t.nodeName:!1},D=a.setDocument=function(e){var r=e?e.ownerDocument||e:R;return r!==L&&9===r.nodeType&&r.documentElement?(L=r,H=r.documentElement,M=E(r),W.tagNameNoComments=o(function(e){return e.appendChild(r.createComment("")),!e.getElementsByTagName("*").length}),W.attributes=o(function(e){e.innerHTML="<select></select>";var t=typeof e.lastChild.getAttribute("multiple");return"boolean"!==t&&"string"!==t}),W.getByClassName=o(function(e){return e.innerHTML="<div class='hidden e'></div><div class='hidden'></div>",e.getElementsByClassName&&e.getElementsByClassName("e").length?(e.lastChild.className="e",2===e.getElementsByClassName("e").length):!1}),W.getByName=o(function(e){e.id=P+0,e.innerHTML="<a name='"+P+"'></a><div name='"+P+"'></div>",H.insertBefore(e,H.firstChild);var t=r.getElementsByName&&r.getElementsByName(P).length===2+r.getElementsByName(P+0).length;return W.getIdNotName=!r.getElementById(P),H.removeChild(e),t}),C.attrHandle=o(function(e){return e.innerHTML="<a href='#'></a>",e.firstChild&&typeof e.firstChild.getAttribute!==V&&"#"===e.firstChild.getAttribute("href")})?{}:{href:function(e){return e.getAttribute("href",2)},type:function(e){return e.getAttribute("type")}},W.getIdNotName?(C.find.ID=function(e,t){if(typeof t.getElementById!==V&&!M){var n=t.getElementById(e);return n&&n.parentNode?[n]:[]}},C.filter.ID=function(e){var t=e.replace(xt,Tt);return function(e){return e.getAttribute("id")===t}}):(C.find.ID=function(e,n){if(typeof n.getElementById!==V&&!M){var r=n.getElementById(e);return r?r.id===e||typeof r.getAttributeNode!==V&&r.getAttributeNode("id").value===e?[r]:t:[]}},C.filter.ID=function(e){var t=e.replace(xt,Tt);return function(e){var n=typeof e.getAttributeNode!==V&&e.getAttributeNode("id");return n&&n.value===t}}),C.find.TAG=W.tagNameNoComments?function(e,n){return typeof n.getElementsByTagName!==V?n.getElementsByTagName(e):t}:function(e,t){var n,r=[],i=0,o=t.getElementsByTagName(e);if("*"===e){for(;n=o[i];i++)1===n.nodeType&&r.push(n);return r}return o},C.find.NAME=W.getByName&&function(e,n){return typeof n.getElementsByName!==V?n.getElementsByName(name):t},C.find.CLASS=W.getByClassName&&function(e,n){return typeof n.getElementsByClassName===V||M?t:n.getElementsByClassName(e)},_=[],q=[":focus"],(W.qsa=n(r.querySelectorAll))&&(o(function(e){e.innerHTML="<select><option selected=''></option></select>",e.querySelectorAll("[selected]").length||q.push("\\["+et+"*(?:checked|disabled|ismap|multiple|readonly|selected|value)"),e.querySelectorAll(":checked").length||q.push(":checked")}),o(function(e){e.innerHTML="<input type='hidden' i=''/>",e.querySelectorAll("[i^='']").length&&q.push("[*^$]="+et+"*(?:\"\"|'')"),e.querySelectorAll(":enabled").length||q.push(":enabled",":disabled"),e.querySelectorAll("*,:x"),q.push(",.*:")})),(W.matchesSelector=n(F=H.matchesSelector||H.mozMatchesSelector||H.webkitMatchesSelector||H.oMatchesSelector||H.msMatchesSelector))&&o(function(e){W.disconnectedMatch=F.call(e,"div"),F.call(e,"[s!='']:x"),_.push("!=",ot)}),q=RegExp(q.join("|")),_=RegExp(_.join("|")),O=n(H.contains)||H.compareDocumentPosition?function(e,t){var n=9===e.nodeType?e.documentElement:e,r=t&&t.parentNode;return e===r||!(!r||1!==r.nodeType||!(n.contains?n.contains(r):e.compareDocumentPosition&&16&e.compareDocumentPosition(r)))}:function(e,t){if(t)for(;t=t.parentNode;)if(t===e)return!0;return!1},B=H.compareDocumentPosition?function(e,t){var n;return e===t?(A=!0,0):(n=t.compareDocumentPosition&&e.compareDocumentPosition&&e.compareDocumentPosition(t))?1&n||e.parentNode&&11===e.parentNode.nodeType?e===r||O(R,e)?-1:t===r||O(R,t)?1:0:4&n?-1:1:e.compareDocumentPosition?-1:1}:function(e,t){var n,i=0,o=e.parentNode,a=t.parentNode,u=[e],l=[t];if(e===t)return A=!0,0;if(e.sourceIndex&&t.sourceIndex)return(~t.sourceIndex||Y)-(O(R,e)&&~e.sourceIndex||Y);if(!o||!a)return e===r?-1:t===r?1:o?-1:a?1:0;if(o===a)return s(e,t);for(n=e;n=n.parentNode;)u.unshift(n);for(n=t;n=n.parentNode;)l.unshift(n);for(;u[i]===l[i];)i++;return i?s(u[i],l[i]):u[i]===R?-1:l[i]===R?1:0},A=!1,[0,0].sort(B),W.detectDuplicates=A,L):L},a.matches=function(e,t){return a(e,null,null,t)},a.matchesSelector=function(e,t){if((e.ownerDocument||e)!==L&&D(e),t=t.replace(bt,"='$1']"),!(!W.matchesSelector||M||_&&_.test(t)||q.test(t)))try{var n=F.call(e,t);if(n||W.disconnectedMatch||e.document&&11!==e.document.nodeType)return n}catch(r){}return a(t,L,null,[e]).length>0},a.contains=function(e,t){return(e.ownerDocument||e)!==L&&D(e),O(e,t)},a.attr=function(e,t){var n;return(e.ownerDocument||e)!==L&&D(e),M||(t=t.toLowerCase()),(n=C.attrHandle[t])?n(e):M||W.attributes?e.getAttribute(t):((n=e.getAttributeNode(t))||e.getAttribute(t))&&e[t]===!0?t:n&&n.specified?n.value:null},a.error=function(e){throw Error("Syntax error, unrecognized expression: "+e)},a.uniqueSort=function(e){var t,n=[],r=1,i=0;if(A=!W.detectDuplicates,e.sort(B),A){for(;t=e[r];r++)t===e[r-1]&&(i=n.push(r));for(;i--;)e.splice(n[i],1)}return e},k=a.getText=function(e){var t,n="",r=0,i=e.nodeType;if(i){if(1===i||9===i||11===i){if("string"==typeof e.textContent)return e.textContent;for(e=e.firstChild;e;e=e.nextSibling)n+=k(e)}else if(3===i||4===i)return e.nodeValue}else for(;t=e[r];r++)n+=k(t);return n},C=a.selectors={cacheLength:50,createPseudo:i,match:pt,find:{},relative:{">":{dir:"parentNode",first:!0}," ":{dir:"parentNode"},"+":{dir:"previousSibling",first:!0},"~":{dir:"previousSibling"}},preFilter:{ATTR:function(e){return e[1]=e[1].replace(xt,Tt),e[3]=(e[4]||e[5]||"").replace(xt,Tt),"~="===e[2]&&(e[3]=" "+e[3]+" "),e.slice(0,4)},CHILD:function(e){return e[1]=e[1].toLowerCase(),"nth"===e[1].slice(0,3)?(e[3]||a.error(e[0]),e[4]=+(e[4]?e[5]+(e[6]||1):2*("even"===e[3]||"odd"===e[3])),e[5]=+(e[7]+e[8]||"odd"===e[3])):e[3]&&a.error(e[0]),e},PSEUDO:function(e){var t,n=!e[5]&&e[2];return pt.CHILD.test(e[0])?null:(e[4]?e[2]=e[4]:n&&ct.test(n)&&(t=f(n,!0))&&(t=n.indexOf(")",n.length-t)-n.length)&&(e[0]=e[0].slice(0,t),e[2]=n.slice(0,t)),e.slice(0,3))}},filter:{TAG:function(e){return"*"===e?function(){return!0}:(e=e.replace(xt,Tt).toLowerCase(),function(t){return t.nodeName&&t.nodeName.toLowerCase()===e})},CLASS:function(e){var t=z[e+" "];return t||(t=RegExp("(^|"+et+")"+e+"("+et+"|$)"))&&z(e,function(e){return t.test(e.className||typeof e.getAttribute!==V&&e.getAttribute("class")||"")})},ATTR:function(e,t,n){return function(r){var i=a.attr(r,e);return null==i?"!="===t:t?(i+="","="===t?i===n:"!="===t?i!==n:"^="===t?n&&0===i.indexOf(n):"*="===t?n&&i.indexOf(n)>-1:"$="===t?n&&i.substr(i.length-n.length)===n:"~="===t?(" "+i+" ").indexOf(n)>-1:"|="===t?i===n||i.substr(0,n.length+1)===n+"-":!1):!0}},CHILD:function(e,t,n,r,i){var o="nth"!==e.slice(0,3),a="last"!==e.slice(-4),s="of-type"===t;return 1===r&&0===i?function(e){return!!e.parentNode}:function(t,n,u){var l,c,f,p,d,h,g=o!==a?"nextSibling":"previousSibling",m=t.parentNode,y=s&&t.nodeName.toLowerCase(),v=!u&&!s;if(m){if(o){for(;g;){for(f=t;f=f[g];)if(s?f.nodeName.toLowerCase()===y:1===f.nodeType)return!1;h=g="only"===e&&!h&&"nextSibling"}return!0}if(h=[a?m.firstChild:m.lastChild],a&&v){for(c=m[P]||(m[P]={}),l=c[e]||[],d=l[0]===$&&l[1],p=l[0]===$&&l[2],f=d&&m.childNodes[d];f=++d&&f&&f[g]||(p=d=0)||h.pop();)if(1===f.nodeType&&++p&&f===t){c[e]=[$,d,p];break}}else if(v&&(l=(t[P]||(t[P]={}))[e])&&l[0]===$)p=l[1];else for(;(f=++d&&f&&f[g]||(p=d=0)||h.pop())&&((s?f.nodeName.toLowerCase()!==y:1!==f.nodeType)||!++p||(v&&((f[P]||(f[P]={}))[e]=[$,p]),f!==t)););return p-=i,p===r||0===p%r&&p/r>=0}}},PSEUDO:function(e,t){var n,r=C.pseudos[e]||C.setFilters[e.toLowerCase()]||a.error("unsupported pseudo: "+e);return r[P]?r(t):r.length>1?(n=[e,e,"",t],C.setFilters.hasOwnProperty(e.toLowerCase())?i(function(e,n){for(var i,o=r(e,t),a=o.length;a--;)i=Z.call(e,o[a]),e[i]=!(n[i]=o[a])}):function(e){return r(e,0,n)}):r}},pseudos:{not:i(function(e){var t=[],n=[],r=S(e.replace(at,"$1"));return r[P]?i(function(e,t,n,i){for(var o,a=r(e,null,i,[]),s=e.length;s--;)(o=a[s])&&(e[s]=!(t[s]=o))}):function(e,i,o){return t[0]=e,r(t,null,o,n),!n.pop()}}),has:i(function(e){return function(t){return a(e,t).length>0}}),contains:i(function(e){return function(t){return(t.textContent||t.innerText||k(t)).indexOf(e)>-1}}),lang:i(function(e){return ft.test(e||"")||a.error("unsupported lang: "+e),e=e.replace(xt,Tt).toLowerCase(),function(t){var n;do if(n=M?t.getAttribute("xml:lang")||t.getAttribute("lang"):t.lang)return n=n.toLowerCase(),n===e||0===n.indexOf(e+"-");while((t=t.parentNode)&&1===t.nodeType);return!1}}),target:function(t){var n=e.location&&e.location.hash;return n&&n.slice(1)===t.id},root:function(e){return e===H},focus:function(e){return e===L.activeElement&&(!L.hasFocus||L.hasFocus())&&!!(e.type||e.href||~e.tabIndex)},enabled:function(e){return e.disabled===!1},disabled:function(e){return e.disabled===!0},checked:function(e){var t=e.nodeName.toLowerCase();return"input"===t&&!!e.checked||"option"===t&&!!e.selected},selected:function(e){return e.parentNode&&e.parentNode.selectedIndex,e.selected===!0},empty:function(e){for(e=e.firstChild;e;e=e.nextSibling)if(e.nodeName>"@"||3===e.nodeType||4===e.nodeType)return!1;return!0},parent:function(e){return!C.pseudos.empty(e)},header:function(e){return yt.test(e.nodeName)},input:function(e){return mt.test(e.nodeName)},button:function(e){var t=e.nodeName.toLowerCase();return"input"===t&&"button"===e.type||"button"===t},text:function(e){var t;return"input"===e.nodeName.toLowerCase()&&"text"===e.type&&(null==(t=e.getAttribute("type"))||t.toLowerCase()===e.type)},first:c(function(){return[0]}),last:c(function(e,t){return[t-1]}),eq:c(function(e,t,n){return[0>n?n+t:n]}),even:c(function(e,t){for(var n=0;t>n;n+=2)e.push(n);return e}),odd:c(function(e,t){for(var n=1;t>n;n+=2)e.push(n);return e}),lt:c(function(e,t,n){for(var r=0>n?n+t:n;--r>=0;)e.push(r);return e}),gt:c(function(e,t,n){for(var r=0>n?n+t:n;t>++r;)e.push(r);return e})}};for(w in{radio:!0,checkbox:!0,file:!0,password:!0,image:!0})C.pseudos[w]=u(w);for(w in{submit:!0,reset:!0})C.pseudos[w]=l(w);S=a.compile=function(e,t){var n,r=[],i=[],o=U[e+" "];if(!o){for(t||(t=f(e)),n=t.length;n--;)o=y(t[n]),o[P]?r.push(o):i.push(o);o=U(e,v(i,r))}return o},C.pseudos.nth=C.pseudos.eq,C.filters=T.prototype=C.pseudos,C.setFilters=new T,D(),a.attr=st.attr,st.find=a,st.expr=a.selectors,st.expr[":"]=st.expr.pseudos,st.unique=a.uniqueSort,st.text=a.getText,st.isXMLDoc=a.isXML,st.contains=a.contains}(e);var Pt=/Until$/,Rt=/^(?:parents|prev(?:Until|All))/,Wt=/^.[^:#\[\.,]*$/,$t=st.expr.match.needsContext,It={children:!0,contents:!0,next:!0,prev:!0};st.fn.extend({find:function(e){var t,n,r;if("string"!=typeof e)return r=this,this.pushStack(st(e).filter(function(){for(t=0;r.length>t;t++)if(st.contains(r[t],this))return!0}));for(n=[],t=0;this.length>t;t++)st.find(e,this[t],n);return n=this.pushStack(st.unique(n)),n.selector=(this.selector?this.selector+" ":"")+e,n},has:function(e){var t,n=st(e,this),r=n.length;return this.filter(function(){for(t=0;r>t;t++)if(st.contains(this,n[t]))return!0})},not:function(e){return this.pushStack(f(this,e,!1))},filter:function(e){return this.pushStack(f(this,e,!0))},is:function(e){return!!e&&("string"==typeof e?$t.test(e)?st(e,this.context).index(this[0])>=0:st.filter(e,this).length>0:this.filter(e).length>0)},closest:function(e,t){for(var n,r=0,i=this.length,o=[],a=$t.test(e)||"string"!=typeof e?st(e,t||this.context):0;i>r;r++)for(n=this[r];n&&n.ownerDocument&&n!==t&&11!==n.nodeType;){if(a?a.index(n)>-1:st.find.matchesSelector(n,e)){o.push(n);break}n=n.parentNode}return this.pushStack(o.length>1?st.unique(o):o)},index:function(e){return e?"string"==typeof e?st.inArray(this[0],st(e)):st.inArray(e.jquery?e[0]:e,this):this[0]&&this[0].parentNode?this.first().prevAll().length:-1},add:function(e,t){var n="string"==typeof e?st(e,t):st.makeArray(e&&e.nodeType?[e]:e),r=st.merge(this.get(),n);return this.pushStack(st.unique(r))},addBack:function(e){return this.add(null==e?this.prevObject:this.prevObject.filter(e))}}),st.fn.andSelf=st.fn.addBack,st.each({parent:function(e){var t=e.parentNode;return t&&11!==t.nodeType?t:null},parents:function(e){return st.dir(e,"parentNode")},parentsUntil:function(e,t,n){return st.dir(e,"parentNode",n)},next:function(e){return c(e,"nextSibling")},prev:function(e){return c(e,"previousSibling")
},nextAll:function(e){return st.dir(e,"nextSibling")},prevAll:function(e){return st.dir(e,"previousSibling")},nextUntil:function(e,t,n){return st.dir(e,"nextSibling",n)},prevUntil:function(e,t,n){return st.dir(e,"previousSibling",n)},siblings:function(e){return st.sibling((e.parentNode||{}).firstChild,e)},children:function(e){return st.sibling(e.firstChild)},contents:function(e){return st.nodeName(e,"iframe")?e.contentDocument||e.contentWindow.document:st.merge([],e.childNodes)}},function(e,t){st.fn[e]=function(n,r){var i=st.map(this,t,n);return Pt.test(e)||(r=n),r&&"string"==typeof r&&(i=st.filter(r,i)),i=this.length>1&&!It[e]?st.unique(i):i,this.length>1&&Rt.test(e)&&(i=i.reverse()),this.pushStack(i)}}),st.extend({filter:function(e,t,n){return n&&(e=":not("+e+")"),1===t.length?st.find.matchesSelector(t[0],e)?[t[0]]:[]:st.find.matches(e,t)},dir:function(e,n,r){for(var i=[],o=e[n];o&&9!==o.nodeType&&(r===t||1!==o.nodeType||!st(o).is(r));)1===o.nodeType&&i.push(o),o=o[n];return i},sibling:function(e,t){for(var n=[];e;e=e.nextSibling)1===e.nodeType&&e!==t&&n.push(e);return n}});var zt="abbr|article|aside|audio|bdi|canvas|data|datalist|details|figcaption|figure|footer|header|hgroup|mark|meter|nav|output|progress|section|summary|time|video",Xt=/ jQuery\d+="(?:null|\d+)"/g,Ut=RegExp("<(?:"+zt+")[\\s/>]","i"),Vt=/^\s+/,Yt=/<(?!area|br|col|embed|hr|img|input|link|meta|param)(([\w:]+)[^>]*)\/>/gi,Jt=/<([\w:]+)/,Gt=/<tbody/i,Qt=/<|&#?\w+;/,Kt=/<(?:script|style|link)/i,Zt=/^(?:checkbox|radio)$/i,en=/checked\s*(?:[^=]|=\s*.checked.)/i,tn=/^$|\/(?:java|ecma)script/i,nn=/^true\/(.*)/,rn=/^\s*<!(?:\[CDATA\[|--)|(?:\]\]|--)>\s*$/g,on={option:[1,"<select multiple='multiple'>","</select>"],legend:[1,"<fieldset>","</fieldset>"],area:[1,"<map>","</map>"],param:[1,"<object>","</object>"],thead:[1,"<table>","</table>"],tr:[2,"<table><tbody>","</tbody></table>"],col:[2,"<table><tbody></tbody><colgroup>","</colgroup></table>"],td:[3,"<table><tbody><tr>","</tr></tbody></table>"],_default:st.support.htmlSerialize?[0,"",""]:[1,"X<div>","</div>"]},an=p(V),sn=an.appendChild(V.createElement("div"));on.optgroup=on.option,on.tbody=on.tfoot=on.colgroup=on.caption=on.thead,on.th=on.td,st.fn.extend({text:function(e){return st.access(this,function(e){return e===t?st.text(this):this.empty().append((this[0]&&this[0].ownerDocument||V).createTextNode(e))},null,e,arguments.length)},wrapAll:function(e){if(st.isFunction(e))return this.each(function(t){st(this).wrapAll(e.call(this,t))});if(this[0]){var t=st(e,this[0].ownerDocument).eq(0).clone(!0);this[0].parentNode&&t.insertBefore(this[0]),t.map(function(){for(var e=this;e.firstChild&&1===e.firstChild.nodeType;)e=e.firstChild;return e}).append(this)}return this},wrapInner:function(e){return st.isFunction(e)?this.each(function(t){st(this).wrapInner(e.call(this,t))}):this.each(function(){var t=st(this),n=t.contents();n.length?n.wrapAll(e):t.append(e)})},wrap:function(e){var t=st.isFunction(e);return this.each(function(n){st(this).wrapAll(t?e.call(this,n):e)})},unwrap:function(){return this.parent().each(function(){st.nodeName(this,"body")||st(this).replaceWith(this.childNodes)}).end()},append:function(){return this.domManip(arguments,!0,function(e){(1===this.nodeType||11===this.nodeType||9===this.nodeType)&&this.appendChild(e)})},prepend:function(){return this.domManip(arguments,!0,function(e){(1===this.nodeType||11===this.nodeType||9===this.nodeType)&&this.insertBefore(e,this.firstChild)})},before:function(){return this.domManip(arguments,!1,function(e){this.parentNode&&this.parentNode.insertBefore(e,this)})},after:function(){return this.domManip(arguments,!1,function(e){this.parentNode&&this.parentNode.insertBefore(e,this.nextSibling)})},remove:function(e,t){for(var n,r=0;null!=(n=this[r]);r++)(!e||st.filter(e,[n]).length>0)&&(t||1!==n.nodeType||st.cleanData(b(n)),n.parentNode&&(t&&st.contains(n.ownerDocument,n)&&m(b(n,"script")),n.parentNode.removeChild(n)));return this},empty:function(){for(var e,t=0;null!=(e=this[t]);t++){for(1===e.nodeType&&st.cleanData(b(e,!1));e.firstChild;)e.removeChild(e.firstChild);e.options&&st.nodeName(e,"select")&&(e.options.length=0)}return this},clone:function(e,t){return e=null==e?!1:e,t=null==t?e:t,this.map(function(){return st.clone(this,e,t)})},html:function(e){return st.access(this,function(e){var n=this[0]||{},r=0,i=this.length;if(e===t)return 1===n.nodeType?n.innerHTML.replace(Xt,""):t;if(!("string"!=typeof e||Kt.test(e)||!st.support.htmlSerialize&&Ut.test(e)||!st.support.leadingWhitespace&&Vt.test(e)||on[(Jt.exec(e)||["",""])[1].toLowerCase()])){e=e.replace(Yt,"<$1></$2>");try{for(;i>r;r++)n=this[r]||{},1===n.nodeType&&(st.cleanData(b(n,!1)),n.innerHTML=e);n=0}catch(o){}}n&&this.empty().append(e)},null,e,arguments.length)},replaceWith:function(e){var t=st.isFunction(e);return t||"string"==typeof e||(e=st(e).not(this).detach()),this.domManip([e],!0,function(e){var t=this.nextSibling,n=this.parentNode;(n&&1===this.nodeType||11===this.nodeType)&&(st(this).remove(),t?t.parentNode.insertBefore(e,t):n.appendChild(e))})},detach:function(e){return this.remove(e,!0)},domManip:function(e,n,r){e=et.apply([],e);var i,o,a,s,u,l,c=0,f=this.length,p=this,m=f-1,y=e[0],v=st.isFunction(y);if(v||!(1>=f||"string"!=typeof y||st.support.checkClone)&&en.test(y))return this.each(function(i){var o=p.eq(i);v&&(e[0]=y.call(this,i,n?o.html():t)),o.domManip(e,n,r)});if(f&&(i=st.buildFragment(e,this[0].ownerDocument,!1,this),o=i.firstChild,1===i.childNodes.length&&(i=o),o)){for(n=n&&st.nodeName(o,"tr"),a=st.map(b(i,"script"),h),s=a.length;f>c;c++)u=i,c!==m&&(u=st.clone(u,!0,!0),s&&st.merge(a,b(u,"script"))),r.call(n&&st.nodeName(this[c],"table")?d(this[c],"tbody"):this[c],u,c);if(s)for(l=a[a.length-1].ownerDocument,st.map(a,g),c=0;s>c;c++)u=a[c],tn.test(u.type||"")&&!st._data(u,"globalEval")&&st.contains(l,u)&&(u.src?st.ajax({url:u.src,type:"GET",dataType:"script",async:!1,global:!1,"throws":!0}):st.globalEval((u.text||u.textContent||u.innerHTML||"").replace(rn,"")));i=o=null}return this}}),st.each({appendTo:"append",prependTo:"prepend",insertBefore:"before",insertAfter:"after",replaceAll:"replaceWith"},function(e,t){st.fn[e]=function(e){for(var n,r=0,i=[],o=st(e),a=o.length-1;a>=r;r++)n=r===a?this:this.clone(!0),st(o[r])[t](n),tt.apply(i,n.get());return this.pushStack(i)}}),st.extend({clone:function(e,t,n){var r,i,o,a,s,u=st.contains(e.ownerDocument,e);if(st.support.html5Clone||st.isXMLDoc(e)||!Ut.test("<"+e.nodeName+">")?s=e.cloneNode(!0):(sn.innerHTML=e.outerHTML,sn.removeChild(s=sn.firstChild)),!(st.support.noCloneEvent&&st.support.noCloneChecked||1!==e.nodeType&&11!==e.nodeType||st.isXMLDoc(e)))for(r=b(s),i=b(e),a=0;null!=(o=i[a]);++a)r[a]&&v(o,r[a]);if(t)if(n)for(i=i||b(e),r=r||b(s),a=0;null!=(o=i[a]);a++)y(o,r[a]);else y(e,s);return r=b(s,"script"),r.length>0&&m(r,!u&&b(e,"script")),r=i=o=null,s},buildFragment:function(e,t,n,r){for(var i,o,a,s,u,l,c,f=e.length,d=p(t),h=[],g=0;f>g;g++)if(o=e[g],o||0===o)if("object"===st.type(o))st.merge(h,o.nodeType?[o]:o);else if(Qt.test(o)){for(s=s||d.appendChild(t.createElement("div")),a=(Jt.exec(o)||["",""])[1].toLowerCase(),u=on[a]||on._default,s.innerHTML=u[1]+o.replace(Yt,"<$1></$2>")+u[2],c=u[0];c--;)s=s.lastChild;if(!st.support.leadingWhitespace&&Vt.test(o)&&h.push(t.createTextNode(Vt.exec(o)[0])),!st.support.tbody)for(o="table"!==a||Gt.test(o)?"<table>"!==u[1]||Gt.test(o)?0:s:s.firstChild,c=o&&o.childNodes.length;c--;)st.nodeName(l=o.childNodes[c],"tbody")&&!l.childNodes.length&&o.removeChild(l);for(st.merge(h,s.childNodes),s.textContent="";s.firstChild;)s.removeChild(s.firstChild);s=d.lastChild}else h.push(t.createTextNode(o));for(s&&d.removeChild(s),st.support.appendChecked||st.grep(b(h,"input"),x),g=0;o=h[g++];)if((!r||-1===st.inArray(o,r))&&(i=st.contains(o.ownerDocument,o),s=b(d.appendChild(o),"script"),i&&m(s),n))for(c=0;o=s[c++];)tn.test(o.type||"")&&n.push(o);return s=null,d},cleanData:function(e,n){for(var r,i,o,a,s=0,u=st.expando,l=st.cache,c=st.support.deleteExpando,f=st.event.special;null!=(o=e[s]);s++)if((n||st.acceptData(o))&&(i=o[u],r=i&&l[i])){if(r.events)for(a in r.events)f[a]?st.event.remove(o,a):st.removeEvent(o,a,r.handle);l[i]&&(delete l[i],c?delete o[u]:o.removeAttribute!==t?o.removeAttribute(u):o[u]=null,K.push(i))}}});var un,ln,cn,fn=/alpha\([^)]*\)/i,pn=/opacity\s*=\s*([^)]*)/,dn=/^(top|right|bottom|left)$/,hn=/^(none|table(?!-c[ea]).+)/,gn=/^margin/,mn=RegExp("^("+ut+")(.*)$","i"),yn=RegExp("^("+ut+")(?!px)[a-z%]+$","i"),vn=RegExp("^([+-])=("+ut+")","i"),bn={BODY:"block"},xn={position:"absolute",visibility:"hidden",display:"block"},Tn={letterSpacing:0,fontWeight:400},wn=["Top","Right","Bottom","Left"],Nn=["Webkit","O","Moz","ms"];st.fn.extend({css:function(e,n){return st.access(this,function(e,n,r){var i,o,a={},s=0;if(st.isArray(n)){for(i=ln(e),o=n.length;o>s;s++)a[n[s]]=st.css(e,n[s],!1,i);return a}return r!==t?st.style(e,n,r):st.css(e,n)},e,n,arguments.length>1)},show:function(){return N(this,!0)},hide:function(){return N(this)},toggle:function(e){var t="boolean"==typeof e;return this.each(function(){(t?e:w(this))?st(this).show():st(this).hide()})}}),st.extend({cssHooks:{opacity:{get:function(e,t){if(t){var n=un(e,"opacity");return""===n?"1":n}}}},cssNumber:{columnCount:!0,fillOpacity:!0,fontWeight:!0,lineHeight:!0,opacity:!0,orphans:!0,widows:!0,zIndex:!0,zoom:!0},cssProps:{"float":st.support.cssFloat?"cssFloat":"styleFloat"},style:function(e,n,r,i){if(e&&3!==e.nodeType&&8!==e.nodeType&&e.style){var o,a,s,u=st.camelCase(n),l=e.style;if(n=st.cssProps[u]||(st.cssProps[u]=T(l,u)),s=st.cssHooks[n]||st.cssHooks[u],r===t)return s&&"get"in s&&(o=s.get(e,!1,i))!==t?o:l[n];if(a=typeof r,"string"===a&&(o=vn.exec(r))&&(r=(o[1]+1)*o[2]+parseFloat(st.css(e,n)),a="number"),!(null==r||"number"===a&&isNaN(r)||("number"!==a||st.cssNumber[u]||(r+="px"),st.support.clearCloneStyle||""!==r||0!==n.indexOf("background")||(l[n]="inherit"),s&&"set"in s&&(r=s.set(e,r,i))===t)))try{l[n]=r}catch(c){}}},css:function(e,n,r,i){var o,a,s,u=st.camelCase(n);return n=st.cssProps[u]||(st.cssProps[u]=T(e.style,u)),s=st.cssHooks[n]||st.cssHooks[u],s&&"get"in s&&(o=s.get(e,!0,r)),o===t&&(o=un(e,n,i)),"normal"===o&&n in Tn&&(o=Tn[n]),r?(a=parseFloat(o),r===!0||st.isNumeric(a)?a||0:o):o},swap:function(e,t,n,r){var i,o,a={};for(o in t)a[o]=e.style[o],e.style[o]=t[o];i=n.apply(e,r||[]);for(o in t)e.style[o]=a[o];return i}}),e.getComputedStyle?(ln=function(t){return e.getComputedStyle(t,null)},un=function(e,n,r){var i,o,a,s=r||ln(e),u=s?s.getPropertyValue(n)||s[n]:t,l=e.style;return s&&(""!==u||st.contains(e.ownerDocument,e)||(u=st.style(e,n)),yn.test(u)&&gn.test(n)&&(i=l.width,o=l.minWidth,a=l.maxWidth,l.minWidth=l.maxWidth=l.width=u,u=s.width,l.width=i,l.minWidth=o,l.maxWidth=a)),u}):V.documentElement.currentStyle&&(ln=function(e){return e.currentStyle},un=function(e,n,r){var i,o,a,s=r||ln(e),u=s?s[n]:t,l=e.style;return null==u&&l&&l[n]&&(u=l[n]),yn.test(u)&&!dn.test(n)&&(i=l.left,o=e.runtimeStyle,a=o&&o.left,a&&(o.left=e.currentStyle.left),l.left="fontSize"===n?"1em":u,u=l.pixelLeft+"px",l.left=i,a&&(o.left=a)),""===u?"auto":u}),st.each(["height","width"],function(e,n){st.cssHooks[n]={get:function(e,r,i){return r?0===e.offsetWidth&&hn.test(st.css(e,"display"))?st.swap(e,xn,function(){return E(e,n,i)}):E(e,n,i):t},set:function(e,t,r){var i=r&&ln(e);return C(e,t,r?k(e,n,r,st.support.boxSizing&&"border-box"===st.css(e,"boxSizing",!1,i),i):0)}}}),st.support.opacity||(st.cssHooks.opacity={get:function(e,t){return pn.test((t&&e.currentStyle?e.currentStyle.filter:e.style.filter)||"")?.01*parseFloat(RegExp.$1)+"":t?"1":""},set:function(e,t){var n=e.style,r=e.currentStyle,i=st.isNumeric(t)?"alpha(opacity="+100*t+")":"",o=r&&r.filter||n.filter||"";n.zoom=1,(t>=1||""===t)&&""===st.trim(o.replace(fn,""))&&n.removeAttribute&&(n.removeAttribute("filter"),""===t||r&&!r.filter)||(n.filter=fn.test(o)?o.replace(fn,i):o+" "+i)}}),st(function(){st.support.reliableMarginRight||(st.cssHooks.marginRight={get:function(e,n){return n?st.swap(e,{display:"inline-block"},un,[e,"marginRight"]):t}}),!st.support.pixelPosition&&st.fn.position&&st.each(["top","left"],function(e,n){st.cssHooks[n]={get:function(e,r){return r?(r=un(e,n),yn.test(r)?st(e).position()[n]+"px":r):t}}})}),st.expr&&st.expr.filters&&(st.expr.filters.hidden=function(e){return 0===e.offsetWidth&&0===e.offsetHeight||!st.support.reliableHiddenOffsets&&"none"===(e.style&&e.style.display||st.css(e,"display"))},st.expr.filters.visible=function(e){return!st.expr.filters.hidden(e)}),st.each({margin:"",padding:"",border:"Width"},function(e,t){st.cssHooks[e+t]={expand:function(n){for(var r=0,i={},o="string"==typeof n?n.split(" "):[n];4>r;r++)i[e+wn[r]+t]=o[r]||o[r-2]||o[0];return i}},gn.test(e)||(st.cssHooks[e+t].set=C)});var Cn=/%20/g,kn=/\[\]$/,En=/\r?\n/g,Sn=/^(?:submit|button|image|reset)$/i,An=/^(?:input|select|textarea|keygen)/i;st.fn.extend({serialize:function(){return st.param(this.serializeArray())},serializeArray:function(){return this.map(function(){var e=st.prop(this,"elements");return e?st.makeArray(e):this}).filter(function(){var e=this.type;return this.name&&!st(this).is(":disabled")&&An.test(this.nodeName)&&!Sn.test(e)&&(this.checked||!Zt.test(e))}).map(function(e,t){var n=st(this).val();return null==n?null:st.isArray(n)?st.map(n,function(e){return{name:t.name,value:e.replace(En,"\r\n")}}):{name:t.name,value:n.replace(En,"\r\n")}}).get()}}),st.param=function(e,n){var r,i=[],o=function(e,t){t=st.isFunction(t)?t():null==t?"":t,i[i.length]=encodeURIComponent(e)+"="+encodeURIComponent(t)};if(n===t&&(n=st.ajaxSettings&&st.ajaxSettings.traditional),st.isArray(e)||e.jquery&&!st.isPlainObject(e))st.each(e,function(){o(this.name,this.value)});else for(r in e)j(r,e[r],n,o);return i.join("&").replace(Cn,"+")};var jn,Dn,Ln=st.now(),Hn=/\?/,Mn=/#.*$/,qn=/([?&])_=[^&]*/,_n=/^(.*?):[ \t]*([^\r\n]*)\r?$/gm,Fn=/^(?:about|app|app-storage|.+-extension|file|res|widget):$/,On=/^(?:GET|HEAD)$/,Bn=/^\/\//,Pn=/^([\w.+-]+:)(?:\/\/([^\/?#:]*)(?::(\d+)|)|)/,Rn=st.fn.load,Wn={},$n={},In="*/".concat("*");try{Dn=Y.href}catch(zn){Dn=V.createElement("a"),Dn.href="",Dn=Dn.href}jn=Pn.exec(Dn.toLowerCase())||[],st.fn.load=function(e,n,r){if("string"!=typeof e&&Rn)return Rn.apply(this,arguments);var i,o,a,s=this,u=e.indexOf(" ");return u>=0&&(i=e.slice(u,e.length),e=e.slice(0,u)),st.isFunction(n)?(r=n,n=t):n&&"object"==typeof n&&(o="POST"),s.length>0&&st.ajax({url:e,type:o,dataType:"html",data:n}).done(function(e){a=arguments,s.html(i?st("<div>").append(st.parseHTML(e)).find(i):e)}).complete(r&&function(e,t){s.each(r,a||[e.responseText,t,e])}),this},st.each(["ajaxStart","ajaxStop","ajaxComplete","ajaxError","ajaxSuccess","ajaxSend"],function(e,t){st.fn[t]=function(e){return this.on(t,e)}}),st.each(["get","post"],function(e,n){st[n]=function(e,r,i,o){return st.isFunction(r)&&(o=o||i,i=r,r=t),st.ajax({url:e,type:n,dataType:o,data:r,success:i})}}),st.extend({active:0,lastModified:{},etag:{},ajaxSettings:{url:Dn,type:"GET",isLocal:Fn.test(jn[1]),global:!0,processData:!0,async:!0,contentType:"application/x-www-form-urlencoded; charset=UTF-8",accepts:{"*":In,text:"text/plain",html:"text/html",xml:"application/xml, text/xml",json:"application/json, text/javascript"},contents:{xml:/xml/,html:/html/,json:/json/},responseFields:{xml:"responseXML",text:"responseText"},converters:{"* text":e.String,"text html":!0,"text json":st.parseJSON,"text xml":st.parseXML},flatOptions:{url:!0,context:!0}},ajaxSetup:function(e,t){return t?H(H(e,st.ajaxSettings),t):H(st.ajaxSettings,e)},ajaxPrefilter:D(Wn),ajaxTransport:D($n),ajax:function(e,n){function r(e,n,r,s){var l,f,v,b,T,N=n;2!==x&&(x=2,u&&clearTimeout(u),i=t,a=s||"",w.readyState=e>0?4:0,r&&(b=M(p,w,r)),e>=200&&300>e||304===e?(p.ifModified&&(T=w.getResponseHeader("Last-Modified"),T&&(st.lastModified[o]=T),T=w.getResponseHeader("etag"),T&&(st.etag[o]=T)),304===e?(l=!0,N="notmodified"):(l=q(p,b),N=l.state,f=l.data,v=l.error,l=!v)):(v=N,(e||!N)&&(N="error",0>e&&(e=0))),w.status=e,w.statusText=(n||N)+"",l?g.resolveWith(d,[f,N,w]):g.rejectWith(d,[w,N,v]),w.statusCode(y),y=t,c&&h.trigger(l?"ajaxSuccess":"ajaxError",[w,p,l?f:v]),m.fireWith(d,[w,N]),c&&(h.trigger("ajaxComplete",[w,p]),--st.active||st.event.trigger("ajaxStop")))}"object"==typeof e&&(n=e,e=t),n=n||{};var i,o,a,s,u,l,c,f,p=st.ajaxSetup({},n),d=p.context||p,h=p.context&&(d.nodeType||d.jquery)?st(d):st.event,g=st.Deferred(),m=st.Callbacks("once memory"),y=p.statusCode||{},v={},b={},x=0,T="canceled",w={readyState:0,getResponseHeader:function(e){var t;if(2===x){if(!s)for(s={};t=_n.exec(a);)s[t[1].toLowerCase()]=t[2];t=s[e.toLowerCase()]}return null==t?null:t},getAllResponseHeaders:function(){return 2===x?a:null},setRequestHeader:function(e,t){var n=e.toLowerCase();return x||(e=b[n]=b[n]||e,v[e]=t),this},overrideMimeType:function(e){return x||(p.mimeType=e),this},statusCode:function(e){var t;if(e)if(2>x)for(t in e)y[t]=[y[t],e[t]];else w.always(e[w.status]);return this},abort:function(e){var t=e||T;return i&&i.abort(t),r(0,t),this}};if(g.promise(w).complete=m.add,w.success=w.done,w.error=w.fail,p.url=((e||p.url||Dn)+"").replace(Mn,"").replace(Bn,jn[1]+"//"),p.type=n.method||n.type||p.method||p.type,p.dataTypes=st.trim(p.dataType||"*").toLowerCase().match(lt)||[""],null==p.crossDomain&&(l=Pn.exec(p.url.toLowerCase()),p.crossDomain=!(!l||l[1]===jn[1]&&l[2]===jn[2]&&(l[3]||("http:"===l[1]?80:443))==(jn[3]||("http:"===jn[1]?80:443)))),p.data&&p.processData&&"string"!=typeof p.data&&(p.data=st.param(p.data,p.traditional)),L(Wn,p,n,w),2===x)return w;c=p.global,c&&0===st.active++&&st.event.trigger("ajaxStart"),p.type=p.type.toUpperCase(),p.hasContent=!On.test(p.type),o=p.url,p.hasContent||(p.data&&(o=p.url+=(Hn.test(o)?"&":"?")+p.data,delete p.data),p.cache===!1&&(p.url=qn.test(o)?o.replace(qn,"$1_="+Ln++):o+(Hn.test(o)?"&":"?")+"_="+Ln++)),p.ifModified&&(st.lastModified[o]&&w.setRequestHeader("If-Modified-Since",st.lastModified[o]),st.etag[o]&&w.setRequestHeader("If-None-Match",st.etag[o])),(p.data&&p.hasContent&&p.contentType!==!1||n.contentType)&&w.setRequestHeader("Content-Type",p.contentType),w.setRequestHeader("Accept",p.dataTypes[0]&&p.accepts[p.dataTypes[0]]?p.accepts[p.dataTypes[0]]+("*"!==p.dataTypes[0]?", "+In+"; q=0.01":""):p.accepts["*"]);for(f in p.headers)w.setRequestHeader(f,p.headers[f]);if(p.beforeSend&&(p.beforeSend.call(d,w,p)===!1||2===x))return w.abort();T="abort";for(f in{success:1,error:1,complete:1})w[f](p[f]);if(i=L($n,p,n,w)){w.readyState=1,c&&h.trigger("ajaxSend",[w,p]),p.async&&p.timeout>0&&(u=setTimeout(function(){w.abort("timeout")},p.timeout));try{x=1,i.send(v,r)}catch(N){if(!(2>x))throw N;r(-1,N)}}else r(-1,"No Transport");return w},getScript:function(e,n){return st.get(e,t,n,"script")},getJSON:function(e,t,n){return st.get(e,t,n,"json")}}),st.ajaxSetup({accepts:{script:"text/javascript, application/javascript, application/ecmascript, application/x-ecmascript"},contents:{script:/(?:java|ecma)script/},converters:{"text script":function(e){return st.globalEval(e),e}}}),st.ajaxPrefilter("script",function(e){e.cache===t&&(e.cache=!1),e.crossDomain&&(e.type="GET",e.global=!1)}),st.ajaxTransport("script",function(e){if(e.crossDomain){var n,r=V.head||st("head")[0]||V.documentElement;return{send:function(t,i){n=V.createElement("script"),n.async=!0,e.scriptCharset&&(n.charset=e.scriptCharset),n.src=e.url,n.onload=n.onreadystatechange=function(e,t){(t||!n.readyState||/loaded|complete/.test(n.readyState))&&(n.onload=n.onreadystatechange=null,n.parentNode&&n.parentNode.removeChild(n),n=null,t||i(200,"success"))},r.insertBefore(n,r.firstChild)},abort:function(){n&&n.onload(t,!0)}}}});var Xn=[],Un=/(=)\?(?=&|$)|\?\?/;st.ajaxSetup({jsonp:"callback",jsonpCallback:function(){var e=Xn.pop()||st.expando+"_"+Ln++;return this[e]=!0,e}}),st.ajaxPrefilter("json jsonp",function(n,r,i){var o,a,s,u=n.jsonp!==!1&&(Un.test(n.url)?"url":"string"==typeof n.data&&!(n.contentType||"").indexOf("application/x-www-form-urlencoded")&&Un.test(n.data)&&"data");return u||"jsonp"===n.dataTypes[0]?(o=n.jsonpCallback=st.isFunction(n.jsonpCallback)?n.jsonpCallback():n.jsonpCallback,u?n[u]=n[u].replace(Un,"$1"+o):n.jsonp!==!1&&(n.url+=(Hn.test(n.url)?"&":"?")+n.jsonp+"="+o),n.converters["script json"]=function(){return s||st.error(o+" was not called"),s[0]},n.dataTypes[0]="json",a=e[o],e[o]=function(){s=arguments},i.always(function(){e[o]=a,n[o]&&(n.jsonpCallback=r.jsonpCallback,Xn.push(o)),s&&st.isFunction(a)&&a(s[0]),s=a=t}),"script"):t});var Vn,Yn,Jn=0,Gn=e.ActiveXObject&&function(){var e;for(e in Vn)Vn[e](t,!0)};st.ajaxSettings.xhr=e.ActiveXObject?function(){return!this.isLocal&&_()||F()}:_,Yn=st.ajaxSettings.xhr(),st.support.cors=!!Yn&&"withCredentials"in Yn,Yn=st.support.ajax=!!Yn,Yn&&st.ajaxTransport(function(n){if(!n.crossDomain||st.support.cors){var r;return{send:function(i,o){var a,s,u=n.xhr();if(n.username?u.open(n.type,n.url,n.async,n.username,n.password):u.open(n.type,n.url,n.async),n.xhrFields)for(s in n.xhrFields)u[s]=n.xhrFields[s];n.mimeType&&u.overrideMimeType&&u.overrideMimeType(n.mimeType),n.crossDomain||i["X-Requested-With"]||(i["X-Requested-With"]="XMLHttpRequest");try{for(s in i)u.setRequestHeader(s,i[s])}catch(l){}u.send(n.hasContent&&n.data||null),r=function(e,i){var s,l,c,f,p;try{if(r&&(i||4===u.readyState))if(r=t,a&&(u.onreadystatechange=st.noop,Gn&&delete Vn[a]),i)4!==u.readyState&&u.abort();else{f={},s=u.status,p=u.responseXML,c=u.getAllResponseHeaders(),p&&p.documentElement&&(f.xml=p),"string"==typeof u.responseText&&(f.text=u.responseText);try{l=u.statusText}catch(d){l=""}s||!n.isLocal||n.crossDomain?1223===s&&(s=204):s=f.text?200:404}}catch(h){i||o(-1,h)}f&&o(s,l,f,c)},n.async?4===u.readyState?setTimeout(r):(a=++Jn,Gn&&(Vn||(Vn={},st(e).unload(Gn)),Vn[a]=r),u.onreadystatechange=r):r()},abort:function(){r&&r(t,!0)}}}});var Qn,Kn,Zn=/^(?:toggle|show|hide)$/,er=RegExp("^(?:([+-])=|)("+ut+")([a-z%]*)$","i"),tr=/queueHooks$/,nr=[W],rr={"*":[function(e,t){var n,r,i=this.createTween(e,t),o=er.exec(t),a=i.cur(),s=+a||0,u=1,l=20;if(o){if(n=+o[2],r=o[3]||(st.cssNumber[e]?"":"px"),"px"!==r&&s){s=st.css(i.elem,e,!0)||n||1;do u=u||".5",s/=u,st.style(i.elem,e,s+r);while(u!==(u=i.cur()/a)&&1!==u&&--l)}i.unit=r,i.start=s,i.end=o[1]?s+(o[1]+1)*n:n}return i}]};st.Animation=st.extend(P,{tweener:function(e,t){st.isFunction(e)?(t=e,e=["*"]):e=e.split(" ");for(var n,r=0,i=e.length;i>r;r++)n=e[r],rr[n]=rr[n]||[],rr[n].unshift(t)},prefilter:function(e,t){t?nr.unshift(e):nr.push(e)}}),st.Tween=$,$.prototype={constructor:$,init:function(e,t,n,r,i,o){this.elem=e,this.prop=n,this.easing=i||"swing",this.options=t,this.start=this.now=this.cur(),this.end=r,this.unit=o||(st.cssNumber[n]?"":"px")},cur:function(){var e=$.propHooks[this.prop];return e&&e.get?e.get(this):$.propHooks._default.get(this)},run:function(e){var t,n=$.propHooks[this.prop];return this.pos=t=this.options.duration?st.easing[this.easing](e,this.options.duration*e,0,1,this.options.duration):e,this.now=(this.end-this.start)*t+this.start,this.options.step&&this.options.step.call(this.elem,this.now,this),n&&n.set?n.set(this):$.propHooks._default.set(this),this}},$.prototype.init.prototype=$.prototype,$.propHooks={_default:{get:function(e){var t;return null==e.elem[e.prop]||e.elem.style&&null!=e.elem.style[e.prop]?(t=st.css(e.elem,e.prop,"auto"),t&&"auto"!==t?t:0):e.elem[e.prop]},set:function(e){st.fx.step[e.prop]?st.fx.step[e.prop](e):e.elem.style&&(null!=e.elem.style[st.cssProps[e.prop]]||st.cssHooks[e.prop])?st.style(e.elem,e.prop,e.now+e.unit):e.elem[e.prop]=e.now}}},$.propHooks.scrollTop=$.propHooks.scrollLeft={set:function(e){e.elem.nodeType&&e.elem.parentNode&&(e.elem[e.prop]=e.now)}},st.each(["toggle","show","hide"],function(e,t){var n=st.fn[t];st.fn[t]=function(e,r,i){return null==e||"boolean"==typeof e?n.apply(this,arguments):this.animate(I(t,!0),e,r,i)}}),st.fn.extend({fadeTo:function(e,t,n,r){return this.filter(w).css("opacity",0).show().end().animate({opacity:t},e,n,r)},animate:function(e,t,n,r){var i=st.isEmptyObject(e),o=st.speed(t,n,r),a=function(){var t=P(this,st.extend({},e),o);a.finish=function(){t.stop(!0)},(i||st._data(this,"finish"))&&t.stop(!0)};return a.finish=a,i||o.queue===!1?this.each(a):this.queue(o.queue,a)},stop:function(e,n,r){var i=function(e){var t=e.stop;delete e.stop,t(r)};return"string"!=typeof e&&(r=n,n=e,e=t),n&&e!==!1&&this.queue(e||"fx",[]),this.each(function(){var t=!0,n=null!=e&&e+"queueHooks",o=st.timers,a=st._data(this);if(n)a[n]&&a[n].stop&&i(a[n]);else for(n in a)a[n]&&a[n].stop&&tr.test(n)&&i(a[n]);for(n=o.length;n--;)o[n].elem!==this||null!=e&&o[n].queue!==e||(o[n].anim.stop(r),t=!1,o.splice(n,1));(t||!r)&&st.dequeue(this,e)})},finish:function(e){return e!==!1&&(e=e||"fx"),this.each(function(){var t,n=st._data(this),r=n[e+"queue"],i=n[e+"queueHooks"],o=st.timers,a=r?r.length:0;for(n.finish=!0,st.queue(this,e,[]),i&&i.cur&&i.cur.finish&&i.cur.finish.call(this),t=o.length;t--;)o[t].elem===this&&o[t].queue===e&&(o[t].anim.stop(!0),o.splice(t,1));for(t=0;a>t;t++)r[t]&&r[t].finish&&r[t].finish.call(this);delete n.finish})}}),st.each({slideDown:I("show"),slideUp:I("hide"),slideToggle:I("toggle"),fadeIn:{opacity:"show"},fadeOut:{opacity:"hide"},fadeToggle:{opacity:"toggle"}},function(e,t){st.fn[e]=function(e,n,r){return this.animate(t,e,n,r)}}),st.speed=function(e,t,n){var r=e&&"object"==typeof e?st.extend({},e):{complete:n||!n&&t||st.isFunction(e)&&e,duration:e,easing:n&&t||t&&!st.isFunction(t)&&t};return r.duration=st.fx.off?0:"number"==typeof r.duration?r.duration:r.duration in st.fx.speeds?st.fx.speeds[r.duration]:st.fx.speeds._default,(null==r.queue||r.queue===!0)&&(r.queue="fx"),r.old=r.complete,r.complete=function(){st.isFunction(r.old)&&r.old.call(this),r.queue&&st.dequeue(this,r.queue)},r},st.easing={linear:function(e){return e},swing:function(e){return.5-Math.cos(e*Math.PI)/2}},st.timers=[],st.fx=$.prototype.init,st.fx.tick=function(){var e,n=st.timers,r=0;for(Qn=st.now();n.length>r;r++)e=n[r],e()||n[r]!==e||n.splice(r--,1);n.length||st.fx.stop(),Qn=t},st.fx.timer=function(e){e()&&st.timers.push(e)&&st.fx.start()},st.fx.interval=13,st.fx.start=function(){Kn||(Kn=setInterval(st.fx.tick,st.fx.interval))},st.fx.stop=function(){clearInterval(Kn),Kn=null},st.fx.speeds={slow:600,fast:200,_default:400},st.fx.step={},st.expr&&st.expr.filters&&(st.expr.filters.animated=function(e){return st.grep(st.timers,function(t){return e===t.elem}).length}),st.fn.offset=function(e){if(arguments.length)return e===t?this:this.each(function(t){st.offset.setOffset(this,e,t)});var n,r,i={top:0,left:0},o=this[0],a=o&&o.ownerDocument;if(a)return n=a.documentElement,st.contains(n,o)?(o.getBoundingClientRect!==t&&(i=o.getBoundingClientRect()),r=z(a),{top:i.top+(r.pageYOffset||n.scrollTop)-(n.clientTop||0),left:i.left+(r.pageXOffset||n.scrollLeft)-(n.clientLeft||0)}):i},st.offset={setOffset:function(e,t,n){var r=st.css(e,"position");"static"===r&&(e.style.position="relative");var i,o,a=st(e),s=a.offset(),u=st.css(e,"top"),l=st.css(e,"left"),c=("absolute"===r||"fixed"===r)&&st.inArray("auto",[u,l])>-1,f={},p={};c?(p=a.position(),i=p.top,o=p.left):(i=parseFloat(u)||0,o=parseFloat(l)||0),st.isFunction(t)&&(t=t.call(e,n,s)),null!=t.top&&(f.top=t.top-s.top+i),null!=t.left&&(f.left=t.left-s.left+o),"using"in t?t.using.call(e,f):a.css(f)}},st.fn.extend({position:function(){if(this[0]){var e,t,n={top:0,left:0},r=this[0];return"fixed"===st.css(r,"position")?t=r.getBoundingClientRect():(e=this.offsetParent(),t=this.offset(),st.nodeName(e[0],"html")||(n=e.offset()),n.top+=st.css(e[0],"borderTopWidth",!0),n.left+=st.css(e[0],"borderLeftWidth",!0)),{top:t.top-n.top-st.css(r,"marginTop",!0),left:t.left-n.left-st.css(r,"marginLeft",!0)}}},offsetParent:function(){return this.map(function(){for(var e=this.offsetParent||V.documentElement;e&&!st.nodeName(e,"html")&&"static"===st.css(e,"position");)e=e.offsetParent;return e||V.documentElement})}}),st.each({scrollLeft:"pageXOffset",scrollTop:"pageYOffset"},function(e,n){var r=/Y/.test(n);st.fn[e]=function(i){return st.access(this,function(e,i,o){var a=z(e);return o===t?a?n in a?a[n]:a.document.documentElement[i]:e[i]:(a?a.scrollTo(r?st(a).scrollLeft():o,r?o:st(a).scrollTop()):e[i]=o,t)},e,i,arguments.length,null)}}),st.each({Height:"height",Width:"width"},function(e,n){st.each({padding:"inner"+e,content:n,"":"outer"+e},function(r,i){st.fn[i]=function(i,o){var a=arguments.length&&(r||"boolean"!=typeof i),s=r||(i===!0||o===!0?"margin":"border");return st.access(this,function(n,r,i){var o;return st.isWindow(n)?n.document.documentElement["client"+e]:9===n.nodeType?(o=n.documentElement,Math.max(n.body["scroll"+e],o["scroll"+e],n.body["offset"+e],o["offset"+e],o["client"+e])):i===t?st.css(n,r,s):st.style(n,r,i,s)},n,a?i:t,a,null)}})}),e.jQuery=e.$=st,"function"==typeof define&&define.amd&&define.amd.jQuery&&define("jquery",[],function(){return st})})(window);
//@ sourceMappingURL=jquery.min.map                                                                                                                    master/js/._jquery.cookie.js                                                                        000755  000767  000024  00000000342 12165642620 016773  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                             Mac OS X            	   2   �      �                                      ATTR       �   �   J                  �   J  com.apple.quarantine q/0001;51e46ecd;Google\x20Chrome.app;46D60EE0-D2B4-4089-BED0-01EC145BF63F                                                                                                                                                                                                                                                                                               master/js/jquery.cookie.js                                                                          000755  000767  000024  00000004420 12165642620 016557  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         /*!
 * jQuery Cookie Plugin v1.3.1
 * https://github.com/carhartl/jquery-cookie
 *
 * Copyright 2013 Klaus Hartl
 * Released under the MIT license
 */
(function (factory) {
	if (typeof define === 'function' && define.amd) {
		// AMD. Register as anonymous module.
		define(['jquery'], factory);
	} else {
		// Browser globals.
		factory(jQuery);
	}
}(function ($) {

	var pluses = /\+/g;

	function raw(s) {
		return s;
	}

	function decoded(s) {
		return decodeURIComponent(s.replace(pluses, ' '));
	}

	function converted(s) {
		if (s.indexOf('"') === 0) {
			// This is a quoted cookie as according to RFC2068, unescape
			s = s.slice(1, -1).replace(/\\"/g, '"').replace(/\\\\/g, '\\');
		}
		try {
			return config.json ? JSON.parse(s) : s;
		} catch(er) {}
	}

	var config = $.cookie = function (key, value, options) {

		// write
		if (value !== undefined) {
			options = $.extend({}, config.defaults, options);

			if (typeof options.expires === 'number') {
				var days = options.expires, t = options.expires = new Date();
				t.setDate(t.getDate() + days);
			}

			value = config.json ? JSON.stringify(value) : String(value);

			return (document.cookie = [
				config.raw ? key : encodeURIComponent(key),
				'=',
				config.raw ? value : encodeURIComponent(value),
				options.expires ? '; expires=' + options.expires.toUTCString() : '', // use expires attribute, max-age is not supported by IE
				options.path    ? '; path=' + options.path : '',
				options.domain  ? '; domain=' + options.domain : '',
				options.secure  ? '; secure' : ''
			].join(''));
		}

		// read
		var decode = config.raw ? raw : decoded;
		var cookies = document.cookie.split('; ');
		var result = key ? undefined : {};
		for (var i = 0, l = cookies.length; i < l; i++) {
			var parts = cookies[i].split('=');
			var name = decode(parts.shift());
			var cookie = decode(parts.join('='));

			if (key && key === name) {
				result = converted(cookie);
				break;
			}

			if (!key) {
				result[name] = converted(cookie);
			}
		}

		return result;
	};

	config.defaults = {};

	$.removeCookie = function (key, options) {
		if ($.cookie(key) !== undefined) {
			// Must not alter options, thus extending a fresh object...
			$.cookie(key, '', $.extend({}, options, { expires: -1 }));
			return true;
		}
		return false;
	};

}));
                                                                                                                                                                                                                                                master/js/less-1.3.3.min.js                                                                         000644  000767  000024  00000161511 12136500402 016147  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         //
// LESS - Leaner CSS v1.3.3
// http://lesscss.org
// 
// Copyright (c) 2009-2013, Alexis Sellier
// Licensed under the Apache 2.0 License.
//
(function(e,t){function n(t){return e.less[t.split("/")[1]]}function f(){r.env==="development"?(r.optimization=0,r.watchTimer=setInterval(function(){r.watchMode&&g(function(e,t,n,r,i){t&&S(t.toCSS(),r,i.lastModified)})},r.poll)):r.optimization=3}function m(){var e=document.getElementsByTagName("style");for(var t=0;t<e.length;t++)e[t].type.match(p)&&(new r.Parser({filename:document.location.href.replace(/#.*$/,""),dumpLineNumbers:r.dumpLineNumbers})).parse(e[t].innerHTML||"",function(n,r){var i=r.toCSS(),s=e[t];s.type="text/css",s.styleSheet?s.styleSheet.cssText=i:s.innerHTML=i})}function g(e,t){for(var n=0;n<r.sheets.length;n++)w(r.sheets[n],e,t,r.sheets.length-(n+1))}function y(e,t){var n=b(e),r=b(t),i,s,o,u,a="";if(n.hostPart!==r.hostPart)return"";s=Math.max(r.directories.length,n.directories.length);for(i=0;i<s;i++)if(r.directories[i]!==n.directories[i])break;u=r.directories.slice(i),o=n.directories.slice(i);for(i=0;i<u.length-1;i++)a+="../";for(i=0;i<o.length-1;i++)a+=o[i]+"/";return a}function b(e,t){var n=/^((?:[a-z-]+:)?\/\/(?:[^\/\?#]*\/)|([\/\\]))?((?:[^\/\\\?#]*[\/\\])*)([^\/\\\?#]*)([#\?].*)?$/,r=e.match(n),i={},s=[],o,u;if(!r)throw new Error("Could not parse sheet href - '"+e+"'");if(!r[1]||r[2]){u=t.match(n);if(!u)throw new Error("Could not parse page url - '"+t+"'");r[1]=u[1],r[2]||(r[3]=u[3]+r[3])}if(r[3]){s=r[3].replace("\\","/").split("/");for(o=0;o<s.length;o++)s[o]===".."&&o>0&&(s.splice(o-1,2),o-=2)}return i.hostPart=r[1],i.directories=s,i.path=r[1]+s.join("/"),i.fileUrl=i.path+(r[4]||""),i.url=i.fileUrl+(r[5]||""),i}function w(t,n,i,s){var o=t.contents||{},u=t.files||{},a=b(t.href,e.location.href),f=a.url,c=l&&l.getItem(f),h=l&&l.getItem(f+":timestamp"),p={css:c,timestamp:h},d;r.relativeUrls?r.rootpath?t.entryPath?d=b(r.rootpath+y(a.path,t.entryPath)).path:d=r.rootpath:d=a.path:r.rootpath?d=r.rootpath:t.entryPath?d=t.entryPath:d=a.path,x(f,t.type,function(e,l){v+=e.replace(/@import .+?;/ig,"");if(!i&&p&&l&&(new Date(l)).valueOf()===(new Date(p.timestamp)).valueOf())S(p.css,t),n(null,null,e,t,{local:!0,remaining:s},f);else try{o[f]=e,(new r.Parser({optimization:r.optimization,paths:[a.path],entryPath:t.entryPath||a.path,mime:t.type,filename:f,rootpath:d,relativeUrls:t.relativeUrls,contents:o,files:u,dumpLineNumbers:r.dumpLineNumbers})).parse(e,function(r,i){if(r)return k(r,f);try{n(r,i,e,t,{local:!1,lastModified:l,remaining:s},f),N(document.getElementById("less-error-message:"+E(f)))}catch(r){k(r,f)}})}catch(c){k(c,f)}},function(e,t){throw new Error("Couldn't load "+t+" ("+e+")")})}function E(e){return e.replace(/^[a-z]+:\/\/?[^\/]+/,"").replace(/^\//,"").replace(/\.[a-zA-Z]+$/,"").replace(/[^\.\w-]+/g,"-").replace(/\./g,":")}function S(e,t,n){var r,i=t.href||"",s="less:"+(t.title||E(i));if((r=document.getElementById(s))===null){r=document.createElement("style"),r.type="text/css",t.media&&(r.media=t.media),r.id=s;var o=t&&t.nextSibling||null;(o||document.getElementsByTagName("head")[0]).parentNode.insertBefore(r,o)}if(r.styleSheet)try{r.styleSheet.cssText=e}catch(u){throw new Error("Couldn't reassign styleSheet.cssText.")}else(function(e){r.childNodes.length>0?r.firstChild.nodeValue!==e.nodeValue&&r.replaceChild(e,r.firstChild):r.appendChild(e)})(document.createTextNode(e));if(n&&l){C("saving "+i+" to cache.");try{l.setItem(i,e),l.setItem(i+":timestamp",n)}catch(u){C("failed to save")}}}function x(e,t,n,i){function a(t,n,r){t.status>=200&&t.status<300?n(t.responseText,t.getResponseHeader("Last-Modified")):typeof r=="function"&&r(t.status,e)}var s=T(),u=o?r.fileAsync:r.async;typeof s.overrideMimeType=="function"&&s.overrideMimeType("text/css"),s.open("GET",e,u),s.setRequestHeader("Accept",t||"text/x-less, text/css; q=0.9, */*; q=0.5"),s.send(null),o&&!r.fileAsync?s.status===0||s.status>=200&&s.status<300?n(s.responseText):i(s.status,e):u?s.onreadystatechange=function(){s.readyState==4&&a(s,n,i)}:a(s,n,i)}function T(){if(e.XMLHttpRequest)return new XMLHttpRequest;try{return new ActiveXObject("MSXML2.XMLHTTP.3.0")}catch(t){return C("browser doesn't support AJAX."),null}}function N(e){return e&&e.parentNode.removeChild(e)}function C(e){r.env=="development"&&typeof console!="undefined"&&console.log("less: "+e)}function k(e,t){var n="less-error-message:"+E(t),i='<li><label>{line}</label><pre class="{class}">{content}</pre></li>',s=document.createElement("div"),o,u,a=[],f=e.filename||t,l=f.match(/([^\/]+(\?.*)?)$/)[1];s.id=n,s.className="less-error-message",u="<h3>"+(e.message||"There is an error in your .less file")+"</h3>"+'<p>in <a href="'+f+'">'+l+"</a> ";var c=function(e,t,n){e.extract[t]&&a.push(i.replace(/\{line\}/,parseInt(e.line)+(t-1)).replace(/\{class\}/,n).replace(/\{content\}/,e.extract[t]))};e.stack?u+="<br/>"+e.stack.split("\n").slice(1).join("<br/>"):e.extract&&(c(e,0,""),c(e,1,"line"),c(e,2,""),u+="on line "+e.line+", column "+(e.column+1)+":</p>"+"<ul>"+a.join("")+"</ul>"),s.innerHTML=u,S([".less-error-message ul, .less-error-message li {","list-style-type: none;","margin-right: 15px;","padding: 4px 0;","margin: 0;","}",".less-error-message label {","font-size: 12px;","margin-right: 15px;","padding: 4px 0;","color: #cc7777;","}",".less-error-message pre {","color: #dd6666;","padding: 4px 0;","margin: 0;","display: inline-block;","}",".less-error-message pre.line {","color: #ff0000;","}",".less-error-message h3 {","font-size: 20px;","font-weight: bold;","padding: 15px 0 5px 0;","margin: 0;","}",".less-error-message a {","color: #10a","}",".less-error-message .error {","color: red;","font-weight: bold;","padding-bottom: 2px;","border-bottom: 1px dashed red;","}"].join("\n"),{title:"error-message"}),s.style.cssText=["font-family: Arial, sans-serif","border: 1px solid #e00","background-color: #eee","border-radius: 5px","-webkit-border-radius: 5px","-moz-border-radius: 5px","color: #e00","padding: 15px","margin-bottom: 15px"].join(";"),r.env=="development"&&(o=setInterval(function(){document.body&&(document.getElementById(n)?document.body.replaceChild(s,document.getElementById(n)):document.body.insertBefore(s,document.body.firstChild),clearInterval(o))},10))}Array.isArray||(Array.isArray=function(e){return Object.prototype.toString.call(e)==="[object Array]"||e instanceof Array}),Array.prototype.forEach||(Array.prototype.forEach=function(e,t){var n=this.length>>>0;for(var r=0;r<n;r++)r in this&&e.call(t,this[r],r,this)}),Array.prototype.map||(Array.prototype.map=function(e){var t=this.length>>>0,n=new Array(t),r=arguments[1];for(var i=0;i<t;i++)i in this&&(n[i]=e.call(r,this[i],i,this));return n}),Array.prototype.filter||(Array.prototype.filter=function(e){var t=[],n=arguments[1];for(var r=0;r<this.length;r++)e.call(n,this[r])&&t.push(this[r]);return t}),Array.prototype.reduce||(Array.prototype.reduce=function(e){var t=this.length>>>0,n=0;if(t===0&&arguments.length===1)throw new TypeError;if(arguments.length>=2)var r=arguments[1];else do{if(n in this){r=this[n++];break}if(++n>=t)throw new TypeError}while(!0);for(;n<t;n++)n in this&&(r=e.call(null,r,this[n],n,this));return r}),Array.prototype.indexOf||(Array.prototype.indexOf=function(e){var t=this.length,n=arguments[1]||0;if(!t)return-1;if(n>=t)return-1;n<0&&(n+=t);for(;n<t;n++){if(!Object.prototype.hasOwnProperty.call(this,n))continue;if(e===this[n])return n}return-1}),Object.keys||(Object.keys=function(e){var t=[];for(var n in e)Object.prototype.hasOwnProperty.call(e,n)&&t.push(n);return t}),String.prototype.trim||(String.prototype.trim=function(){return String(this).replace(/^\s\s*/,"").replace(/\s\s*$/,"")});var r,i,s;typeof environment=="object"&&{}.toString.call(environment)==="[object Environment]"?(typeof e=="undefined"?r={}:r=e.less={},i=r.tree={},r.mode="rhino"):typeof e=="undefined"?(r=exports,i=n("./tree"),r.mode="node"):(typeof e.less=="undefined"&&(e.less={}),r=e.less,i=e.less.tree={},r.mode="browser"),r.Parser=function(t){function g(){a=c[u],f=o,h=o}function y(){c[u]=a,o=f,h=o}function b(){o>h&&(c[u]=c[u].slice(o-h),h=o)}function w(e){var t=e.charCodeAt(0);return t===32||t===10||t===9}function E(e){var t,n,r,i,a;if(e instanceof Function)return e.call(p.parsers);if(typeof e=="string")t=s.charAt(o)===e?e:null,r=1,b();else{b();if(!(t=e.exec(c[u])))return null;r=t[0].length}if(t)return S(r),typeof t=="string"?t:t.length===1?t[0]:t}function S(e){var t=o,n=u,r=o+c[u].length,i=o+=e;while(o<r){if(!w(s.charAt(o)))break;o++}return c[u]=c[u].slice(e+(o-i)),h=o,c[u].length===0&&u<c.length-1&&u++,t!==o||n!==u}function x(e,t){var n=E(e);if(!!n)return n;T(t||(typeof e=="string"?"expected '"+e+"' got '"+s.charAt(o)+"'":"unexpected token"))}function T(e,t){var n=new Error(e);throw n.index=o,n.type=t||"Syntax",n}function N(e){return typeof e=="string"?s.charAt(o)===e:e.test(c[u])?!0:!1}function C(e,t){return e.filename&&t.filename&&e.filename!==t.filename?p.imports.contents[e.filename]:s}function k(e,t){for(var n=e,r=-1;n>=0&&t.charAt(n)!=="\n";n--)r++;return{line:typeof e=="number"?(t.slice(0,e).match(/\n/g)||"").length:null,column:r}}function L(e){return r.mode==="browser"||r.mode==="rhino"?e.filename:n("path").resolve(e.filename)}function A(e,t,n){return{lineNumber:k(e,t).line+1,fileName:L(n)}}function O(e,t){var n=C(e,t),r=k(e.index,n),i=r.line,s=r.column,o=n.split("\n");this.type=e.type||"Syntax",this.message=e.message,this.filename=e.filename||t.filename,this.index=e.index,this.line=typeof i=="number"?i+1:null,this.callLine=e.call&&k(e.call,n).line+1,this.callExtract=o[k(e.call,n).line],this.stack=e.stack,this.column=s,this.extract=[o[i-1],o[i],o[i+1]]}var s,o,u,a,f,l,c,h,p,d=this,t=t||{};t.contents||(t.contents={}),t.rootpath=t.rootpath||"",t.files||(t.files={});var v=function(){},m=this.imports={paths:t.paths||[],queue:[],files:t.files,contents:t.contents,mime:t.mime,error:null,push:function(e,n){var i=this;this.queue.push(e),r.Parser.importer(e,this.paths,function(t,r,s){i.queue.splice(i.queue.indexOf(e),1);var o=s in i.files;i.files[s]=r,t&&!i.error&&(i.error=t),n(t,r,o),i.queue.length===0&&v(i.error)},t)}};return this.env=t=t||{},this.optimization="optimization"in this.env?this.env.optimization:1,this.env.filename=this.env.filename||null,p={imports:m,parse:function(e,a){var f,d,m,g,y,b,w=[],S,x=null;o=u=h=l=0,s=e.replace(/\r\n/g,"\n"),s=s.replace(/^\uFEFF/,""),c=function(e){var n=0,r=/(?:@\{[\w-]+\}|[^"'`\{\}\/\(\)\\])+/g,i=/\/\*(?:[^*]|\*+[^\/*])*\*+\/|\/\/.*/g,o=/"((?:[^"\\\r\n]|\\.)*)"|'((?:[^'\\\r\n]|\\.)*)'|`((?:[^`]|\\.)*)`/g,u=0,a,f=e[0],l;for(var c=0,h,p;c<s.length;){r.lastIndex=c,(a=r.exec(s))&&a.index===c&&(c+=a[0].length,f.push(a[0])),h=s.charAt(c),i.lastIndex=o.lastIndex=c;if(a=o.exec(s))if(a.index===c){c+=a[0].length,f.push(a[0]);continue}if(!l&&h==="/"){p=s.charAt(c+1);if(p==="/"||p==="*")if(a=i.exec(s))if(a.index===c){c+=a[0].length,f.push(a[0]);continue}}switch(h){case"{":if(!l){u++,f.push(h);break};case"}":if(!l){u--,f.push(h),e[++n]=f=[];break};case"(":if(!l){l=!0,f.push(h);break};case")":if(l){l=!1,f.push(h);break};default:f.push(h)}c++}return u!=0&&(x=new O({index:c-1,type:"Parse",message:u>0?"missing closing `}`":"missing opening `{`",filename:t.filename},t)),e.map(function(e){return e.join("")})}([[]]);if(x)return a(x,t);try{f=new i.Ruleset([],E(this.parsers.primary)),f.root=!0}catch(T){return a(new O(T,t))}f.toCSS=function(e){var s,o,u;return function(s,o){var u=[],a;s=s||{},typeof o=="object"&&!Array.isArray(o)&&(o=Object.keys(o).map(function(e){var t=o[e];return t instanceof i.Value||(t instanceof i.Expression||(t=new i.Expression([t])),t=new i.Value([t])),new i.Rule("@"+e,t,!1,0)}),u=[new i.Ruleset(null,o)]);try{var f=e.call(this,{frames:u}).toCSS([],{compress:s.compress||!1,dumpLineNumbers:t.dumpLineNumbers})}catch(l){throw new O(l,t)}if(a=p.imports.error)throw a instanceof O?a:new O(a,t);return s.yuicompress&&r.mode==="node"?n("ycssmin").cssmin(f):s.compress?f.replace(/(\s)+/g,"$1"):f}}(f.eval);if(o<s.length-1){o=l,b=s.split("\n"),y=(s.slice(0,o).match(/\n/g)||"").length+1;for(var N=o,C=-1;N>=0&&s.charAt(N)!=="\n";N--)C++;x={type:"Parse",message:"Syntax Error on line "+y,index:o,filename:t.filename,line:y,column:C,extract:[b[y-2],b[y-1],b[y]]}}this.imports.queue.length>0?v=function(e){e=x||e,e?a(e):a(null,f)}:a(x,f)},parsers:{primary:function(){var e,t=[];while((e=E(this.mixin.definition)||E(this.rule)||E(this.ruleset)||E(this.mixin.call)||E(this.comment)||E(this.directive))||E(/^[\s\n]+/)||E(/^;+/))e&&t.push(e);return t},comment:function(){var e;if(s.charAt(o)!=="/")return;if(s.charAt(o+1)==="/")return new i.Comment(E(/^\/\/.*/),!0);if(e=E(/^\/\*(?:[^*]|\*+[^\/*])*\*+\/\n?/))return new i.Comment(e)},entities:{quoted:function(){var e,t=o,n;s.charAt(t)==="~"&&(t++,n=!0);if(s.charAt(t)!=='"'&&s.charAt(t)!=="'")return;n&&E("~");if(e=E(/^"((?:[^"\\\r\n]|\\.)*)"|'((?:[^'\\\r\n]|\\.)*)'/))return new i.Quoted(e[0],e[1]||e[2],n)},keyword:function(){var e;if(e=E(/^[_A-Za-z-][_A-Za-z0-9-]*/))return i.colors.hasOwnProperty(e)?new i.Color(i.colors[e].slice(1)):new i.Keyword(e)},call:function(){var e,n,r,s,a=o;if(!(e=/^([\w-]+|%|progid:[\w\.]+)\(/.exec(c[u])))return;e=e[1],n=e.toLowerCase();if(n==="url")return null;o+=e.length;if(n==="alpha"){s=E(this.alpha);if(typeof s!="undefined")return s}E("("),r=E(this.entities.arguments);if(!E(")"))return;if(e)return new i.Call(e,r,a,t.filename)},arguments:function(){var e=[],t;while(t=E(this.entities.assignment)||E(this.expression)){e.push(t);if(!E(","))break}return e},literal:function(){return E(this.entities.ratio)||E(this.entities.dimension)||E(this.entities.color)||E(this.entities.quoted)||E(this.entities.unicodeDescriptor)},assignment:function(){var e,t;if((e=E(/^\w+(?=\s?=)/i))&&E("=")&&(t=E(this.entity)))return new i.Assignment(e,t)},url:function(){var e;if(s.charAt(o)!=="u"||!E(/^url\(/))return;return e=E(this.entities.quoted)||E(this.entities.variable)||E(/^(?:(?:\\[\(\)'"])|[^\(\)'"])+/)||"",x(")"),new i.URL(e.value!=null||e instanceof i.Variable?e:new i.Anonymous(e),t.rootpath)},variable:function(){var e,n=o;if(s.charAt(o)==="@"&&(e=E(/^@@?[\w-]+/)))return new i.Variable(e,n,t.filename)},variableCurly:function(){var e,n,r=o;if(s.charAt(o)==="@"&&(n=E(/^@\{([\w-]+)\}/)))return new i.Variable("@"+n[1],r,t.filename)},color:function(){var e;if(s.charAt(o)==="#"&&(e=E(/^#([A-Fa-f0-9]{6}|[A-Fa-f0-9]{3})/)))return new i.Color(e[1])},dimension:function(){var e,t=s.charCodeAt(o);if(t>57||t<43||t===47||t==44)return;if(e=E(/^([+-]?\d*\.?\d+)(px|%|em|pc|ex|in|deg|s|ms|pt|cm|mm|rad|grad|turn|dpi|dpcm|dppx|rem|vw|vh|vmin|vm|ch)?/))return new i.Dimension(e[1],e[2])},ratio:function(){var e,t=s.charCodeAt(o);if(t>57||t<48)return;if(e=E(/^(\d+\/\d+)/))return new i.Ratio(e[1])},unicodeDescriptor:function(){var e;if(e=E(/^U\+[0-9a-fA-F?]+(\-[0-9a-fA-F?]+)?/))return new i.UnicodeDescriptor(e[0])},javascript:function(){var e,t=o,n;s.charAt(t)==="~"&&(t++,n=!0);if(s.charAt(t)!=="`")return;n&&E("~");if(e=E(/^`([^`]*)`/))return new i.JavaScript(e[1],o,n)}},variable:function(){var e;if(s.charAt(o)==="@"&&(e=E(/^(@[\w-]+)\s*:/)))return e[1]},shorthand:function(){var e,t;if(!N(/^[@\w.%-]+\/[@\w.-]+/))return;g();if((e=E(this.entity))&&E("/")&&(t=E(this.entity)))return new i.Shorthand(e,t);y()},mixin:{call:function(){var e=[],n,r,u=[],a=[],f,l,c,h,p,d,v,m=o,b=s.charAt(o),w,S,C=!1;if(b!=="."&&b!=="#")return;g();while(n=E(/^[#.](?:[\w-]|\\(?:[A-Fa-f0-9]{1,6} ?|[^A-Fa-f0-9]))+/))e.push(new i.Element(r,n,o)),r=E(">");if(E("(")){p=[];while(c=E(this.expression)){h=null,S=c;if(c.value.length==1){var k=c.value[0];k instanceof i.Variable&&E(":")&&(p.length>0&&(d&&T("Cannot mix ; and , as delimiter types"),v=!0),S=x(this.expression),h=w=k.name)}p.push(S),a.push({name:h,value:S});if(E(","))continue;if(E(";")||d)v&&T("Cannot mix ; and , as delimiter types"),d=!0,p.length>1&&(S=new i.Value(p)),u.push({name:w,value:S}),w=null,p=[],v=!1}x(")")}f=d?u:a,E(this.important)&&(C=!0);if(e.length>0&&(E(";")||N("}")))return new i.mixin.Call(e,f,m,t.filename,C);y()},definition:function(){var e,t=[],n,r,u,a,f,c=!1;if(s.charAt(o)!=="."&&s.charAt(o)!=="#"||N(/^[^{]*\}/))return;g();if(n=E(/^([#.](?:[\w-]|\\(?:[A-Fa-f0-9]{1,6} ?|[^A-Fa-f0-9]))+)\s*\(/)){e=n[1];do{E(this.comment);if(s.charAt(o)==="."&&E(/^\.{3}/)){c=!0,t.push({variadic:!0});break}if(!(u=E(this.entities.variable)||E(this.entities.literal)||E(this.entities.keyword)))break;if(u instanceof i.Variable)if(E(":"))a=x(this.expression,"expected expression"),t.push({name:u.name,value:a});else{if(E(/^\.{3}/)){t.push({name:u.name,variadic:!0}),c=!0;break}t.push({name:u.name})}else t.push({value:u})}while(E(",")||E(";"));E(")")||(l=o,y()),E(this.comment),E(/^when/)&&(f=x(this.conditions,"expected condition")),r=E(this.block);if(r)return new i.mixin.Definition(e,t,r,f,c);y()}}},entity:function(){return E(this.entities.literal)||E(this.entities.variable)||E(this.entities.url)||E(this.entities.call)||E(this.entities.keyword)||E(this.entities.javascript)||E(this.comment)},end:function(){return E(";")||N("}")},alpha:function(){var e;if(!E(/^\(opacity=/i))return;if(e=E(/^\d+/)||E(this.entities.variable))return x(")"),new i.Alpha(e)},element:function(){var e,t,n,r;n=E(this.combinator),e=E(/^(?:\d+\.\d+|\d+)%/)||E(/^(?:[.#]?|:*)(?:[\w-]|[^\x00-\x9f]|\\(?:[A-Fa-f0-9]{1,6} ?|[^A-Fa-f0-9]))+/)||E("*")||E("&")||E(this.attribute)||E(/^\([^()@]+\)/)||E(/^[\.#](?=@)/)||E(this.entities.variableCurly),e||E("(")&&(r=E(this.entities.variableCurly)||E(this.entities.variable)||E(this.selector))&&E(")")&&(e=new i.Paren(r));if(e)return new i.Element(n,e,o)},combinator:function(){var e,t=s.charAt(o);if(t===">"||t==="+"||t==="~"||t==="|"){o++;while(s.charAt(o).match(/\s/))o++;return new i.Combinator(t)}return s.charAt(o-1).match(/\s/)?new i.Combinator(" "):new i.Combinator(null)},selector:function(){var e,t,n=[],r,u;if(E("("))return e=E(this.entity),E(")")?new i.Selector([new i.Element("",e,o)]):null;while(t=E(this.element)){r=s.charAt(o),n.push(t);if(r==="{"||r==="}"||r===";"||r===","||r===")")break}if(n.length>0)return new i.Selector(n)},attribute:function(){var e="",t,n,r;if(!E("["))return;if(t=E(/^(?:[_A-Za-z0-9-]|\\.)+/)||E(this.entities.quoted))(r=E(/^[|~*$^]?=/))&&(n=E(this.entities.quoted)||E(/^[\w-]+/))?e=[t,r,n.toCSS?n.toCSS():n].join(""):e=t;if(!E("]"))return;if(e)return"["+e+"]"},block:function(){var e;if(E("{")&&(e=E(this.primary))&&E("}"))return e},ruleset:function(){var e=[],n,r,u,a;g(),t.dumpLineNumbers&&(a=A(o,s,t));while(n=E(this.selector)){e.push(n),E(this.comment);if(!E(","))break;E(this.comment)}if(e.length>0&&(r=E(this.block))){var f=new i.Ruleset(e,r,t.strictImports);return t.dumpLineNumbers&&(f.debugInfo=a),f}l=o,y()},rule:function(){var e,t,n=s.charAt(o),r,a;g();if(n==="."||n==="#"||n==="&")return;if(e=E(this.variable)||E(this.property)){e.charAt(0)!="@"&&(a=/^([^@+\/'"*`(;{}-]*);/.exec(c[u]))?(o+=a[0].length-1,t=new i.Anonymous(a[1])):e==="font"?t=E(this.font):t=E(this.value),r=E(this.important);if(t&&E(this.end))return new i.Rule(e,t,r,f);l=o,y()}},"import":function(){var e,n,r=o;g();var s=E(/^@import(?:-(once))?\s+/);if(s&&(e=E(this.entities.quoted)||E(this.entities.url))){n=E(this.mediaFeatures);if(E(";"))return new i.Import(e,m,n,s[1]==="once",r,t.rootpath)}y()},mediaFeature:function(){var e,t,n=[];do if(e=E(this.entities.keyword))n.push(e);else if(E("(")){t=E(this.property),e=E(this.entity);if(!E(")"))return null;if(t&&e)n.push(new i.Paren(new i.Rule(t,e,null,o,!0)));else{if(!e)return null;n.push(new i.Paren(e))}}while(e);if(n.length>0)return new i.Expression(n)},mediaFeatures:function(){var e,t=[];do if(e=E(this.mediaFeature)){t.push(e);if(!E(","))break}else if(e=E(this.entities.variable)){t.push(e);if(!E(","))break}while(e);return t.length>0?t:null},media:function(){var e,n,r,u;t.dumpLineNumbers&&(u=A(o,s,t));if(E(/^@media/)){e=E(this.mediaFeatures);if(n=E(this.block))return r=new i.Media(n,e),t.dumpLineNumbers&&(r.debugInfo=u),r}},directive:function(){var e,n,r,u,a,f,l,c,h,p;if(s.charAt(o)!=="@")return;if(n=E(this["import"])||E(this.media))return n;g(),e=E(/^@[a-z-]+/);if(!e)return;l=e,e.charAt(1)=="-"&&e.indexOf("-",2)>0&&(l="@"+e.slice(e.indexOf("-",2)+1));switch(l){case"@font-face":c=!0;break;case"@viewport":case"@top-left":case"@top-left-corner":case"@top-center":case"@top-right":case"@top-right-corner":case"@bottom-left":case"@bottom-left-corner":case"@bottom-center":case"@bottom-right":case"@bottom-right-corner":case"@left-top":case"@left-middle":case"@left-bottom":case"@right-top":case"@right-middle":case"@right-bottom":c=!0;break;case"@page":case"@document":case"@supports":case"@keyframes":c=!0,h=!0;break;case"@namespace":p=!0}h&&(e+=" "+(E(/^[^{]+/)||"").trim());if(c){if(r=E(this.block))return new i.Directive(e,r)}else if((n=p?E(this.expression):E(this.entity))&&E(";")){var d=new i.Directive(e,n);return t.dumpLineNumbers&&(d.debugInfo=A(o,s,t)),d}y()},font:function(){var e=[],t=[],n,r,s,o;while(o=E(this.shorthand)||E(this.entity))t.push(o);e.push(new i.Expression(t));if(E(","))while(o=E(this.expression)){e.push(o);if(!E(","))break}return new i.Value(e)},value:function(){var e,t=[],n;while(e=E(this.expression)){t.push(e);if(!E(","))break}if(t.length>0)return new i.Value(t)},important:function(){if(s.charAt(o)==="!")return E(/^! *important/)},sub:function(){var e;if(E("(")&&(e=E(this.expression))&&E(")"))return e},multiplication:function(){var e,t,n,r;if(e=E(this.operand)){while(!N(/^\/[*\/]/)&&(n=E("/")||E("*"))&&(t=E(this.operand)))r=new i.Operation(n,[r||e,t]);return r||e}},addition:function(){var e,t,n,r;if(e=E(this.multiplication)){while((n=E(/^[-+]\s+/)||!w(s.charAt(o-1))&&(E("+")||E("-")))&&(t=E(this.multiplication)))r=new i.Operation(n,[r||e,t]);return r||e}},conditions:function(){var e,t,n=o,r;if(e=E(this.condition)){while(E(",")&&(t=E(this.condition)))r=new i.Condition("or",r||e,t,n);return r||e}},condition:function(){var e,t,n,r,s=o,u=!1;E(/^not/)&&(u=!0),x("(");if(e=E(this.addition)||E(this.entities.keyword)||E(this.entities.quoted))return(r=E(/^(?:>=|=<|[<=>])/))?(t=E(this.addition)||E(this.entities.keyword)||E(this.entities.quoted))?n=new i.Condition(r,e,t,s,u):T("expected expression"):n=new i.Condition("=",e,new i.Keyword("true"),s,u),x(")"),E(/^and/)?new i.Condition("and",n,E(this.condition)):n},operand:function(){var e,t=s.charAt(o+1);s.charAt(o)==="-"&&(t==="@"||t==="(")&&(e=E("-"));var n=E(this.sub)||E(this.entities.dimension)||E(this.entities.color)||E(this.entities.variable)||E(this.entities.call);return e?new i.Operation("*",[new i.Dimension(-1),n]):n},expression:function(){var e,t,n=[],r;while(e=E(this.addition)||E(this.entity))n.push(e);if(n.length>0)return new i.Expression(n)},property:function(){var e;if(e=E(/^(\*?-?[_a-z0-9-]+)\s*:/))return e[1]}}}};if(r.mode==="browser"||r.mode==="rhino")r.Parser.importer=function(e,t,n,r){!/^([a-z-]+:)?\//.test(e)&&t.length>0&&(e=t[0]+e),w({href:e,title:e,type:r.mime,contents:r.contents,files:r.files,rootpath:r.rootpath,entryPath:r.entryPath,relativeUrls:r.relativeUrls},function(e,i,s,o,u,a){e&&typeof r.errback=="function"?r.errback.call(null,a,t,n,r):n.call(null,e,i,a)},!0)};(function(e){function t(t){return e.functions.hsla(t.h,t.s,t.l,t.a)}function n(t,n){return t instanceof e.Dimension&&t.unit=="%"?parseFloat(t.value*n/100):r(t)}function r(t){if(t instanceof e.Dimension)return parseFloat(t.unit=="%"?t.value/100:t.value);if(typeof t=="number")return t;throw{error:"RuntimeError",message:"color functions take numbers as parameters"}}function i(e){return Math.min(1,Math.max(0,e))}e.functions={rgb:function(e,t,n){return this.rgba(e,t,n,1)},rgba:function(t,i,s,o){var u=[t,i,s].map(function(e){return n(e,256)});return o=r(o),new e.Color(u,o)},hsl:function(e,t,n){return this.hsla(e,t,n,1)},hsla:function(e,t,n,i){function u(e){return e=e<0?e+1:e>1?e-1:e,e*6<1?o+(s-o)*e*6:e*2<1?s:e*3<2?o+(s-o)*(2/3-e)*6:o}e=r(e)%360/360,t=r(t),n=r(n),i=r(i);var s=n<=.5?n*(t+1):n+t-n*t,o=n*2-s;return this.rgba(u(e+1/3)*255,u(e)*255,u(e-1/3)*255,i)},hsv:function(e,t,n){return this.hsva(e,t,n,1)},hsva:function(e,t,n,i){e=r(e)%360/360*360,t=r(t),n=r(n),i=r(i);var s,o;s=Math.floor(e/60%6),o=e/60-s;var u=[n,n*(1-t),n*(1-o*t),n*(1-(1-o)*t)],a=[[0,3,1],[2,0,1],[1,0,3],[1,2,0],[3,1,0],[0,1,2]];return this.rgba(u[a[s][0]]*255,u[a[s][1]]*255,u[a[s][2]]*255,i)},hue:function(t){return new e.Dimension(Math.round(t.toHSL().h))},saturation:function(t){return new e.Dimension(Math.round(t.toHSL().s*100),"%")},lightness:function(t){return new e.Dimension(Math.round(t.toHSL().l*100),"%")},red:function(t){return new e.Dimension(t.rgb[0])},green:function(t){return new e.Dimension(t.rgb[1])},blue:function(t){return new e.Dimension(t.rgb[2])},alpha:function(t){return new e.Dimension(t.toHSL().a)},luma:function(t){return new e.Dimension(Math.round((.2126*(t.rgb[0]/255)+.7152*(t.rgb[1]/255)+.0722*(t.rgb[2]/255))*t.alpha*100),"%")},saturate:function(e,n){var r=e.toHSL();return r.s+=n.value/100,r.s=i(r.s),t(r)},desaturate:function(e,n){var r=e.toHSL();return r.s-=n.value/100,r.s=i(r.s),t(r)},lighten:function(e,n){var r=e.toHSL();return r.l+=n.value/100,r.l=i(r.l),t(r)},darken:function(e,n){var r=e.toHSL();return r.l-=n.value/100,r.l=i(r.l),t(r)},fadein:function(e,n){var r=e.toHSL();return r.a+=n.value/100,r.a=i(r.a),t(r)},fadeout:function(e,n){var r=e.toHSL();return r.a-=n.value/100,r.a=i(r.a),t(r)},fade:function(e,n){var r=e.toHSL();return r.a=n.value/100,r.a=i(r.a),t(r)},spin:function(e,n){var r=e.toHSL(),i=(r.h+n.value)%360;return r.h=i<0?360+i:i,t(r)},mix:function(t,n,r){r||(r=new e.Dimension(50));var i=r.value/100,s=i*2-1,o=t.toHSL().a-n.toHSL().a,u=((s*o==-1?s:(s+o)/(1+s*o))+1)/2,a=1-u,f=[t.rgb[0]*u+n.rgb[0]*a,t.rgb[1]*u+n.rgb[1]*a,t.rgb[2]*u+n.rgb[2]*a],l=t.alpha*i+n.alpha*(1-i);return new e.Color(f,l)},greyscale:function(t){return this.desaturate(t,new e.Dimension(100))},contrast:function(e,t,n,r){return e.rgb?(typeof n=="undefined"&&(n=this.rgba(255,255,255,1)),typeof t=="undefined"&&(t=this.rgba(0,0,0,1)),typeof r=="undefined"?r=.43:r=r.value,(.2126*(e.rgb[0]/255)+.7152*(e.rgb[1]/255)+.0722*(e.rgb[2]/255))*e.alpha<r?n:t):null},e:function(t){return new e.Anonymous(t instanceof e.JavaScript?t.evaluated:t)},escape:function(t){return new e.Anonymous(encodeURI(t.value).replace(/=/g,"%3D").replace(/:/g,"%3A").replace(/#/g,"%23").replace(/;/g,"%3B").replace(/\(/g,"%28").replace(/\)/g,"%29"))},"%":function(t){var n=Array.prototype.slice.call(arguments,1),r=t.value;for(var i=0;i<n.length;i++)r=r.replace(/%[sda]/i,function(e){var t=e.match(/s/i)?n[i].value:n[i].toCSS();return e.match(/[A-Z]$/)?encodeURIComponent(t):t});return r=r.replace(/%%/g,"%"),new e.Quoted('"'+r+'"',r)},unit:function(t,n){return new e.Dimension(t.value,n?n.toCSS():"")},round:function(e,t){var n=typeof t=="undefined"?0:t.value;return this._math(function(e){return e.toFixed(n)},e)},ceil:function(e){return this._math(Math.ceil,e)},floor:function(e){return this._math(Math.floor,e)},_math:function(t,n){if(n instanceof e.Dimension)return new e.Dimension(t(parseFloat(n.value)),n.unit);if(typeof n=="number")return t(n);throw{type:"Argument",message:"argument must be a number"}},argb:function(t){return new e.Anonymous(t.toARGB())},percentage:function(t){return new e.Dimension(t.value*100,"%")},color:function(t){if(t instanceof e.Quoted)return new e.Color(t.value.slice(1));throw{type:"Argument",message:"argument must be a string"}},iscolor:function(t){return this._isa(t,e.Color)},isnumber:function(t){return this._isa(t,e.Dimension)},isstring:function(t){return this._isa(t,e.Quoted)},iskeyword:function(t){return this._isa(t,e.Keyword)},isurl:function(t){return this._isa(t,e.URL)},ispixel:function(t){return t instanceof e.Dimension&&t.unit==="px"?e.True:e.False},ispercentage:function(t){return t instanceof e.Dimension&&t.unit==="%"?e.True:e.False},isem:function(t){return t instanceof e.Dimension&&t.unit==="em"?e.True:e.False},_isa:function(t,n){return t instanceof n?e.True:e.False},multiply:function(e,t){var n=e.rgb[0]*t.rgb[0]/255,r=e.rgb[1]*t.rgb[1]/255,i=e.rgb[2]*t.rgb[2]/255;return this.rgb(n,r,i)},screen:function(e,t){var n=255-(255-e.rgb[0])*(255-t.rgb[0])/255,r=255-(255-e.rgb[1])*(255-t.rgb[1])/255,i=255-(255-e.rgb[2])*(255-t.rgb[2])/255;return this.rgb(n,r,i)},overlay:function(e,t){var n=e.rgb[0]<128?2*e.rgb[0]*t.rgb[0]/255:255-2*(255-e.rgb[0])*(255-t.rgb[0])/255,r=e.rgb[1]<128?2*e.rgb[1]*t.rgb[1]/255:255-2*(255-e.rgb[1])*(255-t.rgb[1])/255,i=e.rgb[2]<128?2*e.rgb[2]*t.rgb[2]/255:255-2*(255-e.rgb[2])*(255-t.rgb[2])/255;return this.rgb(n,r,i)},softlight:function(e,t){var n=t.rgb[0]*e.rgb[0]/255,r=n+e.rgb[0]*(255-(255-e.rgb[0])*(255-t.rgb[0])/255-n)/255;n=t.rgb[1]*e.rgb[1]/255;var i=n+e.rgb[1]*(255-(255-e.rgb[1])*(255-t.rgb[1])/255-n)/255;n=t.rgb[2]*e.rgb[2]/255;var s=n+e.rgb[2]*(255-(255-e.rgb[2])*(255-t.rgb[2])/255-n)/255;return this.rgb(r,i,s)},hardlight:function(e,t){var n=t.rgb[0]<128?2*t.rgb[0]*e.rgb[0]/255:255-2*(255-t.rgb[0])*(255-e.rgb[0])/255,r=t.rgb[1]<128?2*t.rgb[1]*e.rgb[1]/255:255-2*(255-t.rgb[1])*(255-e.rgb[1])/255,i=t.rgb[2]<128?2*t.rgb[2]*e.rgb[2]/255:255-2*(255-t.rgb[2])*(255-e.rgb[2])/255;return this.rgb(n,r,i)},difference:function(e,t){var n=Math.abs(e.rgb[0]-t.rgb[0]),r=Math.abs(e.rgb[1]-t.rgb[1]),i=Math.abs(e.rgb[2]-t.rgb[2]);return this.rgb(n,r,i)},exclusion:function(e,t){var n=e.rgb[0]+t.rgb[0]*(255-e.rgb[0]-e.rgb[0])/255,r=e.rgb[1]+t.rgb[1]*(255-e.rgb[1]-e.rgb[1])/255,i=e.rgb[2]+t.rgb[2]*(255-e.rgb[2]-e.rgb[2])/255;return this.rgb(n,r,i)},average:function(e,t){var n=(e.rgb[0]+t.rgb[0])/2,r=(e.rgb[1]+t.rgb[1])/2,i=(e.rgb[2]+t.rgb[2])/2;return this.rgb(n,r,i)},negation:function(e,t){var n=255-Math.abs(255-t.rgb[0]-e.rgb[0]),r=255-Math.abs(255-t.rgb[1]-e.rgb[1]),i=255-Math.abs(255-t.rgb[2]-e.rgb[2]);return this.rgb(n,r,i)},tint:function(e,t){return this.mix(this.rgb(255,255,255),e,t)},shade:function(e,t){return this.mix(this.rgb(0,0,0),e,t)}}})(n("./tree")),function(e){e.colors={aliceblue:"#f0f8ff",antiquewhite:"#faebd7",aqua:"#00ffff",aquamarine:"#7fffd4",azure:"#f0ffff",beige:"#f5f5dc",bisque:"#ffe4c4",black:"#000000",blanchedalmond:"#ffebcd",blue:"#0000ff",blueviolet:"#8a2be2",brown:"#a52a2a",burlywood:"#deb887",cadetblue:"#5f9ea0",chartreuse:"#7fff00",chocolate:"#d2691e",coral:"#ff7f50",cornflowerblue:"#6495ed",cornsilk:"#fff8dc",crimson:"#dc143c",cyan:"#00ffff",darkblue:"#00008b",darkcyan:"#008b8b",darkgoldenrod:"#b8860b",darkgray:"#a9a9a9",darkgrey:"#a9a9a9",darkgreen:"#006400",darkkhaki:"#bdb76b",darkmagenta:"#8b008b",darkolivegreen:"#556b2f",darkorange:"#ff8c00",darkorchid:"#9932cc",darkred:"#8b0000",darksalmon:"#e9967a",darkseagreen:"#8fbc8f",darkslateblue:"#483d8b",darkslategray:"#2f4f4f",darkslategrey:"#2f4f4f",darkturquoise:"#00ced1",darkviolet:"#9400d3",deeppink:"#ff1493",deepskyblue:"#00bfff",dimgray:"#696969",dimgrey:"#696969",dodgerblue:"#1e90ff",firebrick:"#b22222",floralwhite:"#fffaf0",forestgreen:"#228b22",fuchsia:"#ff00ff",gainsboro:"#dcdcdc",ghostwhite:"#f8f8ff",gold:"#ffd700",goldenrod:"#daa520",gray:"#808080",grey:"#808080",green:"#008000",greenyellow:"#adff2f",honeydew:"#f0fff0",hotpink:"#ff69b4",indianred:"#cd5c5c",indigo:"#4b0082",ivory:"#fffff0",khaki:"#f0e68c",lavender:"#e6e6fa",lavenderblush:"#fff0f5",lawngreen:"#7cfc00",lemonchiffon:"#fffacd",lightblue:"#add8e6",lightcoral:"#f08080",lightcyan:"#e0ffff",lightgoldenrodyellow:"#fafad2",lightgray:"#d3d3d3",lightgrey:"#d3d3d3",lightgreen:"#90ee90",lightpink:"#ffb6c1",lightsalmon:"#ffa07a",lightseagreen:"#20b2aa",lightskyblue:"#87cefa",lightslategray:"#778899",lightslategrey:"#778899",lightsteelblue:"#b0c4de",lightyellow:"#ffffe0",lime:"#00ff00",limegreen:"#32cd32",linen:"#faf0e6",magenta:"#ff00ff",maroon:"#800000",mediumaquamarine:"#66cdaa",mediumblue:"#0000cd",mediumorchid:"#ba55d3",mediumpurple:"#9370d8",mediumseagreen:"#3cb371",mediumslateblue:"#7b68ee",mediumspringgreen:"#00fa9a",mediumturquoise:"#48d1cc",mediumvioletred:"#c71585",midnightblue:"#191970",mintcream:"#f5fffa",mistyrose:"#ffe4e1",moccasin:"#ffe4b5",navajowhite:"#ffdead",navy:"#000080",oldlace:"#fdf5e6",olive:"#808000",olivedrab:"#6b8e23",orange:"#ffa500",orangered:"#ff4500",orchid:"#da70d6",palegoldenrod:"#eee8aa",palegreen:"#98fb98",paleturquoise:"#afeeee",palevioletred:"#d87093",papayawhip:"#ffefd5",peachpuff:"#ffdab9",peru:"#cd853f",pink:"#ffc0cb",plum:"#dda0dd",powderblue:"#b0e0e6",purple:"#800080",red:"#ff0000",rosybrown:"#bc8f8f",royalblue:"#4169e1",saddlebrown:"#8b4513",salmon:"#fa8072",sandybrown:"#f4a460",seagreen:"#2e8b57",seashell:"#fff5ee",sienna:"#a0522d",silver:"#c0c0c0",skyblue:"#87ceeb",slateblue:"#6a5acd",slategray:"#708090",slategrey:"#708090",snow:"#fffafa",springgreen:"#00ff7f",steelblue:"#4682b4",tan:"#d2b48c",teal:"#008080",thistle:"#d8bfd8",tomato:"#ff6347",turquoise:"#40e0d0",violet:"#ee82ee",wheat:"#f5deb3",white:"#ffffff",whitesmoke:"#f5f5f5",yellow:"#ffff00",yellowgreen
:"#9acd32"}}(n("./tree")),function(e){e.Alpha=function(e){this.value=e},e.Alpha.prototype={toCSS:function(){return"alpha(opacity="+(this.value.toCSS?this.value.toCSS():this.value)+")"},eval:function(e){return this.value.eval&&(this.value=this.value.eval(e)),this}}}(n("../tree")),function(e){e.Anonymous=function(e){this.value=e.value||e},e.Anonymous.prototype={toCSS:function(){return this.value},eval:function(){return this},compare:function(e){if(!e.toCSS)return-1;var t=this.toCSS(),n=e.toCSS();return t===n?0:t<n?-1:1}}}(n("../tree")),function(e){e.Assignment=function(e,t){this.key=e,this.value=t},e.Assignment.prototype={toCSS:function(){return this.key+"="+(this.value.toCSS?this.value.toCSS():this.value)},eval:function(t){return this.value.eval?new e.Assignment(this.key,this.value.eval(t)):this}}}(n("../tree")),function(e){e.Call=function(e,t,n,r){this.name=e,this.args=t,this.index=n,this.filename=r},e.Call.prototype={eval:function(t){var n=this.args.map(function(e){return e.eval(t)}),r;if(this.name in e.functions)try{r=e.functions[this.name].apply(e.functions,n);if(r!=null)return r}catch(i){throw{type:i.type||"Runtime",message:"error evaluating function `"+this.name+"`"+(i.message?": "+i.message:""),index:this.index,filename:this.filename}}return new e.Anonymous(this.name+"("+n.map(function(e){return e.toCSS(t)}).join(", ")+")")},toCSS:function(e){return this.eval(e).toCSS()}}}(n("../tree")),function(e){e.Color=function(e,t){Array.isArray(e)?this.rgb=e:e.length==6?this.rgb=e.match(/.{2}/g).map(function(e){return parseInt(e,16)}):this.rgb=e.split("").map(function(e){return parseInt(e+e,16)}),this.alpha=typeof t=="number"?t:1},e.Color.prototype={eval:function(){return this},toCSS:function(){return this.alpha<1?"rgba("+this.rgb.map(function(e){return Math.round(e)}).concat(this.alpha).join(", ")+")":"#"+this.rgb.map(function(e){return e=Math.round(e),e=(e>255?255:e<0?0:e).toString(16),e.length===1?"0"+e:e}).join("")},operate:function(t,n){var r=[];n instanceof e.Color||(n=n.toColor());for(var i=0;i<3;i++)r[i]=e.operate(t,this.rgb[i],n.rgb[i]);return new e.Color(r,this.alpha+n.alpha)},toHSL:function(){var e=this.rgb[0]/255,t=this.rgb[1]/255,n=this.rgb[2]/255,r=this.alpha,i=Math.max(e,t,n),s=Math.min(e,t,n),o,u,a=(i+s)/2,f=i-s;if(i===s)o=u=0;else{u=a>.5?f/(2-i-s):f/(i+s);switch(i){case e:o=(t-n)/f+(t<n?6:0);break;case t:o=(n-e)/f+2;break;case n:o=(e-t)/f+4}o/=6}return{h:o*360,s:u,l:a,a:r}},toARGB:function(){var e=[Math.round(this.alpha*255)].concat(this.rgb);return"#"+e.map(function(e){return e=Math.round(e),e=(e>255?255:e<0?0:e).toString(16),e.length===1?"0"+e:e}).join("")},compare:function(e){return e.rgb?e.rgb[0]===this.rgb[0]&&e.rgb[1]===this.rgb[1]&&e.rgb[2]===this.rgb[2]&&e.alpha===this.alpha?0:-1:-1}}}(n("../tree")),function(e){e.Comment=function(e,t){this.value=e,this.silent=!!t},e.Comment.prototype={toCSS:function(e){return e.compress?"":this.value},eval:function(){return this}}}(n("../tree")),function(e){e.Condition=function(e,t,n,r,i){this.op=e.trim(),this.lvalue=t,this.rvalue=n,this.index=r,this.negate=i},e.Condition.prototype.eval=function(e){var t=this.lvalue.eval(e),n=this.rvalue.eval(e),r=this.index,i,i=function(e){switch(e){case"and":return t&&n;case"or":return t||n;default:if(t.compare)i=t.compare(n);else{if(!n.compare)throw{type:"Type",message:"Unable to perform comparison",index:r};i=n.compare(t)}switch(i){case-1:return e==="<"||e==="=<";case 0:return e==="="||e===">="||e==="=<";case 1:return e===">"||e===">="}}}(this.op);return this.negate?!i:i}}(n("../tree")),function(e){e.Dimension=function(e,t){this.value=parseFloat(e),this.unit=t||null},e.Dimension.prototype={eval:function(){return this},toColor:function(){return new e.Color([this.value,this.value,this.value])},toCSS:function(){var e=this.value+this.unit;return e},operate:function(t,n){return new e.Dimension(e.operate(t,this.value,n.value),this.unit||n.unit)},compare:function(t){return t instanceof e.Dimension?t.value>this.value?-1:t.value<this.value?1:t.unit&&this.unit!==t.unit?-1:0:-1}}}(n("../tree")),function(e){e.Directive=function(t,n){this.name=t,Array.isArray(n)?(this.ruleset=new e.Ruleset([],n),this.ruleset.allowImports=!0):this.value=n},e.Directive.prototype={toCSS:function(e,t){return this.ruleset?(this.ruleset.root=!0,this.name+(t.compress?"{":" {\n  ")+this.ruleset.toCSS(e,t).trim().replace(/\n/g,"\n  ")+(t.compress?"}":"\n}\n")):this.name+" "+this.value.toCSS()+";\n"},eval:function(t){var n=this;return this.ruleset&&(t.frames.unshift(this),n=new e.Directive(this.name),n.ruleset=this.ruleset.eval(t),t.frames.shift()),n},variable:function(t){return e.Ruleset.prototype.variable.call(this.ruleset,t)},find:function(){return e.Ruleset.prototype.find.apply(this.ruleset,arguments)},rulesets:function(){return e.Ruleset.prototype.rulesets.apply(this.ruleset)}}}(n("../tree")),function(e){e.Element=function(t,n,r){this.combinator=t instanceof e.Combinator?t:new e.Combinator(t),typeof n=="string"?this.value=n.trim():n?this.value=n:this.value="",this.index=r},e.Element.prototype.eval=function(t){return new e.Element(this.combinator,this.value.eval?this.value.eval(t):this.value,this.index)},e.Element.prototype.toCSS=function(e){var t=this.value.toCSS?this.value.toCSS(e):this.value;return t==""&&this.combinator.value.charAt(0)=="&"?"":this.combinator.toCSS(e||{})+t},e.Combinator=function(e){e===" "?this.value=" ":this.value=e?e.trim():""},e.Combinator.prototype.toCSS=function(e){return{"":""," ":" ",":":" :","+":e.compress?"+":" + ","~":e.compress?"~":" ~ ",">":e.compress?">":" > ","|":e.compress?"|":" | "}[this.value]}}(n("../tree")),function(e){e.Expression=function(e){this.value=e},e.Expression.prototype={eval:function(t){return this.value.length>1?new e.Expression(this.value.map(function(e){return e.eval(t)})):this.value.length===1?this.value[0].eval(t):this},toCSS:function(e){return this.value.map(function(t){return t.toCSS?t.toCSS(e):""}).join(" ")}}}(n("../tree")),function(e){e.Import=function(t,n,r,i,s,o){var u=this;this.once=i,this.index=s,this._path=t,this.features=r&&new e.Value(r),this.rootpath=o,t instanceof e.Quoted?this.path=/(\.[a-z]*$)|([\?;].*)$/.test(t.value)?t.value:t.value+".less":this.path=t.value.value||t.value,this.css=/css([\?;].*)?$/.test(this.path),this.css||n.push(this.path,function(t,n,r){t&&(t.index=s),r&&u.once&&(u.skip=r),u.root=n||new e.Ruleset([],[])})},e.Import.prototype={toCSS:function(e){var t=this.features?" "+this.features.toCSS(e):"";return this.css?(typeof this._path.value=="string"&&!/^(?:[a-z-]+:|\/)/.test(this._path.value)&&(this._path.value=this.rootpath+this._path.value),"@import "+this._path.toCSS()+t+";\n"):""},eval:function(t){var n,r=this.features&&this.features.eval(t);return this.skip?[]:this.css?this:(n=new e.Ruleset([],this.root.rules.slice(0)),n.evalImports(t),this.features?new e.Media(n.rules,this.features.value):n.rules)}}}(n("../tree")),function(e){e.JavaScript=function(e,t,n){this.escaped=n,this.expression=e,this.index=t},e.JavaScript.prototype={eval:function(t){var n,r=this,i={},s=this.expression.replace(/@\{([\w-]+)\}/g,function(n,i){return e.jsify((new e.Variable("@"+i,r.index)).eval(t))});try{s=new Function("return ("+s+")")}catch(o){throw{message:"JavaScript evaluation error: `"+s+"`",index:this.index}}for(var u in t.frames[0].variables())i[u.slice(1)]={value:t.frames[0].variables()[u].value,toJS:function(){return this.value.eval(t).toCSS()}};try{n=s.call(i)}catch(o){throw{message:"JavaScript evaluation error: '"+o.name+": "+o.message+"'",index:this.index}}return typeof n=="string"?new e.Quoted('"'+n+'"',n,this.escaped,this.index):Array.isArray(n)?new e.Anonymous(n.join(", ")):new e.Anonymous(n)}}}(n("../tree")),function(e){e.Keyword=function(e){this.value=e},e.Keyword.prototype={eval:function(){return this},toCSS:function(){return this.value},compare:function(t){return t instanceof e.Keyword?t.value===this.value?0:1:-1}},e.True=new e.Keyword("true"),e.False=new e.Keyword("false")}(n("../tree")),function(e){e.Media=function(t,n){var r=this.emptySelectors();this.features=new e.Value(n),this.ruleset=new e.Ruleset(r,t),this.ruleset.allowImports=!0},e.Media.prototype={toCSS:function(e,t){var n=this.features.toCSS(t);return this.ruleset.root=e.length===0||e[0].multiMedia,"@media "+n+(t.compress?"{":" {\n  ")+this.ruleset.toCSS(e,t).trim().replace(/\n/g,"\n  ")+(t.compress?"}":"\n}\n")},eval:function(t){t.mediaBlocks||(t.mediaBlocks=[],t.mediaPath=[]);var n=new e.Media([],[]);return this.debugInfo&&(this.ruleset.debugInfo=this.debugInfo,n.debugInfo=this.debugInfo),n.features=this.features.eval(t),t.mediaPath.push(n),t.mediaBlocks.push(n),t.frames.unshift(this.ruleset),n.ruleset=this.ruleset.eval(t),t.frames.shift(),t.mediaPath.pop(),t.mediaPath.length===0?n.evalTop(t):n.evalNested(t)},variable:function(t){return e.Ruleset.prototype.variable.call(this.ruleset,t)},find:function(){return e.Ruleset.prototype.find.apply(this.ruleset,arguments)},rulesets:function(){return e.Ruleset.prototype.rulesets.apply(this.ruleset)},emptySelectors:function(){var t=new e.Element("","&",0);return[new e.Selector([t])]},evalTop:function(t){var n=this;if(t.mediaBlocks.length>1){var r=this.emptySelectors();n=new e.Ruleset(r,t.mediaBlocks),n.multiMedia=!0}return delete t.mediaBlocks,delete t.mediaPath,n},evalNested:function(t){var n,r,i=t.mediaPath.concat([this]);for(n=0;n<i.length;n++)r=i[n].features instanceof e.Value?i[n].features.value:i[n].features,i[n]=Array.isArray(r)?r:[r];return this.features=new e.Value(this.permute(i).map(function(t){t=t.map(function(t){return t.toCSS?t:new e.Anonymous(t)});for(n=t.length-1;n>0;n--)t.splice(n,0,new e.Anonymous("and"));return new e.Expression(t)})),new e.Ruleset([],[])},permute:function(e){if(e.length===0)return[];if(e.length===1)return e[0];var t=[],n=this.permute(e.slice(1));for(var r=0;r<n.length;r++)for(var i=0;i<e[0].length;i++)t.push([e[0][i]].concat(n[r]));return t},bubbleSelectors:function(t){this.ruleset=new e.Ruleset(t.slice(0),[this.ruleset])}}}(n("../tree")),function(e){e.mixin={},e.mixin.Call=function(t,n,r,i,s){this.selector=new e.Selector(t),this.arguments=n,this.index=r,this.filename=i,this.important=s},e.mixin.Call.prototype={eval:function(t){var n,r,i,s=[],o=!1,u,a,f,l,c;i=this.arguments&&this.arguments.map(function(e){return{name:e.name,value:e.value.eval(t)}});for(u=0;u<t.frames.length;u++)if((n=t.frames[u].find(this.selector)).length>0){c=!0;for(a=0;a<n.length;a++){r=n[a],l=!1;for(f=0;f<t.frames.length;f++)if(!(r instanceof e.mixin.Definition)&&r===(t.frames[f].originalRuleset||t.frames[f])){l=!0;break}if(l)continue;if(r.matchArgs(i,t)){if(!r.matchCondition||r.matchCondition(i,t))try{Array.prototype.push.apply(s,r.eval(t,i,this.important).rules)}catch(h){throw{message:h.message,index:this.index,filename:this.filename,stack:h.stack}}o=!0}}if(o)return s}throw c?{type:"Runtime",message:"No matching definition was found for `"+this.selector.toCSS().trim()+"("+(i?i.map(function(e){var t="";return e.name&&(t+=e.name+":"),e.value.toCSS?t+=e.value.toCSS():t+="???",t}).join(", "):"")+")`",index:this.index,filename:this.filename}:{type:"Name",message:this.selector.toCSS().trim()+" is undefined",index:this.index,filename:this.filename}}},e.mixin.Definition=function(t,n,r,i,s){this.name=t,this.selectors=[new e.Selector([new e.Element(null,t)])],this.params=n,this.condition=i,this.variadic=s,this.arity=n.length,this.rules=r,this._lookups={},this.required=n.reduce(function(e,t){return!t.name||t.name&&!t.value?e+1:e},0),this.parent=e.Ruleset.prototype,this.frames=[]},e.mixin.Definition.prototype={toCSS:function(){return""},variable:function(e){return this.parent.variable.call(this,e)},variables:function(){return this.parent.variables.call(this)},find:function(){return this.parent.find.apply(this,arguments)},rulesets:function(){return this.parent.rulesets.apply(this)},evalParams:function(t,n,r,i){var s=new e.Ruleset(null,[]),o,u,a=this.params.slice(0),f,l,c,h,p,d;if(r){r=r.slice(0);for(f=0;f<r.length;f++){u=r[f];if(h=u&&u.name){p=!1;for(l=0;l<a.length;l++)if(!i[l]&&h===a[l].name){i[l]=u.value.eval(t),s.rules.unshift(new e.Rule(h,u.value.eval(t))),p=!0;break}if(p){r.splice(f,1),f--;continue}throw{type:"Runtime",message:"Named argument for "+this.name+" "+r[f].name+" not found"}}}}d=0;for(f=0;f<a.length;f++){if(i[f])continue;u=r&&r[d];if(h=a[f].name)if(a[f].variadic&&r){o=[];for(l=d;l<r.length;l++)o.push(r[l].value.eval(t));s.rules.unshift(new e.Rule(h,(new e.Expression(o)).eval(t)))}else{c=u&&u.value;if(c)c=c.eval(t);else{if(!a[f].value)throw{type:"Runtime",message:"wrong number of arguments for "+this.name+" ("+r.length+" for "+this.arity+")"};c=a[f].value.eval(n)}s.rules.unshift(new e.Rule(h,c)),i[f]=c}if(a[f].variadic&&r)for(l=d;l<r.length;l++)i[l]=r[l].value.eval(t);d++}return s},eval:function(t,n,r){var i=[],s=this.frames.concat(t.frames),o=this.evalParams(t,{frames:s},n,i),u,a,f,l;return o.rules.unshift(new e.Rule("@arguments",(new e.Expression(i)).eval(t))),a=r?this.parent.makeImportant.apply(this).rules:this.rules.slice(0),l=(new e.Ruleset(null,a)).eval({frames:[this,o].concat(s)}),l.originalRuleset=this,l},matchCondition:function(e,t){return this.condition&&!this.condition.eval({frames:[this.evalParams(t,{frames:this.frames.concat(t.frames)},e,[])].concat(t.frames)})?!1:!0},matchArgs:function(e,t){var n=e&&e.length||0,r,i;if(!this.variadic){if(n<this.required)return!1;if(n>this.params.length)return!1;if(this.required>0&&n>this.params.length)return!1}r=Math.min(n,this.arity);for(var s=0;s<r;s++)if(!this.params[s].name&&!this.params[s].variadic&&e[s].value.eval(t).toCSS()!=this.params[s].value.eval(t).toCSS())return!1;return!0}}}(n("../tree")),function(e){e.Operation=function(e,t){this.op=e.trim(),this.operands=t},e.Operation.prototype.eval=function(t){var n=this.operands[0].eval(t),r=this.operands[1].eval(t),i;if(n instanceof e.Dimension&&r instanceof e.Color){if(this.op!=="*"&&this.op!=="+")throw{name:"OperationError",message:"Can't substract or divide a color from a number"};i=r,r=n,n=i}if(!n.operate)throw{name:"OperationError",message:"Operation on an invalid type"};return n.operate(this.op,r)},e.operate=function(e,t,n){switch(e){case"+":return t+n;case"-":return t-n;case"*":return t*n;case"/":return t/n}}}(n("../tree")),function(e){e.Paren=function(e){this.value=e},e.Paren.prototype={toCSS:function(e){return"("+this.value.toCSS(e)+")"},eval:function(t){return new e.Paren(this.value.eval(t))}}}(n("../tree")),function(e){e.Quoted=function(e,t,n,r){this.escaped=n,this.value=t||"",this.quote=e.charAt(0),this.index=r},e.Quoted.prototype={toCSS:function(){return this.escaped?this.value:this.quote+this.value+this.quote},eval:function(t){var n=this,r=this.value.replace(/`([^`]+)`/g,function(r,i){return(new e.JavaScript(i,n.index,!0)).eval(t).value}).replace(/@\{([\w-]+)\}/g,function(r,i){var s=(new e.Variable("@"+i,n.index)).eval(t);return s instanceof e.Quoted?s.value:s.toCSS()});return new e.Quoted(this.quote+r+this.quote,r,this.escaped,this.index)},compare:function(e){if(!e.toCSS)return-1;var t=this.toCSS(),n=e.toCSS();return t===n?0:t<n?-1:1}}}(n("../tree")),function(e){e.Ratio=function(e){this.value=e},e.Ratio.prototype={toCSS:function(e){return this.value},eval:function(){return this}}}(n("../tree")),function(e){e.Rule=function(t,n,r,i,s){this.name=t,this.value=n instanceof e.Value?n:new e.Value([n]),this.important=r?" "+r.trim():"",this.index=i,this.inline=s||!1,t.charAt(0)==="@"?this.variable=!0:this.variable=!1},e.Rule.prototype.toCSS=function(e){return this.variable?"":this.name+(e.compress?":":": ")+this.value.toCSS(e)+this.important+(this.inline?"":";")},e.Rule.prototype.eval=function(t){return new e.Rule(this.name,this.value.eval(t),this.important,this.index,this.inline)},e.Rule.prototype.makeImportant=function(){return new e.Rule(this.name,this.value,"!important",this.index,this.inline)},e.Shorthand=function(e,t){this.a=e,this.b=t},e.Shorthand.prototype={toCSS:function(e){return this.a.toCSS(e)+"/"+this.b.toCSS(e)},eval:function(){return this}}}(n("../tree")),function(e){e.Ruleset=function(e,t,n){this.selectors=e,this.rules=t,this._lookups={},this.strictImports=n},e.Ruleset.prototype={eval:function(t){var n=this.selectors&&this.selectors.map(function(e){return e.eval(t)}),r=new e.Ruleset(n,this.rules.slice(0),this.strictImports),i;r.originalRuleset=this,r.root=this.root,r.allowImports=this.allowImports,this.debugInfo&&(r.debugInfo=this.debugInfo),t.frames.unshift(r),(r.root||r.allowImports||!r.strictImports)&&r.evalImports(t);for(var s=0;s<r.rules.length;s++)r.rules[s]instanceof e.mixin.Definition&&(r.rules[s].frames=t.frames.slice(0));var o=t.mediaBlocks&&t.mediaBlocks.length||0;for(var s=0;s<r.rules.length;s++)r.rules[s]instanceof e.mixin.Call&&(i=r.rules[s].eval(t),r.rules.splice.apply(r.rules,[s,1].concat(i)),s+=i.length-1,r.resetCache());for(var s=0,u;s<r.rules.length;s++)u=r.rules[s],u instanceof e.mixin.Definition||(r.rules[s]=u.eval?u.eval(t):u);t.frames.shift();if(t.mediaBlocks)for(var s=o;s<t.mediaBlocks.length;s++)t.mediaBlocks[s].bubbleSelectors(n);return r},evalImports:function(t){var n,r;for(n=0;n<this.rules.length;n++)this.rules[n]instanceof e.Import&&(r=this.rules[n].eval(t),typeof r.length=="number"?(this.rules.splice.apply(this.rules,[n,1].concat(r)),n+=r.length-1):this.rules.splice(n,1,r),this.resetCache())},makeImportant:function(){return new e.Ruleset(this.selectors,this.rules.map(function(e){return e.makeImportant?e.makeImportant():e}),this.strictImports)},matchArgs:function(e){return!e||e.length===0},resetCache:function(){this._rulesets=null,this._variables=null,this._lookups={}},variables:function(){return this._variables?this._variables:this._variables=this.rules.reduce(function(t,n){return n instanceof e.Rule&&n.variable===!0&&(t[n.name]=n),t},{})},variable:function(e){return this.variables()[e]},rulesets:function(){return this._rulesets?this._rulesets:this._rulesets=this.rules.filter(function(t){return t instanceof e.Ruleset||t instanceof e.mixin.Definition})},find:function(t,n){n=n||this;var r=[],i,s,o=t.toCSS();return o in this._lookups?this._lookups[o]:(this.rulesets().forEach(function(i){if(i!==n)for(var o=0;o<i.selectors.length;o++)if(s=t.match(i.selectors[o])){t.elements.length>i.selectors[o].elements.length?Array.prototype.push.apply(r,i.find(new e.Selector(t.elements.slice(1)),n)):r.push(i);break}}),this._lookups[o]=r)},toCSS:function(t,n){var r=[],i=[],s=[],o=[],u=[],a,f,l;this.root||this.joinSelectors(u,t,this.selectors);for(var c=0;c<this.rules.length;c++){l=this.rules[c];if(l.rules||l instanceof e.Media)o.push(l.toCSS(u,n));else if(l instanceof e.Directive){var h=l.toCSS(u,n);if(l.name==="@charset"){if(n.charset){l.debugInfo&&(o.push(e.debugInfo(n,l)),o.push((new e.Comment("/* "+h.replace(/\n/g,"")+" */\n")).toCSS(n)));continue}n.charset=!0}o.push(h)}else l instanceof e.Comment?l.silent||(this.root?o.push(l.toCSS(n)):i.push(l.toCSS(n))):l.toCSS&&!l.variable?i.push(l.toCSS(n)):l.value&&!l.variable&&i.push(l.value.toString())}o=o.join("");if(this.root)r.push(i.join(n.compress?"":"\n"));else if(i.length>0){f=e.debugInfo(n,this),a=u.map(function(e){return e.map(function(e){return e.toCSS(n)}).join("").trim()}).join(n.compress?",":",\n");for(var c=i.length-1;c>=0;c--)s.indexOf(i[c])===-1&&s.unshift(i[c]);i=s,r.push(f+a+(n.compress?"{":" {\n  ")+i.join(n.compress?"":"\n  ")+(n.compress?"}":"\n}\n"))}return r.push(o),r.join("")+(n.compress?"\n":"")},joinSelectors:function(e,t,n){for(var r=0;r<n.length;r++)this.joinSelector(e,t,n[r])},joinSelector:function(t,n,r){var i,s,o,u,a,f,l,c,h,p,d,v,m,g,y;for(i=0;i<r.elements.length;i++)f=r.elements[i],f.value==="&"&&(u=!0);if(!u){if(n.length>0)for(i=0;i<n.length;i++)t.push(n[i].concat(r));else t.push([r]);return}g=[],a=[[]];for(i=0;i<r.elements.length;i++){f=r.elements[i];if(f.value!=="&")g.push(f);else{y=[],g.length>0&&this.mergeElementsOnToSelectors(g,a);for(s=0;s<a.length;s++){l=a[s];if(n.length==0)l.length>0&&(l[0].elements=l[0].elements.slice(0),l[0].elements.push(new e.Element(f.combinator,"",0))),y.push(l);else for(o=0;o<n.length;o++)c=n[o],h=[],p=[],v=!0,l.length>0?(h=l.slice(0),m=h.pop(),d=new e.Selector(m.elements.slice(0)),v=!1):d=new e.Selector([]),c.length>1&&(p=p.concat(c.slice(1))),c.length>0&&(v=!1,d.elements.push(new e.Element(f.combinator,c[0].elements[0].value,0)),d.elements=d.elements.concat(c[0].elements.slice(1))),v||h.push(d),h=h.concat(p),y.push(h)}a=y,g=[]}}g.length>0&&this.mergeElementsOnToSelectors(g,a);for(i=0;i<a.length;i++)t.push(a[i])},mergeElementsOnToSelectors:function(t,n){var r,i;if(n.length==0){n.push([new e.Selector(t)]);return}for(r=0;r<n.length;r++)i=n[r],i.length>0?i[i.length-1]=new e.Selector(i[i.length-1].elements.concat(t)):i.push(new e.Selector(t))}}}(n("../tree")),function(e){e.Selector=function(e){this.elements=e},e.Selector.prototype.match=function(e){var t=this.elements,n=t.length,r,i,s,o;r=e.elements.slice(e.elements.length&&e.elements[0].value==="&"?1:0),i=r.length,s=Math.min(n,i);if(i===0||n<i)return!1;for(o=0;o<s;o++)if(t[o].value!==r[o].value)return!1;return!0},e.Selector.prototype.eval=function(t){return new e.Selector(this.elements.map(function(e){return e.eval(t)}))},e.Selector.prototype.toCSS=function(e){return this._css?this._css:(this.elements[0].combinator.value===""?this._css=" ":this._css="",this._css+=this.elements.map(function(t){return typeof t=="string"?" "+t.trim():t.toCSS(e)}).join(""),this._css)}}(n("../tree")),function(e){e.UnicodeDescriptor=function(e){this.value=e},e.UnicodeDescriptor.prototype={toCSS:function(e){return this.value},eval:function(){return this}}}(n("../tree")),function(e){e.URL=function(e,t){this.value=e,this.rootpath=t},e.URL.prototype={toCSS:function(){return"url("+this.value.toCSS()+")"},eval:function(t){var n=this.value.eval(t),r;return typeof n.value=="string"&&!/^(?:[a-z-]+:|\/)/.test(n.value)&&(r=this.rootpath,n.quote||(r=r.replace(/[\(\)'"\s]/g,function(e){return"\\"+e})),n.value=r+n.value),new e.URL(n,this.rootpath)}}}(n("../tree")),function(e){e.Value=function(e){this.value=e,this.is="value"},e.Value.prototype={eval:function(t){return this.value.length===1?this.value[0].eval(t):new e.Value(this.value.map(function(e){return e.eval(t)}))},toCSS:function(e){return this.value.map(function(t){return t.toCSS(e)}).join(e.compress?",":", ")}}}(n("../tree")),function(e){e.Variable=function(e,t,n){this.name=e,this.index=t,this.file=n},e.Variable.prototype={eval:function(t){var n,r,i=this.name;i.indexOf("@@")==0&&(i="@"+(new e.Variable(i.slice(1))).eval(t).value);if(this.evaluating)throw{type:"Name",message:"Recursive variable definition for "+i,filename:this.file,index:this.index};this.evaluating=!0;if(n=e.find(t.frames,function(e){if(r=e.variable(i))return r.value.eval(t)}))return this.evaluating=!1,n;throw{type:"Name",message:"variable "+i+" is undefined",filename:this.file,index:this.index}}}}(n("../tree")),function(e){e.debugInfo=function(t,n){var r="";if(t.dumpLineNumbers&&!t.compress)switch(t.dumpLineNumbers){case"comments":r=e.debugInfo.asComment(n);break;case"mediaquery":r=e.debugInfo.asMediaQuery(n);break;case"all":r=e.debugInfo.asComment(n)+e.debugInfo.asMediaQuery(n)}return r},e.debugInfo.asComment=function(e){return"/* line "+e.debugInfo.lineNumber+", "+e.debugInfo.fileName+" */\n"},e.debugInfo.asMediaQuery=function(e){return"@media -sass-debug-info{filename{font-family:"+("file://"+e.debugInfo.fileName).replace(/[\/:.]/g,"\\$&")+"}line{font-family:\\00003"+e.debugInfo.lineNumber+"}}\n"},e.find=function(e,t){for(var n=0,r;n<e.length;n++)if(r=t.call(e,e[n]))return r;return null},e.jsify=function(e){return Array.isArray(e.value)&&e.value.length>1?"["+e.value.map(function(e){return e.toCSS(!1)}).join(", ")+"]":e.toCSS(!1)}}(n("./tree"));var o=/^(file|chrome(-extension)?|resource|qrc|app):/.test(location.protocol);r.env=r.env||(location.hostname=="127.0.0.1"||location.hostname=="0.0.0.0"||location.hostname=="localhost"||location.port.length>0||o?"development":"production"),r.async=r.async||!1,r.fileAsync=r.fileAsync||!1,r.poll=r.poll||(o?1e3:1500);if(r.functions)for(var u in r.functions)r.tree.functions[u]=r.functions[u];var a=/!dumpLineNumbers:(comments|mediaquery|all)/.exec(location.hash);a&&(r.dumpLineNumbers=a[1]),r.watch=function(){return r.watchMode||(r.env="development",f()),this.watchMode=!0},r.unwatch=function(){return clearInterval(r.watchTimer),this.watchMode=!1},/!watch/.test(location.hash)&&r.watch();var l=null;if(r.env!="development")try{l=typeof e.localStorage=="undefined"?null:e.localStorage}catch(c){}var h=document.getElementsByTagName("link"),p=/^text\/(x-)?less$/;r.sheets=[];for(var d=0;d<h.length;d++)(h[d].rel==="stylesheet/less"||h[d].rel.match(/stylesheet/)&&h[d].type.match(p))&&r.sheets.push(h[d]);var v="";r.modifyVars=function(e){var t=v;for(name in e)t+=(name.slice(0,1)==="@"?"":"@")+name+": "+(e[name].slice(-1)===";"?e[name]:e[name]+";");(new r.Parser).parse(t,function(e,t){S(t.toCSS(),r.sheets[r.sheets.length-1])})},r.refresh=function(e){var t,n;t=n=new Date,g(function(e,r,i,s,o){o.local?C("loading "+s.href+" from cache."):(C("parsed "+s.href+" successfully."),S(r.toCSS(),s,o.lastModified)),C("css for "+s.href+" generated in "+(new Date-n)+"ms"),o.remaining===0&&C("css generated in "+(new Date-t)+"ms"),n=new Date},e),m()},r.refreshStyles=m,r.refresh(r.env==="development"),typeof define=="function"&&define.amd&&define("less",[],function(){return r})})(window);                                                                                                                                                                                       master/js/wgxpath.install.js                                                                        000644  000767  000024  00000060374 12110524611 017113  0                                                                                                    ustar 00joshua                          staff                           000000  000000                                                                                                                                                                         (function(){function h(a){throw a;}var i=void 0,j=!0,k=null,l=!1;function m(a){return function(){return this[a]}}function aa(a){return function(){return a}}var n=this;function p(a){return"string"==typeof a}Math.floor(2147483648*Math.random()).toString(36);function q(a){var b=t;function c(){}c.prototype=b.prototype;a.t=b.prototype;a.prototype=new c};var u,ba,ca,da;function ea(){return n.navigator?n.navigator.userAgent:k}da=ca=ba=u=l;var fa;if(fa=ea()){var ga=n.navigator;u=0==fa.indexOf("Opera");ba=!u&&-1!=fa.indexOf("MSIE");ca=!u&&-1!=fa.indexOf("WebKit");da=!u&&!ca&&"Gecko"==ga.product}var w=ba,ha=da,ia=ca,ja;
a:{var ka="",y;if(u&&n.opera)var la=n.opera.version,ka="function"==typeof la?la():la;else if(ha?y=/rv\:([^\);]+)(\)|;)/:w?y=/MSIE\s+([^\);]+)(\)|;)/:ia&&(y=/WebKit\/(\S+)/),y)var ma=y.exec(ea()),ka=ma?ma[1]:"";if(w){var na,oa=n.document;na=oa?oa.documentMode:i;if(na>parseFloat(ka)){ja=String(na);break a}}ja=ka}var pa=ja,qa={};
function ra(a){if(!qa[a]){for(var b=0,c=String(pa).replace(/^[\s\xa0]+|[\s\xa0]+$/g,"").split("."),d=String(a).replace(/^[\s\xa0]+|[\s\xa0]+$/g,"").split("."),e=Math.max(c.length,d.length),f=0;0==b&&f<e;f++){var g=c[f]||"",r=d[f]||"",v=RegExp("(\\d*)(\\D*)","g"),J=RegExp("(\\d*)(\\D*)","g");do{var s=v.exec(g)||["","",""],x=J.exec(r)||["","",""];if(0==s[0].length&&0==x[0].length)break;b=((0==s[1].length?0:parseInt(s[1],10))<(0==x[1].length?0:parseInt(x[1],10))?-1:(0==s[1].length?0:parseInt(s[1],10))>
(0==x[1].length?0:parseInt(x[1],10))?1:0)||((0==s[2].length)<(0==x[2].length)?-1:(0==s[2].length)>(0==x[2].length)?1:0)||(s[2]<x[2]?-1:s[2]>x[2]?1:0)}while(0==b)}qa[a]=0<=b}}var sa={};function z(a){return sa[a]||(sa[a]=w&&!!document.documentMode&&document.documentMode>=a)};function A(a,b,c){this.a=a;this.b=b||1;this.d=c||1};var B=Array.prototype,ta=B.indexOf?function(a,b,c){return B.indexOf.call(a,b,c)}:function(a,b,c){c=c==k?0:0>c?Math.max(0,a.length+c):c;if(p(a))return!p(b)||1!=b.length?-1:a.indexOf(b,c);for(;c<a.length;c++)if(c in a&&a[c]===b)return c;return-1},C=B.forEach?function(a,b,c){B.forEach.call(a,b,c)}:function(a,b,c){for(var d=a.length,e=p(a)?a.split(""):a,f=0;f<d;f++)f in e&&b.call(c,e[f],f,a)},ua=B.filter?function(a,b,c){return B.filter.call(a,b,c)}:function(a,b,c){for(var d=a.length,e=[],f=0,g=p(a)?a.split(""):
a,r=0;r<d;r++)if(r in g){var v=g[r];b.call(c,v,r,a)&&(e[f++]=v)}return e};function va(a,b,c){if(a.reduce)return a.reduce(b,c);var d=c;C(a,function(c,f){d=b.call(i,d,c,f,a)});return d}var wa=B.some?function(a,b,c){return B.some.call(a,b,c)}:function(a,b,c){for(var d=a.length,e=p(a)?a.split(""):a,f=0;f<d;f++)if(f in e&&b.call(c,e[f],f,a))return j;return l};function xa(a){return B.concat.apply(B,arguments)}function ya(a,b,c){return 2>=arguments.length?B.slice.call(a,b):B.slice.call(a,b,c)};!w||z(9);!ha&&!w||w&&z(9)||ha&&ra("1.9.1");w&&ra("9");function za(a,b){if(a.contains&&1==b.nodeType)return a==b||a.contains(b);if("undefined"!=typeof a.compareDocumentPosition)return a==b||Boolean(a.compareDocumentPosition(b)&16);for(;b&&a!=b;)b=b.parentNode;return b==a}
function Aa(a,b){if(a==b)return 0;if(a.compareDocumentPosition)return a.compareDocumentPosition(b)&2?1:-1;if(w&&!z(9)){if(9==a.nodeType)return-1;if(9==b.nodeType)return 1}if("sourceIndex"in a||a.parentNode&&"sourceIndex"in a.parentNode){var c=1==a.nodeType,d=1==b.nodeType;if(c&&d)return a.sourceIndex-b.sourceIndex;var e=a.parentNode,f=b.parentNode;return e==f?Ba(a,b):!c&&za(e,b)?-1*Ca(a,b):!d&&za(f,a)?Ca(b,a):(c?a.sourceIndex:e.sourceIndex)-(d?b.sourceIndex:f.sourceIndex)}d=9==a.nodeType?a:a.ownerDocument||
a.document;c=d.createRange();c.selectNode(a);c.collapse(j);d=d.createRange();d.selectNode(b);d.collapse(j);return c.compareBoundaryPoints(n.Range.START_TO_END,d)}function Ca(a,b){var c=a.parentNode;if(c==b)return-1;for(var d=b;d.parentNode!=c;)d=d.parentNode;return Ba(d,a)}function Ba(a,b){for(var c=b;c=c.previousSibling;)if(c==a)return-1;return 1};var D=w&&!z(9),Da=w&&!z(8);function E(a,b,c,d){this.a=a;this.nodeName=c;this.nodeValue=d;this.nodeType=2;this.parentNode=this.ownerElement=b}function Ea(a,b){var c=Da&&"href"==b.nodeName?a.getAttribute(b.nodeName,2):b.nodeValue;return new E(b,a,b.nodeName,c)};function Fa(a){this.b=a;this.a=0}var Ga=RegExp("\\$?(?:(?![0-9-])[\\w-]+:)?(?![0-9-])[\\w-]+|\\/\\/|\\.\\.|::|\\d+(?:\\.\\d*)?|\\.\\d+|\"[^\"]*\"|'[^']*'|[!<>]=|\\s+|.","g"),Ha=/^\s/;function F(a,b){return a.b[a.a+(b||0)]}function G(a){return a.b[a.a++]};function H(a){var b=k,c=a.nodeType;1==c&&(b=a.textContent,b=b==i||b==k?a.innerText:b,b=b==i||b==k?"":b);if("string"!=typeof b)if(D&&"title"==a.nodeName.toLowerCase()&&1==c)b=a.text;else if(9==c||1==c)for(var a=9==c?a.documentElement:a.firstChild,c=0,d=[],b="";a;){do 1!=a.nodeType&&(b+=a.nodeValue),D&&"title"==a.nodeName.toLowerCase()&&(b+=a.text),d[c++]=a;while(a=a.firstChild);for(;c&&!(a=d[--c].nextSibling););}else b=a.nodeValue;return""+b}
function I(a,b,c){if(b===k)return j;try{if(!a.getAttribute)return l}catch(d){return l}Da&&"class"==b&&(b="className");return c==k?!!a.getAttribute(b):a.getAttribute(b,2)==c}function Ia(a,b,c,d,e){return(D?Ja:Ka).call(k,a,b,p(c)?c:k,p(d)?d:k,e||new K)}
function Ja(a,b,c,d,e){if(a instanceof L||8==a.b||c&&a.b===k){var f=b.all;if(!f)return e;a=La(a);if("*"!=a&&(f=b.getElementsByTagName(a),!f))return e;if(c){for(var g=[],r=0;b=f[r++];)I(b,c,d)&&g.push(b);f=g}for(r=0;b=f[r++];)("*"!=a||"!"!=b.tagName)&&M(e,b);return e}Ma(a,b,c,d,e);return e}
function Ka(a,b,c,d,e){b.getElementsByName&&d&&"name"==c&&!w?(b=b.getElementsByName(d),C(b,function(b){a.a(b)&&M(e,b)})):b.getElementsByClassName&&d&&"class"==c?(b=b.getElementsByClassName(d),C(b,function(b){b.className==d&&a.a(b)&&M(e,b)})):a instanceof N?Ma(a,b,c,d,e):b.getElementsByTagName&&(b=b.getElementsByTagName(a.d()),C(b,function(a){I(a,c,d)&&M(e,a)}));return e}
function Na(a,b,c,d,e){var f;if((a instanceof L||8==a.b||c&&a.b===k)&&(f=b.childNodes)){var g=La(a);if("*"!=g&&(f=ua(f,function(a){return a.tagName&&a.tagName.toLowerCase()==g}),!f))return e;c&&(f=ua(f,function(a){return I(a,c,d)}));C(f,function(a){("*"!=g||"!"!=a.tagName&&!("*"==g&&1!=a.nodeType))&&M(e,a)});return e}return Oa(a,b,c,d,e)}function Oa(a,b,c,d,e){for(b=b.firstChild;b;b=b.nextSibling)I(b,c,d)&&a.a(b)&&M(e,b);return e}
function Ma(a,b,c,d,e){for(b=b.firstChild;b;b=b.nextSibling)I(b,c,d)&&a.a(b)&&M(e,b),Ma(a,b,c,d,e)}function La(a){if(a instanceof N){if(8==a.b)return"!";if(a.b===k)return"*"}return a.d()};function K(){this.b=this.a=k;this.i=0}function Pa(a){this.b=a;this.a=this.d=k}function Qa(a,b){if(a.a){if(!b.a)return a}else return b;for(var c=a.a,d=b.a,e=k,f=k,g=0;c&&d;)c.b==d.b||c.b instanceof E&&d.b instanceof E&&c.b.a==d.b.a?(f=c,c=c.a,d=d.a):0<Aa(c.b,d.b)?(f=d,d=d.a):(f=c,c=c.a),(f.d=e)?e.a=f:a.a=f,e=f,g++;for(f=c||d;f;)f.d=e,e=e.a=f,g++,f=f.a;a.b=e;a.i=g;return a}function Ra(a,b){var c=new Pa(b);c.a=a.a;a.b?a.a.d=c:a.a=a.b=c;a.a=c;a.i++}
function M(a,b){var c=new Pa(b);c.d=a.b;a.a?a.b.a=c:a.a=a.b=c;a.b=c;a.i++}function Sa(a){return(a=a.a)?a.b:k}function Ta(a){return(a=Sa(a))?H(a):""}function O(a,b){return new Ua(a,!!b)}function Ua(a,b){this.d=a;this.b=(this.c=b)?a.b:a.a;this.a=k}function P(a){var b=a.b;if(b==k)return k;var c=a.a=b;a.b=a.c?b.d:b.a;return c.b};function t(a){this.g=a;this.b=this.f=l;this.d=k}function Q(a,b){var c=a.a(b);return c instanceof K?+Ta(c):+c}function R(a,b){var c=a.a(b);return c instanceof K?Ta(c):""+c}function S(a,b){var c=a.a(b);return c instanceof K?!!c.i:!!c};function Va(a,b,c){t.call(this,a.g);this.c=a;this.e=b;this.j=c;this.f=b.f||c.f;this.b=b.b||c.b;this.c==Wa&&(!c.b&&!c.f&&4!=c.g&&0!=c.g&&b.d?this.d={name:b.d.name,l:c}:!b.b&&(!b.f&&4!=b.g&&0!=b.g&&c.d)&&(this.d={name:c.d.name,l:b}))}q(Va);
function T(a,b,c,d,e){var b=b.a(d),c=c.a(d),f;if(b instanceof K&&c instanceof K){f=O(b);for(b=P(f);b;b=P(f)){e=O(c);for(d=P(e);d;d=P(e))if(a(H(b),H(d)))return j}return l}if(b instanceof K||c instanceof K){b instanceof K?e=b:(e=c,c=b);e=O(e);b=typeof c;for(d=P(e);d;d=P(e)){switch(b){case "number":f=+H(d);break;case "boolean":f=!!H(d);break;case "string":f=H(d);break;default:h(Error("Illegal primitive type for comparison."))}if(a(f,c))return j}return l}return e?"boolean"==typeof b||"boolean"==typeof c?
a(!!b,!!c):"number"==typeof b||"number"==typeof c?a(+b,+c):a(b,c):a(+b,+c)}Va.prototype.a=function(a){return this.c.k(this.e,this.j,a)};Va.prototype.toString=function(a){var a=a||"",b=a+"binary expression: "+this.c+"\n",a=a+"  ",b=b+(this.e.toString(a)+"\n");return b+=this.j.toString(a)};function Xa(a,b,c,d){this.a=a;this.p=b;this.g=c;this.k=d}Xa.prototype.toString=m("a");var Ya={};
function U(a,b,c,d){a in Ya&&h(Error("Binary operator already created: "+a));a=new Xa(a,b,c,d);return Ya[a.toString()]=a}U("div",6,1,function(a,b,c){return Q(a,c)/Q(b,c)});U("mod",6,1,function(a,b,c){return Q(a,c)%Q(b,c)});U("*",6,1,function(a,b,c){return Q(a,c)*Q(b,c)});U("+",5,1,function(a,b,c){return Q(a,c)+Q(b,c)});U("-",5,1,function(a,b,c){return Q(a,c)-Q(b,c)});U("<",4,2,function(a,b,c){return T(function(a,b){return a<b},a,b,c)});
U(">",4,2,function(a,b,c){return T(function(a,b){return a>b},a,b,c)});U("<=",4,2,function(a,b,c){return T(function(a,b){return a<=b},a,b,c)});U(">=",4,2,function(a,b,c){return T(function(a,b){return a>=b},a,b,c)});var Wa=U("=",3,2,function(a,b,c){return T(function(a,b){return a==b},a,b,c,j)});U("!=",3,2,function(a,b,c){return T(function(a,b){return a!=b},a,b,c,j)});U("and",2,2,function(a,b,c){return S(a,c)&&S(b,c)});U("or",1,2,function(a,b,c){return S(a,c)||S(b,c)});function Za(a,b){b.a.length&&4!=a.g&&h(Error("Primary expression must evaluate to nodeset if filter has predicate(s)."));t.call(this,a.g);this.c=a;this.e=b;this.f=a.f;this.b=a.b}q(Za);Za.prototype.a=function(a){a=this.c.a(a);return $a(this.e,a)};Za.prototype.toString=function(a){var a=a||"",b=a+"Filter: \n",a=a+"  ",b=b+this.c.toString(a);return b+=this.e.toString(a)};function ab(a,b){b.length<a.o&&h(Error("Function "+a.h+" expects at least"+a.o+" arguments, "+b.length+" given"));a.n!==k&&b.length>a.n&&h(Error("Function "+a.h+" expects at most "+a.n+" arguments, "+b.length+" given"));a.s&&C(b,function(b,d){4!=b.g&&h(Error("Argument "+d+" to function "+a.h+" is not of type Nodeset: "+b))});t.call(this,a.g);this.e=a;this.c=b;this.f=a.f||wa(b,function(a){return a.f});this.b=a.r&&!b.length||a.q&&!!b.length||wa(b,function(a){return a.b})}q(ab);
ab.prototype.a=function(a){return this.e.k.apply(k,xa(a,this.c))};ab.prototype.toString=function(a){var b=a||"",a=b+"Function: "+this.e+"\n",b=b+"  ";this.c.length&&(a+=b+"Arguments:",b+="  ",a=va(this.c,function(a,d){return a+"\n"+d.toString(b)},a));return a};function bb(a,b,c,d,e,f,g,r,v){this.h=a;this.g=b;this.f=c;this.r=d;this.q=e;this.k=f;this.o=g;this.n=r!==i?r:g;this.s=!!v}bb.prototype.toString=m("h");var cb={};
function V(a,b,c,d,e,f,g,r){a in cb&&h(Error("Function already created: "+a+"."));cb[a]=new bb(a,b,c,d,l,e,f,g,r)}V("boolean",2,l,l,function(a,b){return S(b,a)},1);V("ceiling",1,l,l,function(a,b){return Math.ceil(Q(b,a))},1);V("concat",3,l,l,function(a,b){var c=ya(arguments,1);return va(c,function(b,c){return b+R(c,a)},"")},2,k);V("contains",2,l,l,function(a,b,c){b=R(b,a);a=R(c,a);return-1!=b.indexOf(a)},2);V("count",1,l,l,function(a,b){return b.a(a).i},1,1,j);V("false",2,l,l,aa(l),0);
V("floor",1,l,l,function(a,b){return Math.floor(Q(b,a))},1);
V("id",4,l,l,function(a,b){function c(a){if(D){var b=e.all[a];if(b){if(b.nodeType&&a==b.id)return b;if(b.length){var c;a:{c=function(b){return a==b.id};for(var d=b.length,f=p(b)?b.split(""):b,g=0;g<d;g++)if(g in f&&c.call(i,f[g])){c=g;break a}c=-1}return 0>c?k:p(b)?b.charAt(c):b[c]}}return k}return e.getElementById(a)}var d=a.a,e=9==d.nodeType?d:d.ownerDocument,d=R(b,a).split(/\s+/),f=[];C(d,function(a){(a=c(a))&&!(0<=ta(f,a))&&f.push(a)});f.sort(Aa);var g=new K;C(f,function(a){M(g,a)});return g},
1);V("lang",2,l,l,aa(l),1);V("last",1,j,l,function(a){1!=arguments.length&&h(Error("Function last expects ()"));return a.d},0);V("local-name",3,l,j,function(a,b){var c=b?Sa(b.a(a)):a.a;return c?c.nodeName.toLowerCase():""},0,1,j);V("name",3,l,j,function(a,b){var c=b?Sa(b.a(a)):a.a;return c?c.nodeName.toLowerCase():""},0,1,j);V("namespace-uri",3,j,l,aa(""),0,1,j);V("normalize-space",3,l,j,function(a,b){return(b?R(b,a):H(a.a)).replace(/[\s\xa0]+/g," ").replace(/^\s+|\s+$/g,"")},0,1);
V("not",2,l,l,function(a,b){return!S(b,a)},1);V("number",1,l,j,function(a,b){return b?Q(b,a):+H(a.a)},0,1);V("position",1,j,l,function(a){return a.b},0);V("round",1,l,l,function(a,b){return Math.round(Q(b,a))},1);V("starts-with",2,l,l,function(a,b,c){b=R(b,a);a=R(c,a);return 0==b.lastIndexOf(a,0)},2);V("string",3,l,j,function(a,b){return b?R(b,a):H(a.a)},0,1);V("string-length",1,l,j,function(a,b){return(b?R(b,a):H(a.a)).length},0,1);
V("substring",3,l,l,function(a,b,c,d){c=Q(c,a);if(isNaN(c)||Infinity==c||-Infinity==c)return"";d=d?Q(d,a):Infinity;if(isNaN(d)||-Infinity===d)return"";var c=Math.round(c)-1,e=Math.max(c,0),a=R(b,a);if(Infinity==d)return a.substring(e);b=Math.round(d);return a.substring(e,c+b)},2,3);V("substring-after",3,l,l,function(a,b,c){b=R(b,a);a=R(c,a);c=b.indexOf(a);return-1==c?"":b.substring(c+a.length)},2);
V("substring-before",3,l,l,function(a,b,c){b=R(b,a);a=R(c,a);a=b.indexOf(a);return-1==a?"":b.substring(0,a)},2);V("sum",1,l,l,function(a,b){for(var c=O(b.a(a)),d=0,e=P(c);e;e=P(c))d+=+H(e);return d},1,1,j);V("translate",3,l,l,function(a,b,c,d){for(var b=R(b,a),c=R(c,a),e=R(d,a),a=[],d=0;d<c.length;d++){var f=c.charAt(d);f in a||(a[f]=e.charAt(d))}c="";for(d=0;d<b.length;d++)f=b.charAt(d),c+=f in a?a[f]:f;return c},3);V("true",2,l,l,aa(j),0);function N(a,b){this.e=a;this.c=b!==i?b:k;this.b=k;switch(a){case "comment":this.b=8;break;case "text":this.b=3;break;case "processing-instruction":this.b=7;break;case "node":break;default:h(Error("Unexpected argument"))}}function db(a){return"comment"==a||"text"==a||"processing-instruction"==a||"node"==a}N.prototype.a=function(a){return this.b===k||this.b==a.nodeType};N.prototype.d=m("e");
N.prototype.toString=function(a){var a=a||"",b=a+"kindtest: "+this.e;this.c===k||(b+="\n"+this.c.toString(a+"  "));return b};function eb(a){t.call(this,3);this.c=a.substring(1,a.length-1)}q(eb);eb.prototype.a=m("c");eb.prototype.toString=function(a){return(a||"")+"literal: "+this.c};function L(a){this.h=a.toLowerCase()}L.prototype.a=function(a){var b=a.nodeType;if(1==b||2==b)return"*"==this.h||this.h==a.nodeName.toLowerCase()?j:this.h==(a.namespaceURI||"http://www.w3.org/1999/xhtml")+":*"};L.prototype.d=m("h");L.prototype.toString=function(a){return(a||"")+"nametest: "+this.h};function fb(a){t.call(this,1);this.c=a}q(fb);fb.prototype.a=m("c");fb.prototype.toString=function(a){return(a||"")+"number: "+this.c};function gb(a,b){t.call(this,a.g);this.e=a;this.c=b;this.f=a.f;this.b=a.b;if(1==this.c.length){var c=this.c[0];!c.m&&c.e==hb&&(c=c.j,"*"!=c.d()&&(this.d={name:c.d(),l:k}))}}q(gb);function ib(){t.call(this,4)}q(ib);ib.prototype.a=function(a){var b=new K,a=a.a;9==a.nodeType?M(b,a):M(b,a.ownerDocument);return b};ib.prototype.toString=function(a){return a+"RootHelperExpr"};function jb(){t.call(this,4)}q(jb);jb.prototype.a=function(a){var b=new K;M(b,a.a);return b};
jb.prototype.toString=function(a){return a+"ContextHelperExpr"};gb.prototype.a=function(a){var b=this.e.a(a);b instanceof K||h(Error("FilterExpr must evaluate to nodeset."));for(var a=this.c,c=0,d=a.length;c<d&&b.i;c++){var e=a[c],f=O(b,e.e.a),g;if(!e.f&&e.e==kb){for(g=P(f);(b=P(f))&&(!g.contains||g.contains(b))&&b.compareDocumentPosition(g)&8;g=b);b=e.a(new A(g))}else if(!e.f&&e.e==lb)g=P(f),b=e.a(new A(g));else{g=P(f);for(b=e.a(new A(g));(g=P(f))!=k;)g=e.a(new A(g)),b=Qa(b,g)}}return b};
gb.prototype.toString=function(a){var b=a||"",c=b+"PathExpr:\n",b=b+"  ",c=c+this.e.toString(b);this.c.length&&(c+=b+"Steps:\n",b+="  ",C(this.c,function(a){c+=a.toString(b)}));return c};function mb(a,b){this.a=a;this.b=!!b}function $a(a,b,c){for(c=c||0;c<a.a.length;c++)for(var d=a.a[c],e=O(b),f=b.i,g,r=0;g=P(e);r++){var v=a.b?f-r:r+1;g=d.a(new A(g,v,f));var J;"number"==typeof g?J=v==g:"string"==typeof g||"boolean"==typeof g?J=!!g:g instanceof K?J=0<g.i:h(Error("Predicate.evaluate returned an unexpected type."));if(!J){v=e;g=v.d;var s=v.a;s||h(Error("Next must be called at least once before remove."));var x=s.d,s=s.a;x?x.a=s:g.a=s;s?s.d=x:g.b=x;g.i--;v.a=k}}return b}
mb.prototype.toString=function(a){var b=a||"",a=b+"Predicates:",b=b+"  ";return va(this.a,function(a,d){return a+"\n"+b+d.toString(b)},a)};function W(a,b,c,d){t.call(this,4);this.e=a;this.j=b;this.c=c||new mb([]);this.m=!!d;b=0<this.c.a.length?this.c.a[0].d:k;a.b&&b&&(a=b.name,a=D?a.toLowerCase():a,this.d={name:a,l:b.l});a:{a=this.c;for(b=0;b<a.a.length;b++)if(c=a.a[b],c.f||1==c.g||0==c.g){a=j;break a}a=l}this.f=a}q(W);
W.prototype.a=function(a){var b=a.a,c=k,c=this.d,d=k,e=k,f=0;c&&(d=c.name,e=c.l?R(c.l,a):k,f=1);if(this.m)if(!this.f&&this.e==nb)c=Ia(this.j,b,d,e),c=$a(this.c,c,f);else if(a=O((new W(ob,new N("node"))).a(a)),b=P(a))for(c=this.k(b,d,e,f);(b=P(a))!=k;)c=Qa(c,this.k(b,d,e,f));else c=new K;else c=this.k(a.a,d,e,f);return c};W.prototype.k=function(a,b,c,d){a=this.e.d(this.j,a,b,c);return a=$a(this.c,a,d)};
W.prototype.toString=function(a){var a=a||"",b=a+"Step: \n",a=a+"  ",b=b+(a+"Operator: "+(this.m?"//":"/")+"\n");this.e.h&&(b+=a+"Axis: "+this.e+"\n");b+=this.j.toString(a);if(this.c.length)for(var b=b+(a+"Predicates: \n"),c=0;c<this.c.length;c++)var d=c<this.c.length-1?", ":"",b=b+(this.c[c].toString(a)+d);return b};function pb(a,b,c,d){this.h=a;this.d=b;this.a=c;this.b=d}pb.prototype.toString=m("h");var qb={};
function X(a,b,c,d){a in qb&&h(Error("Axis already created: "+a));b=new pb(a,b,c,!!d);return qb[a]=b}X("ancestor",function(a,b){for(var c=new K,d=b;d=d.parentNode;)a.a(d)&&Ra(c,d);return c},j);X("ancestor-or-self",function(a,b){var c=new K,d=b;do a.a(d)&&Ra(c,d);while(d=d.parentNode);return c},j);
var hb=X("attribute",function(a,b){var c=new K,d=a.d();if("style"==d&&b.style&&D)return M(c,new E(b.style,b,"style",b.style.cssText)),c;var e=b.attributes;if(e)if(a instanceof N&&a.b===k||"*"==d)for(var d=0,f;f=e[d];d++)D?f.nodeValue&&M(c,Ea(b,f)):M(c,f);else(f=e.getNamedItem(d))&&(D?f.nodeValue&&M(c,Ea(b,f)):M(c,f));return c},l),nb=X("child",function(a,b,c,d,e){return(D?Na:Oa).call(k,a,b,p(c)?c:k,p(d)?d:k,e||new K)},l,j);X("descendant",Ia,l,j);
var ob=X("descendant-or-self",function(a,b,c,d){var e=new K;I(b,c,d)&&a.a(b)&&M(e,b);return Ia(a,b,c,d,e)},l,j),kb=X("following",function(a,b,c,d){var e=new K;do for(var f=b;f=f.nextSibling;)I(f,c,d)&&a.a(f)&&M(e,f),e=Ia(a,f,c,d,e);while(b=b.parentNode);return e},l,j);X("following-sibling",function(a,b){for(var c=new K,d=b;d=d.nextSibling;)a.a(d)&&M(c,d);return c},l);X("namespace",function(){return new K},l);
var rb=X("parent",function(a,b){var c=new K;if(9==b.nodeType)return c;if(2==b.nodeType)return M(c,b.ownerElement),c;var d=b.parentNode;a.a(d)&&M(c,d);return c},l),lb=X("preceding",function(a,b,c,d){var e=new K,f=[];do f.unshift(b);while(b=b.parentNode);for(var g=1,r=f.length;g<r;g++){for(var v=[],b=f[g];b=b.previousSibling;)v.unshift(b);for(var J=0,s=v.length;J<s;J++)b=v[J],I(b,c,d)&&a.a(b)&&M(e,b),e=Ia(a,b,c,d,e)}return e},j,j);
X("preceding-sibling",function(a,b){for(var c=new K,d=b;d=d.previousSibling;)a.a(d)&&Ra(c,d);return c},j);var sb=X("self",function(a,b){var c=new K;a.a(b)&&M(c,b);return c},l);function tb(a){t.call(this,1);this.c=a;this.f=a.f;this.b=a.b}q(tb);tb.prototype.a=function(a){return-Q(this.c,a)};tb.prototype.toString=function(a){var a=a||"",b=a+"UnaryExpr: -\n";return b+=this.c.toString(a+"  ")};function ub(a){t.call(this,4);this.c=a;this.f=wa(this.c,function(a){return a.f});this.b=wa(this.c,function(a){return a.b})}q(ub);ub.prototype.a=function(a){var b=new K;C(this.c,function(c){c=c.a(a);c instanceof K||h(Error("PathExpr must evaluate to NodeSet."));b=Qa(b,c)});return b};ub.prototype.toString=function(a){var b=a||"",c=b+"UnionExpr:\n",b=b+"  ";C(this.c,function(a){c+=a.toString(b)+"\n"});return c.substring(0,c.length)};function vb(a){this.a=a}function wb(a){for(var b,c=[];;){Y(a,"Missing right hand side of binary expression.");b=xb(a);var d=G(a.a);if(!d)break;var e=(d=Ya[d]||k)&&d.p;if(!e){a.a.a--;break}for(;c.length&&e<=c[c.length-1].p;)b=new Va(c.pop(),c.pop(),b);c.push(b,d)}for(;c.length;)b=new Va(c.pop(),c.pop(),b);return b}function Y(a,b){a.a.b.length<=a.a.a&&h(Error(b))}function yb(a,b){var c=G(a.a);c!=b&&h(Error("Bad token, expected: "+b+" got: "+c))}
function zb(a){a=G(a.a);")"!=a&&h(Error("Bad token: "+a))}function Ab(a){a=G(a.a);2>a.length&&h(Error("Unclosed literal string"));return new eb(a)}function Bb(a){return"*"!=F(a.a)&&":"==F(a.a,1)&&"*"==F(a.a,2)?new L(G(a.a)+G(a.a)+G(a.a)):new L(G(a.a))}
function Cb(a){var b,c=[],d;if("/"==F(a.a)||"//"==F(a.a)){b=G(a.a);d=F(a.a);if("/"==b&&(a.a.b.length<=a.a.a||"."!=d&&".."!=d&&"@"!=d&&"*"!=d&&!/(?![0-9])[\w]/.test(d)))return new ib;d=new ib;Y(a,"Missing next location step.");b=Db(a,b);c.push(b)}else{a:{b=F(a.a);d=b.charAt(0);switch(d){case "$":h(Error("Variable reference not allowed in HTML XPath"));case "(":G(a.a);b=wb(a);Y(a,'unclosed "("');yb(a,")");break;case '"':case "'":b=Ab(a);break;default:if(isNaN(+b))if(!db(b)&&/(?![0-9])[\w]/.test(d)&&
"("==F(a.a,1)){b=G(a.a);b=cb[b]||k;G(a.a);for(d=[];")"!=F(a.a);){Y(a,"Missing function argument list.");d.push(wb(a));if(","!=F(a.a))break;G(a.a)}Y(a,"Unclosed function argument list.");zb(a);b=new ab(b,d)}else{b=k;break a}else b=new fb(+G(a.a))}"["==F(a.a)&&(d=new mb(Eb(a)),b=new Za(b,d))}if(b)if("/"==F(a.a)||"//"==F(a.a))d=b;else return b;else b=Db(a,"/"),d=new jb,c.push(b)}for(;"/"==F(a.a)||"//"==F(a.a);)b=G(a.a),Y(a,"Missing next location step."),b=Db(a,b),c.push(b);return new gb(d,c)}
function Db(a,b){var c,d,e;"/"!=b&&"//"!=b&&h(Error('Step op should be "/" or "//"'));if("."==F(a.a))return d=new W(sb,new N("node")),G(a.a),d;if(".."==F(a.a))return d=new W(rb,new N("node")),G(a.a),d;var f;"@"==F(a.a)?(f=hb,G(a.a),Y(a,"Missing attribute name")):"::"==F(a.a,1)?(/(?![0-9])[\w]/.test(F(a.a).charAt(0))||h(Error("Bad token: "+G(a.a))),e=G(a.a),(f=qb[e]||k)||h(Error("No axis with name: "+e)),G(a.a),Y(a,"Missing node name")):f=nb;e=F(a.a);if(/(?![0-9])[\w]/.test(e.charAt(0)))if("("==F(a.a,
1)){db(e)||h(Error("Invalid node type: "+e));c=G(a.a);db(c)||h(Error("Invalid type name: "+c));yb(a,"(");Y(a,"Bad nodetype");e=F(a.a).charAt(0);var g=k;if('"'==e||"'"==e)g=Ab(a);Y(a,"Bad nodetype");zb(a);c=new N(c,g)}else c=Bb(a);else"*"==e?c=Bb(a):h(Error("Bad token: "+G(a.a)));e=new mb(Eb(a),f.a);return d||new W(f,c,e,"//"==b)}function Eb(a){for(var b=[];"["==F(a.a);){G(a.a);Y(a,"Missing predicate expression.");var c=wb(a);b.push(c);Y(a,"Unclosed predicate expression.");yb(a,"]")}return b}
function xb(a){if("-"==F(a.a))return G(a.a),new tb(xb(a));var b=Cb(a);if("|"!=F(a.a))a=b;else{for(b=[b];"|"==G(a.a);)Y(a,"Missing next union location path."),b.push(Cb(a));a.a.a--;a=new ub(b)}return a};function Fb(a){a.length||h(Error("Empty XPath expression."));for(var a=a.match(Ga),b=0;b<a.length;b++)Ha.test(a[b])&&a.splice(b,1);a=new Fa(a);a.b.length<=a.a&&h(Error("Invalid XPath expression."));var c=wb(new vb(a));a.b.length<=a.a||h(Error("Bad token: "+G(a)));this.evaluate=function(a,b){var f=c.a(new A(a));return new Z(f,b)}}
function Z(a,b){0==b&&(a instanceof K?b=4:"string"==typeof a?b=2:"number"==typeof a?b=1:"boolean"==typeof a?b=3:h(Error("Unexpected evaluation result.")));2!=b&&(1!=b&&3!=b&&!(a instanceof K))&&h(Error("value could not be converted to the specified type"));this.resultType=b;var c;switch(b){case 2:this.stringValue=a instanceof K?Ta(a):""+a;break;case 1:this.numberValue=a instanceof K?+Ta(a):+a;break;case 3:this.booleanValue=a instanceof K?0<a.i:!!a;break;case 4:case 5:case 6:case 7:var d=O(a);c=[];
for(var e=P(d);e;e=P(d))c.push(e instanceof E?e.a:e);this.snapshotLength=a.i;this.invalidIteratorState=l;break;case 8:case 9:d=Sa(a);this.singleNodeValue=d instanceof E?d.a:d;break;default:h(Error("Unknown XPathResult type."))}var f=0;this.iterateNext=function(){4!=b&&5!=b&&h(Error("iterateNext called with wrong result type"));return f>=c.length?k:c[f++]};this.snapshotItem=function(a){6!=b&&7!=b&&h(Error("snapshotItem called with wrong result type"));return a>=c.length||0>a?k:c[a]}}Z.ANY_TYPE=0;
Z.NUMBER_TYPE=1;Z.STRING_TYPE=2;Z.BOOLEAN_TYPE=3;Z.UNORDERED_NODE_ITERATOR_TYPE=4;Z.ORDERED_NODE_ITERATOR_TYPE=5;Z.UNORDERED_NODE_SNAPSHOT_TYPE=6;Z.ORDERED_NODE_SNAPSHOT_TYPE=7;Z.ANY_UNORDERED_NODE_TYPE=8;Z.FIRST_ORDERED_NODE_TYPE=9;function Gb(a){var a=a||n,b=a.document;b.evaluate||(a.XPathResult=Z,b.evaluate=function(a,b,e,f){return(new Fb(a)).evaluate(b,f)},b.createExpression=function(a){return new Fb(a)})}var Hb=["wgxpath","install"],$=n;!(Hb[0]in $)&&$.execScript&&$.execScript("var "+Hb[0]);for(var Ib;Hb.length&&(Ib=Hb.shift());)!Hb.length&&Gb!==i?$[Ib]=Gb:$=$[Ib]?$[Ib]:$[Ib]={};})()
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    