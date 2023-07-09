`[node](on a machine with GPUs) <---> [nodes controller client](on a controlling workstation or device)`

`[node](on a machine with GPUs) <---> [BN cloud](nodes network)`

`[BN colab website](on a BN webserver) <---> [BN cloud](nodes network)`

`[BN colab website](on a BN webserver) <---> [node](on a machine with GPUs)`

----

`node` ::= `[cmd_boinc AKA client]` with GUI app `boinc-mgr` and CLI app `boinc-cmd` communicating with `client` via RPC port

```xml
  <refsect1>
    <title>DESCRIPTION</title>
    <para>The BOINC "client", &cmd_boinc;, is the heart of BOINC.
      It controls which project applications are run on your computer,
      downloading "Tasks" and uploading the resulting files from completed
      tasks. &cmd_boinc; is usually run in the background, ideally as a
      daemon. It can then be controlled either by a graphical tool called the
      BOINC Manager, &man_boincmgr;, or a command-line tool called
      &man_boinccmd;, by means of Remote Procedure Calls (RPCs) over port
      &rpc_port;.</para>

    <para>The BOINC client can be controlled by command-line options,
      configuration files, and environment variables. Standard usage is simply
      to start the client running in the background.</para>
  </refsect1>
```
