FROM python
MAINTAINER 'deepanshu'
RUN apt install python3 -y
RUN mkdir /dockertest
COPY dataframe_filter_row.py /dockertest/dataframe_filter_row.py
WORKDIR /dockerTest
CMD python3 /dockertest/dataframe_filter_row.py
