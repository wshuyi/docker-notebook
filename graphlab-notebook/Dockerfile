FROM ipython/ipython

MAINTAINER IPython Project <ipython-dev@scipy.org>

VOLUME /notebooks
WORKDIR /notebooks

EXPOSE 8888

RUN pip2 install --upgrade --no-cache-dir https://get.dato.com/GraphLab-Create/1.7.1/s.wang@moreheadstate.edu/7B90-A79D-625B-5222-A2FD-ECE3-2C12-1DDD/GraphLab-Create-License.tar.gz

ADD notebook.sh /

CMD ["/notebook.sh"]
