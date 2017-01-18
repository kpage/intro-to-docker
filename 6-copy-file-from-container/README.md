UUID=$(cat /proc/sys/kernel/random/uuid)
docker run --name $UUID busybox sh -c 'echo "lalalola" > test.txt'
docker cp $UUID:test.txt .
docker rm $UUID > /dev/null
ls -la test.txt
cat test.txt