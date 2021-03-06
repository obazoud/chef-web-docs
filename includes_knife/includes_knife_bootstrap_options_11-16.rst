.. The contents of this file may be included in multiple topics (using the includes directive).
.. The contents of this file should be modified in a way that preserves its ability to appear in multiple topics.


This subcommand has the following options:

``-A``, ``--forward-agent``
   |forward_agent|

``--bootstrap-curl-options OPTIONS``
   |bootstrap curl_options| |bootstrap no_install_command|

``--bootstrap-install-command COMMAND``
   |bootstrap install_command| |bootstrap no_curl_sh_wget|
 
``--bootstrap-install-sh URL``
   |bootstrap install_sh| |bootstrap no_install_command|

``--bootstrap-no-proxy NO_PROXY_URL_or_IP``
   |bootstrap no_proxy|

   .. note:: This option is used internally by |company_name| to help verify bootstrap operations during testing and should never be used during an actual bootstrap operation.

``--bootstrap-proxy PROXY_URL``
   |bootstrap proxy|

``--bootstrap-version VERSION``
   |bootstrap version|

``--bootstrap-wget-options OPTIONS``
   |bootstrap wget_options| |bootstrap no_install_command|
   
``-d DISTRO``, ``--distro DISTRO``
   .. include:: ../../includes_knife/includes_knife_bootstrap_distro.rst

   .. warning:: The default bootstrap operation uses the |omnibus installer|, which means the default template file (``chef-full``) should work on all supported platforms. It is recommended to use custom bootstrap templates only when the |omnibus installer| cannot be used. The ``.erb`` file extension is added automatically and should not be passed as part of the bootstrap command.

``-E ENVIRONMENT``, ``--environment ENVIRONMENT``
   |name environment| When this option is added to a command, the command will run only against the named environment.

``-G GATEWAY``, ``--ssh-gateway GATEWAY``
   |ssh_gateway|

``--hint HINT_NAME[=HINT_FILE]``
   |hint|

   .. include:: ../../includes_ohai/includes_ohai_hints.rst

   |hint_file| |hint_name| |hint_multiple|

``-i IDENTITY_FILE``, ``--identity-file IDENTITY_FILE``
   |identity_file|

``-j JSON_ATTRIBS``, ``--json-attributes JSON_ATTRIBS``
   |json first_run_string|

``-N NAME``, ``--node-name NAME``
   |name node|

``--[no-]host-key-verify``
   |no_host_key_verify| Default setting: ``--host-key-verify``.

``-p PORT``, ``--ssh-port PORT``
   |ssh_port|

``-P PASSWORD``, ``--ssh-password PASSWORD``
   |ssh_password|

``--prerelease``
   |prerelease|

``-r RUN_LIST``, ``--run-list RUN_LIST``
   |run_list|

``--secret SECRET``
   |secret|

``--secret-file FILE``
   |secret_file|

``--sudo``
   |sudo bootstrap|

``--template-file TEMPLATE``
   |path bootstrap_template| Do not use the ``--distro`` option when ``--template-file`` is specified.

``--use-sudo-password``
   |use sudo_password|

``-V -V``
   |verbose knife_bootstrap|

``-x USERNAME``, ``--ssh-user USERNAME``
   |ssh_user|

