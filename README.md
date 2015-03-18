ChatWorld, OperService IRCBot
=============================

----------------------------------------------------------------------------------------
Changes from cw2000.20.5 to cw.2001:

By:		Fix/Change:
---		----
Pyra		bahamut support
Pyra		level in Chanclient
Pyra		misc. cmds_*

Changes from cw2000.20.5 to cw.2000.21.0:

By:		Fix/Change:
---		----
Pyra		EC axs
Pyra		LoadAverage/loadgraph
Pyra		Bug in m_create
Pyra		str_level bug
Pyra		Remove clinets on Defence

Changes from cw2000.20.3 to cw.2000.20.5:

By:      	Fix/Change:
---		----
Pyra		Stats. squits, nickchgs, quits
Pyra		ubf flags on chaninfo
Pyra		More stats stuff
Pyra		cmd_locked

Changes from cw2000.20.1 to cw.2000.20.3:

By:      	Fix/Change:
---		----
Pyra		Map V, IRCd version (+ m_531)
Pyra		new Level: LocalOper
Pyra		added IMOPER, allowing localopers to login (+ m_313)
Pyra		added dumpcmds


Changes from cw2000.19.8 to cw.2000.20.0:

By:      	Fix/Change:
---		----
Pyra & Sharky	Optimized fifo buffer reading
Sharky		Changed clonewarning
Pyra		Fixed bug in check_pings
Pyra		Added stats.runs
Pyra		Added T parameter to map command (Server local time)
Pyra		Dies on /mode #stuff +k %s%s%s%s and other %s%s%s%s
Pyra		Added cmd_LastCmds, shoes the, up to KEEP_COMMANDS, last commands
Pyra		Added GCClone, gline all persons on a channel with more
		    than 1 client from a host
Pyra		Added cmd_clearmode, remove all +o/+v/+b etc from a chan
Pyra		Added cmd_say, say stuff to a channel
Pyra		Added cmd_lock, cmd_unlock

----------------------------------------------------------------------------------------
Changes since cw2000.19.6:

By:      	Fix/Change:
---		----
Pyra		Dies on more than 400 bytes commands.
Pyra		Optimized the fifo.
Pyra		Added exec(self) on error..
Sharky		rewote cmd_mode.
Sharky		Added togglemsg.
Sharky		Added mbroadcast.
Sharky		Altered opers command.
Sharky		Added reson to exceptions, and changed elist report.
Sharky		Changed SIGNAL handler.
Sharky		Added gpurge command.

----------------------------------------------------------------------------------------
Changes before cw2000.19.6:

Lost :-/
/Pyra

----------------------------------------------------------------------------------------

V2004.2.6 written by:
Drizzt/Timothy Redaelli (drizzt@drizzt.it)
Smith/Alberto Casoni (smith@chatnet.org / smith@smit-h.net)

ChatNetProject - http://www.chatnetproject.org/
ChatWorld      - http://www.smit-h.net/cwproject/

Pyra: pyra@chatnet.dk / jesper@liscom.dk
Sharky: sharky@chatnet.dk / simon@liscom.dk
