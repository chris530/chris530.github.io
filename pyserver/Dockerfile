FROM python
COPY app.py /opt
COPY requirements.txt .
RUN pip install -r requirements.txt
RUN chmod a+x /opt/app.py
EXPOSE 5000
ENTRYPOINT ["/opt/app.py"]
