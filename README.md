cmd

  git add . && git commit -m "ci"
  
  TAG=v1.0.2
  git tag -a $TAG -m "Release version ${TAG}" && git push origin $TAG
