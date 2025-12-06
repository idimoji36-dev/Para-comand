python3 para-m-scope.py ... --concurrency 6






python3 para-m-scope.py https://target.example --output /path/to/results.json







pkg install libxml2 libxslt -y
pip3 install lxmlpython3 para-m-scope.py https://target.example --depth 3 --domain-only --max-pages 100python3 para-m-scope.py https://target.example --depth 2 --concurrency 8{
  "generated_at": "2025-01-01T19:25:32",
  "count": 1,
  "results": [
    {
      "url": "https://example.com/?id=10",
      "params": {"id": ["10"]},
      "analysis": {
        "reflections": {"id": true},
        "fuzz": {
          "id": [
            {"payload": "'", "final_url": "https://...", "errors": ["mysql"], "len_change_pct": 4.5},
            {"payload": "\"", "final_url": "https://...", "errors": [], "len_change_pct": 0.0}
          ]
        },
        "error_keywords_in_base": []
      }
    }
  ]
}[2025-01-01]-[19:22:10] [INFO]  | [SCOPING] depth=1 -> https://example.com
[2025-01-01]-[19:22:11] [INFO]  | [PARA-MS] https://example.com/?id=10 -> ['id']
[2025-01-01]-[19:22:12] [INFO]  | [PARA-REFLECT] ➤ [params] https://example.com/?id=10 :: param 'id' appears reflected in response
[2025-01-01]-[19:22:14] [INFO]  | [FUZZ-ERR] ➤ [fetch] https://example.com/?id=10' -> keywords ['mysql']python3 para-m-scope.py https://example.com --depth 2 --domain-only --concurrency 10 --timeout 20 --max-pages 100 --output results.jsonpython3 para-m-scope.py --helppkg update -y
pkg install libxml2 -y
pkg install libxslt -y
pkg install python -y
pkg install python3 -y
pkg install git -y
git clone https://github.com/TEAMBCS/Para-M-Scope.git
cd Para-M-Scope
chmod +x *
chmod +w .
chmod 777 *
pip3 install -r para-m-scope.txt
python3 para-m-scope.py --helppip install para-m-scope==1.2.1
para-m-scope -hpkg update -y
pkg install libxml2 -y
pkg install libxslt -y
pkg install python -y
pkg install python3 -y
pkg install git -y
git clone https://github.com/TEAMBCS/Para-M-Scope.git
cd Para-M-Scope
chmod +x *
chmod +w .
chmod 777 *
pip3 install -r para-m-scope.txt
python3 para-m-scope.py --helppython3 para-m-scope.py https://example.com --depth 2 --domain-only --concurrency 10 --timeout 20 --max-pages 100 --output results.jsonpython3 para-m-scope.py --helppython3 para-m-scope.py https://target.example --depth 2 --concurrency 8python3 para-m-scope.py https://target.example --depth 3 --domain-only --max-pages 100
