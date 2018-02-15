Allow cookies to be set from iframes in Internet Explorer.
----------------------------------------------------------------------------------------------------

	<IfModule mod_headers.c>
		Header set P3P "policyref=\"/w3c/p3p.xml\", CP=\"IDC DSP COR ADM DEVi TAIi PSA PSD IVAi IVDi CONi HIS OUR IND CNT\""
	</IfModule>

See also:

- https://msdn.microsoft.com/en-us/library/ms537343.aspx
- http://www.w3.org/TR/2000/CR-P3P-20001215/