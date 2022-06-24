<link href="style.css" rel="stylesheet">
<div id="c">Chargement... <noscript>Activez Javascript pour accéder aux applications</noscript></div>
<script src="https://code.jquery.com/jquery-3.6.0.min.js" integrity="sha256-/xUj+3OJU5yExlq6GSYGSHk7tPXikynS7ogEvDej/m4=" crossorigin="anonymous"></script>
<script type="text/javascript">
    $(document).ready(function() {
        const str = window.location.href;

        const words = str.split('#');
        $("#c").load("App/"+words[1]+".app");
    });
</script>