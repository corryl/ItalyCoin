ItalyCoin è una valuta elettronica basata su una rete P2P, la quale permette pagamenti istantanei e anonimi a qualsiasi persona nel mondo, ma principalmente studiata per il mercato italiano. ItalyCoin si basa sul protocollo Bitcoin ma ne differisce, in quanto il mining può essere eseguito con una certa efficienza anche con l'hardware in possesso del normale consumatore. ItalyCoin garantisce conferme delle transazioni più veloci (1 minuto in media) e adopera un algoritmo di mining basato su scrypt, in modo da avere come target i normali computer e le GPU più diffuse. La rete ItalyCoin è programmata per produrre 5 Miliardi di unità monetarie.

ItalyCoin è basata su LiteCoin:

LiteCoin è la versione lite di Bitcoin che utilizza scrypt come algoritmo di lavoro.

Informazioni su ItalyCoin:

5 Miliardi di coin massimi.

Un nuovo blocco ogni 60 sec.

50 coin per blocco.

RPC Port: 9004

Possibilità di mining direttamente dal portafoglio elettronico.

Licenza

ItalyCoin è rilasciato sotto i termini della licenza MIT per maggiori informazioni: http://opensource.org/licenses/MIT

Development process

Developers work in their own trees, then submit pull requests when they think their feature or bug fix is ready.

If it is a simple/trivial/non-controversial change, then one of the ItalyCoin development team members simply pulls it.

If it is a more complicated or potentially controversial change, then the patch submitter will be asked to start a discussion (if they haven't already) on the mailing list.

The patch will be accepted if there is broad consensus that it is a good thing. Developers should expect to rework and resubmit patches if the code doesn't match the project's coding conventions (see doc/coding.txt) or are controversial.

The master branch is regularly built and tested, but is not guaranteed to be completely stable. Tags are created regularly to indicate new official, stable release versions of ItalyCoin.

Compilazione.

cd ~/ItalyCoin/src

make -f makefile.unix USE_UPNP=1

compilazione gui qt:

cd ~/ItalyCoin

qmake "USE_UPNP=1"

make


