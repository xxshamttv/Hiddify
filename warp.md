//profile-title: base64:8J+UpSBXQVJQIPCflKU=
//profile-update-interval: 24
//subscription-userinfo: upload=0; download=0; total=10737418240000000; expire=2546249531

{
  "outbounds": 
  [
    {
      "type": "wireguard",
      "tag": "Warp-IR",
      "server": "162.159.195.107",
      "server_port": 854,

      "local_address": [
        "172.16.0.2/32",
        "2606:4700:110:8a17:9b3:a57e:421d:ea9e/128"
      ],
      "private_key": "cABcbzQ3xF4ZL/mbksRY3o2dXBVhbB9LgH/5bUGX0XE=",
      "peer_public_key": "bmXOC+F1FxEMF9dyiK2H5/1SUtzH0JuVo51h2wPfgyo=",
      "reserved": [ 0, 223, 62 ],

      "mtu": 1280,
      "fake_packets": "5-10"
    },
    {
      "type": "wireguard",
      "tag": "Warp-Main",
      "detour": "Warp-IR",
      "server": "162.159.195.107",
      "server_port": 854,
      
      "local_address": [
          "172.16.0.2/32",
          "2606:4700:110:8cc1:1ea5:58cf:1755:4ff8/128"
      ],
      "private_key": "MDpZxunwMICC3OUjp4hdXmaNd60mXhVyGUlML0i8Z28=",
      "peer_public_key": "bmXOC+F1FxEMF9dyiK2H5/1SUtzH0JuVo51h2wPfgyo=",
      "reserved": [ 126, 70, 45 ],  

      "mtu": 1120,
      "fake_packets": "5-10"
    }
  ]
}
