# 1. Update version in manifest.json to 1.0.1
# 2. Repack extension with your .pem file
# 3. Update updates.xml version to 1.0.1
# 4. Replace extension.crx in repo
git add extension.crx updates.xml
git commit -m "Release v1.0.1"
git push