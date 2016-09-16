FROM openblockchaininfo/docker-spark
MAINTAINER Dan Hassan <daniel.san@dyne.org>

ADD spark-master-entrypoint.sh /spark-master-entrypoint.sh
RUN chmod a+x /spark-master-entrypoint.sh

ENTRYPOINT ["/spark-master-entrypoint.sh"]
