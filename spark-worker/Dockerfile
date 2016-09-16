FROM openblockchaininfo/docker-spark
MAINTAINER Dan Hassan <daniel.san@dyne.org>

ADD spark-worker-entrypoint.sh /spark-worker-entrypoint.sh
RUN chmod a+x /spark-worker-entrypoint.sh

ENTRYPOINT ["/spark-worker-entrypoint.sh"]
