# Solidity's `delegatecall` proxy factory

A factory for a Solidity's `delegatecall` proxy factory.

A repo derived from the work in this gist: https://gist.github.com/GNSPS/ba7b88565c947cfd781d44cf469c2ddb

Tests are inexistent for the time being but it has undergone extensive usage in production environments as can be seen in the comments in the gist.

## Usage

You can use the library here present by direct download and importing with:
```
import "ProxyFactory.sol";
```

or, if you have installed it from EPM (see below), with Truffle's specific paths:
```
import "proxy/ProxyFactory.sol";`
```

## EthPM

This library is published in EPM under the alias `proxy`

**Installing it with Truffle**

```
$ truffle install proxy
```

## NPM

This library is published in NPM under the alias `delegatecall-proxy-factory`

**Installing it with NPM**

```
$ npm install delegatecall-proxy-factory
```

**Importing it in your Truffle project**

```
import "delegatecall-proxy-factory/BytesLib.sol";
```

