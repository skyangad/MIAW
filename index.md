<html>
  <body>
    <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DO9000002CX8j',
				'MessagingWebDeployment',
				'https://verifiedfirst--staging.sandbox.my.site.com/ESWMessagingWebDeployment1722515198655',
				{
					scrt2URL: 'https://verifiedfirst--staging.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://verifiedfirst--staging.sandbox.my.site.com/ESWMessagingWebDeployment1722515198655/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

  </body>
</html>