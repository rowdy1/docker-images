FROM selenium/hub:3.4.0-einsteinium
LABEL org.freenas.interactive="true"                        \
      org.freenas.command="/opt/bin/entry_point.sh"         \
      org.freenas.version="3.4.0-einsteinium"               \
      org.freenas.upgradeable="false"                       \
      org.freenas.expose-ports-at-host="true"		        \
      org.freenas.autostart="true"				            \
	  org.freenas.port-mappings="4444:4444/tcp"             \
	  org.freenas.privileged="true"                         \
      org.freenas.settings="[                               \
          {                                                 \
              \"env\": \"GRID_MAX_SESSION\",                \
              \"descr\": \"As integer, maps to 'maxSession' DEF=5\", \
              \"optional\": true                            \
          },                                                \
		  {                                                 \
              \"env\": \"GRID_NEW_SESSION_WAIT_TIMEOUT\",   \
              \"descr\": \"In milliseconds, maps to 'newSessionWaitTimeout'\",	\
              \"optional\": true                            \
          },                                                \
		  {                                                 \
              \"env\": \"GRID_THROW_ON_CAPABILITY_NOT_PRESENT\",   \
              \"descr\": \"As a boolean, maps to 'throwOnCapabilityNotPresent'\",	\
              \"optional\": true                            \
          },                                                \
		  {                                                 \
              \"env\": \"GRID_JETTY_MAX_THREADS\",          \
              \"descr\": \"As an integer\",                 \
              \"optional\": true                            \
          },                                                \
		  {                                                 \
              \"env\": \"GRID_CLEAN_UP_CYCLE\",             \
              \"descr\": \"In milliseconds, maps to 'cleanUpCycle'\",	\
              \"optional\": true                            \
          },                                                \
		  {                                                 \
              \"env\": \"GRID_BROWSER_TIMEOUT\",            \
              \"descr\": \"In seconds, maps to 'browserTimeout'\",	\
              \"optional\": true                            \
          },                                                \
		  {                                                 \
              \"env\": \"GRID_TIMEOUT\",                    \
              \"descr\": \"In seconds, maps to 'timeout'\",	\
              \"optional\": true				            \
          },                                                \
		  {                                                 \
              \"env\": \"GRID_DEBUG\",                      \
              \"descr\": \"Debug\",	                        \
              \"optional\": true				            \
          }                                                 \
      ]"