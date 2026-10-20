docker build -t greeter:v1 app/stats
docker run -d -p 9000 --name greeter nginx:1.30-alpine
משנים ב-GREETING שיהיה כתוב את המילה shalom במקום hello
shalom
מה שכבר נבנה=cached השורה ששיננו תרוץ מחדש ולמה כי מה שכבר קיים חבל שירוץ שוב ולכן מריץ רק את השינויים.
