scala_library(name='scala',
  provides = scala_artifact(
    org = 'com.twitter',
    name = 'util-zk-common',
    repo = artifactory,
  ),
  dependencies=[
    '3rdparty:guava',
    '3rdparty:zookeeper',
    '3rdparty/jvm/com/twitter/common:quantity',
    '3rdparty/jvm/com/twitter/common:service-thrift',
    '3rdparty/jvm/com/twitter/common/zookeeper:client',
    '3rdparty/jvm/com/twitter/common/zookeeper:server-set',
    'util/util-collection/src/main/scala',
    'util/util-core/src/main/scala',
    'util/util-hashing/src/main/scala',
    'util/util-logging/src/main/scala',
    'util/util-zk/src/main/scala',
  ],
  sources=rglobs('*.scala'),
)
