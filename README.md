# Ignite-Hadoop Interface

The `ignite-hadoop` interface connects the [Apache Ignite-Hadoop charm][] to
the [Apache Hadoop slave charm][].

# Usage

## Apache Ignite-Hadoop charm (requires)

The Ignite-Hadoop charm is subordinate to the slave.

The interface layer will set the following state:

  * `{relation_name}.joined` The relation between Ignite-Hadoop and the
    slave has been established.


## Apache Hadoop slave charm (provides)

The Hadoop slave charm serves as the principal.

The interface layer will set the following state:

  * `{relation_name}.joined` The relation between Ignite-Hadoop and the
    slave has been established.


[Apache Ignite-Hadoop charm]: https://jujucharms.com/ignite-hadoop
[Apache Hadoop slave charm]: https://jujucharms.com/hadoop-slave
