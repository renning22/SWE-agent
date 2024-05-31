SWE-agent but using prebuilt SWE-bench env dockers.


Benchmark SWE-bench-lite (300 test instances).

```
python run.py --image_name=sweagent/swe-agent:latest --model_name gpt-4-0215-preview --split=test --skip_existing=True
```