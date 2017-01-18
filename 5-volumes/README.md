docker run -it -v $PWD:/some/dir busybox sh
cd /some/dir
ls
echo "some stuff" > container-made-me
ls -la
exit
ls -la
rm container-made-me
sudo rm container-made-me