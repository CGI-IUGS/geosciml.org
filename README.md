# geosciml.org
Files for the www.geosciml.org and schemas.geosciml.org websites


## This repository is a frozen archive

The GeoSciML web pages are now at <https://cgi-iugs.org/geosciml/> and are edited in the [cgi-iugs.github.io](https://github.com/CGI-IUGS/cgi-iugs.github.io) repository. This site's home page just points there.

Everything else here is kept so that existing URLs keep working. The documentation, XSD schemas, example XML and vocabulary files are cited by URL in `schemaLocation` attributes, papers and INSPIRE data.

* Don't move, rename or delete files.
* Keep "Enforce HTTPS" turned off in *Settings → Pages*. Many XML validators use Java's `URLConnection`, which does not follow a redirect from `http://` to `https://`.
* `schemas.geosciml.org` and `resource.geosciml.org` are redirected (DNS held by Geoscience Australia) to `/schemas/` and `/resource/` on this site.
