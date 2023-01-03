# docker-ps2-samba
Run a samba share compatible with openps2loader

Solution uses dperson/samba repository docker image. Share will have guest/all read-write access.
SMB1 isn't a secure protocol you should use it with caution.

The reasoning behind this low-effort - low-security container is that PS2 will be a b!tch and would not connect to anything else. So put your files in a folder that you would not mind to be ereased or filled up with garbage.

Keep in mind that this is only so that you can back up your disks to a network share to preserve the cd drive in your console. This container is a child that can choke on a piece of dirt if you leave it in the sandbox long enough.
