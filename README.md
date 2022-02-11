# test
Test

mvn package

print current version
mvn help:evaluate -Dexpression=project.version -q -DforceStdout


## signing commits and tags with gpg key
sign every commit with commit 
git config --global commit.gpgsign true

git config --global user.signingKey <gpgkeyid>
