FROM python3
MAINTAINER 'deepanshu'
RUN apt install python3 -y
RUN mkdir /dockertest
COPY dataframe_rows_filter.py /dockertest/dataframe_rows_filter.py
WORKDIR /dockerTest
CMD python3 /dockertest/dataframe_rows_filter.py
