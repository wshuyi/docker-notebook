FROM ipython/ipython:3.x

MAINTAINER IPython Project <ipython-dev@scipy.org>

VOLUME /notebooks
WORKDIR /notebooks

EXPOSE 8888

ADD add_sql.sh /

CMD ["/add_sql.sh"]

ADD notebook.sh /

CMD ["/notebook.sh"]
