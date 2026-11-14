# Free My TV — Telugu / India
Personal builds of https://github.com/simbasjungles/free-my-tv.
TMDB region IN, original language te, title text te-IN when available.
Updates in the app come from this repository and must match the original custom signing certificate.
The workflow checks daily at 03:17 UTC and builds new stable upstream releases. A patch/build failure stops publication. GitHub may disable scheduled workflows after 60 days without repository activity; enable them again in Actions if that happens.
The signing key is stored only as an encrypted GitHub Actions secret. No TMDB key is included.
Install the first update-feed APK over the earlier custom Telugu APK using adb install -r. Subsequent updates use Home Settings → Updates.
Release source consists of upstream-source.tar.gz plus source-changes.patch. MIT license inherited from upstream.
