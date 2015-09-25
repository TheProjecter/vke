Verbal Key Exchange is an authenticated key exchange protocol that uses
words from a dictionary to represent a public key fingerprint.

Authenticated key exchange is easier when two users wishing to establish a
security association are both present. Verbal key exchange protocol uses
words from a dictionary to represent a public key fingerprint. Using a
dictionary containing N words, each word can represent log2(N) bits of a
public key fingerprint. A number of words representing a fingerprint is read
to the initiator user. The initiator user enters the same words and upon
public key match, key exchange is performed.

An RSA-based implementation that uses GTK word completion with mouse and
keyboard is demonstrated.

For more information:
http://tools.ietf.org/id/draft-mutaf-dke-02.txt
