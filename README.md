# DeepESMCfg
Stores the DeepESM config files for easy downloads

## Adding a new release

- Commit the version of the config file that you wish to make into a release.
- Now select the "releases" option.
- Now select "Draft a new release".
- Add a good "Tag version" and "Release title" name. For example I would make them both: "Keras_Tensorflow_vX.Y.Z"
- Add a good comment.
- Now attach a tar file that has the "keras_frozen.pb" with the name "MVAFILES.tar.gz" using the "Attach binaries by dropping them here...."
```
tar czf MVAFILES.tar.gz keras_frozen.pb
```

- Now hit the "Publish release" button and it should be done. 
