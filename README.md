clash

1. tải định dạng clash
https://convert.v2ray-subscribe.workers.dev/?url=https://raw.githubusercontent.com/sattheptonghop/sattheptonghop.github.io/main/v2ray&sni=dl.kgvn.garenanow.com&flag=clash

2. tìm dòng proxy-groups
  - copy code "- { name: ...}" 2 dòng nữa
  - dòng 1 sửa "name.." => "name: "Auto 24h"" ; "type: select" => "type = url-test" thêm đuôi ", url: "http://www.gstatic.com/generate_204", interval: 86400}"
  - dòng 2 sửa "name.." => "name: "Auto 2h"" ; "type: select" => "type = fallback" thêm đuôi ", url: "http://www.gstatic.com/generate_204", interval: 7200}"
  
  url-test
  fallback
  "Auto 2h","Auto 22h"
  , url: "http://www.gstatic.com/generate_204", interval: 86400
  , url: "http://www.gstatic.com/generate_204", interval: 7200
