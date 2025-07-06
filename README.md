# something
hello the world
git add .
git commit -m " làm quen với githup"
git push origin main
git add .
git commit -m "test lần 2"
git push origin main
git add .
git commit -m "test lần 3"
git push origin main
123
456
789
1
2
#!/bin/bash

# Thời gian chờ giữa mỗi lần commit (tính bằng giây)
INTERVAL=300  # 300 giây = 5 phút

while true; do
  git add .
  git commit -m "Auto-commit on $(date '+%Y-%m-%d %H:%M:%S')"
  git push origin main
  echo "Đã push lên GitHub lúc $(date)"
  sleep $INTERVAL
done
4#!/bin/bash

# Thời gian chờ giữa mỗi lần commit (tính bằng giây)
INTERVAL=300  # 300 giây = 5 phút

while true; do
  git add .
  git commit -m "Auto-commit on $(date '+%Y-%m-%d %H:%M:%S')"
  git push origin main
  echo "Đã push lên GitHub lúc $(date)"
  sleep $INTERVAL
done
