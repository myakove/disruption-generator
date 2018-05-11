FROM python

RUN git clone https://github.com/grafuls/disruption-generator.git
WORKDIR /disruption-generator/listener
RUN pip install -r requirements.txt
ENTRYPOINT python log_listener.py

