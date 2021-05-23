FROM python
MAINTAINER 'deepanshu'
RUN apt install python -y
RUN mkdir /dockertest
COPY dataframe_rows_filter.py /dockertest/dataframe_rows_filter.py
WORKDIR /dockerTest
CMD python /dockertest/dataframe_rows_filter.py
