# yocto-docker
Repository to store a customized docker container file to aid people use yocto on distros not tested.

## Warning
Remember to change the user `earl` to your username, using the following command:

```
sed -i "s/earl/$USER/" dockerfile_focal
```

Remember to change the `uid` and `gid` fields with your values (use the command `id` in terminal to see)

## Credits
The `dockerfile_local` was based on: https://boundarydevices.com/using-docker-containers-for-reproducible-yocto-builds/
