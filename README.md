# Creative CDN

Staging area for ad creatives so Meta can fetch them by URL.
Managed by the /ads-uploader skill. `.nojekyll` keeps Pages serving raw files
instead of running Jekyll over them.

Nothing here is permanent: Meta caches the bytes at upload time, so batches can
be pruned once their ads exist. Never stage anything containing customer data.
