<script>
    // CSS
    import normalize from './css/normalize.css';
    import postmedia from './css/postmedia.css';
    import colours from './css/colors.css';
    import fonts from './css/fonts.css';
    import css from './css/main.css';

    // IMAGES
    import gfx from '/images/map.jpg';

    // SET CHART HEIGH & URL HERE...
    const chartId01 = '27235207';
    const chartId02 = '27235238';
    const chartHeight = '375px';
</script>

<!-- MARKUP -->
<header>
    <h1>Crimes going unreported</h1>
    <p class="subhead">Many B.C. businesses are not reporting property and other non-violent crimes, according to a recent survey conducted by the Business Improvement Association of B.C.</p>
</header>

<!-- SIDE-BY-SIDE -->
<div class="graphic-container">
    <iframe src='https://flo.uri.sh/visualisation/{chartId01}/embed' title='Interactive or visual content' frameborder='0' scrolling='no' style='width:100%;height:{chartHeight};' sandbox='allow-same-origin allow-forms allow-scripts allow-downloads allow-popups allow-popups-to-escape-sandbox allow-top-navigation-by-user-activation'></iframe>
    <iframe src='https://flo.uri.sh/visualisation/{chartId02}/embed' title='Interactive or visual content' frameborder='0' scrolling='no' style='width:100%;height:{chartHeight};' sandbox='allow-same-origin allow-forms allow-scripts allow-downloads allow-popups allow-popups-to-escape-sandbox allow-top-navigation-by-user-activation'></iframe>
</div>

 <p class="note">NOTE: The survey of 260 businesses was conducted in November 2025. The results are non-representative. No margin of error can be calculated.</p>


<footer>
    <p class="source">Source: Business Improvement Association of B.C.</p>
    <!-- flourish logo -->
    <div style='width:100%!;margin-top:4px!important;text-align:right!important;'><a class='flourish-credit' href='https://public.flourish.studio/visualisation/3706064/?utm_source=embed&utm_campaign=visualisation/3706064' target='_top' style='text-decoration:none!important'><img alt='Made with Flourish' src='https://public.flourish.studio/resources/made_with_flourish.svg' style='width:105px!important;height:16px!important;border:none!important;margin:0!important;'> </a></div>
</footer>
