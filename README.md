# telephone-sy

سوق عربي لبيع وشراء الهواتف، بواجهة RTL عربية وخادم FastAPI وقاعدة بيانات SQLAlchemy. راجع [دليل النشر العربي](DEPLOY-AR.md) قبل النشر. لا يعمل التطبيق كخادم خلفي على GitHub Pages؛ استخدم استضافة تدعم Python/Docker وقاعدة بيانات وRedis.

Local development: install `requirements.txt`, copy `.env.example` to `.env`, then run `uvicorn main:app --reload`.
