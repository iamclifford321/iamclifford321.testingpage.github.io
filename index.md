
<html>
<body>
test
</body>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00D26000000HxWc',
				'Creditfix_Live_Chat',
				'https://ukdebtexpert--orcadev.sandbox.my.site.com/ESWCreditfixLiveChat1713535073503',
				{
					scrt2URL: 'https://ukdebtexpert--orcadev.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://ukdebtexpert--orcadev.sandbox.my.site.com/ESWCreditfixLiveChat1713535073503/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

</html>
