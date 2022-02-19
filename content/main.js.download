$(document).ready(function () {
    $('.nav-item').click(function () {
        var _this = $(this).attr('data-target');
        $('.section').each(function () {
            if ($(this).attr('data-href') === _this) {
                $('html,body').animate({ scrollTop: $(this).offset().top }, 750);
            }
        })
    });
	
	$("#jsLogo").click(function() {
		var self = this;
		$(self).addClass('animated flip');
		setTimeout(function()  {  $(self).attr("class","") },1000)
	})

   setTimeout(function () {
        $("#cookieConsent").fadeIn(200);
     }, 1000);
    $("#closeCookieConsent, .cookieConsentOK").click(function() {
        $("#cookieConsent").fadeOut(200);
    }); 
})

