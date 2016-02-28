FROM elasticsearch:1.7

RUN set -x \
	&& /usr/share/elasticsearch/bin/plugin -install lmenezes/elasticsearch-kopf/1.0 \
	&& /usr/share/elasticsearch/bin/plugin -install mobz/elasticsearch-head/1.x \
	&& /usr/share/elasticsearch/bin/plugin -install polyfractal/elasticsearch-segmentspy \
	&& /usr/share/elasticsearch/bin/plugin -install lukas-vlcek/bigdesk/2.5.0 \
	&& /usr/share/elasticsearch/bin/plugin -install elasticsearch/elasticsearch-analysis-icu/2.7.0
