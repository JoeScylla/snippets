Allow Cross-Origin Requests for Web-Fonts.
----------------------------------------------------------------------------------------------------
	
	<IfModule mod_headers.c>
		<FilesMatch "\.(eot|otf|tt[cf]|woff2?)$">
			Header set Access-Control-Allow-Origin "*"
		</FilesMatch>
	</IfModule>
