# harmony_reader
![Harmony](https://github.com/yukyu30/harmony_reader/assets/61819079/7e02eda6-342a-4366-9705-b163988353e4)

## development
2023年1月7日現在、ruby3.3.0のイメージを使うとアプリケーションが立ち上がらないのでローカルで動かす
ref: [Ruby 3.3.0: aarch64-linux環境でFiber.new{ }.resumeを呼ぶと落ちる問題](https://techracho.bpsinc.jp/hachi8833/2023_12_28/138310)

```
docker-compose up -d
bundle exec rails s
```
