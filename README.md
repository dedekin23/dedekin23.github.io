<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="robots" content="noindex, nofollow">
</header>


<main class="wp-container-61e15fb4d519d wp-block-group" id="wp--skip-link--target">

<div class="wp-container-61e15fb4d4ac3 entry-content wp-block-post-content">
<div class="wp-container-61e15fb4d3140 wp-block-query"><ul class="wp-container-61e15fb4d217c wp-block-post-template"><li class="wp-block-post post-3 post type-post status-publish format-standard hentry category-tidak-dikategorikan">
<h2 style="font-size: 64px; line-height: 1.2;" class="wp-container-61e15fb4d1837 wp-block-post-title"><p rel="">Halo Dunia!</p></h2>



<div class="wp-container-61e15fb4cfdf7 entry-content wp-block-post-content"> <p>Selamat Datang di WordPress! Ini adalah pos pertama Anda. Sunting atau hapus pos tersebut sebagai langkah pertama dalam perjalanan blogging Anda.</p> </div>


<div class="wp-block-image"><figure class="aligncenter size-large"><img loading="lazy" width="802" height="404" data-attachment-id="17" data-permalink="https://michaelbonar0021.wordpress.com/uhushuhds/" data-orig-file="https://michaelbonar0021.files.wordpress.com/2022/01/uhushuhds.jpg" data-orig-size="802,404" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;0&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;0&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;0&quot;,&quot;iso&quot;:&quot;0&quot;,&quot;shutter_speed&quot;:&quot;0&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;0&quot;}" data-image-title="uhushuhds" data-image-description="" data-image-caption="" data-medium-file="https://michaelbonar0021.files.wordpress.com/2022/01/uhushuhds.jpg?w=300" data-large-file="https://michaelbonar0021.files.wordpress.com/2022/01/uhushuhds.jpg?w=802" src="https://michaelbonar0021.files.wordpress.com/2022/01/uhushuhds.jpg?w=802" alt="" class="wp-image-17" srcset="https://michaelbonar0021.files.wordpress.com/2022/01/uhushuhds.jpg 802w, https://michaelbonar0021.files.wordpress.com/2022/01/uhushuhds.jpg?w=150 150w, https://michaelbonar0021.files.wordpress.com/2022/01/uhushuhds.jpg?w=300 300w, https://michaelbonar0021.files.wordpress.com/2022/01/uhushuhds.jpg?w=768 768w" sizes="(max-width: 802px) 100vw, 802px"></figure></div>


<div class="wp-container-61e15fb4d066b entry-content wp-block-post-content"> <p>Selamat Datang di WordPress! Ini adalah pos pertama Anda. Sunting atau hapus pos tersebut sebagai langkah pertama dalam perjalanan blogging Anda.</p> </div>


<div class="wp-container-61e15fb4d1148 wp-block-group"><div style="font-size: 16px;" class="wp-block-post-date"><time datetime="2022-01-13T18:21:16+07:00"><p>13 Januari 2022</p></time></div>

<div style="font-size: 16px;" class="taxonomy-category wp-block-post-terms"><p>Tidak Dikategorikan</p></div>

</div>



<div style="height:120px;" aria-hidden="true" class="wp-block-spacer"></div>

</li></ul>

</div>
</div>
</main>


<footer class="site-footer-container wp-block-template-part">
<div style="height:70px" aria-hidden="true" class="wp-block-spacer"></div>

<div style="height:120px" aria-hidden="true" class="wp-block-spacer"></div>
</footer>
</div>
<!-- wpcom_wp_footer -->
<script type="text/javascript">
/* <![CDATA[ */
    jQuery(document).ready( function($) {
        function doFollowingHover() {
            $('#wp-admin-bar-follow > a').unbind( '.unfollow' );

            $('#wp-admin-bar-follow > a').bind( 'mouseover.unfollow', function() {

                $(this).html( "Berhenti mengikuti" ).parent( 'li' ).addClass( 'unfollow' );
            });
            $('#wp-admin-bar-follow > a').bind( 'mouseout.unfollow', function() {
                $(this).html( "Mengikuti" ).parent( 'li' ).removeClass( 'unfollow' );
            });
        }
                        doFollowingHover();
        
        $('#wp-admin-bar-follow > a').click( function( e ) {
            $('#wp-admin-bar-follow > a').unbind( '.unfollow' );

            e.preventDefault();

            var link = $( this ), li = $( '#wp-admin-bar-follow' ), timeout = 0;

            if ( li.hasClass( 'subscribed' ) ) {
                li.removeClass( 'subscribed' ).removeClass( 'unfollow' );
                link.html( "Ikuti" );

                $('body').append( $( 'div.wpcom-bubble' ).removeClass( 'fadein' ) ).off( 'click.bubble' );

                var action = 'ab_unsubscribe_from_blog';
            } else {
                li.addClass( 'subscribed' ).removeClass( 'unfollow' );
                link.html( "Mengikuti" );

                    var left = 131 - link.width();
                    li.append( $( 'div.wpcom-bubble' ).css( { left: '-' + left + 'px' } ) );
                    $( 'div.bubble-txt', 'div.wpcom-bubble' ).html( "New posts from this blog will now appear in \u003Ca target=\u0022_blank\u0022 href=\u0022http:\/\/id.wordpress.com\/\u0022\u003Eyour reader\u003C\/a\u003E. You can manage email alerts from your \u003Ca target=\u0022_blank\u0022 href=\u0022http:\/\/id.wordpress.com\/following\/edit\/\u0022\u003Esubscriptions page\u003C\/a\u003E." );

                    $( 'div.wpcom-bubble.action-bubble' ).addClass( 'fadein' );

                    setTimeout( function() {
                        $('body').on( 'click.bubble touchstart.bubble', function(e) {
                            if ( !$(e.target).hasClass('wpcom-bubble') && !$(e.target).parents( 'div.wpcom-bubble' ).length )
                                hideBubble();
                        });
                        setTimeout( hideBubble, 15000 );
                    }, 500 );

                var action = 'ab_subscribe_to_blog';
                $('#wp-admin-bar-follow > a').bind( 'mouseout.shift', function() {
                    doFollowingHover();
                    $(this).unbind( '.shift' );
                });
            }

            var nonce = link.attr( 'href' ).split( '_wpnonce=' );
            nonce = nonce[1];

            $.post( "https:\/\/michaelbonar0021.wordpress.com\/wp-admin\/admin-ajax.php", {
                'action': action,
                '_wpnonce': nonce,
                'source': 'admin_bar',
                'blog_id': 201706991				});
        });
    });
/* ]]> */
</script>

            <style id="skip-link-styles">
        .skip-link.screen-reader-text {
            border: 0;
            clip: rect(1px,1px,1px,1px);
            clip-path: inset(50%);
            height: 1px;
            margin: -1px;
            overflow: hidden;
            padding: 0;
            position: absolute !important;
            width: 1px;
            word-wrap: normal !important;
        }

        .skip-link.screen-reader-text:focus {
            background-color: #eee;
            clip: auto !important;
            clip-path: none;
            color: #444;
            display: block;
            font-size: 1em;
            height: auto;
            left: 5px;
            line-height: normal;
            padding: 15px 23px 14px;
            text-decoration: none;
            top: 5px;
            width: auto;
            z-index: 100000;
        }
    </style>
            <script>
    ( function() {
        var skipLinkTarget = document.querySelector( 'main' ),
            sibling,
            skipLinkTargetID,
            skipLink;

        // Early exit if a skip-link target can't be located.
        if ( ! skipLinkTarget ) {
            return;
        }

        // Get the site wrapper.
        // The skip-link will be injected in the beginning of it.
        sibling = document.querySelector( '.wp-site-blocks' );

        // Early exit if the root element was not found.
        if ( ! sibling ) {
            return;
        }

        // Get the skip-link target's ID, and generate one if it doesn't exist.
        skipLinkTargetID = skipLinkTarget.id;
        if ( ! skipLinkTargetID ) {
            skipLinkTargetID = 'wp--skip-link--target';
            skipLinkTarget.id = skipLinkTargetID;
        }

        // Create the skip link.
        skipLink = document.createElement( 'a' );
        skipLink.classList.add( 'skip-link', 'screen-reader-text' );
        skipLink.href = '#' + skipLinkTargetID;
        skipLink.innerHTML = 'Lanjut ke konten';

        // Inject the skip link.
        sibling.parentElement.insertBefore( skipLink, sibling );
    }() );
    </script>
    <script src="//0.gravatar.com/js/gprofiles.js?ver=202202y" id="grofiles-cards-js"></script>
<script id="wpgroho-js-extra">
var WPGroHo = {"my_hash":"4a850e994dd9a005877d7116b716404c"};
</script>
<script crossorigin="anonymous" type="text/javascript" src="https://s0.wp.com/wp-content/mu-plugins/gravatar-hovercards/wpgroho.js?m=1610363240h"></script>

<script>
    // Initialize and attach hovercards to all gravatars
    ( function() {
        function init() {
            if ( typeof Gravatar === 'undefined' ) {
                return;
            }

            if ( typeof Gravatar.init !== 'function' ) {
                return;
            }

            Gravatar.profile_cb = function ( hash, id ) {
                WPGroHo.syncProfileData( hash, id );
            };

            Gravatar.my_hash = WPGroHo.my_hash;
            Gravatar.init( 'body', '#wp-admin-bar-my-account' );
        }

        if ( document.readyState !== 'loading' ) {
            init();
        } else {
            document.addEventListener( 'DOMContentLoaded', init );
        }
    } )();
</script>

    <div style="display:none">
<div class="grofile-hash-map-4a850e994dd9a005877d7116b716404c">
</div>
</div>
<div id="report-form-window" style="display:none;"></div><style>.wp-container-61e15fb4cbf46 {display: flex;gap: var( --wp--style--block-gap, 0.5em );flex-wrap: wrap;align-items: center;}.wp-container-61e15fb4cbf46 > * { margin: 0; }</style><style>.wp-container-61e15fb4cc5bc {display: flex;gap: var( --wp--style--block-gap, 0.5em );flex-wrap: wrap;align-items: center;}.wp-container-61e15fb4cc5bc > * { margin: 0; }</style><style>.wp-container-61e15fb4cdd25 {display: flex;gap: var( --wp--style--block-gap, 0.5em );flex-wrap: wrap;align-items: center;justify-content: flex-end;}.wp-container-61e15fb4cdd25 > * { margin: 0; }</style><style>.wp-container-61e15fb4ce3fb {display: flex;gap: var( --wp--style--block-gap, 0.5em );flex-wrap: wrap;align-items: center;justify-content: space-between;}.wp-container-61e15fb4ce3fb > * { margin: 0; }</style><style>.wp-container-61e15fb4cea83 > * {max-width: 664px;margin-left: auto !important;margin-right: auto !important;}.wp-container-61e15fb4cea83 > .alignwide { max-width: 1128px;}.wp-container-61e15fb4cea83 .alignfull { max-width: none; }.wp-container-61e15fb4cea83 .alignleft { float: left; margin-right: 2em; }.wp-container-61e15fb4cea83 .alignright { float: right; margin-left: 2em; }.wp-container-61e15fb4cea83 > * { margin-top: 0; margin-bottom: 0; }.wp-container-61e15fb4cea83 > * + * { margin-top: var( --wp--style--block-gap );  margin-bottom: 0; }</style><style>.wp-container-61e15fb4cfdf7 .alignleft { float: left; margin-right: 2em; }.wp-container-61e15fb4cfdf7 .alignright { float: right; margin-left: 2em; }.wp-container-61e15fb4cfdf7 > * { margin-top: 0; margin-bottom: 0; }.wp-container-61e15fb4cfdf7 > * + * { margin-top: var( --wp--style--block-gap );  margin-bottom: 0; }</style><style>.wp-container-61e15fb4d066b .alignleft { float: left; margin-right: 2em; }.wp-container-61e15fb4d066b .alignright { float: right; margin-left: 2em; }.wp-container-61e15fb4d066b > * { margin-top: 0; margin-bottom: 0; }.wp-container-61e15fb4d066b > * + * { margin-top: var( --wp--style--block-gap );  margin-bottom: 0; }</style><style>.wp-container-61e15fb4d1148 {display: flex;gap: var( --wp--style--block-gap, 0.5em );flex-wrap: wrap;align-items: center;}.wp-container-61e15fb4d1148 > * { margin: 0; }</style><style>.wp-container-61e15fb4d1837 .alignleft { float: left; margin-right: 2em; }.wp-container-61e15fb4d1837 .alignright { float: right; margin-left: 2em; }.wp-container-61e15fb4d1837 > * { margin-top: 0; margin-bottom: 0; }.wp-container-61e15fb4d1837 > * + * { margin-top: var( --wp--style--block-gap );  margin-bottom: 0; }</style><style>.wp-container-61e15fb4d217c .alignleft { float: left; margin-right: 2em; }.wp-container-61e15fb4d217c .alignright { float: right; margin-left: 2em; }.wp-container-61e15fb4d217c > * { margin-top: 0; margin-bottom: 0; }.wp-container-61e15fb4d217c > * + * { margin-top: var( --wp--style--block-gap );  margin-bottom: 0; }</style><style>.wp-container-61e15fb4d2ab6 {display: flex;gap: var( --wp--style--block-gap, 0.5em );flex-wrap: wrap;align-items: center;}.wp-container-61e15fb4d2ab6 > * { margin: 0; }</style><style>.wp-container-61e15fb4d3140 .alignleft { float: left; margin-right: 2em; }.wp-container-61e15fb4d3140 .alignright { float: right; margin-left: 2em; }.wp-container-61e15fb4d3140 > * { margin-top: 0; margin-bottom: 0; }.wp-container-61e15fb4d3140 > * + * { margin-top: var( --wp--style--block-gap );  margin-bottom: 0; }</style>		<div id="jp-carousel-loading-overlay">
        <div id="jp-carousel-loading-wrapper">
            <span id="jp-carousel-library-loading">&nbsp;</span>
        </div>
    </div>
    <div class="jp-carousel-overlay" style="display: none;">

    <div class="jp-carousel-container">
        <!-- The Carousel Swiper -->
        <div class="jp-carousel-wrap swiper-container jp-carousel-swiper-container jp-carousel-transitions" itemscope="" itemtype="https://schema.org/ImageGallery">
            <div class="jp-carousel swiper-wrapper"></div>
            <div class="jp-swiper-button-prev swiper-button-prev">
                <svg width="25" height="24" viewBox="0 0 25 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <mask id="maskPrev" mask-type="alpha" maskUnits="userSpaceOnUse" x="8" y="6" width="9" height="12">
                        <path d="M16.2072 16.59L11.6496 12L16.2072 7.41L14.8041 6L8.8335 12L14.8041 18L16.2072 16.59Z" fill="white"></path>
                    </mask>
                    <g mask="url(#maskPrev)">
                        <rect x="0.579102" width="23.8823" height="24" fill="#FFFFFF"></rect>
                    </g>
                </svg>
            </div>
            <div class="jp-swiper-button-next swiper-button-next">
                <svg width="25" height="24" viewBox="0 0 25 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <mask id="maskNext" mask-type="alpha" maskUnits="userSpaceOnUse" x="8" y="6" width="8" height="12">
                        <path d="M8.59814 16.59L13.1557 12L8.59814 7.41L10.0012 6L15.9718 12L10.0012 18L8.59814 16.59Z" fill="white"></path>
                    </mask>
                    <g mask="url(#maskNext)">
                        <rect x="0.34375" width="23.8822" height="24" fill="#FFFFFF"></rect>
                    </g>
                </svg>
            </div>
        </div>
        <!-- The main close buton -->
        <div class="jp-carousel-close-hint">
            <svg width="25" height="24" viewBox="0 0 25 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                <mask id="maskClose" mask-type="alpha" maskUnits="userSpaceOnUse" x="5" y="5" width="15" height="14">
                    <path d="M19.3166 6.41L17.9135 5L12.3509 10.59L6.78834 5L5.38525 6.41L10.9478 12L5.38525 17.59L6.78834 19L12.3509 13.41L17.9135 19L19.3166 17.59L13.754 12L19.3166 6.41Z" fill="white"></path>
                </mask>
                <g mask="url(#maskClose)">
                    <rect x="0.409668" width="23.8823" height="24" fill="#FFFFFF"></rect>
                </g>
            </svg>
        </div>
        <!-- Image info, comments and meta -->
        <div class="jp-carousel-info">
            <div class="jp-carousel-info-footer">
                <div class="jp-carousel-pagination-container">
                    <div class="jp-swiper-pagination swiper-pagination"></div>
                    <div class="jp-carousel-pagination"></div>
                </div>
                <div class="jp-carousel-photo-title-container">
                    <h2 class="jp-carousel-photo-caption"></h2>
                </div>
                <div class="jp-carousel-photo-icons-container">
                    <a href="#" class="jp-carousel-icon-btn jp-carousel-icon-info" aria-label="Ubah visibilitas metadata foto">
                        <span class="jp-carousel-icon">
                            <svg width="25" height="24" viewBox="0 0 25 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                                <mask id="maskInfo" mask-type="alpha" maskUnits="userSpaceOnUse" x="2" y="2" width="21" height="20">
                                    <path fill-rule="evenodd" clip-rule="evenodd" d="M12.7537 2C7.26076 2 2.80273 6.48 2.80273 12C2.80273 17.52 7.26076 22 12.7537 22C18.2466 22 22.7046 17.52 22.7046 12C22.7046 6.48 18.2466 2 12.7537 2ZM11.7586 7V9H13.7488V7H11.7586ZM11.7586 11V17H13.7488V11H11.7586ZM4.79292 12C4.79292 16.41 8.36531 20 12.7537 20C17.142 20 20.7144 16.41 20.7144 12C20.7144 7.59 17.142 4 12.7537 4C8.36531 4 4.79292 7.59 4.79292 12Z" fill="white"></path>
                                </mask>
                                <g mask="url(#maskInfo)">
                                    <rect x="0.8125" width="23.8823" height="24" fill="#FFFFFF"></rect>
                                </g>
                            </svg>
                        </span>
                    </a>
                                            <a href="#" class="jp-carousel-icon-btn jp-carousel-icon-comments" aria-label="Ubah visibilitas komentar foto">
                        <span class="jp-carousel-icon">
                            <svg width="25" height="24" viewBox="0 0 25 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                                <mask id="maskComments" mask-type="alpha" maskUnits="userSpaceOnUse" x="2" y="2" width="21" height="20">
                                    <path fill-rule="evenodd" clip-rule="evenodd" d="M4.3271 2H20.2486C21.3432 2 22.2388 2.9 22.2388 4V16C22.2388 17.1 21.3432 18 20.2486 18H6.31729L2.33691 22V4C2.33691 2.9 3.2325 2 4.3271 2ZM6.31729 16H20.2486V4H4.3271V18L6.31729 16Z" fill="white"></path>
                                </mask>
                                <g mask="url(#maskComments)">
                                    <rect x="0.34668" width="23.8823" height="24" fill="#FFFFFF"></rect>
                                </g>
                            </svg>

                            <span class="jp-carousel-has-comments-indicator" aria-label="Gambar ini memiliki komentar."></span>
                        </span>
                    </a>
                                        </div>
            </div>
            <div class="jp-carousel-info-extra">
                <div class="jp-carousel-info-content-wrapper">
                    <div class="jp-carousel-photo-title-container">
                        <h2 class="jp-carousel-photo-title"></h2>
                    </div>
                    <div class="jp-carousel-comments-wrapper">
                                                        <div id="jp-carousel-comments-loading">
                                <span>Memuat Komentar...</span>
                            </div>
                            <div class="jp-carousel-comments"></div>
                            <div id="jp-carousel-comment-form-container">
                                <span id="jp-carousel-comment-form-spinner">&nbsp;</span>
                                <div id="jp-carousel-comment-post-results"></div>
                                                                                                                    <form id="jp-carousel-comment-form">
                                            <label for="jp-carousel-comment-form-comment-field" class="screen-reader-text">Tulis Komentar...</label>
                                            <textarea name="comment" class="jp-carousel-comment-form-field jp-carousel-comment-form-textarea" id="jp-carousel-comment-form-comment-field" placeholder="Tulis Komentar..."></textarea>
                                            <div id="jp-carousel-comment-form-submit-and-info-wrapper">
                                                <div id="jp-carousel-comment-form-commenting-as">
                                                                                                                <p id="jp-carousel-commenting-as">
                                                            Berkomentar sebagai Michael Manullang															</p>
                                                                                                        </div>
                                                <input type="submit" name="submit" class="jp-carousel-comment-form-button" id="jp-carousel-comment-form-button-submit" value="Kirim Komentar">
                                            </div>
                                        </form>
                                                                                                        </div>
                                                </div>
                    <div class="jp-carousel-image-meta">
                        <div class="jp-carousel-title-and-caption">
                            <div class="jp-carousel-photo-info">
                                <h3 class="jp-carousel-caption" itemprop="caption description"></h3>
                            </div>

                            <div class="jp-carousel-photo-description"></div>
                        </div>
                        <ul class="jp-carousel-image-exif" style="display: none;"></ul>
                        <a class="jp-carousel-image-download" target="_blank" style="display: none;">
                            <svg width="25" height="24" viewBox="0 0 25 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                                <mask id="mask0" mask-type="alpha" maskUnits="userSpaceOnUse" x="3" y="3" width="19" height="18">
                                    <path fill-rule="evenodd" clip-rule="evenodd" d="M5.84615 5V19H19.7775V12H21.7677V19C21.7677 20.1 20.8721 21 19.7775 21H5.84615C4.74159 21 3.85596 20.1 3.85596 19V5C3.85596 3.9 4.74159 3 5.84615 3H12.8118V5H5.84615ZM14.802 5V3H21.7677V10H19.7775V6.41L9.99569 16.24L8.59261 14.83L18.3744 5H14.802Z" fill="white"></path>
                                </mask>
                                <g mask="url(#mask0)">
                                    <rect x="0.870605" width="23.8823" height="24" fill="#FFFFFF"></rect>
                                </g>
                            </svg>
                            <span class="jp-carousel-download-text"></span>
                        </a>
                        <div class="jp-carousel-image-map" style="display: none;"></div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    </div>
    <style>.wp-container-61e15fb4d4ac3 > * {max-width: 664px;margin-left: auto !important;margin-right: auto !important;}.wp-container-61e15fb4d4ac3 > .alignwide { max-width: 1128px;}.wp-container-61e15fb4d4ac3 .alignfull { max-width: none; }.wp-container-61e15fb4d4ac3 .alignleft { float: left; margin-right: 2em; }.wp-container-61e15fb4d4ac3 .alignright { float: right; margin-left: 2em; }.wp-container-61e15fb4d4ac3 > * { margin-top: 0; margin-bottom: 0; }.wp-container-61e15fb4d4ac3 > * + * { margin-top: var( --wp--style--block-gap );  margin-bottom: 0; }</style><style>.wp-container-61e15fb4d519d .alignleft { float: left; margin-right: 2em; }.wp-container-61e15fb4d519d .alignright { float: right; margin-left: 2em; }.wp-container-61e15fb4d519d > * { margin-top: 0; margin-bottom: 0; }.wp-container-61e15fb4d519d > * + * { margin-top: var( --wp--style--block-gap );  margin-bottom: 0; }</style><style>.wp-container-61e15fb4d5e74 .alignleft { float: left; margin-right: 2em; }.wp-container-61e15fb4d5e74 .alignright { float: right; margin-left: 2em; }.wp-container-61e15fb4d5e74 > * { margin-top: 0; margin-bottom: 0; }.wp-container-61e15fb4d5e74 > * + * { margin-top: var( --wp--style--block-gap );  margin-bottom: 0; }</style><style>.wp-container-61e15fb4d6523 > * {max-width: 664px;margin-left: auto !important;margin-right: auto !important;}.wp-container-61e15fb4d6523 > .alignwide { max-width: 1128px;}.wp-container-61e15fb4d6523 .alignfull { max-width: none; }.wp-container-61e15fb4d6523 .alignleft { float: left; margin-right: 2em; }.wp-container-61e15fb4d6523 .alignright { float: right; margin-left: 2em; }.wp-container-61e15fb4d6523 > * { margin-top: 0; margin-bottom: 0; }.wp-container-61e15fb4d6523 > * + * { margin-top: var( --wp--style--block-gap );  margin-bottom: 0; }</style>	<div id="actionbar" class="actnbr-pub-quadrat actnbr-has-customize actnbr-has-edit">
    <ul>
                            <li class="actnbr-btn actnbr-customize">
                    <a href="https://michaelbonar0021.wordpress.com/wp-admin/customize.php?url=https%3A%2F%2Fmichaelbonar0021.wordpress.com%2F">
                        <svg class="gridicon gridicons-customize" height="20" width="20" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g><path d="M2 6c0-1.505.78-3.08 2-4 0 .845.69 2 2 2 1.657 0 3 1.343 3 3 0 .386-.08.752-.212 1.09.74.594 1.476 1.19 2.19 1.81L8.9 11.98c-.62-.716-1.214-1.454-1.807-2.192C6.753 9.92 6.387 10 6 10c-2.21 0-4-1.79-4-4zm12.152 6.848l1.34-1.34c.607.304 1.283.492 2.008.492 2.485 0 4.5-2.015 4.5-4.5 0-.725-.188-1.4-.493-2.007L18 9l-2-2 3.507-3.507C18.9 3.188 18.225 3 17.5 3 15.015 3 13 5.015 13 7.5c0 .725.188 1.4.493 2.007L3 20l2 2 6.848-6.848c1.885 1.928 3.874 3.753 5.977 5.45l1.425 1.148 1.5-1.5-1.15-1.425c-1.695-2.103-3.52-4.092-5.448-5.977z"></path></g></svg>							<span>Sesuaikan</span>
                    </a>
                </li>
                                <li class="actnbr-btn actnbr-edit">
                    <a href="https://wordpress.com/page/michaelbonar0021.wordpress.com/2">
                        <svg class="gridicon gridicons-pencil" height="20" width="20" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g><path d="M13 6l5 5-9.507 9.507c-.686-.686-.69-1.794-.012-2.485l-.002-.003c-.69.676-1.8.673-2.485-.013-.677-.677-.686-1.762-.036-2.455l-.008-.008c-.694.65-1.78.64-2.456-.036L13 6zm7.586-.414l-2.172-2.172c-.78-.78-2.047-.78-2.828 0L14 5l5 5 1.586-1.586c.78-.78.78-2.047 0-2.828zM3 18v3h3c0-1.657-1.343-3-3-3z"></path></g></svg>							<span>Edit</span>
                    </a>
                </li>
                <li class="actnbr-btn actnbr-stats">
                    <a href="https://wordpress.com/stats/post/2/michaelbonar0021.wordpress.com">
                        <svg class="gridicon gridicons-stats-alt" height="20" width="20" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g><path d="M21 21H3v-2h18v2zM8 10H4v7h4v-7zm6-7h-4v14h4V3zm6 3h-4v11h4V6z"></path></g></svg>							<span>Statistik</span>
                    </a>
                </li>
                        <li class="actnbr-ellipsis actnbr-hidden">
            <svg class="gridicon gridicons-ellipsis" height="24" width="24" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g><path d="M7 12c0 1.104-.896 2-2 2s-2-.896-2-2 .896-2 2-2 2 .896 2 2zm12-2c-1.104 0-2 .896-2 2s.896 2 2 2 2-.896 2-2-.896-2-2-2zm-7 0c-1.104 0-2 .896-2 2s.896 2 2 2 2-.896 2-2-.896-2-2-2z"></path></g></svg>				<div class="actnbr-popover tip tip-top-left actnbr-more">
                <div class="tip-arrow"></div>
                <div class="tip-inner">
                    <ul>
                                <li class="actnbr-sitename">
        <a href="https://michaelbonar0021.wordpress.com">
            <img alt="" src="https://s0.wp.com/i/logo/wpcom-gray-white.png" class="avatar avatar-50" height="50" width="50">				Self Biography			</a>
    </li>
                            <li class="actnbr-folded-customize">
                            <a href="https://michaelbonar0021.wordpress.com/wp-admin/customize.php?url=https%3A%2F%2Fmichaelbonar0021.wordpress.com%2F">
                                <svg class="gridicon gridicons-customize" height="20" width="20" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g><path d="M2 6c0-1.505.78-3.08 2-4 0 .845.69 2 2 2 1.657 0 3 1.343 3 3 0 .386-.08.752-.212 1.09.74.594 1.476 1.19 2.19 1.81L8.9 11.98c-.62-.716-1.214-1.454-1.807-2.192C6.753 9.92 6.387 10 6 10c-2.21 0-4-1.79-4-4zm12.152 6.848l1.34-1.34c.607.304 1.283.492 2.008.492 2.485 0 4.5-2.015 4.5-4.5 0-.725-.188-1.4-.493-2.007L18 9l-2-2 3.507-3.507C18.9 3.188 18.225 3 17.5 3 15.015 3 13 5.015 13 7.5c0 .725.188 1.4.493 2.007L3 20l2 2 6.848-6.848c1.885 1.928 3.874 3.753 5.977 5.45l1.425 1.148 1.5-1.5-1.15-1.425c-1.695-2.103-3.52-4.092-5.448-5.977z"></path></g></svg>									<span>Sesuaikan</span>
                            </a>
                        </li>
                                                            <li class="actnbr-folded-follow">
                                            <a class="actnbr-action actnbr-actn-follow  no-display" href="">
        <svg class="gridicon gridicons-reader-follow" height="24" width="24" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g><path d="M23 16v2h-3v3h-2v-3h-3v-2h3v-3h2v3h3zM20 2v9h-4v3h-3v4H4c-1.1 0-2-.9-2-2V2h18zM8 13v-1H4v1h4zm3-3H4v1h7v-1zm0-2H4v1h7V8zm7-4H4v2h14V4z"></path></g></svg><span>Ikuti</span>
    </a>
    <a class="actnbr-action actnbr-actn-following " href="">
        <svg class="gridicon gridicons-reader-following" height="24" width="24" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g><path d="M23 13.482L15.508 21 12 17.4l1.412-1.388 2.106 2.188 6.094-6.094L23 13.482zm-7.455 1.862L20 10.89V2H2v14c0 1.1.9 2 2 2h4.538l4.913-4.832 2.095 2.176zM8 13H4v-1h4v1zm3-2H4v-1h7v1zm0-2H4V8h7v1zm7-3H4V4h14v2z"></path></g></svg><span>Mengikuti</span>
    </a>
                                    </li>
                                                                <li class="actnbr-theme">
                                    <a href="https://wordpress.com/theme/quadrat/">Dapatkan tema: Quadrat</a>
                                </li>
                                                                <li class="actnbr-shortlink"><a href="https://wp.me/PdElcz-2">Salin shortlink</a></li>
                                                                <li class="actnbr-reader">
                                    <a href="https://wordpress.com/read/blogs/201706991/posts/2">
                                        View post in Reader										</a>
                                </li>
                                                                <li class="actnbr-follows">
                                    <a href="https://wordpress.com/following/manage?s=michaelbonar0021.wordpress.com">
                                        Kelola langganan										</a>
                                </li>
                                                                    <li class="actnbr-fold"><a href="">Ciutkan bilah ini</a></li>
                                                        </ul>
                </div>
            </div>
        </li>
    </ul>
</div>

<script>
window.addEventListener( "load", function( event ) {
var link = document.createElement( "link" );
link.href = "https://s0.wp.com/wp-content/mu-plugins/actionbar/actionbar.css?v=20210915";
link.type = "text/css";
link.rel = "stylesheet";
document.head.appendChild( link );

var script = document.createElement( "script" );
script.src = "https://s0.wp.com/wp-content/mu-plugins/actionbar/actionbar.js?v=20211028";
script.defer = true;
document.body.appendChild( script );
} );
</script>

<link rel="stylesheet" id="screen-css-0-2" href="https://s0.wp.com/wp-content/blog-plugins/launch-banner/style.css?m=1637168422h&amp;cssminify=yes" type="text/css" media="screen">
<script id="thickbox-js-extra">
var thickboxL10n = {"next":"Berikutnya >","prev":"< Sebelumnya","image":"Gambar","of":"dari","close":"Tutup","noiframes":"Fitur ini memerlukan bingkai langsung di tempat. Anda memiliki iframe dinonaktifkan atau browser Anda tidak mendukung mereka.","loadingAnimation":"https:\/\/s0.wp.com\/wp-includes\/js\/thickbox\/loadingAnimation.gif"};
</script>
<script id="jetpack-carousel-js-extra">
var jetpackSwiperLibraryPath = {"url":"\/wp-content\/mu-plugins\/carousel\/swiper-bundle.js"};
var jetpackCarouselStrings = {"widths":[370,700,1000,1200,1400,2000],"is_logged_in":"1","lang":"id","ajaxurl":"https:\/\/michaelbonar0021.wordpress.com\/wp-admin\/admin-ajax.php","nonce":"a93b446079","display_exif":"1","display_comments":"1","display_geo":"1","single_image_gallery":"1","single_image_gallery_media_file":"","background_color":"black","comment":"Komentar","post_comment":"Kirim Komentar","write_comment":"Tulis Komentar...","loading_comments":"Memuat Komentar...","download_original":"Tampilkan ukuran penuh <span class=\"photo-size\">{0}<span class=\"photo-size-times\">\u00d7<\/span>{1}<\/span>","no_comment_text":"Pastikan memasukkan teks sebelum mengirimkan komentar Anda.","no_comment_email":"Silakan masukkan alamat email ke form komentar.","no_comment_author":"Silakan masukkan nama ke form komentar.","comment_post_error":"Maaf, terjadi galat saat menerbitkan komentar Anda. Silakan coba lagi.","comment_approved":"Komentar Anda telah disetujui.","comment_unapproved":"Komentar Anda sedang dimoderasi.","camera":"Kamera","aperture":"Aperture","shutter_speed":"Shutter Speed","focal_length":"Focal Length","copyright":"Hak cipta","comment_registration":"0","require_name_email":"1","login_url":"https:\/\/michaelbonar0021.wordpress.com\/wp-login.php?redirect_to=https%3A%2F%2Fmichaelbonar0021.wordpress.com%2F","blog_id":"201706991","meta_data":["camera","aperture","shutter_speed","focal_length","copyright"],"stats_query_args":"blog=201706991&v=wpcom&tz=7&user=1&user_id=215980900&subd=michaelbonar0021","is_public":"0"};
</script>
<script id="comment-like-js-extra">
var comment_like_text = {"loading":"Memuat...","swipeUrl":"https:\/\/s0.wp.com\/wp-content\/mu-plugins\/comment-likes\/js\/lib\/swipe.js?ver=20131008"};
</script>
<script id="notes-rest-common-js-extra">
var wpNotesArgs = {"cacheBuster":"calypso-4917-3286-g69c83d04d2v2","iframeUrl":"https:\/\/widgets.wp.com\/notifications\/","iframeAppend":"2","iframeScroll":"no","wide":"1"};
</script>
<script id="tos-report-form-js-extra">
var wpcom_tos_report_form = {"ajaxurl":"\/wp-admin\/admin-ajax.php","isLoggedoutUser":"","post_ID":"2","current_url":"https:\/\/michaelbonar0021.wordpress.com","report_this_content":"Laporkan isi ini"};
</script>
<script type="text/javascript">
const launchBarUserData = {"blogId":201706991}
</script>
<script crossorigin="anonymous" type="text/javascript" src="https://s0.wp.com/_static/??-eJyNUtFSwyAQ/CEJJq2OL47fAuRMLoEjc0Ba/17SmqgdjH3JZNlluV2Qp0kYTxEoyiHIFmY0MJ2rITzITCEZm1oICxd7NKP25+2nJOr9DIwXPzGEyiGVVKrNhNCKfwrWMSabOqQgu5ShBu4ywyDnuqkOVSN1QttKbb0ZhUXNij+uKEhSM3Yqoic5I5xK5i6J1d8o9imAlQPESWW3dWFnzzZ45o134jvIzjneuaUOi+M1/a+FUj2JWuCwpP6rQK2WGyAoRcy0SyEq08POVOQjfH3FMpAnMTf/6re8++Log2CYPEfx7tnd4rsKdipE4OWoyDltsagMwWloSzXkN9FttlYlMn32JQKWwTBO8Y6nIS63fAPzvjf3Wj8f6+Nj/fRyGD4Ba+A2sQ=="></script>
<script type="text/javascript">
// <![CDATA[
(function() {
try{
if ( window.external &&'msIsSiteMode' in window.external) {
if (window.external.msIsSiteMode()) {
  var jl = document.createElement('script');
  jl.type='text/javascript';
  jl.async=true;
  jl.src='/wp-content/plugins/ie-sitemode/custom-jumplist.php';
  var s = document.getElementsByTagName('script')[0];
  s.parentNode.insertBefore(jl, s);
}
}
}catch(e){}
})();
// ]]>
</script><script src="//stats.wp.com/w.js?63" defer=""></script> <script type="text/javascript">
_tkq = window._tkq || [];
_stq = window._stq || [];
_tkq.push(['identifyUser', 215980900, 'michaelmanullang29']);
_tkq.push(['storeContext', {'blog_id':'201706991','blog_tz':'7','user_lang':'id','blog_lang':'id'}]);
_stq.push(['view', {'blog':'201706991','v':'wpcom','tz':'7','user':'1','user_id':'215980900','post':'2','subd':'michaelbonar0021'}]);
_stq.push(['extra', {'crypt':'UE40eW5QN0p8M2Y/RE1mN3FZZmo1ciV5XXJsZ24wUjJacUxGNiVZTFVrRGNHdkxHbS8sQzF1dHQ9MGZsMmlHcy9iRTBzK0o1TnVxfD91Nkk3YWVtbmcuVTdbSHd5eEVzfFVyTGhNOWtGdyZKXXxBSXgyLlFxajhkbllraUE5UCwxfEE9OGktUjZDTy5YMTJxR1slSTcwY2hJc0l5WUQ4NFBIfHAlJWF3dEpuYTlKcCUwK2lQTFVvbG9kSlRCOHZ8T29fa3kzX01LX0huVFRZZ0w9MVFHeVVZamVbeXlXfnxjWGNSTS1UY2c0NGI4ZXdPczNnRjAv'}]);
</script>
<noscript><img src="https://pixel.wp.com/b.gif?v=noscript" style="height:1px;width:1px;overflow:hidden;position:absolute;bottom:1px;" alt="" /></noscript>
<script>
if ( 'object' === typeof wpcom_mobile_user_agent_info ) {

wpcom_mobile_user_agent_info.init();
var mobileStatsQueryString = "";

if( false !== wpcom_mobile_user_agent_info.matchedPlatformName )
    mobileStatsQueryString += "&x_" + 'mobile_platforms' + '=' + wpcom_mobile_user_agent_info.matchedPlatformName;

if( false !== wpcom_mobile_user_agent_info.matchedUserAgentName )
    mobileStatsQueryString += "&x_" + 'mobile_devices' + '=' + wpcom_mobile_user_agent_info.matchedUserAgentName;

if( wpcom_mobile_user_agent_info.isIPad() )
    mobileStatsQueryString += "&x_" + 'ipad_views' + '=' + 'views';

if( "" != mobileStatsQueryString ) {
    new Image().src = document.location.protocol + '//pixel.wp.com/g.gif?v=wpcom-no-pv' + mobileStatsQueryString + '&baba=' + Math.random();
}

}
</script>

<style>img#wpstats {
        position: absolute !important;
        clip: rect(0, 0, 0, 0);
        padding: 0 !important;
        border: 0 !important;
        height: 0 !important;
        width: 0 !important;
        overflow: hidden;
    }</style><img src="https://pixel.wp.com/g.gif?blog=201706991&amp;v=wpcom&amp;tz=7&amp;user=1&amp;user_id=215980900&amp;post=2&amp;subd=michaelbonar0021&amp;host=michaelbonar0021.wordpress.com&amp;ref=&amp;rand=0.14791226251242828" alt=":)" id="wpstats"><div class="comment-likes-overlay" style="display: none;"></div><script src="https://s0.wp.com/wp-content/mu-plugins/actionbar/actionbar.js?v=20211028" defer=""></script><a class="ab-item grav-tilt-parent" href="https://wordpress.com/me/" style="top: 5.25px; left: 1270px;"></a>
    </body>
