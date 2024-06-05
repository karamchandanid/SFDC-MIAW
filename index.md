<html lang="en">
<head>
	<title>MIAW</title>
	<script type='text/javascript'>
		function initEmbeddedMessaging() {
			console.log('initEmbeddedMessaging');
			try {
				console.log('initEmbeddedMessaging', 'embeddedservice_bootstrap');
				embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'
				
				console.log('initEmbeddedMessaging','embeddedservice_bootstrap','init');
				embeddedservice_bootstrap.init(
					'00Ddx0000001gtF',
					'Github',
					'https://legrandav--echochat.sandbox.my.site.com/ESWGithub1717396104980',
					{
						scrt2URL: 'https://legrandav--echochat.sandbox.my.salesforce-scrt.com'
					}
				);
				console.log('initEmbeddedMessaging','embeddedservice_bootstrap','done');
			} catch (err) {
				console.error('Error loading Embedded Messaging: ', err);
			}
		};
	</script>
	<script type='text/javascript' src='https://legrandav--echochat.sandbox.my.site.com/ESWGithub1717396104980/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
</head>
<body >
	Hello
	
</body>
