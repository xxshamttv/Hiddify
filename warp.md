//profile-title: base64:8J+UpSBXQVJQIPCflKU=
//profile-update-interval: 24
//subscription-userinfo: upload=0; download=0; total=10737418240000000; expire=2546249531

{
  "outbounds": [
    {
      "type": "wireguard",
      "tag": "Warp-IR",
      "local_address": [
        "172.16.0.2/24",
        "2606:4700:110:86f3:84e5:51ae:c527:e09b/128"
      ],
      "private_key": "gCphplbEOL5yUjAQr5M7sWkpdI+M/5zna0cFy/tYeEQ=",
      "server": "162.159.192.147",
      "server_port": 4233,
      "peer_public_key": "bmXOC+F1FxEMF9dyiK2H5/1SUtzH0JuVo51h2wPfgyo=",
      "reserved": "BMUr",
      "mtu": 1280,
      "fake_packets": "5-10"
    },
    {
      "type": "wireguard",
      "tag": "Warp-Main",
      "detour": "Warp-IR",
      "local_address": [
        "172.16.0.2/24",
        "2606:4700:110:8120:5b1e:ec89:fa8a:21ce/128"
      ],
      "private_key": "YJEMe8x3qsFFA4iZ0/diHOat7pG5zsRSfOh+QNFndWM=",
      "server": "162.159.192.147",
      "server_port": 4233,
      "peer_public_key": "bmXOC+F1FxEMF9dyiK2H5/1SUtzH0JuVo51h2wPfgyo=",
      "reserved": "iAvy",
      "mtu": 1280,
      "fake_packets": "5-10"
    }
  ]
}
