#Spinn Address

Spinn addresses are very similar to bitcoin addresses as they use base58 with a leading prefix of '7c' hex. 

That's it! Spinn private keys are no different than a bitcoin WIF Private Key and can be generated in the same methods. 

The only difference is the address encoding. 

Example of simple conversion method:

    var start = '3DnW8JGpPViEZdpqat8qky1zc26EKbXnmM'
    var data = b58.decode(start);
    data = data.slice(1);
    data = Buffer.concat([Buffer.from('7c','hex'), data]);
    return b58.encode(data);
    //s71HJDk6sxrVtDR9VommTtQcW3kUzmBA5b
