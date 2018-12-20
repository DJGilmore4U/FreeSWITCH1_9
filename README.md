Root Directory Map
```
/usr/local/freeswitch/
├── bin
│   ├── freeswitch
│   ├── fs_cli
│   ├── fs_encode
│   ├── fs_ivrd
│   ├── fsxs
│   ├── gentls_cert
│   └── tone2wav
├── certs
│   ├── dtls-srtp.pem
│   ├── self.crt
│   ├── self.key
│   ├── wss.pem
│   └── wss.pem.orig
├── conf
│   ├── autoload_configs
│   │   ├── abstraction.conf.xml
│   │   ├── acl.conf.xml
│   │   ├── alsa.conf.xml
│   │   ├── amqp.conf.xml
│   │   ├── amr.conf.xml
│   │   ├── amrwb.conf.xml
│   │   ├── avmd.conf.xml
│   │   ├── blacklist.conf.xml
│   │   ├── callcenter.conf.xml
│   │   ├── cdr_csv.conf.xml
│   │   ├── cdr_mongodb.conf.xml
│   │   ├── cdr_pg_csv.conf.xml
│   │   ├── cdr_sqlite.conf.xml
│   │   ├── cepstral.conf.xml
│   │   ├── cidlookup.conf.xml
│   │   ├── conference.conf.xml
│   │   ├── conference_layouts.conf.xml
│   │   ├── console.conf.xml
│   │   ├── db.conf.xml
│   │   ├── dialplan_directory.conf.xml
│   │   ├── dingaling.conf.xml
│   │   ├── directory.conf.xml
│   │   ├── distributor.conf.xml
│   │   ├── easyroute.conf.xml
│   │   ├── enum.conf.xml
│   │   ├── erlang_event.conf.xml
│   │   ├── event_multicast.conf.xml
│   │   ├── event_socket.conf.xml
│   │   ├── fax.conf.xml
│   │   ├── fifo.conf.xml
│   │   ├── format_cdr.conf.xml
│   │   ├── graylog2.conf.xml
│   │   ├── hash.conf.xml
│   │   ├── hiredis.conf.xml
│   │   ├── httapi.conf.xml
│   │   ├── http_cache.conf.xml
│   │   ├── ivr.conf.xml
│   │   ├── java.conf.xml
│   │   ├── kazoo.conf.xml
│   │   ├── lcr.conf.xml
│   │   ├── local_stream.conf.xml
│   │   ├── logfile.conf.xml
│   │   ├── lua.conf.xml
│   │   ├── memcache.conf.xml
│   │   ├── modules.conf.xml
│   │   ├── modules.conf.xml~
│   │   ├── mongo.conf.xml
│   │   ├── msrp.conf.xml
│   │   ├── nibblebill.conf.xml
│   │   ├── opal.conf.xml
│   │   ├── opus.conf.xml
│   │   ├── oreka.conf.xml
│   │   ├── osp.conf.xml
│   │   ├── perl.conf.xml
│   │   ├── pocketsphinx.conf.xml
│   │   ├── portaudio.conf.xml
│   │   ├── post_load_modules.conf.xml
│   │   ├── presence_map.conf.xml
│   │   ├── python.conf.xml
│   │   ├── redis.conf.xml
│   │   ├── rss.conf.xml
│   │   ├── rtmp.conf.xml
│   │   ├── sangoma_codec.conf.xml
│   │   ├── shout.conf.xml
│   │   ├── skinny.conf.xml
│   │   ├── smpp.conf.xml
│   │   ├── sms_flowroute.conf.xml
│   │   ├── sofia.conf.xml
│   │   ├── spandsp.conf.xml
│   │   ├── switch.conf.xml
│   │   ├── syslog.conf.xml
│   │   ├── timezones.conf.xml
│   │   ├── translate.conf.xml
│   │   ├── tts_commandline.conf.xml
│   │   ├── unicall.conf.xml
│   │   ├── unimrcp.conf.xml
│   │   ├── v8.conf.xml
│   │   ├── verto.conf.xml
│   │   ├── voicemail.conf.xml
│   │   ├── voicemail_ivr.conf.xml
│   │   ├── xml_cdr.conf.xml
│   │   ├── xml_curl.conf.xml
│   │   ├── xml_rpc.conf.xml
│   │   ├── xml_scgi.conf.xml
│   │   └── zeroconf.conf.xml
│   ├── chatplan
│   │   └── default.xml
│   ├── dialplan
│   │   ├── default
│   │   │   ├── 00_ladspa.xml
│   │   │   ├── 00_pizza_demo.xml
│   │   │   ├── 01_example.com.xml
│   │   │   └── 01_Talking_Clock.xml
│   │   ├── default.xml
│   │   ├── default.xml~
│   │   ├── features.xml
│   │   ├── public
│   │   │   └── 00_inbound_did.xml
│   │   ├── public.xml
│   │   ├── skinny-patterns
│   │   │   ├── 20-Demo.xml
│   │   │   ├── 20-Local_extension.xml
│   │   │   ├── 90-External.xml
│   │   │   └── 99-Default_Drop.xml
│   │   └── skinny-patterns.xml
│   ├── directory
│   │   ├── default
│   │   │   ├── 1000.xml
│   │   │   ├── 1001.xml
│   │   │   ├── 1001.xml~
│   │   │   ├── 1002.xml
│   │   │   ├── 1003.xml
│   │   │   ├── 1004.xml
│   │   │   ├── 1005.xml
│   │   │   ├── 1006.xml
│   │   │   ├── 1007.xml
│   │   │   ├── 1008.xml
│   │   │   ├── 1009.xml
│   │   │   ├── 1010.xml
│   │   │   ├── 1011.xml
│   │   │   ├── 1012.xml
│   │   │   ├── 1013.xml
│   │   │   ├── 1014.xml
│   │   │   ├── 1015.xml
│   │   │   ├── 1016.xml
│   │   │   ├── 1017.xml
│   │   │   ├── 1018.xml
│   │   │   ├── 1019.xml
│   │   │   ├── brian.xml
│   │   │   ├── default.xml
│   │   │   ├── example.com.xml
│   │   │   └── skinny-example.xml
│   │   ├── default.xml
│   │   └── default.xml~
│   ├── extensions.conf
│   ├── freeswitch.xml
│   ├── fur_elise.ttml
│   ├── ivr_menus
│   │   ├── demo_ivr.xml
│   │   └── new_demo_ivr.xml
│   ├── jingle_profiles
│   │   ├── client.xml
│   │   └── server.xml
│   ├── lang
│   │   ├── de
│   │   │   ├── demo
│   │   │   │   └── demo.xml
│   │   │   ├── de.xml
│   │   │   └── vm
│   │   │       ├── sounds.xml
│   │   │       └── tts.xml
│   │   ├── en
│   │   │   ├── demo
│   │   │   │   ├── demo-ivr.xml
│   │   │   │   ├── demo.xml
│   │   │   │   ├── funnies.xml
│   │   │   │   └── new-demo-ivr.xml
│   │   │   ├── dir
│   │   │   │   ├── sounds.xml
│   │   │   │   └── tts.xml
│   │   │   ├── en.xml
│   │   │   ├── ivr
│   │   │   │   └── sounds.xml
│   │   │   └── vm
│   │   │       ├── sounds.xml
│   │   │       ├── tts.xml
│   │   │       └── voicemail_ivr.xml
│   │   ├── es
│   │   │   ├── demo
│   │   │   │   ├── demo-es-ES.xml
│   │   │   │   ├── demo-es-MX.xml
│   │   │   │   ├── demo-ivr-es-ES.xml
│   │   │   │   └── demo-ivr-es-MX.xml
│   │   │   ├── dir
│   │   │   │   ├── sounds-es-ES.xml
│   │   │   │   ├── sounds-es-MX.xml
│   │   │   │   ├── tts-es-ES.xml
│   │   │   │   └── tts-es-MX.xml
│   │   │   ├── es_ES.xml
│   │   │   ├── es_MX.xml
│   │   │   └── vm
│   │   │       ├── sounds-es-ES.xml
│   │   │       ├── sounds-es-MX.xml
│   │   │       ├── tts-es-ES.xml
│   │   │       └── tts-es-MX.xml
│   │   ├── fr
│   │   │   ├── demo
│   │   │   │   └── demo.xml
│   │   │   ├── dir
│   │   │   │   ├── sounds.xml
│   │   │   │   └── tts.xml
│   │   │   ├── fr.xml
│   │   │   └── vm
│   │   │       └── sounds.xml
│   │   ├── he
│   │   │   ├── demo
│   │   │   │   ├── demo-ivr.xml
│   │   │   │   └── demo.xml
│   │   │   ├── dir
│   │   │   │   └── sounds.xml
│   │   │   ├── he.xml
│   │   │   └── vm
│   │   │       └── sounds.xml
│   │   ├── pt
│   │   │   ├── demo
│   │   │   │   ├── demo-ivr-pt-BR.xml
│   │   │   │   ├── demo-ivr-pt-PT.xml
│   │   │   │   ├── demo-pt-BR.xml
│   │   │   │   └── demo-pt-PT.xml
│   │   │   ├── dir
│   │   │   │   ├── sounds-pt-BR.xml
│   │   │   │   ├── sounds-pt-PT.xml
│   │   │   │   ├── tts-pt-BR.xml
│   │   │   │   └── tts-pt-PT.xml
│   │   │   ├── pt_BR.xml
│   │   │   ├── pt_PT.xml
│   │   │   └── vm
│   │   │       ├── sounds-pt-BR.xml
│   │   │       ├── sounds-pt-PT.xml
│   │   │       ├── tts-pt-BR.xml
│   │   │       └── tts-pt-PT.xml
│   │   ├── ru
│   │   │   ├── demo
│   │   │   │   ├── demo-ivr.xml
│   │   │   │   └── demo.xml
│   │   │   ├── dir
│   │   │   │   ├── sounds.xml
│   │   │   │   └── tts.xml
│   │   │   ├── ru.xml
│   │   │   └── vm
│   │   │       ├── sounds.xml
│   │   │       └── tts.xml
│   │   └── sv
│   │       ├── sv.xml
│   │       └── vm
│   │           └── sounds.xml
│   ├── mime.types
│   ├── mrcp_profiles
│   │   ├── loquendo-7-mrcp-v2.xml
│   │   ├── nuance-1.0.0-mrcp-v1.xml
│   │   ├── nuance-5.0-mrcp-v1.xml
│   │   ├── nuance-5.0-mrcp-v2.xml
│   │   ├── unimrcpserver-mrcp-v1.xml
│   │   ├── vestec-mrcp-v1.xml
│   │   └── voxeo-prophecy-8.0-mrcp-v1.xml
│   ├── notify-voicemail.tpl
│   ├── sip_profiles
│   │   ├── external
│   │   │   └── example.xml
│   │   ├── external-ipv6
│   │   │   └── example.xml
│   │   ├── external-ipv6.xml
│   │   ├── external.xml
│   │   ├── internal-ipv6.xml
│   │   └── internal.xml
│   ├── skinny_profiles
│   │   └── internal.xml
│   ├── tetris.ttml
│   ├── vars.xml
│   ├── vars.xml~
│   ├── voicemail.tpl
│   └── web-vm.tpl
├── db
│   ├── call_limit.db
│   ├── core.db
│   ├── fifo.db
│   ├── json.db
│   ├── nibblebill.db
│   ├── sofia_reg_external.db
│   ├── sofia_reg_external-ipv6.db
│   ├── sofia_reg_internal.db
│   ├── sofia_reg_internal-ipv6.db
│   └── voicemail_default.db
├── fonts
│   ├── FreeMonoBoldOblique.ttf
│   ├── FreeMonoBold.ttf
│   ├── FreeMonoOblique.ttf
│   ├── FreeMono.ttf
│   ├── FreeSansBoldOblique.ttf
│   ├── FreeSansBold.ttf
│   ├── FreeSansOblique.ttf
│   ├── FreeSans.ttf
│   ├── FreeSerifBoldItalic.ttf
│   ├── FreeSerifBold.ttf
│   ├── FreeSerifItalic.ttf
│   ├── FreeSerif.ttf
│   ├── OFL.txt
│   └── README.fonts
├── grammar
├── htdocs
│   ├── license.txt
│   ├── portal
│   │   ├── assets
│   │   │   ├── bootstrap
│   │   │   │   ├── css
│   │   │   │   │   ├── bootstrap.css
│   │   │   │   │   ├── bootstrap.min.css
│   │   │   │   │   ├── bootstrap-responsive.css
│   │   │   │   │   └── bootstrap-responsive.min.css
│   │   │   │   ├── img
│   │   │   │   │   ├── glyphicons-halflings.png
│   │   │   │   │   └── glyphicons-halflings-white.png
│   │   │   │   └── js
│   │   │   │       ├── bootstrap.js
│   │   │   │       └── bootstrap.min.js
│   │   │   ├── bootstrap-3.1.1
│   │   │   │   ├── css
│   │   │   │   │   ├── bootstrap.css
│   │   │   │   │   ├── bootstrap.min.css
│   │   │   │   │   ├── bootstrap-theme.css
│   │   │   │   │   └── bootstrap-theme.min.css
│   │   │   │   ├── fonts
│   │   │   │   │   ├── glyphicons-halflings-regular.eot
│   │   │   │   │   ├── glyphicons-halflings-regular.svg
│   │   │   │   │   ├── glyphicons-halflings-regular.ttf
│   │   │   │   │   └── glyphicons-halflings-regular.woff
│   │   │   │   └── js
│   │   │   │       ├── bootstrap.js
│   │   │   │       └── bootstrap.min.js
│   │   │   ├── bs_for_ember
│   │   │   │   ├── css
│   │   │   │   │   └── bs-growl-notifications.min.css
│   │   │   │   └── js
│   │   │   │       ├── bs-alert.min.js
│   │   │   │       ├── bs-badge.min.js
│   │   │   │       ├── bs-basic.min.js
│   │   │   │       ├── bs-button.min.js
│   │   │   │       ├── bs-core.min.js
│   │   │   │       ├── bs-growl-notifications.min.js
│   │   │   │       ├── bs-items-action-bar.min.js
│   │   │   │       ├── bs-label.min.js
│   │   │   │       ├── bs-list-group.min.js
│   │   │   │       ├── bs-modal.min.js
│   │   │   │       ├── bs-nav.min.js
│   │   │   │       ├── bs-notifications.min.js
│   │   │   │       ├── bs-progressbar.min.js
│   │   │   │       └── bs-wizard.min.js
│   │   │   └── js
│   │   │       ├── ember-1.0.0-rc.1.js
│   │   │       ├── ember-1.0.0-rc.1.min.js
│   │   │       ├── ember-data.js
│   │   │       ├── ember-data.min.js
│   │   │       ├── ember.js
│   │   │       ├── ember.min.js
│   │   │       ├── fsportal.js
│   │   │       ├── handlebars.js
│   │   │       ├── handlebars.min.js
│   │   │       ├── ie-console.js
│   │   │       ├── jquery-1.9.1.min.js
│   │   │       └── jquery.min.js
│   │   ├── index.html
│   │   ├── LICENCE
│   │   └── README.md
│   ├── slim.swf
│   └── slimtest.htm
├── images
│   ├── default-avatar.png
│   └── default-mute.png
├── include
│   └── freeswitch
│       ├── libteletone_detect.h
│       ├── libteletone_generate.h
│       ├── libteletone.h
│       ├── switch_am_config.h
│       ├── switch_apr.h
│       ├── switch_buffer.h
│       ├── switch_caller.h
│       ├── switch_channel.h
│       ├── switch_cJSON.h
│       ├── switch_cJSON_Utils.h
│       ├── switch_config.h
│       ├── switch_console.h
│       ├── switch_core_db.h
│       ├── switch_core_event_hook.h
│       ├── switch_core.h
│       ├── switch_core_media.h
│       ├── switch_core_video.h
│       ├── switch_cpp.h
│       ├── switch_curl.h
│       ├── switch_dso.h
│       ├── switch_estimators.h
│       ├── switch_event.h
│       ├── switch_frame.h
│       ├── switch.h
│       ├── switch_hashtable.h
│       ├── switch_image.h
│       ├── switch_ivr.h
│       ├── switch_jitterbuffer.h
│       ├── switch_json.h
│       ├── switch_limit.h
│       ├── switch_loadable_module.h
│       ├── switch_log.h
│       ├── switch_module_interfaces.h
│       ├── switch_mprintf.h
│       ├── switch_msrp.h
│       ├── switch_nat.h
│       ├── switch_odbc.h
│       ├── switch_pgsql.h
│       ├── switch_platform.h
│       ├── switch_regex.h
│       ├── switch_resample.h
│       ├── switch_rtcp_frame.h
│       ├── switch_rtp.h
│       ├── switch_scheduler.h
│       ├── switch_stun.h
│       ├── switch_types.h
│       ├── switch_utf8.h
│       ├── switch_utils.h
│       ├── switch_vpx.h
│       ├── switch_xml_config.h
│       ├── switch_xml.h
│       └── tpl.h
├── lib
│   ├── libfreeswitch.a
│   ├── libfreeswitch.la
│   ├── libfreeswitch.so -> libfreeswitch.so.1.0.0
│   ├── libfreeswitch.so.1 -> libfreeswitch.so.1.0.0
│   ├── libfreeswitch.so.1.0.0
│   └── pkgconfig
│       └── freeswitch.pc
├── log
│   ├── cdr-csv
│   │   ├── 1000.csv
│   │   ├── 1001.csv
│   │   ├── 1006.csv
│   │   ├── 1007.csv
│   │   └── Master.csv
│   ├── freeswitch.log
│   ├── freeswitch.log.1
│   ├── freeswitch.xml.fsxml
│   └── xml_cdr
├── mod
│   ├── mod_amr.la
│   ├── mod_amr.so
│   ├── mod_av.la
│   ├── mod_av.so
│   ├── mod_b64.la
│   ├── mod_b64.so
│   ├── mod_cdr_csv.la
│   ├── mod_cdr_csv.so
│   ├── mod_cdr_sqlite.la
│   ├── mod_cdr_sqlite.so
│   ├── mod_commands.la
│   ├── mod_commands.so
│   ├── mod_conference.la
│   ├── mod_conference.so
│   ├── mod_console.la
│   ├── mod_console.so
│   ├── mod_db.la
│   ├── mod_db.so
│   ├── mod_dialplan_asterisk.la
│   ├── mod_dialplan_asterisk.so
│   ├── mod_dialplan_xml.la
│   ├── mod_dialplan_xml.so
│   ├── mod_dptools.la
│   ├── mod_dptools.so
│   ├── mod_enum.la
│   ├── mod_enum.so
│   ├── mod_esf.la
│   ├── mod_esf.so
│   ├── mod_event_socket.la
│   ├── mod_event_socket.so
│   ├── mod_expr.la
│   ├── mod_expr.so
│   ├── mod_fifo.la
│   ├── mod_fifo.so
│   ├── mod_fsv.la
│   ├── mod_fsv.so
│   ├── mod_g723_1.la
│   ├── mod_g723_1.so
│   ├── mod_g729.la
│   ├── mod_g729.so
│   ├── mod_h26x.la
│   ├── mod_h26x.so
│   ├── mod_hash.la
│   ├── mod_hash.so
│   ├── mod_httapi.la
│   ├── mod_httapi.so
│   ├── mod_local_stream.la
│   ├── mod_local_stream.so
│   ├── mod_logfile.la
│   ├── mod_logfile.so
│   ├── mod_loopback.la
│   ├── mod_loopback.so
│   ├── mod_lua.la
│   ├── mod_lua.so
│   ├── mod_native_file.la
│   ├── mod_native_file.so
│   ├── mod_nibblebill.la
│   ├── mod_nibblebill.so
│   ├── mod_opus.la
│   ├── mod_opus.so
│   ├── mod_png.la
│   ├── mod_png.so
│   ├── mod_rtc.la
│   ├── mod_rtc.so
│   ├── mod_say_en.la
│   ├── mod_say_en.so
│   ├── mod_shout.la
│   ├── mod_shout.so
│   ├── mod_skinny.la
│   ├── mod_skinny.so
│   ├── mod_sms.la
│   ├── mod_sms.so
│   ├── mod_sndfile.la
│   ├── mod_sndfile.so
│   ├── mod_sofia.la
│   ├── mod_sofia.so
│   ├── mod_spandsp.la
│   ├── mod_spandsp.so
│   ├── mod_syslog.la
│   ├── mod_syslog.so
│   ├── mod_tone_stream.la
│   ├── mod_tone_stream.so
│   ├── mod_valet_parking.la
│   ├── mod_valet_parking.so
│   ├── mod_verto.la
│   ├── mod_verto.so
│   ├── mod_voicemail.la
│   ├── mod_voicemail.so
│   ├── mod_xml_cdr.la
│   ├── mod_xml_cdr.so
│   ├── mod_xml_rpc.la
│   ├── mod_xml_rpc.so
│   ├── mod_xml_scgi.la
│   └── mod_xml_scgi.so
├── recordings
├── run
│   └── freeswitch.pid
├── scripts
├── sounds
│   ├── en
│   │   └── us
│   │       └── callie
│   │           ├── ascii
│   │           │   ├── 16000
│   │           │   │   ├── 100.wav
│   │           │   │   ├── 101.wav
│   │           │   │   ├── 102.wav
│   │           │   │   ├── 103.wav
│   │           │   │   ├── 104.wav
│   │           │   │   ├── 105.wav
│   │           │   │   ├── 106.wav
│   │           │   │   ├── 107.wav
│   │           │   │   ├── 108.wav
│   │           │   │   ├── 109.wav
│   │           │   │   ├── 110.wav
│   │           │   │   ├── 111.wav
│   │           │   │   ├── 112.wav
│   │           │   │   ├── 113.wav
│   │           │   │   ├── 114.wav
│   │           │   │   ├── 115.wav
│   │           │   │   ├── 116.wav
│   │           │   │   ├── 117.wav
│   │           │   │   ├── 118.wav
│   │           │   │   ├── 119.wav
│   │           │   │   ├── 120.wav
│   │           │   │   ├── 121.wav
│   │           │   │   ├── 122.wav
│   │           │   │   ├── 123.wav
│   │           │   │   ├── 124.wav
│   │           │   │   ├── 125.wav
│   │           │   │   ├── 126.wav
│   │           │   │   ├── 32.wav
│   │           │   │   ├── 33.wav
│   │           │   │   ├── 34.wav
│   │           │   │   ├── 35.wav
│   │           │   │   ├── 36.wav
│   │           │   │   ├── 37.wav
│   │           │   │   ├── 38.wav
│   │           │   │   ├── 39.wav
│   │           │   │   ├── 40.wav
│   │           │   │   ├── 41.wav
│   │           │   │   ├── 42.wav
│   │           │   │   ├── 43.wav
│   │           │   │   ├── 44.wav
│   │           │   │   ├── 45.wav
│   │           │   │   ├── 46.wav
│   │           │   │   ├── 47.wav
│   │           │   │   ├── 58.wav
│   │           │   │   ├── 59.wav
│   │           │   │   ├── 60.wav
│   │           │   │   ├── 61.wav
│   │           │   │   ├── 62.wav
│   │           │   │   ├── 64.wav
│   │           │   │   ├── 91.wav
│   │           │   │   ├── 92.wav
│   │           │   │   ├── 93.wav
│   │           │   │   ├── 94.wav
│   │           │   │   ├── 95.wav
│   │           │   │   ├── 96.wav
│   │           │   │   ├── 97.wav
│   │           │   │   ├── 98.wav
│   │           │   │   └── 99.wav
│   │           │   ├── 32000
│   │           │   │   ├── 100.wav
│   │           │   │   ├── 101.wav
│   │           │   │   ├── 102.wav
│   │           │   │   ├── 103.wav
│   │           │   │   ├── 104.wav
│   │           │   │   ├── 105.wav
│   │           │   │   ├── 106.wav
│   │           │   │   ├── 107.wav
│   │           │   │   ├── 108.wav
│   │           │   │   ├── 109.wav
│   │           │   │   ├── 110.wav
│   │           │   │   ├── 111.wav
│   │           │   │   ├── 112.wav
│   │           │   │   ├── 113.wav
│   │           │   │   ├── 114.wav
│   │           │   │   ├── 115.wav
│   │           │   │   ├── 116.wav
│   │           │   │   ├── 117.wav
│   │           │   │   ├── 118.wav
│   │           │   │   ├── 119.wav
│   │           │   │   ├── 120.wav
│   │           │   │   ├── 121.wav
│   │           │   │   ├── 122.wav
│   │           │   │   ├── 123.wav
│   │           │   │   ├── 124.wav
│   │           │   │   ├── 125.wav
│   │           │   │   ├── 126.wav
│   │           │   │   ├── 32.wav
│   │           │   │   ├── 33.wav
│   │           │   │   ├── 34.wav
│   │           │   │   ├── 35.wav
│   │           │   │   ├── 36.wav
│   │           │   │   ├── 37.wav
│   │           │   │   ├── 38.wav
│   │           │   │   ├── 39.wav
│   │           │   │   ├── 40.wav
│   │           │   │   ├── 41.wav
│   │           │   │   ├── 42.wav
│   │           │   │   ├── 43.wav
│   │           │   │   ├── 44.wav
│   │           │   │   ├── 45.wav
│   │           │   │   ├── 46.wav
│   │           │   │   ├── 47.wav
│   │           │   │   ├── 58.wav
│   │           │   │   ├── 59.wav
│   │           │   │   ├── 60.wav
│   │           │   │   ├── 61.wav
│   │           │   │   ├── 62.wav
│   │           │   │   ├── 64.wav
│   │           │   │   ├── 91.wav
│   │           │   │   ├── 92.wav
│   │           │   │   ├── 93.wav
│   │           │   │   ├── 94.wav
│   │           │   │   ├── 95.wav
│   │           │   │   ├── 96.wav
│   │           │   │   ├── 97.wav
│   │           │   │   ├── 98.wav
│   │           │   │   └── 99.wav
│   │           │   ├── 48000
│   │           │   │   ├── 100.wav
│   │           │   │   ├── 101.wav
│   │           │   │   ├── 102.wav
│   │           │   │   ├── 103.wav
│   │           │   │   ├── 104.wav
│   │           │   │   ├── 105.wav
│   │           │   │   ├── 106.wav
│   │           │   │   ├── 107.wav
│   │           │   │   ├── 108.wav
│   │           │   │   ├── 109.wav
│   │           │   │   ├── 110.wav
│   │           │   │   ├── 111.wav
│   │           │   │   ├── 112.wav
│   │           │   │   ├── 113.wav
│   │           │   │   ├── 114.wav
│   │           │   │   ├── 115.wav
│   │           │   │   ├── 116.wav
│   │           │   │   ├── 117.wav
│   │           │   │   ├── 118.wav
│   │           │   │   ├── 119.wav
│   │           │   │   ├── 120.wav
│   │           │   │   ├── 121.wav
│   │           │   │   ├── 122.wav
│   │           │   │   ├── 123.wav
│   │           │   │   ├── 124.wav
│   │           │   │   ├── 125.wav
│   │           │   │   ├── 126.wav
│   │           │   │   ├── 32.wav
│   │           │   │   ├── 33.wav
│   │           │   │   ├── 34.wav
│   │           │   │   ├── 35.wav
│   │           │   │   ├── 36.wav
│   │           │   │   ├── 37.wav
│   │           │   │   ├── 38.wav
│   │           │   │   ├── 39.wav
│   │           │   │   ├── 40.wav
│   │           │   │   ├── 41.wav
│   │           │   │   ├── 42.wav
│   │           │   │   ├── 43.wav
│   │           │   │   ├── 44.wav
│   │           │   │   ├── 45.wav
│   │           │   │   ├── 46.wav
│   │           │   │   ├── 47.wav
│   │           │   │   ├── 58.wav
│   │           │   │   ├── 59.wav
│   │           │   │   ├── 60.wav
│   │           │   │   ├── 61.wav
│   │           │   │   ├── 62.wav
│   │           │   │   ├── 64.wav
│   │           │   │   ├── 91.wav
│   │           │   │   ├── 92.wav
│   │           │   │   ├── 93.wav
│   │           │   │   ├── 94.wav
│   │           │   │   ├── 95.wav
│   │           │   │   ├── 96.wav
│   │           │   │   ├── 97.wav
│   │           │   │   ├── 98.wav
│   │           │   │   └── 99.wav
│   │           │   └── 8000
│   │           │       ├── 100.wav
│   │           │       ├── 101.wav
│   │           │       ├── 102.wav
│   │           │       ├── 103.wav
│   │           │       ├── 104.wav
│   │           │       ├── 105.wav
│   │           │       ├── 106.wav
│   │           │       ├── 107.wav
│   │           │       ├── 108.wav
│   │           │       ├── 109.wav
│   │           │       ├── 110.wav
│   │           │       ├── 111.wav
│   │           │       ├── 112.wav
│   │           │       ├── 113.wav
│   │           │       ├── 114.wav
│   │           │       ├── 115.wav
│   │           │       ├── 116.wav
│   │           │       ├── 117.wav
│   │           │       ├── 118.wav
│   │           │       ├── 119.wav
│   │           │       ├── 120.wav
│   │           │       ├── 121.wav
│   │           │       ├── 122.wav
│   │           │       ├── 123.wav
│   │           │       ├── 124.wav
│   │           │       ├── 125.wav
│   │           │       ├── 126.wav
│   │           │       ├── 32.wav
│   │           │       ├── 33.wav
│   │           │       ├── 34.wav
│   │           │       ├── 35.wav
│   │           │       ├── 36.wav
│   │           │       ├── 37.wav
│   │           │       ├── 38.wav
│   │           │       ├── 39.wav
│   │           │       ├── 40.wav
│   │           │       ├── 41.wav
│   │           │       ├── 42.wav
│   │           │       ├── 43.wav
│   │           │       ├── 44.wav
│   │           │       ├── 45.wav
│   │           │       ├── 46.wav
│   │           │       ├── 47.wav
│   │           │       ├── 58.wav
│   │           │       ├── 59.wav
│   │           │       ├── 60.wav
│   │           │       ├── 61.wav
│   │           │       ├── 62.wav
│   │           │       ├── 64.wav
│   │           │       ├── 91.wav
│   │           │       ├── 92.wav
│   │           │       ├── 93.wav
│   │           │       ├── 94.wav
│   │           │       ├── 95.wav
│   │           │       ├── 96.wav
│   │           │       ├── 97.wav
│   │           │       ├── 98.wav
│   │           │       └── 99.wav
│   │           ├── base256
│   │           │   ├── 16000
│   │           │   │   ├── aardvark.wav
│   │           │   │   ├── absurd.wav
│   │           │   │   ├── accrue.wav
│   │           │   │   ├── acme.wav
│   │           │   │   ├── adrift.wav
│   │           │   │   ├── adroitness.wav
│   │           │   │   ├── adult.wav
│   │           │   │   ├── adviser.wav
│   │           │   │   ├── afflict.wav
│   │           │   │   ├── aftermath.wav
│   │           │   │   ├── aggregate.wav
│   │           │   │   ├── ahead.wav
│   │           │   │   ├── aimless.wav
│   │           │   │   ├── Algol.wav
│   │           │   │   ├── alkali.wav
│   │           │   │   ├── allow.wav
│   │           │   │   ├── almighty.wav
│   │           │   │   ├── alone.wav
│   │           │   │   ├── ammo.wav
│   │           │   │   ├── amulet.wav
│   │           │   │   ├── amusement.wav
│   │           │   │   ├── ancient.wav
│   │           │   │   ├── antenna.wav
│   │           │   │   ├── Apollo.wav
│   │           │   │   ├── apple.wav
│   │           │   │   ├── applicant.wav
│   │           │   │   ├── armistice.wav
│   │           │   │   ├── article.wav
│   │           │   │   ├── artist.wav
│   │           │   │   ├── assume.wav
│   │           │   │   ├── asteroid.wav
│   │           │   │   ├── Athens.wav
│   │           │   │   ├── Atlantic.wav
│   │           │   │   ├── atlas.wav
│   │           │   │   ├── atmosphere.wav
│   │           │   │   ├── autopsy.wav
│   │           │   │   ├── Aztec.wav
│   │           │   │   ├── baboon.wav
│   │           │   │   ├── Babylon.wav
│   │           │   │   ├── backfield.wav
│   │           │   │   ├── backward.wav
│   │           │   │   ├── backwater.wav
│   │           │   │   ├── banjo.wav
│   │           │   │   ├── barbecue.wav
│   │           │   │   ├── beaming.wav
│   │           │   │   ├── bedlamp.wav
│   │           │   │   ├── beehive.wav
│   │           │   │   ├── beeswax.wav
│   │           │   │   ├── befriend.wav
│   │           │   │   ├── Belfast.wav
│   │           │   │   ├── belowground.wav
│   │           │   │   ├── berserk.wav
│   │           │   │   ├── bifocals.wav
│   │           │   │   ├── billiard.wav
│   │           │   │   ├── bison.wav
│   │           │   │   ├── blackjack.wav
│   │           │   │   ├── blockade.wav
│   │           │   │   ├── blowtorch.wav
│   │           │   │   ├── bluebird.wav
│   │           │   │   ├── bodyguard.wav
│   │           │   │   ├── bombast.wav
│   │           │   │   ├── bookseller.wav
│   │           │   │   ├── bookshelf.wav
│   │           │   │   ├── borderline.wav
│   │           │   │   ├── bottomless.wav
│   │           │   │   ├── brackish.wav
│   │           │   │   ├── Bradbury.wav
│   │           │   │   ├── bravado.wav
│   │           │   │   ├── Brazilian.wav
│   │           │   │   ├── breadline.wav
│   │           │   │   ├── breakaway.wav
│   │           │   │   ├── breakup.wav
│   │           │   │   ├── brickyard.wav
│   │           │   │   ├── briefcase.wav
│   │           │   │   ├── Burbank.wav
│   │           │   │   ├── Burlington.wav
│   │           │   │   ├── businessman.wav
│   │           │   │   ├── butterfat.wav
│   │           │   │   ├── button.wav
│   │           │   │   ├── buzzard.wav
│   │           │   │   ├── Camelot.wav
│   │           │   │   ├── candidate.wav
│   │           │   │   ├── cannonball.wav
│   │           │   │   ├── Capricorn.wav
│   │           │   │   ├── caravan.wav
│   │           │   │   ├── caretaker.wav
│   │           │   │   ├── celebrate.wav
│   │           │   │   ├── cellulose.wav
│   │           │   │   ├── cement.wav
│   │           │   │   ├── certify.wav
│   │           │   │   ├── chairlift.wav
│   │           │   │   ├── chambermaid.wav
│   │           │   │   ├── chatter.wav
│   │           │   │   ├── checkup.wav
│   │           │   │   ├── Cherokee.wav
│   │           │   │   ├── Chicago.wav
│   │           │   │   ├── chisel.wav
│   │           │   │   ├── choking.wav
│   │           │   │   ├── chopper.wav
│   │           │   │   ├── Christmas.wav
│   │           │   │   ├── clamshell.wav
│   │           │   │   ├── classic.wav
│   │           │   │   ├── classroom.wav
│   │           │   │   ├── cleanup.wav
│   │           │   │   ├── clergyman.wav
│   │           │   │   ├── clockwork.wav
│   │           │   │   ├── cobra.wav
│   │           │   │   ├── coherence.wav
│   │           │   │   ├── combustion.wav
│   │           │   │   ├── commando.wav
│   │           │   │   ├── commence.wav
│   │           │   │   ├── company.wav
│   │           │   │   ├── component.wav
│   │           │   │   ├── concert.wav
│   │           │   │   ├── concurrent.wav
│   │           │   │   ├── confidence.wav
│   │           │   │   ├── conformist.wav
│   │           │   │   ├── congregate.wav
│   │           │   │   ├── consensus.wav
│   │           │   │   ├── consulting.wav
│   │           │   │   ├── corporate.wav
│   │           │   │   ├── corrosion.wav
│   │           │   │   ├── councilman.wav
│   │           │   │   ├── cowbell.wav
│   │           │   │   ├── crackdown.wav
│   │           │   │   ├── cranky.wav
│   │           │   │   ├── crossover.wav
│   │           │   │   ├── crowfoot.wav
│   │           │   │   ├── crucial.wav
│   │           │   │   ├── crucifix.wav
│   │           │   │   ├── crumpled.wav
│   │           │   │   ├── crusade.wav
│   │           │   │   ├── cubic.wav
│   │           │   │   ├── cumbersome.wav
│   │           │   │   ├── customer.wav
│   │           │   │   ├── Dakota.wav
│   │           │   │   ├── dashboard.wav
│   │           │   │   ├── deadbolt.wav
│   │           │   │   ├── decadence.wav
│   │           │   │   ├── December.wav
│   │           │   │   ├── decimal.wav
│   │           │   │   ├── deckhand.wav
│   │           │   │   ├── designing.wav
│   │           │   │   ├── detector.wav
│   │           │   │   ├── detergent.wav
│   │           │   │   ├── determine.wav
│   │           │   │   ├── dictator.wav
│   │           │   │   ├── dinosaur.wav
│   │           │   │   ├── direction.wav
│   │           │   │   ├── disable.wav
│   │           │   │   ├── disbelief.wav
│   │           │   │   ├── disruptive.wav
│   │           │   │   ├── distortion.wav
│   │           │   │   ├── document.wav
│   │           │   │   ├── dogsled.wav
│   │           │   │   ├── dragnet.wav
│   │           │   │   ├── drainage.wav
│   │           │   │   ├── dreadful.wav
│   │           │   │   ├── drifter.wav
│   │           │   │   ├── dropper.wav
│   │           │   │   ├── drumbeat.wav
│   │           │   │   ├── drunken.wav
│   │           │   │   ├── Dupont.wav
│   │           │   │   ├── dwelling.wav
│   │           │   │   ├── eating.wav
│   │           │   │   ├── edict.wav
│   │           │   │   ├── egghead.wav
│   │           │   │   ├── eightball.wav
│   │           │   │   ├── embezzle.wav
│   │           │   │   ├── enchanting.wav
│   │           │   │   ├── endorse.wav
│   │           │   │   ├── endow.wav
│   │           │   │   ├── enlist.wav
│   │           │   │   ├── enrollment.wav
│   │           │   │   ├── enterprise.wav
│   │           │   │   ├── equation.wav
│   │           │   │   ├── equipment.wav
│   │           │   │   ├── erase.wav
│   │           │   │   ├── escapade.wav
│   │           │   │   ├── escape.wav
│   │           │   │   ├── Eskimo.wav
│   │           │   │   ├── everyday.wav
│   │           │   │   ├── examine.wav
│   │           │   │   ├── exceed.wav
│   │           │   │   ├── existence.wav
│   │           │   │   ├── exodus.wav
│   │           │   │   ├── eyeglass.wav
│   │           │   │   ├── eyetooth.wav
│   │           │   │   ├── facial.wav
│   │           │   │   ├── fallout.wav
│   │           │   │   ├── fascinate.wav
│   │           │   │   ├── filament.wav
│   │           │   │   ├── finicky.wav
│   │           │   │   ├── flagpole.wav
│   │           │   │   ├── flatfoot.wav
│   │           │   │   ├── flytrap.wav
│   │           │   │   ├── forever.wav
│   │           │   │   ├── fortitude.wav
│   │           │   │   ├── fracture.wav
│   │           │   │   ├── framework.wav
│   │           │   │   ├── freedom.wav
│   │           │   │   ├── frequency.wav
│   │           │   │   ├── frighten.wav
│   │           │   │   ├── gadgetry.wav
│   │           │   │   ├── Galveston.wav
│   │           │   │   ├── gazelle.wav
│   │           │   │   ├── Geiger.wav
│   │           │   │   ├── getaway.wav
│   │           │   │   ├── glitter.wav
│   │           │   │   ├── glossary.wav
│   │           │   │   ├── glucose.wav
│   │           │   │   ├── goggles.wav
│   │           │   │   ├── goldfish.wav
│   │           │   │   ├── gossamer.wav
│   │           │   │   ├── graduate.wav
│   │           │   │   ├── gravity.wav
│   │           │   │   ├── gremlin.wav
│   │           │   │   ├── guidance.wav
│   │           │   │   ├── guitarist.wav
│   │           │   │   ├── hamburger.wav
│   │           │   │   ├── Hamilton.wav
│   │           │   │   ├── hamlet.wav
│   │           │   │   ├── handiwork.wav
│   │           │   │   ├── hazardous.wav
│   │           │   │   ├── headwaters.wav
│   │           │   │   ├── hemisphere.wav
│   │           │   │   ├── hesitate.wav
│   │           │   │   ├── hideaway.wav
│   │           │   │   ├── highchair.wav
│   │           │   │   ├── hockey.wav
│   │           │   │   ├── holiness.wav
│   │           │   │   ├── hurricane.wav
│   │           │   │   ├── hydraulic.wav
│   │           │   │   ├── impartial.wav
│   │           │   │   ├── impetus.wav
│   │           │   │   ├── inception.wav
│   │           │   │   ├── indigo.wav
│   │           │   │   ├── indoors.wav
│   │           │   │   ├── indulge.wav
│   │           │   │   ├── inertia.wav
│   │           │   │   ├── infancy.wav
│   │           │   │   ├── inferno.wav
│   │           │   │   ├── informant.wav
│   │           │   │   ├── insincere.wav
│   │           │   │   ├── insurgent.wav
│   │           │   │   ├── integrate.wav
│   │           │   │   ├── intention.wav
│   │           │   │   ├── inventive.wav
│   │           │   │   ├── inverse.wav
│   │           │   │   ├── involve.wav
│   │           │   │   ├── island.wav
│   │           │   │   ├── Istanbul.wav
│   │           │   │   ├── Jamaica.wav
│   │           │   │   ├── jawbone.wav
│   │           │   │   ├── Jupiter.wav
│   │           │   │   ├── keyboard.wav
│   │           │   │   ├── kickoff.wav
│   │           │   │   ├── kiwi.wav
│   │           │   │   ├── klaxon.wav
│   │           │   │   ├── leprosy.wav
│   │           │   │   ├── letterhead.wav
│   │           │   │   ├── liberty.wav
│   │           │   │   ├── locale.wav
│   │           │   │   ├── lockup.wav
│   │           │   │   ├── maritime.wav
│   │           │   │   ├── matchmaker.wav
│   │           │   │   ├── maverick.wav
│   │           │   │   ├── Medusa.wav
│   │           │   │   ├── megaton.wav
│   │           │   │   ├── merit.wav
│   │           │   │   ├── microscope.wav
│   │           │   │   ├── microwave.wav
│   │           │   │   ├── midsummer.wav
│   │           │   │   ├── millionaire.wav
│   │           │   │   ├── minnow.wav
│   │           │   │   ├── miracle.wav
│   │           │   │   ├── miser.wav
│   │           │   │   ├── misnomer.wav
│   │           │   │   ├── Mohawk.wav
│   │           │   │   ├── molasses.wav
│   │           │   │   ├── molecule.wav
│   │           │   │   ├── Montana.wav
│   │           │   │   ├── monument.wav
│   │           │   │   ├── mosquito.wav
│   │           │   │   ├── mural.wav
│   │           │   │   ├── music.wav
│   │           │   │   ├── narrative.wav
│   │           │   │   ├── nebula.wav
│   │           │   │   ├── necklace.wav
│   │           │   │   ├── Neptune.wav
│   │           │   │   ├── newborn.wav
│   │           │   │   ├── newsletter.wav
│   │           │   │   ├── nightbird.wav
│   │           │   │   ├── Norwegian.wav
│   │           │   │   ├── Oakland.wav
│   │           │   │   ├── obtuse.wav
│   │           │   │   ├── October.wav
│   │           │   │   ├── offload.wav
│   │           │   │   ├── Ohio.wav
│   │           │   │   ├── onlooker.wav
│   │           │   │   ├── optic.wav
│   │           │   │   ├── opulent.wav
│   │           │   │   ├── orca.wav
│   │           │   │   ├── Orlando.wav
│   │           │   │   ├── outfielder.wav
│   │           │   │   ├── Pacific.wav
│   │           │   │   ├── pandemic.wav
│   │           │   │   ├── Pandora.wav
│   │           │   │   ├── paperweight.wav
│   │           │   │   ├── paragon.wav
│   │           │   │   ├── paragraph.wav
│   │           │   │   ├── paramount.wav
│   │           │   │   ├── passenger.wav
│   │           │   │   ├── payday.wav
│   │           │   │   ├── peachy.wav
│   │           │   │   ├── pedigree.wav
│   │           │   │   ├── Pegasus.wav
│   │           │   │   ├── penetrate.wav
│   │           │   │   ├── perceptive.wav
│   │           │   │   ├── performance.wav
│   │           │   │   ├── pharmacy.wav
│   │           │   │   ├── pheasant.wav
│   │           │   │   ├── phonetic.wav
│   │           │   │   ├── photograph.wav
│   │           │   │   ├── physique.wav
│   │           │   │   ├── pioneer.wav
│   │           │   │   ├── playhouse.wav
│   │           │   │   ├── Pluto.wav
│   │           │   │   ├── pocketful.wav
│   │           │   │   ├── politeness.wav
│   │           │   │   ├── positive.wav
│   │           │   │   ├── potato.wav
│   │           │   │   ├── preclude.wav
│   │           │   │   ├── prefer.wav
│   │           │   │   ├── preshrunk.wav
│   │           │   │   ├── printer.wav
│   │           │   │   ├── processor.wav
│   │           │   │   ├── provincial.wav
│   │           │   │   ├── prowler.wav
│   │           │   │   ├── proximate.wav
│   │           │   │   ├── puberty.wav
│   │           │   │   ├── publisher.wav
│   │           │   │   ├── pupil.wav
│   │           │   │   ├── puppy.wav
│   │           │   │   ├── pyramid.wav
│   │           │   │   ├── python.wav
│   │           │   │   ├── quadrant.wav
│   │           │   │   ├── quantity.wav
│   │           │   │   ├── quiver.wav
│   │           │   │   ├── quota.wav
│   │           │   │   ├── racketeer.wav
│   │           │   │   ├── ragtime.wav
│   │           │   │   ├── ratchet.wav
│   │           │   │   ├── rebellion.wav
│   │           │   │   ├── rebirth.wav
│   │           │   │   ├── recipe.wav
│   │           │   │   ├── recover.wav
│   │           │   │   ├── reform.wav
│   │           │   │   ├── regain.wav
│   │           │   │   ├── reindeer.wav
│   │           │   │   ├── rematch.wav
│   │           │   │   ├── repay.wav
│   │           │   │   ├── repellent.wav
│   │           │   │   ├── replica.wav
│   │           │   │   ├── reproduce.wav
│   │           │   │   ├── resistor.wav
│   │           │   │   ├── responsive.wav
│   │           │   │   ├── retouch.wav
│   │           │   │   ├── retraction.wav
│   │           │   │   ├── retrieval.wav
│   │           │   │   ├── retrospect.wav
│   │           │   │   ├── revenge.wav
│   │           │   │   ├── revenue.wav
│   │           │   │   ├── revival.wav
│   │           │   │   ├── revolver.wav
│   │           │   │   ├── reward.wav
│   │           │   │   ├── rhythm.wav
│   │           │   │   ├── ribcage.wav
│   │           │   │   ├── ringbolt.wav
│   │           │   │   ├── robust.wav
│   │           │   │   ├── rocker.wav
│   │           │   │   ├── ruffled.wav
│   │           │   │   ├── sailboat.wav
│   │           │   │   ├── sandalwood.wav
│   │           │   │   ├── sardonic.wav
│   │           │   │   ├── Saturday.wav
│   │           │   │   ├── savagery.wav
│   │           │   │   ├── sawdust.wav
│   │           │   │   ├── scallion.wav
│   │           │   │   ├── scavenger.wav
│   │           │   │   ├── scenic.wav
│   │           │   │   ├── scorecard.wav
│   │           │   │   ├── Scotland.wav
│   │           │   │   ├── seabird.wav
│   │           │   │   ├── select.wav
│   │           │   │   ├── sensation.wav
│   │           │   │   ├── sentence.wav
│   │           │   │   ├── shadow.wav
│   │           │   │   ├── shamrock.wav
│   │           │   │   ├── showgirl.wav
│   │           │   │   ├── skullcap.wav
│   │           │   │   ├── skydive.wav
│   │           │   │   ├── slingshot.wav
│   │           │   │   ├── slowdown.wav
│   │           │   │   ├── snapline.wav
│   │           │   │   ├── snapshot.wav
│   │           │   │   ├── snowcap.wav
│   │           │   │   ├── snowslide.wav
│   │           │   │   ├── sociable.wav
│   │           │   │   ├── solo.wav
│   │           │   │   ├── southward.wav
│   │           │   │   ├── souvenir.wav
│   │           │   │   ├── soybean.wav
│   │           │   │   ├── spaniel.wav
│   │           │   │   ├── spearhead.wav
│   │           │   │   ├── specialist.wav
│   │           │   │   ├── speculate.wav
│   │           │   │   ├── spellbind.wav
│   │           │   │   ├── spheroid.wav
│   │           │   │   ├── spigot.wav
│   │           │   │   ├── spindle.wav
│   │           │   │   ├── spyglass.wav
│   │           │   │   ├── stagehand.wav
│   │           │   │   ├── stagnate.wav
│   │           │   │   ├── stairway.wav
│   │           │   │   ├── standard.wav
│   │           │   │   ├── stapler.wav
│   │           │   │   ├── steamship.wav
│   │           │   │   ├── sterling.wav
│   │           │   │   ├── stethoscope.wav
│   │           │   │   ├── stockman.wav
│   │           │   │   ├── stopwatch.wav
│   │           │   │   ├── stormy.wav
│   │           │   │   ├── stupendous.wav
│   │           │   │   ├── sugar.wav
│   │           │   │   ├── supportive.wav
│   │           │   │   ├── surmount.wav
│   │           │   │   ├── surrender.wav
│   │           │   │   ├── suspense.wav
│   │           │   │   ├── suspicious.wav
│   │           │   │   ├── sweatband.wav
│   │           │   │   ├── swelter.wav
│   │           │   │   ├── sympathy.wav
│   │           │   │   ├── tactics.wav
│   │           │   │   ├── talon.wav
│   │           │   │   ├── tambourine.wav
│   │           │   │   ├── tapeworm.wav
│   │           │   │   ├── telephone.wav
│   │           │   │   ├── tempest.wav
│   │           │   │   ├── therapist.wav
│   │           │   │   ├── tiger.wav
│   │           │   │   ├── tissue.wav
│   │           │   │   ├── tobacco.wav
│   │           │   │   ├── tolerance.wav
│   │           │   │   ├── tomorrow.wav
│   │           │   │   ├── tonic.wav
│   │           │   │   ├── topmost.wav
│   │           │   │   ├── torpedo.wav
│   │           │   │   ├── tracker.wav
│   │           │   │   ├── tradition.wav
│   │           │   │   ├── transit.wav
│   │           │   │   ├── trauma.wav
│   │           │   │   ├── travesty.wav
│   │           │   │   ├── treadmill.wav
│   │           │   │   ├── Trojan.wav
│   │           │   │   ├── trombonist.wav
│   │           │   │   ├── trouble.wav
│   │           │   │   ├── truncated.wav
│   │           │   │   ├── tumor.wav
│   │           │   │   ├── tunnel.wav
│   │           │   │   ├── tycoon.wav
│   │           │   │   ├── typewriter.wav
│   │           │   │   ├── ultimate.wav
│   │           │   │   ├── uncut.wav
│   │           │   │   ├── undaunted.wav
│   │           │   │   ├── underfoot.wav
│   │           │   │   ├── unearth.wav
│   │           │   │   ├── unicorn.wav
│   │           │   │   ├── unify.wav
│   │           │   │   ├── universe.wav
│   │           │   │   ├── unravel.wav
│   │           │   │   ├── unwind.wav
│   │           │   │   ├── upcoming.wav
│   │           │   │   ├── uproot.wav
│   │           │   │   ├── upset.wav
│   │           │   │   ├── upshot.wav
│   │           │   │   ├── vacancy.wav
│   │           │   │   ├── vagabond.wav
│   │           │   │   ├── vapor.wav
│   │           │   │   ├── vertigo.wav
│   │           │   │   ├── village.wav
│   │           │   │   ├── Virginia.wav
│   │           │   │   ├── virus.wav
│   │           │   │   ├── visitor.wav
│   │           │   │   ├── vocalist.wav
│   │           │   │   ├── voyager.wav
│   │           │   │   ├── Vulcan.wav
│   │           │   │   ├── waffle.wav
│   │           │   │   ├── wallet.wav
│   │           │   │   ├── warranty.wav
│   │           │   │   ├── watchword.wav
│   │           │   │   ├── Waterloo.wav
│   │           │   │   ├── wayside.wav
│   │           │   │   ├── whimsical.wav
│   │           │   │   ├── Wichita.wav
│   │           │   │   ├── willow.wav
│   │           │   │   ├── Wilmington.wav
│   │           │   │   ├── woodlark.wav
│   │           │   │   ├── Wyoming.wav
│   │           │   │   ├── yesteryear.wav
│   │           │   │   ├── Yucatan.wav
│   │           │   │   └── Zulu.wav
│   │           │   ├── 32000
│   │           │   │   ├── aardvark.wav
│   │           │   │   ├── absurd.wav
│   │           │   │   ├── accrue.wav
│   │           │   │   ├── acme.wav
│   │           │   │   ├── adrift.wav
│   │           │   │   ├── adroitness.wav
│   │           │   │   ├── adult.wav
│   │           │   │   ├── adviser.wav
│   │           │   │   ├── afflict.wav
│   │           │   │   ├── aftermath.wav
│   │           │   │   ├── aggregate.wav
│   │           │   │   ├── ahead.wav
│   │           │   │   ├── aimless.wav
│   │           │   │   ├── Algol.wav
│   │           │   │   ├── alkali.wav
│   │           │   │   ├── allow.wav
│   │           │   │   ├── almighty.wav
│   │           │   │   ├── alone.wav
│   │           │   │   ├── ammo.wav
│   │           │   │   ├── amulet.wav
│   │           │   │   ├── amusement.wav
│   │           │   │   ├── ancient.wav
│   │           │   │   ├── antenna.wav
│   │           │   │   ├── Apollo.wav
│   │           │   │   ├── apple.wav
│   │           │   │   ├── applicant.wav
│   │           │   │   ├── armistice.wav
│   │           │   │   ├── article.wav
│   │           │   │   ├── artist.wav
│   │           │   │   ├── assume.wav
│   │           │   │   ├── asteroid.wav
│   │           │   │   ├── Athens.wav
│   │           │   │   ├── Atlantic.wav
│   │           │   │   ├── atlas.wav
│   │           │   │   ├── atmosphere.wav
│   │           │   │   ├── autopsy.wav
│   │           │   │   ├── Aztec.wav
│   │           │   │   ├── baboon.wav
│   │           │   │   ├── Babylon.wav
│   │           │   │   ├── backfield.wav
│   │           │   │   ├── backward.wav
│   │           │   │   ├── backwater.wav
│   │           │   │   ├── banjo.wav
│   │           │   │   ├── barbecue.wav
│   │           │   │   ├── beaming.wav
│   │           │   │   ├── bedlamp.wav
│   │           │   │   ├── beehive.wav
│   │           │   │   ├── beeswax.wav
│   │           │   │   ├── befriend.wav
│   │           │   │   ├── Belfast.wav
│   │           │   │   ├── belowground.wav
│   │           │   │   ├── berserk.wav
│   │           │   │   ├── bifocals.wav
│   │           │   │   ├── billiard.wav
│   │           │   │   ├── bison.wav
│   │           │   │   ├── blackjack.wav
│   │           │   │   ├── blockade.wav
│   │           │   │   ├── blowtorch.wav
│   │           │   │   ├── bluebird.wav
│   │           │   │   ├── bodyguard.wav
│   │           │   │   ├── bombast.wav
│   │           │   │   ├── bookseller.wav
│   │           │   │   ├── bookshelf.wav
│   │           │   │   ├── borderline.wav
│   │           │   │   ├── bottomless.wav
│   │           │   │   ├── brackish.wav
│   │           │   │   ├── Bradbury.wav
│   │           │   │   ├── bravado.wav
│   │           │   │   ├── Brazilian.wav
│   │           │   │   ├── breadline.wav
│   │           │   │   ├── breakaway.wav
│   │           │   │   ├── breakup.wav
│   │           │   │   ├── brickyard.wav
│   │           │   │   ├── briefcase.wav
│   │           │   │   ├── Burbank.wav
│   │           │   │   ├── Burlington.wav
│   │           │   │   ├── businessman.wav
│   │           │   │   ├── butterfat.wav
│   │           │   │   ├── button.wav
│   │           │   │   ├── buzzard.wav
│   │           │   │   ├── Camelot.wav
│   │           │   │   ├── candidate.wav
│   │           │   │   ├── cannonball.wav
│   │           │   │   ├── Capricorn.wav
│   │           │   │   ├── caravan.wav
│   │           │   │   ├── caretaker.wav
│   │           │   │   ├── celebrate.wav
│   │           │   │   ├── cellulose.wav
│   │           │   │   ├── cement.wav
│   │           │   │   ├── certify.wav
│   │           │   │   ├── chairlift.wav
│   │           │   │   ├── chambermaid.wav
│   │           │   │   ├── chatter.wav
│   │           │   │   ├── checkup.wav
│   │           │   │   ├── Cherokee.wav
│   │           │   │   ├── Chicago.wav
│   │           │   │   ├── chisel.wav
│   │           │   │   ├── choking.wav
│   │           │   │   ├── chopper.wav
│   │           │   │   ├── Christmas.wav
│   │           │   │   ├── clamshell.wav
│   │           │   │   ├── classic.wav
│   │           │   │   ├── classroom.wav
│   │           │   │   ├── cleanup.wav
│   │           │   │   ├── clergyman.wav
│   │           │   │   ├── clockwork.wav
│   │           │   │   ├── cobra.wav
│   │           │   │   ├── coherence.wav
│   │           │   │   ├── combustion.wav
│   │           │   │   ├── commando.wav
│   │           │   │   ├── commence.wav
│   │           │   │   ├── company.wav
│   │           │   │   ├── component.wav
│   │           │   │   ├── concert.wav
│   │           │   │   ├── concurrent.wav
│   │           │   │   ├── confidence.wav
│   │           │   │   ├── conformist.wav
│   │           │   │   ├── congregate.wav
│   │           │   │   ├── consensus.wav
│   │           │   │   ├── consulting.wav
│   │           │   │   ├── corporate.wav
│   │           │   │   ├── corrosion.wav
│   │           │   │   ├── councilman.wav
│   │           │   │   ├── cowbell.wav
│   │           │   │   ├── crackdown.wav
│   │           │   │   ├── cranky.wav
│   │           │   │   ├── crossover.wav
│   │           │   │   ├── crowfoot.wav
│   │           │   │   ├── crucial.wav
│   │           │   │   ├── crucifix.wav
│   │           │   │   ├── crumpled.wav
│   │           │   │   ├── crusade.wav
│   │           │   │   ├── cubic.wav
│   │           │   │   ├── cumbersome.wav
│   │           │   │   ├── customer.wav
│   │           │   │   ├── Dakota.wav
│   │           │   │   ├── dashboard.wav
│   │           │   │   ├── deadbolt.wav
│   │           │   │   ├── decadence.wav
│   │           │   │   ├── December.wav
│   │           │   │   ├── decimal.wav
│   │           │   │   ├── deckhand.wav
│   │           │   │   ├── designing.wav
│   │           │   │   ├── detector.wav
│   │           │   │   ├── detergent.wav
│   │           │   │   ├── determine.wav
│   │           │   │   ├── dictator.wav
│   │           │   │   ├── dinosaur.wav
│   │           │   │   ├── direction.wav
│   │           │   │   ├── disable.wav
│   │           │   │   ├── disbelief.wav
│   │           │   │   ├── disruptive.wav
│   │           │   │   ├── distortion.wav
│   │           │   │   ├── document.wav
│   │           │   │   ├── dogsled.wav
│   │           │   │   ├── dragnet.wav
│   │           │   │   ├── drainage.wav
│   │           │   │   ├── dreadful.wav
│   │           │   │   ├── drifter.wav
│   │           │   │   ├── dropper.wav
│   │           │   │   ├── drumbeat.wav
│   │           │   │   ├── drunken.wav
│   │           │   │   ├── Dupont.wav
│   │           │   │   ├── dwelling.wav
│   │           │   │   ├── eating.wav
│   │           │   │   ├── edict.wav
│   │           │   │   ├── egghead.wav
│   │           │   │   ├── eightball.wav
│   │           │   │   ├── embezzle.wav
│   │           │   │   ├── enchanting.wav
│   │           │   │   ├── endorse.wav
│   │           │   │   ├── endow.wav
│   │           │   │   ├── enlist.wav
│   │           │   │   ├── enrollment.wav
│   │           │   │   ├── enterprise.wav
│   │           │   │   ├── equation.wav
│   │           │   │   ├── equipment.wav
│   │           │   │   ├── erase.wav
│   │           │   │   ├── escapade.wav
│   │           │   │   ├── escape.wav
│   │           │   │   ├── Eskimo.wav
│   │           │   │   ├── everyday.wav
│   │           │   │   ├── examine.wav
│   │           │   │   ├── exceed.wav
│   │           │   │   ├── existence.wav
│   │           │   │   ├── exodus.wav
│   │           │   │   ├── eyeglass.wav
│   │           │   │   ├── eyetooth.wav
│   │           │   │   ├── facial.wav
│   │           │   │   ├── fallout.wav
│   │           │   │   ├── fascinate.wav
│   │           │   │   ├── filament.wav
│   │           │   │   ├── finicky.wav
│   │           │   │   ├── flagpole.wav
│   │           │   │   ├── flatfoot.wav
│   │           │   │   ├── flytrap.wav
│   │           │   │   ├── forever.wav
│   │           │   │   ├── fortitude.wav
│   │           │   │   ├── fracture.wav
│   │           │   │   ├── framework.wav
│   │           │   │   ├── freedom.wav
│   │           │   │   ├── frequency.wav
│   │           │   │   ├── frighten.wav
│   │           │   │   ├── gadgetry.wav
│   │           │   │   ├── Galveston.wav
│   │           │   │   ├── gazelle.wav
│   │           │   │   ├── Geiger.wav
│   │           │   │   ├── getaway.wav
│   │           │   │   ├── glitter.wav
│   │           │   │   ├── glossary.wav
│   │           │   │   ├── glucose.wav
│   │           │   │   ├── goggles.wav
│   │           │   │   ├── goldfish.wav
│   │           │   │   ├── gossamer.wav
│   │           │   │   ├── graduate.wav
│   │           │   │   ├── gravity.wav
│   │           │   │   ├── gremlin.wav
│   │           │   │   ├── guidance.wav
│   │           │   │   ├── guitarist.wav
│   │           │   │   ├── hamburger.wav
│   │           │   │   ├── Hamilton.wav
│   │           │   │   ├── hamlet.wav
│   │           │   │   ├── handiwork.wav
│   │           │   │   ├── hazardous.wav
│   │           │   │   ├── headwaters.wav
│   │           │   │   ├── hemisphere.wav
│   │           │   │   ├── hesitate.wav
│   │           │   │   ├── hideaway.wav
│   │           │   │   ├── highchair.wav
│   │           │   │   ├── hockey.wav
│   │           │   │   ├── holiness.wav
│   │           │   │   ├── hurricane.wav
│   │           │   │   ├── hydraulic.wav
│   │           │   │   ├── impartial.wav
│   │           │   │   ├── impetus.wav
│   │           │   │   ├── inception.wav
│   │           │   │   ├── indigo.wav
│   │           │   │   ├── indoors.wav
│   │           │   │   ├── indulge.wav
│   │           │   │   ├── inertia.wav
│   │           │   │   ├── infancy.wav
│   │           │   │   ├── inferno.wav
│   │           │   │   ├── informant.wav
│   │           │   │   ├── insincere.wav
│   │           │   │   ├── insurgent.wav
│   │           │   │   ├── integrate.wav
│   │           │   │   ├── intention.wav
│   │           │   │   ├── inventive.wav
│   │           │   │   ├── inverse.wav
│   │           │   │   ├── involve.wav
│   │           │   │   ├── island.wav
│   │           │   │   ├── Istanbul.wav
│   │           │   │   ├── Jamaica.wav
│   │           │   │   ├── jawbone.wav
│   │           │   │   ├── Jupiter.wav
│   │           │   │   ├── keyboard.wav
│   │           │   │   ├── kickoff.wav
│   │           │   │   ├── kiwi.wav
│   │           │   │   ├── klaxon.wav
│   │           │   │   ├── leprosy.wav
│   │           │   │   ├── letterhead.wav
│   │           │   │   ├── liberty.wav
│   │           │   │   ├── locale.wav
│   │           │   │   ├── lockup.wav
│   │           │   │   ├── maritime.wav
│   │           │   │   ├── matchmaker.wav
│   │           │   │   ├── maverick.wav
│   │           │   │   ├── Medusa.wav
│   │           │   │   ├── megaton.wav
│   │           │   │   ├── merit.wav
│   │           │   │   ├── microscope.wav
│   │           │   │   ├── microwave.wav
│   │           │   │   ├── midsummer.wav
│   │           │   │   ├── millionaire.wav
│   │           │   │   ├── minnow.wav
│   │           │   │   ├── miracle.wav
│   │           │   │   ├── miser.wav
│   │           │   │   ├── misnomer.wav
│   │           │   │   ├── Mohawk.wav
│   │           │   │   ├── molasses.wav
│   │           │   │   ├── molecule.wav
│   │           │   │   ├── Montana.wav
│   │           │   │   ├── monument.wav
│   │           │   │   ├── mosquito.wav
│   │           │   │   ├── mural.wav
│   │           │   │   ├── music.wav
│   │           │   │   ├── narrative.wav
│   │           │   │   ├── nebula.wav
│   │           │   │   ├── necklace.wav
│   │           │   │   ├── Neptune.wav
│   │           │   │   ├── newborn.wav
│   │           │   │   ├── newsletter.wav
│   │           │   │   ├── nightbird.wav
│   │           │   │   ├── Norwegian.wav
│   │           │   │   ├── Oakland.wav
│   │           │   │   ├── obtuse.wav
│   │           │   │   ├── October.wav
│   │           │   │   ├── offload.wav
│   │           │   │   ├── Ohio.wav
│   │           │   │   ├── onlooker.wav
│   │           │   │   ├── optic.wav
│   │           │   │   ├── opulent.wav
│   │           │   │   ├── orca.wav
│   │           │   │   ├── Orlando.wav
│   │           │   │   ├── outfielder.wav
│   │           │   │   ├── Pacific.wav
│   │           │   │   ├── pandemic.wav
│   │           │   │   ├── Pandora.wav
│   │           │   │   ├── paperweight.wav
│   │           │   │   ├── paragon.wav
│   │           │   │   ├── paragraph.wav
│   │           │   │   ├── paramount.wav
│   │           │   │   ├── passenger.wav
│   │           │   │   ├── payday.wav
│   │           │   │   ├── peachy.wav
│   │           │   │   ├── pedigree.wav
│   │           │   │   ├── Pegasus.wav
│   │           │   │   ├── penetrate.wav
│   │           │   │   ├── perceptive.wav
│   │           │   │   ├── performance.wav
│   │           │   │   ├── pharmacy.wav
│   │           │   │   ├── pheasant.wav
│   │           │   │   ├── phonetic.wav
│   │           │   │   ├── photograph.wav
│   │           │   │   ├── physique.wav
│   │           │   │   ├── pioneer.wav
│   │           │   │   ├── playhouse.wav
│   │           │   │   ├── Pluto.wav
│   │           │   │   ├── pocketful.wav
│   │           │   │   ├── politeness.wav
│   │           │   │   ├── positive.wav
│   │           │   │   ├── potato.wav
│   │           │   │   ├── preclude.wav
│   │           │   │   ├── prefer.wav
│   │           │   │   ├── preshrunk.wav
│   │           │   │   ├── printer.wav
│   │           │   │   ├── processor.wav
│   │           │   │   ├── provincial.wav
│   │           │   │   ├── prowler.wav
│   │           │   │   ├── proximate.wav
│   │           │   │   ├── puberty.wav
│   │           │   │   ├── publisher.wav
│   │           │   │   ├── pupil.wav
│   │           │   │   ├── puppy.wav
│   │           │   │   ├── pyramid.wav
│   │           │   │   ├── python.wav
│   │           │   │   ├── quadrant.wav
│   │           │   │   ├── quantity.wav
│   │           │   │   ├── quiver.wav
│   │           │   │   ├── quota.wav
│   │           │   │   ├── racketeer.wav
│   │           │   │   ├── ragtime.wav
│   │           │   │   ├── ratchet.wav
│   │           │   │   ├── rebellion.wav
│   │           │   │   ├── rebirth.wav
│   │           │   │   ├── recipe.wav
│   │           │   │   ├── recover.wav
│   │           │   │   ├── reform.wav
│   │           │   │   ├── regain.wav
│   │           │   │   ├── reindeer.wav
│   │           │   │   ├── rematch.wav
│   │           │   │   ├── repay.wav
│   │           │   │   ├── repellent.wav
│   │           │   │   ├── replica.wav
│   │           │   │   ├── reproduce.wav
│   │           │   │   ├── resistor.wav
│   │           │   │   ├── responsive.wav
│   │           │   │   ├── retouch.wav
│   │           │   │   ├── retraction.wav
│   │           │   │   ├── retrieval.wav
│   │           │   │   ├── retrospect.wav
│   │           │   │   ├── revenge.wav
│   │           │   │   ├── revenue.wav
│   │           │   │   ├── revival.wav
│   │           │   │   ├── revolver.wav
│   │           │   │   ├── reward.wav
│   │           │   │   ├── rhythm.wav
│   │           │   │   ├── ribcage.wav
│   │           │   │   ├── ringbolt.wav
│   │           │   │   ├── robust.wav
│   │           │   │   ├── rocker.wav
│   │           │   │   ├── ruffled.wav
│   │           │   │   ├── sailboat.wav
│   │           │   │   ├── sandalwood.wav
│   │           │   │   ├── sardonic.wav
│   │           │   │   ├── Saturday.wav
│   │           │   │   ├── savagery.wav
│   │           │   │   ├── sawdust.wav
│   │           │   │   ├── scallion.wav
│   │           │   │   ├── scavenger.wav
│   │           │   │   ├── scenic.wav
│   │           │   │   ├── scorecard.wav
│   │           │   │   ├── Scotland.wav
│   │           │   │   ├── seabird.wav
│   │           │   │   ├── select.wav
│   │           │   │   ├── sensation.wav
│   │           │   │   ├── sentence.wav
│   │           │   │   ├── shadow.wav
│   │           │   │   ├── shamrock.wav
│   │           │   │   ├── showgirl.wav
│   │           │   │   ├── skullcap.wav
│   │           │   │   ├── skydive.wav
│   │           │   │   ├── slingshot.wav
│   │           │   │   ├── slowdown.wav
│   │           │   │   ├── snapline.wav
│   │           │   │   ├── snapshot.wav
│   │           │   │   ├── snowcap.wav
│   │           │   │   ├── snowslide.wav
│   │           │   │   ├── sociable.wav
│   │           │   │   ├── solo.wav
│   │           │   │   ├── southward.wav
│   │           │   │   ├── souvenir.wav
│   │           │   │   ├── soybean.wav
│   │           │   │   ├── spaniel.wav
│   │           │   │   ├── spearhead.wav
│   │           │   │   ├── specialist.wav
│   │           │   │   ├── speculate.wav
│   │           │   │   ├── spellbind.wav
│   │           │   │   ├── spheroid.wav
│   │           │   │   ├── spigot.wav
│   │           │   │   ├── spindle.wav
│   │           │   │   ├── spyglass.wav
│   │           │   │   ├── stagehand.wav
│   │           │   │   ├── stagnate.wav
│   │           │   │   ├── stairway.wav
│   │           │   │   ├── standard.wav
│   │           │   │   ├── stapler.wav
│   │           │   │   ├── steamship.wav
│   │           │   │   ├── sterling.wav
│   │           │   │   ├── stethoscope.wav
│   │           │   │   ├── stockman.wav
│   │           │   │   ├── stopwatch.wav
│   │           │   │   ├── stormy.wav
│   │           │   │   ├── stupendous.wav
│   │           │   │   ├── sugar.wav
│   │           │   │   ├── supportive.wav
│   │           │   │   ├── surmount.wav
│   │           │   │   ├── surrender.wav
│   │           │   │   ├── suspense.wav
│   │           │   │   ├── suspicious.wav
│   │           │   │   ├── sweatband.wav
│   │           │   │   ├── swelter.wav
│   │           │   │   ├── sympathy.wav
│   │           │   │   ├── tactics.wav
│   │           │   │   ├── talon.wav
│   │           │   │   ├── tambourine.wav
│   │           │   │   ├── tapeworm.wav
│   │           │   │   ├── telephone.wav
│   │           │   │   ├── tempest.wav
│   │           │   │   ├── therapist.wav
│   │           │   │   ├── tiger.wav
│   │           │   │   ├── tissue.wav
│   │           │   │   ├── tobacco.wav
│   │           │   │   ├── tolerance.wav
│   │           │   │   ├── tomorrow.wav
│   │           │   │   ├── tonic.wav
│   │           │   │   ├── topmost.wav
│   │           │   │   ├── torpedo.wav
│   │           │   │   ├── tracker.wav
│   │           │   │   ├── tradition.wav
│   │           │   │   ├── transit.wav
│   │           │   │   ├── trauma.wav
│   │           │   │   ├── travesty.wav
│   │           │   │   ├── treadmill.wav
│   │           │   │   ├── Trojan.wav
│   │           │   │   ├── trombonist.wav
│   │           │   │   ├── trouble.wav
│   │           │   │   ├── truncated.wav
│   │           │   │   ├── tumor.wav
│   │           │   │   ├── tunnel.wav
│   │           │   │   ├── tycoon.wav
│   │           │   │   ├── typewriter.wav
│   │           │   │   ├── ultimate.wav
│   │           │   │   ├── uncut.wav
│   │           │   │   ├── undaunted.wav
│   │           │   │   ├── underfoot.wav
│   │           │   │   ├── unearth.wav
│   │           │   │   ├── unicorn.wav
│   │           │   │   ├── unify.wav
│   │           │   │   ├── universe.wav
│   │           │   │   ├── unravel.wav
│   │           │   │   ├── unwind.wav
│   │           │   │   ├── upcoming.wav
│   │           │   │   ├── uproot.wav
│   │           │   │   ├── upset.wav
│   │           │   │   ├── upshot.wav
│   │           │   │   ├── vacancy.wav
│   │           │   │   ├── vagabond.wav
│   │           │   │   ├── vapor.wav
│   │           │   │   ├── vertigo.wav
│   │           │   │   ├── village.wav
│   │           │   │   ├── Virginia.wav
│   │           │   │   ├── virus.wav
│   │           │   │   ├── visitor.wav
│   │           │   │   ├── vocalist.wav
│   │           │   │   ├── voyager.wav
│   │           │   │   ├── Vulcan.wav
│   │           │   │   ├── waffle.wav
│   │           │   │   ├── wallet.wav
│   │           │   │   ├── warranty.wav
│   │           │   │   ├── watchword.wav
│   │           │   │   ├── Waterloo.wav
│   │           │   │   ├── wayside.wav
│   │           │   │   ├── whimsical.wav
│   │           │   │   ├── Wichita.wav
│   │           │   │   ├── willow.wav
│   │           │   │   ├── Wilmington.wav
│   │           │   │   ├── woodlark.wav
│   │           │   │   ├── Wyoming.wav
│   │           │   │   ├── yesteryear.wav
│   │           │   │   ├── Yucatan.wav
│   │           │   │   └── Zulu.wav
│   │           │   ├── 48000
│   │           │   │   ├── aardvark.wav
│   │           │   │   ├── absurd.wav
│   │           │   │   ├── accrue.wav
│   │           │   │   ├── acme.wav
│   │           │   │   ├── adrift.wav
│   │           │   │   ├── adroitness.wav
│   │           │   │   ├── adult.wav
│   │           │   │   ├── adviser.wav
│   │           │   │   ├── afflict.wav
│   │           │   │   ├── aftermath.wav
│   │           │   │   ├── aggregate.wav
│   │           │   │   ├── ahead.wav
│   │           │   │   ├── aimless.wav
│   │           │   │   ├── Algol.wav
│   │           │   │   ├── alkali.wav
│   │           │   │   ├── allow.wav
│   │           │   │   ├── almighty.wav
│   │           │   │   ├── alone.wav
│   │           │   │   ├── ammo.wav
│   │           │   │   ├── amulet.wav
│   │           │   │   ├── amusement.wav
│   │           │   │   ├── ancient.wav
│   │           │   │   ├── antenna.wav
│   │           │   │   ├── Apollo.wav
│   │           │   │   ├── apple.wav
│   │           │   │   ├── applicant.wav
│   │           │   │   ├── armistice.wav
│   │           │   │   ├── article.wav
│   │           │   │   ├── artist.wav
│   │           │   │   ├── assume.wav
│   │           │   │   ├── asteroid.wav
│   │           │   │   ├── Athens.wav
│   │           │   │   ├── Atlantic.wav
│   │           │   │   ├── atlas.wav
│   │           │   │   ├── atmosphere.wav
│   │           │   │   ├── autopsy.wav
│   │           │   │   ├── Aztec.wav
│   │           │   │   ├── baboon.wav
│   │           │   │   ├── Babylon.wav
│   │           │   │   ├── backfield.wav
│   │           │   │   ├── backward.wav
│   │           │   │   ├── backwater.wav
│   │           │   │   ├── banjo.wav
│   │           │   │   ├── barbecue.wav
│   │           │   │   ├── beaming.wav
│   │           │   │   ├── bedlamp.wav
│   │           │   │   ├── beehive.wav
│   │           │   │   ├── beeswax.wav
│   │           │   │   ├── befriend.wav
│   │           │   │   ├── Belfast.wav
│   │           │   │   ├── belowground.wav
│   │           │   │   ├── berserk.wav
│   │           │   │   ├── bifocals.wav
│   │           │   │   ├── billiard.wav
│   │           │   │   ├── bison.wav
│   │           │   │   ├── blackjack.wav
│   │           │   │   ├── blockade.wav
│   │           │   │   ├── blowtorch.wav
│   │           │   │   ├── bluebird.wav
│   │           │   │   ├── bodyguard.wav
│   │           │   │   ├── bombast.wav
│   │           │   │   ├── bookseller.wav
│   │           │   │   ├── bookshelf.wav
│   │           │   │   ├── borderline.wav
│   │           │   │   ├── bottomless.wav
│   │           │   │   ├── brackish.wav
│   │           │   │   ├── Bradbury.wav
│   │           │   │   ├── bravado.wav
│   │           │   │   ├── Brazilian.wav
│   │           │   │   ├── breadline.wav
│   │           │   │   ├── breakaway.wav
│   │           │   │   ├── breakup.wav
│   │           │   │   ├── brickyard.wav
│   │           │   │   ├── briefcase.wav
│   │           │   │   ├── Burbank.wav
│   │           │   │   ├── Burlington.wav
│   │           │   │   ├── businessman.wav
│   │           │   │   ├── butterfat.wav
│   │           │   │   ├── button.wav
│   │           │   │   ├── buzzard.wav
│   │           │   │   ├── Camelot.wav
│   │           │   │   ├── candidate.wav
│   │           │   │   ├── cannonball.wav
│   │           │   │   ├── Capricorn.wav
│   │           │   │   ├── caravan.wav
│   │           │   │   ├── caretaker.wav
│   │           │   │   ├── celebrate.wav
│   │           │   │   ├── cellulose.wav
│   │           │   │   ├── cement.wav
│   │           │   │   ├── certify.wav
│   │           │   │   ├── chairlift.wav
│   │           │   │   ├── chambermaid.wav
│   │           │   │   ├── chatter.wav
│   │           │   │   ├── checkup.wav
│   │           │   │   ├── Cherokee.wav
│   │           │   │   ├── Chicago.wav
│   │           │   │   ├── chisel.wav
│   │           │   │   ├── choking.wav
│   │           │   │   ├── chopper.wav
│   │           │   │   ├── Christmas.wav
│   │           │   │   ├── clamshell.wav
│   │           │   │   ├── classic.wav
│   │           │   │   ├── classroom.wav
│   │           │   │   ├── cleanup.wav
│   │           │   │   ├── clergyman.wav
│   │           │   │   ├── clockwork.wav
│   │           │   │   ├── cobra.wav
│   │           │   │   ├── coherence.wav
│   │           │   │   ├── combustion.wav
│   │           │   │   ├── commando.wav
│   │           │   │   ├── commence.wav
│   │           │   │   ├── company.wav
│   │           │   │   ├── component.wav
│   │           │   │   ├── concert.wav
│   │           │   │   ├── concurrent.wav
│   │           │   │   ├── confidence.wav
│   │           │   │   ├── conformist.wav
│   │           │   │   ├── congregate.wav
│   │           │   │   ├── consensus.wav
│   │           │   │   ├── consulting.wav
│   │           │   │   ├── corporate.wav
│   │           │   │   ├── corrosion.wav
│   │           │   │   ├── councilman.wav
│   │           │   │   ├── cowbell.wav
│   │           │   │   ├── crackdown.wav
│   │           │   │   ├── cranky.wav
│   │           │   │   ├── crossover.wav
│   │           │   │   ├── crowfoot.wav
│   │           │   │   ├── crucial.wav
│   │           │   │   ├── crucifix.wav
│   │           │   │   ├── crumpled.wav
│   │           │   │   ├── crusade.wav
│   │           │   │   ├── cubic.wav
│   │           │   │   ├── cumbersome.wav
│   │           │   │   ├── customer.wav
│   │           │   │   ├── Dakota.wav
│   │           │   │   ├── dashboard.wav
│   │           │   │   ├── deadbolt.wav
│   │           │   │   ├── decadence.wav
│   │           │   │   ├── December.wav
│   │           │   │   ├── decimal.wav
│   │           │   │   ├── deckhand.wav
│   │           │   │   ├── designing.wav
│   │           │   │   ├── detector.wav
│   │           │   │   ├── detergent.wav
│   │           │   │   ├── determine.wav
│   │           │   │   ├── dictator.wav
│   │           │   │   ├── dinosaur.wav
│   │           │   │   ├── direction.wav
│   │           │   │   ├── disable.wav
│   │           │   │   ├── disbelief.wav
│   │           │   │   ├── disruptive.wav
│   │           │   │   ├── distortion.wav
│   │           │   │   ├── document.wav
│   │           │   │   ├── dogsled.wav
│   │           │   │   ├── dragnet.wav
│   │           │   │   ├── drainage.wav
│   │           │   │   ├── dreadful.wav
│   │           │   │   ├── drifter.wav
│   │           │   │   ├── dropper.wav
│   │           │   │   ├── drumbeat.wav
│   │           │   │   ├── drunken.wav
│   │           │   │   ├── Dupont.wav
│   │           │   │   ├── dwelling.wav
│   │           │   │   ├── eating.wav
│   │           │   │   ├── edict.wav
│   │           │   │   ├── egghead.wav
│   │           │   │   ├── eightball.wav
│   │           │   │   ├── embezzle.wav
│   │           │   │   ├── enchanting.wav
│   │           │   │   ├── endorse.wav
│   │           │   │   ├── endow.wav
│   │           │   │   ├── enlist.wav
│   │           │   │   ├── enrollment.wav
│   │           │   │   ├── enterprise.wav
│   │           │   │   ├── equation.wav
│   │           │   │   ├── equipment.wav
│   │           │   │   ├── erase.wav
│   │           │   │   ├── escapade.wav
│   │           │   │   ├── escape.wav
│   │           │   │   ├── Eskimo.wav
│   │           │   │   ├── everyday.wav
│   │           │   │   ├── examine.wav
│   │           │   │   ├── exceed.wav
│   │           │   │   ├── existence.wav
│   │           │   │   ├── exodus.wav
│   │           │   │   ├── eyeglass.wav
│   │           │   │   ├── eyetooth.wav
│   │           │   │   ├── facial.wav
│   │           │   │   ├── fallout.wav
│   │           │   │   ├── fascinate.wav
│   │           │   │   ├── filament.wav
│   │           │   │   ├── finicky.wav
│   │           │   │   ├── flagpole.wav
│   │           │   │   ├── flatfoot.wav
│   │           │   │   ├── flytrap.wav
│   │           │   │   ├── forever.wav
│   │           │   │   ├── fortitude.wav
│   │           │   │   ├── fracture.wav
│   │           │   │   ├── framework.wav
│   │           │   │   ├── freedom.wav
│   │           │   │   ├── frequency.wav
│   │           │   │   ├── frighten.wav
│   │           │   │   ├── gadgetry.wav
│   │           │   │   ├── Galveston.wav
│   │           │   │   ├── gazelle.wav
│   │           │   │   ├── Geiger.wav
│   │           │   │   ├── getaway.wav
│   │           │   │   ├── glitter.wav
│   │           │   │   ├── glossary.wav
│   │           │   │   ├── glucose.wav
│   │           │   │   ├── goggles.wav
│   │           │   │   ├── goldfish.wav
│   │           │   │   ├── gossamer.wav
│   │           │   │   ├── graduate.wav
│   │           │   │   ├── gravity.wav
│   │           │   │   ├── gremlin.wav
│   │           │   │   ├── guidance.wav
│   │           │   │   ├── guitarist.wav
│   │           │   │   ├── hamburger.wav
│   │           │   │   ├── Hamilton.wav
│   │           │   │   ├── hamlet.wav
│   │           │   │   ├── handiwork.wav
│   │           │   │   ├── hazardous.wav
│   │           │   │   ├── headwaters.wav
│   │           │   │   ├── hemisphere.wav
│   │           │   │   ├── hesitate.wav
│   │           │   │   ├── hideaway.wav
│   │           │   │   ├── highchair.wav
│   │           │   │   ├── hockey.wav
│   │           │   │   ├── holiness.wav
│   │           │   │   ├── hurricane.wav
│   │           │   │   ├── hydraulic.wav
│   │           │   │   ├── impartial.wav
│   │           │   │   ├── impetus.wav
│   │           │   │   ├── inception.wav
│   │           │   │   ├── indigo.wav
│   │           │   │   ├── indoors.wav
│   │           │   │   ├── indulge.wav
│   │           │   │   ├── inertia.wav
│   │           │   │   ├── infancy.wav
│   │           │   │   ├── inferno.wav
│   │           │   │   ├── informant.wav
│   │           │   │   ├── insincere.wav
│   │           │   │   ├── insurgent.wav
│   │           │   │   ├── integrate.wav
│   │           │   │   ├── intention.wav
│   │           │   │   ├── inventive.wav
│   │           │   │   ├── inverse.wav
│   │           │   │   ├── involve.wav
│   │           │   │   ├── island.wav
│   │           │   │   ├── Istanbul.wav
│   │           │   │   ├── Jamaica.wav
│   │           │   │   ├── jawbone.wav
│   │           │   │   ├── Jupiter.wav
│   │           │   │   ├── keyboard.wav
│   │           │   │   ├── kickoff.wav
│   │           │   │   ├── kiwi.wav
│   │           │   │   ├── klaxon.wav
│   │           │   │   ├── leprosy.wav
│   │           │   │   ├── letterhead.wav
│   │           │   │   ├── liberty.wav
│   │           │   │   ├── locale.wav
│   │           │   │   ├── lockup.wav
│   │           │   │   ├── maritime.wav
│   │           │   │   ├── matchmaker.wav
│   │           │   │   ├── maverick.wav
│   │           │   │   ├── Medusa.wav
│   │           │   │   ├── megaton.wav
│   │           │   │   ├── merit.wav
│   │           │   │   ├── microscope.wav
│   │           │   │   ├── microwave.wav
│   │           │   │   ├── midsummer.wav
│   │           │   │   ├── millionaire.wav
│   │           │   │   ├── minnow.wav
│   │           │   │   ├── miracle.wav
│   │           │   │   ├── miser.wav
│   │           │   │   ├── misnomer.wav
│   │           │   │   ├── Mohawk.wav
│   │           │   │   ├── molasses.wav
│   │           │   │   ├── molecule.wav
│   │           │   │   ├── Montana.wav
│   │           │   │   ├── monument.wav
│   │           │   │   ├── mosquito.wav
│   │           │   │   ├── mural.wav
│   │           │   │   ├── music.wav
│   │           │   │   ├── narrative.wav
│   │           │   │   ├── nebula.wav
│   │           │   │   ├── necklace.wav
│   │           │   │   ├── Neptune.wav
│   │           │   │   ├── newborn.wav
│   │           │   │   ├── newsletter.wav
│   │           │   │   ├── nightbird.wav
│   │           │   │   ├── Norwegian.wav
│   │           │   │   ├── Oakland.wav
│   │           │   │   ├── obtuse.wav
│   │           │   │   ├── October.wav
│   │           │   │   ├── offload.wav
│   │           │   │   ├── Ohio.wav
│   │           │   │   ├── onlooker.wav
│   │           │   │   ├── optic.wav
│   │           │   │   ├── opulent.wav
│   │           │   │   ├── orca.wav
│   │           │   │   ├── Orlando.wav
│   │           │   │   ├── outfielder.wav
│   │           │   │   ├── Pacific.wav
│   │           │   │   ├── pandemic.wav
│   │           │   │   ├── Pandora.wav
│   │           │   │   ├── paperweight.wav
│   │           │   │   ├── paragon.wav
│   │           │   │   ├── paragraph.wav
│   │           │   │   ├── paramount.wav
│   │           │   │   ├── passenger.wav
│   │           │   │   ├── payday.wav
│   │           │   │   ├── peachy.wav
│   │           │   │   ├── pedigree.wav
│   │           │   │   ├── Pegasus.wav
│   │           │   │   ├── penetrate.wav
│   │           │   │   ├── perceptive.wav
│   │           │   │   ├── performance.wav
│   │           │   │   ├── pharmacy.wav
│   │           │   │   ├── pheasant.wav
│   │           │   │   ├── phonetic.wav
│   │           │   │   ├── photograph.wav
│   │           │   │   ├── physique.wav
│   │           │   │   ├── pioneer.wav
│   │           │   │   ├── playhouse.wav
│   │           │   │   ├── Pluto.wav
│   │           │   │   ├── pocketful.wav
│   │           │   │   ├── politeness.wav
│   │           │   │   ├── positive.wav
│   │           │   │   ├── potato.wav
│   │           │   │   ├── preclude.wav
│   │           │   │   ├── prefer.wav
│   │           │   │   ├── preshrunk.wav
│   │           │   │   ├── printer.wav
│   │           │   │   ├── processor.wav
│   │           │   │   ├── provincial.wav
│   │           │   │   ├── prowler.wav
│   │           │   │   ├── proximate.wav
│   │           │   │   ├── puberty.wav
│   │           │   │   ├── publisher.wav
│   │           │   │   ├── pupil.wav
│   │           │   │   ├── puppy.wav
│   │           │   │   ├── pyramid.wav
│   │           │   │   ├── python.wav
│   │           │   │   ├── quadrant.wav
│   │           │   │   ├── quantity.wav
│   │           │   │   ├── quiver.wav
│   │           │   │   ├── quota.wav
│   │           │   │   ├── racketeer.wav
│   │           │   │   ├── ragtime.wav
│   │           │   │   ├── ratchet.wav
│   │           │   │   ├── rebellion.wav
│   │           │   │   ├── rebirth.wav
│   │           │   │   ├── recipe.wav
│   │           │   │   ├── recover.wav
│   │           │   │   ├── reform.wav
│   │           │   │   ├── regain.wav
│   │           │   │   ├── reindeer.wav
│   │           │   │   ├── rematch.wav
│   │           │   │   ├── repay.wav
│   │           │   │   ├── repellent.wav
│   │           │   │   ├── replica.wav
│   │           │   │   ├── reproduce.wav
│   │           │   │   ├── resistor.wav
│   │           │   │   ├── responsive.wav
│   │           │   │   ├── retouch.wav
│   │           │   │   ├── retraction.wav
│   │           │   │   ├── retrieval.wav
│   │           │   │   ├── retrospect.wav
│   │           │   │   ├── revenge.wav
│   │           │   │   ├── revenue.wav
│   │           │   │   ├── revival.wav
│   │           │   │   ├── revolver.wav
│   │           │   │   ├── reward.wav
│   │           │   │   ├── rhythm.wav
│   │           │   │   ├── ribcage.wav
│   │           │   │   ├── ringbolt.wav
│   │           │   │   ├── robust.wav
│   │           │   │   ├── rocker.wav
│   │           │   │   ├── ruffled.wav
│   │           │   │   ├── sailboat.wav
│   │           │   │   ├── sandalwood.wav
│   │           │   │   ├── sardonic.wav
│   │           │   │   ├── Saturday.wav
│   │           │   │   ├── savagery.wav
│   │           │   │   ├── sawdust.wav
│   │           │   │   ├── scallion.wav
│   │           │   │   ├── scavenger.wav
│   │           │   │   ├── scenic.wav
│   │           │   │   ├── scorecard.wav
│   │           │   │   ├── Scotland.wav
│   │           │   │   ├── seabird.wav
│   │           │   │   ├── select.wav
│   │           │   │   ├── sensation.wav
│   │           │   │   ├── sentence.wav
│   │           │   │   ├── shadow.wav
│   │           │   │   ├── shamrock.wav
│   │           │   │   ├── showgirl.wav
│   │           │   │   ├── skullcap.wav
│   │           │   │   ├── skydive.wav
│   │           │   │   ├── slingshot.wav
│   │           │   │   ├── slowdown.wav
│   │           │   │   ├── snapline.wav
│   │           │   │   ├── snapshot.wav
│   │           │   │   ├── snowcap.wav
│   │           │   │   ├── snowslide.wav
│   │           │   │   ├── sociable.wav
│   │           │   │   ├── solo.wav
│   │           │   │   ├── southward.wav
│   │           │   │   ├── souvenir.wav
│   │           │   │   ├── soybean.wav
│   │           │   │   ├── spaniel.wav
│   │           │   │   ├── spearhead.wav
│   │           │   │   ├── specialist.wav
│   │           │   │   ├── speculate.wav
│   │           │   │   ├── spellbind.wav
│   │           │   │   ├── spheroid.wav
│   │           │   │   ├── spigot.wav
│   │           │   │   ├── spindle.wav
│   │           │   │   ├── spyglass.wav
│   │           │   │   ├── stagehand.wav
│   │           │   │   ├── stagnate.wav
│   │           │   │   ├── stairway.wav
│   │           │   │   ├── standard.wav
│   │           │   │   ├── stapler.wav
│   │           │   │   ├── steamship.wav
│   │           │   │   ├── sterling.wav
│   │           │   │   ├── stethoscope.wav
│   │           │   │   ├── stockman.wav
│   │           │   │   ├── stopwatch.wav
│   │           │   │   ├── stormy.wav
│   │           │   │   ├── stupendous.wav
│   │           │   │   ├── sugar.wav
│   │           │   │   ├── supportive.wav
│   │           │   │   ├── surmount.wav
│   │           │   │   ├── surrender.wav
│   │           │   │   ├── suspense.wav
│   │           │   │   ├── suspicious.wav
│   │           │   │   ├── sweatband.wav
│   │           │   │   ├── swelter.wav
│   │           │   │   ├── sympathy.wav
│   │           │   │   ├── tactics.wav
│   │           │   │   ├── talon.wav
│   │           │   │   ├── tambourine.wav
│   │           │   │   ├── tapeworm.wav
│   │           │   │   ├── telephone.wav
│   │           │   │   ├── tempest.wav
│   │           │   │   ├── therapist.wav
│   │           │   │   ├── tiger.wav
│   │           │   │   ├── tissue.wav
│   │           │   │   ├── tobacco.wav
│   │           │   │   ├── tolerance.wav
│   │           │   │   ├── tomorrow.wav
│   │           │   │   ├── tonic.wav
│   │           │   │   ├── topmost.wav
│   │           │   │   ├── torpedo.wav
│   │           │   │   ├── tracker.wav
│   │           │   │   ├── tradition.wav
│   │           │   │   ├── transit.wav
│   │           │   │   ├── trauma.wav
│   │           │   │   ├── travesty.wav
│   │           │   │   ├── treadmill.wav
│   │           │   │   ├── Trojan.wav
│   │           │   │   ├── trombonist.wav
│   │           │   │   ├── trouble.wav
│   │           │   │   ├── truncated.wav
│   │           │   │   ├── tumor.wav
│   │           │   │   ├── tunnel.wav
│   │           │   │   ├── tycoon.wav
│   │           │   │   ├── typewriter.wav
│   │           │   │   ├── ultimate.wav
│   │           │   │   ├── uncut.wav
│   │           │   │   ├── undaunted.wav
│   │           │   │   ├── underfoot.wav
│   │           │   │   ├── unearth.wav
│   │           │   │   ├── unicorn.wav
│   │           │   │   ├── unify.wav
│   │           │   │   ├── universe.wav
│   │           │   │   ├── unravel.wav
│   │           │   │   ├── unwind.wav
│   │           │   │   ├── upcoming.wav
│   │           │   │   ├── uproot.wav
│   │           │   │   ├── upset.wav
│   │           │   │   ├── upshot.wav
│   │           │   │   ├── vacancy.wav
│   │           │   │   ├── vagabond.wav
│   │           │   │   ├── vapor.wav
│   │           │   │   ├── vertigo.wav
│   │           │   │   ├── village.wav
│   │           │   │   ├── Virginia.wav
│   │           │   │   ├── virus.wav
│   │           │   │   ├── visitor.wav
│   │           │   │   ├── vocalist.wav
│   │           │   │   ├── voyager.wav
│   │           │   │   ├── Vulcan.wav
│   │           │   │   ├── waffle.wav
│   │           │   │   ├── wallet.wav
│   │           │   │   ├── warranty.wav
│   │           │   │   ├── watchword.wav
│   │           │   │   ├── Waterloo.wav
│   │           │   │   ├── wayside.wav
│   │           │   │   ├── whimsical.wav
│   │           │   │   ├── Wichita.wav
│   │           │   │   ├── willow.wav
│   │           │   │   ├── Wilmington.wav
│   │           │   │   ├── woodlark.wav
│   │           │   │   ├── Wyoming.wav
│   │           │   │   ├── yesteryear.wav
│   │           │   │   ├── Yucatan.wav
│   │           │   │   └── Zulu.wav
│   │           │   └── 8000
│   │           │       ├── aardvark.wav
│   │           │       ├── absurd.wav
│   │           │       ├── accrue.wav
│   │           │       ├── acme.wav
│   │           │       ├── adrift.wav
│   │           │       ├── adroitness.wav
│   │           │       ├── adult.wav
│   │           │       ├── adviser.wav
│   │           │       ├── afflict.wav
│   │           │       ├── aftermath.wav
│   │           │       ├── aggregate.wav
│   │           │       ├── ahead.wav
│   │           │       ├── aimless.wav
│   │           │       ├── Algol.wav
│   │           │       ├── alkali.wav
│   │           │       ├── allow.wav
│   │           │       ├── almighty.wav
│   │           │       ├── alone.wav
│   │           │       ├── ammo.wav
│   │           │       ├── amulet.wav
│   │           │       ├── amusement.wav
│   │           │       ├── ancient.wav
│   │           │       ├── antenna.wav
│   │           │       ├── Apollo.wav
│   │           │       ├── apple.wav
│   │           │       ├── applicant.wav
│   │           │       ├── armistice.wav
│   │           │       ├── article.wav
│   │           │       ├── artist.wav
│   │           │       ├── assume.wav
│   │           │       ├── asteroid.wav
│   │           │       ├── Athens.wav
│   │           │       ├── Atlantic.wav
│   │           │       ├── atlas.wav
│   │           │       ├── atmosphere.wav
│   │           │       ├── autopsy.wav
│   │           │       ├── Aztec.wav
│   │           │       ├── baboon.wav
│   │           │       ├── Babylon.wav
│   │           │       ├── backfield.wav
│   │           │       ├── backward.wav
│   │           │       ├── backwater.wav
│   │           │       ├── banjo.wav
│   │           │       ├── barbecue.wav
│   │           │       ├── beaming.wav
│   │           │       ├── bedlamp.wav
│   │           │       ├── beehive.wav
│   │           │       ├── beeswax.wav
│   │           │       ├── befriend.wav
│   │           │       ├── Belfast.wav
│   │           │       ├── belowground.wav
│   │           │       ├── berserk.wav
│   │           │       ├── bifocals.wav
│   │           │       ├── billiard.wav
│   │           │       ├── bison.wav
│   │           │       ├── blackjack.wav
│   │           │       ├── blockade.wav
│   │           │       ├── blowtorch.wav
│   │           │       ├── bluebird.wav
│   │           │       ├── bodyguard.wav
│   │           │       ├── bombast.wav
│   │           │       ├── bookseller.wav
│   │           │       ├── bookshelf.wav
│   │           │       ├── borderline.wav
│   │           │       ├── bottomless.wav
│   │           │       ├── brackish.wav
│   │           │       ├── Bradbury.wav
│   │           │       ├── bravado.wav
│   │           │       ├── Brazilian.wav
│   │           │       ├── breadline.wav
│   │           │       ├── breakaway.wav
│   │           │       ├── breakup.wav
│   │           │       ├── brickyard.wav
│   │           │       ├── briefcase.wav
│   │           │       ├── Burbank.wav
│   │           │       ├── Burlington.wav
│   │           │       ├── businessman.wav
│   │           │       ├── butterfat.wav
│   │           │       ├── button.wav
│   │           │       ├── buzzard.wav
│   │           │       ├── Camelot.wav
│   │           │       ├── candidate.wav
│   │           │       ├── cannonball.wav
│   │           │       ├── Capricorn.wav
│   │           │       ├── caravan.wav
│   │           │       ├── caretaker.wav
│   │           │       ├── celebrate.wav
│   │           │       ├── cellulose.wav
│   │           │       ├── cement.wav
│   │           │       ├── certify.wav
│   │           │       ├── chairlift.wav
│   │           │       ├── chambermaid.wav
│   │           │       ├── chatter.wav
│   │           │       ├── checkup.wav
│   │           │       ├── Cherokee.wav
│   │           │       ├── Chicago.wav
│   │           │       ├── chisel.wav
│   │           │       ├── choking.wav
│   │           │       ├── chopper.wav
│   │           │       ├── Christmas.wav
│   │           │       ├── clamshell.wav
│   │           │       ├── classic.wav
│   │           │       ├── classroom.wav
│   │           │       ├── cleanup.wav
│   │           │       ├── clergyman.wav
│   │           │       ├── clockwork.wav
│   │           │       ├── cobra.wav
│   │           │       ├── coherence.wav
│   │           │       ├── combustion.wav
│   │           │       ├── commando.wav
│   │           │       ├── commence.wav
│   │           │       ├── company.wav
│   │           │       ├── component.wav
│   │           │       ├── concert.wav
│   │           │       ├── concurrent.wav
│   │           │       ├── confidence.wav
│   │           │       ├── conformist.wav
│   │           │       ├── congregate.wav
│   │           │       ├── consensus.wav
│   │           │       ├── consulting.wav
│   │           │       ├── corporate.wav
│   │           │       ├── corrosion.wav
│   │           │       ├── councilman.wav
│   │           │       ├── cowbell.wav
│   │           │       ├── crackdown.wav
│   │           │       ├── cranky.wav
│   │           │       ├── crossover.wav
│   │           │       ├── crowfoot.wav
│   │           │       ├── crucial.wav
│   │           │       ├── crucifix.wav
│   │           │       ├── crumpled.wav
│   │           │       ├── crusade.wav
│   │           │       ├── cubic.wav
│   │           │       ├── cumbersome.wav
│   │           │       ├── customer.wav
│   │           │       ├── Dakota.wav
│   │           │       ├── dashboard.wav
│   │           │       ├── deadbolt.wav
│   │           │       ├── decadence.wav
│   │           │       ├── December.wav
│   │           │       ├── decimal.wav
│   │           │       ├── deckhand.wav
│   │           │       ├── designing.wav
│   │           │       ├── detector.wav
│   │           │       ├── detergent.wav
│   │           │       ├── determine.wav
│   │           │       ├── dictator.wav
│   │           │       ├── dinosaur.wav
│   │           │       ├── direction.wav
│   │           │       ├── disable.wav
│   │           │       ├── disbelief.wav
│   │           │       ├── disruptive.wav
│   │           │       ├── distortion.wav
│   │           │       ├── document.wav
│   │           │       ├── dogsled.wav
│   │           │       ├── dragnet.wav
│   │           │       ├── drainage.wav
│   │           │       ├── dreadful.wav
│   │           │       ├── drifter.wav
│   │           │       ├── dropper.wav
│   │           │       ├── drumbeat.wav
│   │           │       ├── drunken.wav
│   │           │       ├── Dupont.wav
│   │           │       ├── dwelling.wav
│   │           │       ├── eating.wav
│   │           │       ├── edict.wav
│   │           │       ├── egghead.wav
│   │           │       ├── eightball.wav
│   │           │       ├── embezzle.wav
│   │           │       ├── enchanting.wav
│   │           │       ├── endorse.wav
│   │           │       ├── endow.wav
│   │           │       ├── enlist.wav
│   │           │       ├── enrollment.wav
│   │           │       ├── enterprise.wav
│   │           │       ├── equation.wav
│   │           │       ├── equipment.wav
│   │           │       ├── erase.wav
│   │           │       ├── escapade.wav
│   │           │       ├── escape.wav
│   │           │       ├── Eskimo.wav
│   │           │       ├── everyday.wav
│   │           │       ├── examine.wav
│   │           │       ├── exceed.wav
│   │           │       ├── existence.wav
│   │           │       ├── exodus.wav
│   │           │       ├── eyeglass.wav
│   │           │       ├── eyetooth.wav
│   │           │       ├── facial.wav
│   │           │       ├── fallout.wav
│   │           │       ├── fascinate.wav
│   │           │       ├── filament.wav
│   │           │       ├── finicky.wav
│   │           │       ├── flagpole.wav
│   │           │       ├── flatfoot.wav
│   │           │       ├── flytrap.wav
│   │           │       ├── forever.wav
│   │           │       ├── fortitude.wav
│   │           │       ├── fracture.wav
│   │           │       ├── framework.wav
│   │           │       ├── freedom.wav
│   │           │       ├── frequency.wav
│   │           │       ├── frighten.wav
│   │           │       ├── gadgetry.wav
│   │           │       ├── Galveston.wav
│   │           │       ├── gazelle.wav
│   │           │       ├── Geiger.wav
│   │           │       ├── getaway.wav
│   │           │       ├── glitter.wav
│   │           │       ├── glossary.wav
│   │           │       ├── glucose.wav
│   │           │       ├── goggles.wav
│   │           │       ├── goldfish.wav
│   │           │       ├── gossamer.wav
│   │           │       ├── graduate.wav
│   │           │       ├── gravity.wav
│   │           │       ├── gremlin.wav
│   │           │       ├── guidance.wav
│   │           │       ├── guitarist.wav
│   │           │       ├── hamburger.wav
│   │           │       ├── Hamilton.wav
│   │           │       ├── hamlet.wav
│   │           │       ├── handiwork.wav
│   │           │       ├── hazardous.wav
│   │           │       ├── headwaters.wav
│   │           │       ├── hemisphere.wav
│   │           │       ├── hesitate.wav
│   │           │       ├── hideaway.wav
│   │           │       ├── highchair.wav
│   │           │       ├── hockey.wav
│   │           │       ├── holiness.wav
│   │           │       ├── hurricane.wav
│   │           │       ├── hydraulic.wav
│   │           │       ├── impartial.wav
│   │           │       ├── impetus.wav
│   │           │       ├── inception.wav
│   │           │       ├── indigo.wav
│   │           │       ├── indoors.wav
│   │           │       ├── indulge.wav
│   │           │       ├── inertia.wav
│   │           │       ├── infancy.wav
│   │           │       ├── inferno.wav
│   │           │       ├── informant.wav
│   │           │       ├── insincere.wav
│   │           │       ├── insurgent.wav
│   │           │       ├── integrate.wav
│   │           │       ├── intention.wav
│   │           │       ├── inventive.wav
│   │           │       ├── inverse.wav
│   │           │       ├── involve.wav
│   │           │       ├── island.wav
│   │           │       ├── Istanbul.wav
│   │           │       ├── Jamaica.wav
│   │           │       ├── jawbone.wav
│   │           │       ├── Jupiter.wav
│   │           │       ├── keyboard.wav
│   │           │       ├── kickoff.wav
│   │           │       ├── kiwi.wav
│   │           │       ├── klaxon.wav
│   │           │       ├── leprosy.wav
│   │           │       ├── letterhead.wav
│   │           │       ├── liberty.wav
│   │           │       ├── locale.wav
│   │           │       ├── lockup.wav
│   │           │       ├── maritime.wav
│   │           │       ├── matchmaker.wav
│   │           │       ├── maverick.wav
│   │           │       ├── Medusa.wav
│   │           │       ├── megaton.wav
│   │           │       ├── merit.wav
│   │           │       ├── microscope.wav
│   │           │       ├── microwave.wav
│   │           │       ├── midsummer.wav
│   │           │       ├── millionaire.wav
│   │           │       ├── minnow.wav
│   │           │       ├── miracle.wav
│   │           │       ├── miser.wav
│   │           │       ├── misnomer.wav
│   │           │       ├── Mohawk.wav
│   │           │       ├── molasses.wav
│   │           │       ├── molecule.wav
│   │           │       ├── Montana.wav
│   │           │       ├── monument.wav
│   │           │       ├── mosquito.wav
│   │           │       ├── mural.wav
│   │           │       ├── music.wav
│   │           │       ├── narrative.wav
│   │           │       ├── nebula.wav
│   │           │       ├── necklace.wav
│   │           │       ├── Neptune.wav
│   │           │       ├── newborn.wav
│   │           │       ├── newsletter.wav
│   │           │       ├── nightbird.wav
│   │           │       ├── Norwegian.wav
│   │           │       ├── Oakland.wav
│   │           │       ├── obtuse.wav
│   │           │       ├── October.wav
│   │           │       ├── offload.wav
│   │           │       ├── Ohio.wav
│   │           │       ├── onlooker.wav
│   │           │       ├── optic.wav
│   │           │       ├── opulent.wav
│   │           │       ├── orca.wav
│   │           │       ├── Orlando.wav
│   │           │       ├── outfielder.wav
│   │           │       ├── Pacific.wav
│   │           │       ├── pandemic.wav
│   │           │       ├── Pandora.wav
│   │           │       ├── paperweight.wav
│   │           │       ├── paragon.wav
│   │           │       ├── paragraph.wav
│   │           │       ├── paramount.wav
│   │           │       ├── passenger.wav
│   │           │       ├── payday.wav
│   │           │       ├── peachy.wav
│   │           │       ├── pedigree.wav
│   │           │       ├── Pegasus.wav
│   │           │       ├── penetrate.wav
│   │           │       ├── perceptive.wav
│   │           │       ├── performance.wav
│   │           │       ├── pharmacy.wav
│   │           │       ├── pheasant.wav
│   │           │       ├── phonetic.wav
│   │           │       ├── photograph.wav
│   │           │       ├── physique.wav
│   │           │       ├── pioneer.wav
│   │           │       ├── playhouse.wav
│   │           │       ├── Pluto.wav
│   │           │       ├── pocketful.wav
│   │           │       ├── politeness.wav
│   │           │       ├── positive.wav
│   │           │       ├── potato.wav
│   │           │       ├── preclude.wav
│   │           │       ├── prefer.wav
│   │           │       ├── preshrunk.wav
│   │           │       ├── printer.wav
│   │           │       ├── processor.wav
│   │           │       ├── provincial.wav
│   │           │       ├── prowler.wav
│   │           │       ├── proximate.wav
│   │           │       ├── puberty.wav
│   │           │       ├── publisher.wav
│   │           │       ├── pupil.wav
│   │           │       ├── puppy.wav
│   │           │       ├── pyramid.wav
│   │           │       ├── python.wav
│   │           │       ├── quadrant.wav
│   │           │       ├── quantity.wav
│   │           │       ├── quiver.wav
│   │           │       ├── quota.wav
│   │           │       ├── racketeer.wav
│   │           │       ├── ragtime.wav
│   │           │       ├── ratchet.wav
│   │           │       ├── rebellion.wav
│   │           │       ├── rebirth.wav
│   │           │       ├── recipe.wav
│   │           │       ├── recover.wav
│   │           │       ├── reform.wav
│   │           │       ├── regain.wav
│   │           │       ├── reindeer.wav
│   │           │       ├── rematch.wav
│   │           │       ├── repay.wav
│   │           │       ├── repellent.wav
│   │           │       ├── replica.wav
│   │           │       ├── reproduce.wav
│   │           │       ├── resistor.wav
│   │           │       ├── responsive.wav
│   │           │       ├── retouch.wav
│   │           │       ├── retraction.wav
│   │           │       ├── retrieval.wav
│   │           │       ├── retrospect.wav
│   │           │       ├── revenge.wav
│   │           │       ├── revenue.wav
│   │           │       ├── revival.wav
│   │           │       ├── revolver.wav
│   │           │       ├── reward.wav
│   │           │       ├── rhythm.wav
│   │           │       ├── ribcage.wav
│   │           │       ├── ringbolt.wav
│   │           │       ├── robust.wav
│   │           │       ├── rocker.wav
│   │           │       ├── ruffled.wav
│   │           │       ├── sailboat.wav
│   │           │       ├── sandalwood.wav
│   │           │       ├── sardonic.wav
│   │           │       ├── Saturday.wav
│   │           │       ├── savagery.wav
│   │           │       ├── sawdust.wav
│   │           │       ├── scallion.wav
│   │           │       ├── scavenger.wav
│   │           │       ├── scenic.wav
│   │           │       ├── scorecard.wav
│   │           │       ├── Scotland.wav
│   │           │       ├── seabird.wav
│   │           │       ├── select.wav
│   │           │       ├── sensation.wav
│   │           │       ├── sentence.wav
│   │           │       ├── shadow.wav
│   │           │       ├── shamrock.wav
│   │           │       ├── showgirl.wav
│   │           │       ├── skullcap.wav
│   │           │       ├── skydive.wav
│   │           │       ├── slingshot.wav
│   │           │       ├── slowdown.wav
│   │           │       ├── snapline.wav
│   │           │       ├── snapshot.wav
│   │           │       ├── snowcap.wav
│   │           │       ├── snowslide.wav
│   │           │       ├── sociable.wav
│   │           │       ├── solo.wav
│   │           │       ├── southward.wav
│   │           │       ├── souvenir.wav
│   │           │       ├── soybean.wav
│   │           │       ├── spaniel.wav
│   │           │       ├── spearhead.wav
│   │           │       ├── specialist.wav
│   │           │       ├── speculate.wav
│   │           │       ├── spellbind.wav
│   │           │       ├── spheroid.wav
│   │           │       ├── spigot.wav
│   │           │       ├── spindle.wav
│   │           │       ├── spyglass.wav
│   │           │       ├── stagehand.wav
│   │           │       ├── stagnate.wav
│   │           │       ├── stairway.wav
│   │           │       ├── standard.wav
│   │           │       ├── stapler.wav
│   │           │       ├── steamship.wav
│   │           │       ├── sterling.wav
│   │           │       ├── stethoscope.wav
│   │           │       ├── stockman.wav
│   │           │       ├── stopwatch.wav
│   │           │       ├── stormy.wav
│   │           │       ├── stupendous.wav
│   │           │       ├── sugar.wav
│   │           │       ├── supportive.wav
│   │           │       ├── surmount.wav
│   │           │       ├── surrender.wav
│   │           │       ├── suspense.wav
│   │           │       ├── suspicious.wav
│   │           │       ├── sweatband.wav
│   │           │       ├── swelter.wav
│   │           │       ├── sympathy.wav
│   │           │       ├── tactics.wav
│   │           │       ├── talon.wav
│   │           │       ├── tambourine.wav
│   │           │       ├── tapeworm.wav
│   │           │       ├── telephone.wav
│   │           │       ├── tempest.wav
│   │           │       ├── therapist.wav
│   │           │       ├── tiger.wav
│   │           │       ├── tissue.wav
│   │           │       ├── tobacco.wav
│   │           │       ├── tolerance.wav
│   │           │       ├── tomorrow.wav
│   │           │       ├── tonic.wav
│   │           │       ├── topmost.wav
│   │           │       ├── torpedo.wav
│   │           │       ├── tracker.wav
│   │           │       ├── tradition.wav
│   │           │       ├── transit.wav
│   │           │       ├── trauma.wav
│   │           │       ├── travesty.wav
│   │           │       ├── treadmill.wav
│   │           │       ├── Trojan.wav
│   │           │       ├── trombonist.wav
│   │           │       ├── trouble.wav
│   │           │       ├── truncated.wav
│   │           │       ├── tumor.wav
│   │           │       ├── tunnel.wav
│   │           │       ├── tycoon.wav
│   │           │       ├── typewriter.wav
│   │           │       ├── ultimate.wav
│   │           │       ├── uncut.wav
│   │           │       ├── undaunted.wav
│   │           │       ├── underfoot.wav
│   │           │       ├── unearth.wav
│   │           │       ├── unicorn.wav
│   │           │       ├── unify.wav
│   │           │       ├── universe.wav
│   │           │       ├── unravel.wav
│   │           │       ├── unwind.wav
│   │           │       ├── upcoming.wav
│   │           │       ├── uproot.wav
│   │           │       ├── upset.wav
│   │           │       ├── upshot.wav
│   │           │       ├── vacancy.wav
│   │           │       ├── vagabond.wav
│   │           │       ├── vapor.wav
│   │           │       ├── vertigo.wav
│   │           │       ├── village.wav
│   │           │       ├── Virginia.wav
│   │           │       ├── virus.wav
│   │           │       ├── visitor.wav
│   │           │       ├── vocalist.wav
│   │           │       ├── voyager.wav
│   │           │       ├── Vulcan.wav
│   │           │       ├── waffle.wav
│   │           │       ├── wallet.wav
│   │           │       ├── warranty.wav
│   │           │       ├── watchword.wav
│   │           │       ├── Waterloo.wav
│   │           │       ├── wayside.wav
│   │           │       ├── whimsical.wav
│   │           │       ├── Wichita.wav
│   │           │       ├── willow.wav
│   │           │       ├── Wilmington.wav
│   │           │       ├── woodlark.wav
│   │           │       ├── Wyoming.wav
│   │           │       ├── yesteryear.wav
│   │           │       ├── Yucatan.wav
│   │           │       └── Zulu.wav
│   │           ├── conference
│   │           │   ├── 16000
│   │           │   │   ├── conf-alone.wav
│   │           │   │   ├── conf-bad-pin.wav
│   │           │   │   ├── conf-conference_is_full.wav
│   │           │   │   ├── conf-conference_is_in_qna_mode.wav
│   │           │   │   ├── conf-conference_will_start_shortly.wav
│   │           │   │   ├── conf-enter_conf_number.wav
│   │           │   │   ├── conf-enter_conf_pin.wav
│   │           │   │   ├── conf-entry_sound.wav
│   │           │   │   ├── conf-exit_sound.wav
│   │           │   │   ├── conf-goodbye.wav
│   │           │   │   ├── conf-has_joined.wav
│   │           │   │   ├── conf-has_left.wav
│   │           │   │   ├── conf-is-locked.wav
│   │           │   │   ├── conf-is-unlocked.wav
│   │           │   │   ├── conf-kicked.wav
│   │           │   │   ├── conf-listener_in_conference.wav
│   │           │   │   ├── conf-listeners_in_conference.wav
│   │           │   │   ├── conf-locked.wav
│   │           │   │   ├── conf-members_in_conference.wav
│   │           │   │   ├── conf-muted.wav
│   │           │   │   ├── conf-number_of_listeners.wav
│   │           │   │   ├── conf-one_other_member_conference.wav
│   │           │   │   ├── conf-one_other_person_conference.wav
│   │           │   │   ├── conf-other_persons_conference.wav
│   │           │   │   ├── conf-pin.wav
│   │           │   │   ├── conf-qna_mode.wav
│   │           │   │   ├── conf-unmuted.wav
│   │           │   │   ├── conf-welcome.wav
│   │           │   │   ├── conf-you_are_already_muted.wav
│   │           │   │   └── conf-you_are_now_bidirectionally_muted.wav
│   │           │   ├── 32000
│   │           │   │   ├── conf-alone.wav
│   │           │   │   ├── conf-bad-pin.wav
│   │           │   │   ├── conf-conference_is_full.wav
│   │           │   │   ├── conf-conference_is_in_qna_mode.wav
│   │           │   │   ├── conf-conference_will_start_shortly.wav
│   │           │   │   ├── conf-enter_conf_number.wav
│   │           │   │   ├── conf-enter_conf_pin.wav
│   │           │   │   ├── conf-entry_sound.wav
│   │           │   │   ├── conf-exit_sound.wav
│   │           │   │   ├── conf-goodbye.wav
│   │           │   │   ├── conf-has_joined.wav
│   │           │   │   ├── conf-has_left.wav
│   │           │   │   ├── conf-is-locked.wav
│   │           │   │   ├── conf-is-unlocked.wav
│   │           │   │   ├── conf-kicked.wav
│   │           │   │   ├── conf-listener_in_conference.wav
│   │           │   │   ├── conf-listeners_in_conference.wav
│   │           │   │   ├── conf-locked.wav
│   │           │   │   ├── conf-members_in_conference.wav
│   │           │   │   ├── conf-muted.wav
│   │           │   │   ├── conf-number_of_listeners.wav
│   │           │   │   ├── conf-one_other_member_conference.wav
│   │           │   │   ├── conf-one_other_person_conference.wav
│   │           │   │   ├── conf-other_persons_conference.wav
│   │           │   │   ├── conf-pin.wav
│   │           │   │   ├── conf-qna_mode.wav
│   │           │   │   ├── conf-unmuted.wav
│   │           │   │   ├── conf-welcome.wav
│   │           │   │   ├── conf-you_are_already_muted.wav
│   │           │   │   └── conf-you_are_now_bidirectionally_muted.wav
│   │           │   ├── 48000
│   │           │   │   ├── conf-alone.wav
│   │           │   │   ├── conf-bad-pin.wav
│   │           │   │   ├── conf-conference_is_full.wav
│   │           │   │   ├── conf-conference_is_in_qna_mode.wav
│   │           │   │   ├── conf-conference_will_start_shortly.wav
│   │           │   │   ├── conf-enter_conf_number.wav
│   │           │   │   ├── conf-enter_conf_pin.wav
│   │           │   │   ├── conf-entry_sound.wav
│   │           │   │   ├── conf-exit_sound.wav
│   │           │   │   ├── conf-goodbye.wav
│   │           │   │   ├── conf-has_joined.wav
│   │           │   │   ├── conf-has_left.wav
│   │           │   │   ├── conf-is-locked.wav
│   │           │   │   ├── conf-is-unlocked.wav
│   │           │   │   ├── conf-kicked.wav
│   │           │   │   ├── conf-listener_in_conference.wav
│   │           │   │   ├── conf-listeners_in_conference.wav
│   │           │   │   ├── conf-locked.wav
│   │           │   │   ├── conf-members_in_conference.wav
│   │           │   │   ├── conf-muted.wav
│   │           │   │   ├── conf-number_of_listeners.wav
│   │           │   │   ├── conf-one_other_member_conference.wav
│   │           │   │   ├── conf-one_other_person_conference.wav
│   │           │   │   ├── conf-other_persons_conference.wav
│   │           │   │   ├── conf-pin.wav
│   │           │   │   ├── conf-qna_mode.wav
│   │           │   │   ├── conf-unmuted.wav
│   │           │   │   ├── conf-welcome.wav
│   │           │   │   ├── conf-you_are_already_muted.wav
│   │           │   │   └── conf-you_are_now_bidirectionally_muted.wav
│   │           │   └── 8000
│   │           │       ├── conf-alone.wav
│   │           │       ├── conf-bad-pin.wav
│   │           │       ├── conf-conference_is_full.wav
│   │           │       ├── conf-conference_is_in_qna_mode.wav
│   │           │       ├── conf-conference_will_start_shortly.wav
│   │           │       ├── conf-enter_conf_number.wav
│   │           │       ├── conf-enter_conf_pin.wav
│   │           │       ├── conf-entry_sound.wav
│   │           │       ├── conf-exit_sound.wav
│   │           │       ├── conf-goodbye.wav
│   │           │       ├── conf-has_joined.wav
│   │           │       ├── conf-has_left.wav
│   │           │       ├── conf-is-locked.wav
│   │           │       ├── conf-is-unlocked.wav
│   │           │       ├── conf-kicked.wav
│   │           │       ├── conf-listener_in_conference.wav
│   │           │       ├── conf-listeners_in_conference.wav
│   │           │       ├── conf-locked.wav
│   │           │       ├── conf-members_in_conference.wav
│   │           │       ├── conf-muted.wav
│   │           │       ├── conf-number_of_listeners.wav
│   │           │       ├── conf-one_other_member_conference.wav
│   │           │       ├── conf-one_other_person_conference.wav
│   │           │       ├── conf-other_persons_conference.wav
│   │           │       ├── conf-pin.wav
│   │           │       ├── conf-qna_mode.wav
│   │           │       ├── conf-unmuted.wav
│   │           │       ├── conf-welcome.wav
│   │           │       ├── conf-you_are_already_muted.wav
│   │           │       └── conf-you_are_now_bidirectionally_muted.wav
│   │           ├── currency
│   │           │   ├── 16000
│   │           │   │   ├── and.wav
│   │           │   │   ├── central.wav
│   │           │   │   ├── cents-per-minute.wav
│   │           │   │   ├── cents.wav
│   │           │   │   ├── cent.wav
│   │           │   │   ├── dollars.wav
│   │           │   │   ├── dollar.wav
│   │           │   │   ├── minus.wav
│   │           │   │   └── negative.wav
│   │           │   ├── 32000
│   │           │   │   ├── and.wav
│   │           │   │   ├── central.wav
│   │           │   │   ├── cents-per-minute.wav
│   │           │   │   ├── cents.wav
│   │           │   │   ├── cent.wav
│   │           │   │   ├── dollars.wav
│   │           │   │   ├── dollar.wav
│   │           │   │   ├── minus.wav
│   │           │   │   └── negative.wav
│   │           │   ├── 48000
│   │           │   │   ├── and.wav
│   │           │   │   ├── central.wav
│   │           │   │   ├── cents-per-minute.wav
│   │           │   │   ├── cents.wav
│   │           │   │   ├── cent.wav
│   │           │   │   ├── dollars.wav
│   │           │   │   ├── dollar.wav
│   │           │   │   ├── minus.wav
│   │           │   │   └── negative.wav
│   │           │   └── 8000
│   │           │       ├── and.wav
│   │           │       ├── central.wav
│   │           │       ├── cents-per-minute.wav
│   │           │       ├── cents.wav
│   │           │       ├── cent.wav
│   │           │       ├── dollars.wav
│   │           │       ├── dollar.wav
│   │           │       ├── minus.wav
│   │           │       └── negative.wav
│   │           ├── digits
│   │           │   ├── 16000
│   │           │   │   ├── 0.wav
│   │           │   │   ├── 10.wav
│   │           │   │   ├── 11.wav
│   │           │   │   ├── 12.wav
│   │           │   │   ├── 13.wav
│   │           │   │   ├── 14.wav
│   │           │   │   ├── 15.wav
│   │           │   │   ├── 16.wav
│   │           │   │   ├── 17.wav
│   │           │   │   ├── 18.wav
│   │           │   │   ├── 19.wav
│   │           │   │   ├── 1.wav
│   │           │   │   ├── 20.wav
│   │           │   │   ├── 2.wav
│   │           │   │   ├── 30.wav
│   │           │   │   ├── 3.wav
│   │           │   │   ├── 40.wav
│   │           │   │   ├── 4.wav
│   │           │   │   ├── 50.wav
│   │           │   │   ├── 5.wav
│   │           │   │   ├── 60.wav
│   │           │   │   ├── 6.wav
│   │           │   │   ├── 70.wav
│   │           │   │   ├── 7.wav
│   │           │   │   ├── 80.wav
│   │           │   │   ├── 8.wav
│   │           │   │   ├── 90.wav
│   │           │   │   ├── 9.wav
│   │           │   │   ├── dot.wav
│   │           │   │   ├── h-10.wav
│   │           │   │   ├── h-11.wav
│   │           │   │   ├── h-12.wav
│   │           │   │   ├── h-13.wav
│   │           │   │   ├── h-14.wav
│   │           │   │   ├── h-15.wav
│   │           │   │   ├── h-16.wav
│   │           │   │   ├── h-17.wav
│   │           │   │   ├── h-18.wav
│   │           │   │   ├── h-19.wav
│   │           │   │   ├── h-1.wav
│   │           │   │   ├── h-20.wav
│   │           │   │   ├── h-2.wav
│   │           │   │   ├── h-30.wav
│   │           │   │   ├── h-3.wav
│   │           │   │   ├── h-4.wav
│   │           │   │   ├── h-5.wav
│   │           │   │   ├── h-6.wav
│   │           │   │   ├── h-7.wav
│   │           │   │   ├── h-8.wav
│   │           │   │   ├── h-9.wav
│   │           │   │   ├── hundred.wav
│   │           │   │   ├── million.wav
│   │           │   │   ├── period.wav
│   │           │   │   ├── point.wav
│   │           │   │   ├── pound.wav
│   │           │   │   ├── star.wav
│   │           │   │   └── thousand.wav
│   │           │   ├── 32000
│   │           │   │   ├── 0.wav
│   │           │   │   ├── 10.wav
│   │           │   │   ├── 11.wav
│   │           │   │   ├── 12.wav
│   │           │   │   ├── 13.wav
│   │           │   │   ├── 14.wav
│   │           │   │   ├── 15.wav
│   │           │   │   ├── 16.wav
│   │           │   │   ├── 17.wav
│   │           │   │   ├── 18.wav
│   │           │   │   ├── 19.wav
│   │           │   │   ├── 1.wav
│   │           │   │   ├── 20.wav
│   │           │   │   ├── 2.wav
│   │           │   │   ├── 30.wav
│   │           │   │   ├── 3.wav
│   │           │   │   ├── 40.wav
│   │           │   │   ├── 4.wav
│   │           │   │   ├── 50.wav
│   │           │   │   ├── 5.wav
│   │           │   │   ├── 60.wav
│   │           │   │   ├── 6.wav
│   │           │   │   ├── 70.wav
│   │           │   │   ├── 7.wav
│   │           │   │   ├── 80.wav
│   │           │   │   ├── 8.wav
│   │           │   │   ├── 90.wav
│   │           │   │   ├── 9.wav
│   │           │   │   ├── dot.wav
│   │           │   │   ├── h-10.wav
│   │           │   │   ├── h-11.wav
│   │           │   │   ├── h-12.wav
│   │           │   │   ├── h-13.wav
│   │           │   │   ├── h-14.wav
│   │           │   │   ├── h-15.wav
│   │           │   │   ├── h-16.wav
│   │           │   │   ├── h-17.wav
│   │           │   │   ├── h-18.wav
│   │           │   │   ├── h-19.wav
│   │           │   │   ├── h-1.wav
│   │           │   │   ├── h-20.wav
│   │           │   │   ├── h-2.wav
│   │           │   │   ├── h-30.wav
│   │           │   │   ├── h-3.wav
│   │           │   │   ├── h-4.wav
│   │           │   │   ├── h-5.wav
│   │           │   │   ├── h-6.wav
│   │           │   │   ├── h-7.wav
│   │           │   │   ├── h-8.wav
│   │           │   │   ├── h-9.wav
│   │           │   │   ├── hundred.wav
│   │           │   │   ├── million.wav
│   │           │   │   ├── period.wav
│   │           │   │   ├── point.wav
│   │           │   │   ├── pound.wav
│   │           │   │   ├── star.wav
│   │           │   │   └── thousand.wav
│   │           │   ├── 48000
│   │           │   │   ├── 0.wav
│   │           │   │   ├── 10.wav
│   │           │   │   ├── 11.wav
│   │           │   │   ├── 12.wav
│   │           │   │   ├── 13.wav
│   │           │   │   ├── 14.wav
│   │           │   │   ├── 15.wav
│   │           │   │   ├── 16.wav
│   │           │   │   ├── 17.wav
│   │           │   │   ├── 18.wav
│   │           │   │   ├── 19.wav
│   │           │   │   ├── 1.wav
│   │           │   │   ├── 20.wav
│   │           │   │   ├── 2.wav
│   │           │   │   ├── 30.wav
│   │           │   │   ├── 3.wav
│   │           │   │   ├── 40.wav
│   │           │   │   ├── 4.wav
│   │           │   │   ├── 50.wav
│   │           │   │   ├── 5.wav
│   │           │   │   ├── 60.wav
│   │           │   │   ├── 6.wav
│   │           │   │   ├── 70.wav
│   │           │   │   ├── 7.wav
│   │           │   │   ├── 80.wav
│   │           │   │   ├── 8.wav
│   │           │   │   ├── 90.wav
│   │           │   │   ├── 9.wav
│   │           │   │   ├── dot.wav
│   │           │   │   ├── h-10.wav
│   │           │   │   ├── h-11.wav
│   │           │   │   ├── h-12.wav
│   │           │   │   ├── h-13.wav
│   │           │   │   ├── h-14.wav
│   │           │   │   ├── h-15.wav
│   │           │   │   ├── h-16.wav
│   │           │   │   ├── h-17.wav
│   │           │   │   ├── h-18.wav
│   │           │   │   ├── h-19.wav
│   │           │   │   ├── h-1.wav
│   │           │   │   ├── h-20.wav
│   │           │   │   ├── h-2.wav
│   │           │   │   ├── h-30.wav
│   │           │   │   ├── h-3.wav
│   │           │   │   ├── h-4.wav
│   │           │   │   ├── h-5.wav
│   │           │   │   ├── h-6.wav
│   │           │   │   ├── h-7.wav
│   │           │   │   ├── h-8.wav
│   │           │   │   ├── h-9.wav
│   │           │   │   ├── hundred.wav
│   │           │   │   ├── million.wav
│   │           │   │   ├── period.wav
│   │           │   │   ├── point.wav
│   │           │   │   ├── pound.wav
│   │           │   │   ├── star.wav
│   │           │   │   └── thousand.wav
│   │           │   └── 8000
│   │           │       ├── 0.wav
│   │           │       ├── 10.wav
│   │           │       ├── 11.wav
│   │           │       ├── 12.wav
│   │           │       ├── 13.wav
│   │           │       ├── 14.wav
│   │           │       ├── 15.wav
│   │           │       ├── 16.wav
│   │           │       ├── 17.wav
│   │           │       ├── 18.wav
│   │           │       ├── 19.wav
│   │           │       ├── 1.wav
│   │           │       ├── 20.wav
│   │           │       ├── 2.wav
│   │           │       ├── 30.wav
│   │           │       ├── 3.wav
│   │           │       ├── 40.wav
│   │           │       ├── 4.wav
│   │           │       ├── 50.wav
│   │           │       ├── 5.wav
│   │           │       ├── 60.wav
│   │           │       ├── 6.wav
│   │           │       ├── 70.wav
│   │           │       ├── 7.wav
│   │           │       ├── 80.wav
│   │           │       ├── 8.wav
│   │           │       ├── 90.wav
│   │           │       ├── 9.wav
│   │           │       ├── dot.wav
│   │           │       ├── h-10.wav
│   │           │       ├── h-11.wav
│   │           │       ├── h-12.wav
│   │           │       ├── h-13.wav
│   │           │       ├── h-14.wav
│   │           │       ├── h-15.wav
│   │           │       ├── h-16.wav
│   │           │       ├── h-17.wav
│   │           │       ├── h-18.wav
│   │           │       ├── h-19.wav
│   │           │       ├── h-1.wav
│   │           │       ├── h-20.wav
│   │           │       ├── h-2.wav
│   │           │       ├── h-30.wav
│   │           │       ├── h-3.wav
│   │           │       ├── h-4.wav
│   │           │       ├── h-5.wav
│   │           │       ├── h-6.wav
│   │           │       ├── h-7.wav
│   │           │       ├── h-8.wav
│   │           │       ├── h-9.wav
│   │           │       ├── hundred.wav
│   │           │       ├── million.wav
│   │           │       ├── period.wav
│   │           │       ├── point.wav
│   │           │       ├── pound.wav
│   │           │       ├── star.wav
│   │           │       └── thousand.wav
│   │           ├── directory
│   │           │   ├── 16000
│   │           │   │   ├── dir-at_extension.wav
│   │           │   │   ├── dir-enter_person_first_or_last.wav
│   │           │   │   ├── dir-enter_person.wav
│   │           │   │   ├── dir-first_name.wav
│   │           │   │   ├── dir-for_next.wav
│   │           │   │   ├── dir-for_prev.wav
│   │           │   │   ├── dir-last_name.wav
│   │           │   │   ├── dir-letters_of_person_name.wav
│   │           │   │   ├── dir-no_matching_results.wav
│   │           │   │   ├── dir-no_more_results.wav
│   │           │   │   ├── dir-please_try_again.wav
│   │           │   │   ├── dir-result_match.wav
│   │           │   │   ├── dir-result_number.wav
│   │           │   │   ├── dir-specify_mininum.wav
│   │           │   │   ├── dir-start_new_search.wav
│   │           │   │   ├── dir-too_many_result.wav
│   │           │   │   ├── dir-to_search_by.wav
│   │           │   │   └── dir-to_select_entry.wav
│   │           │   ├── 32000
│   │           │   │   ├── dir-at_extension.wav
│   │           │   │   ├── dir-enter_person_first_or_last.wav
│   │           │   │   ├── dir-enter_person.wav
│   │           │   │   ├── dir-first_name.wav
│   │           │   │   ├── dir-for_next.wav
│   │           │   │   ├── dir-for_prev.wav
│   │           │   │   ├── dir-last_name.wav
│   │           │   │   ├── dir-letters_of_person_name.wav
│   │           │   │   ├── dir-no_matching_results.wav
│   │           │   │   ├── dir-no_more_results.wav
│   │           │   │   ├── dir-please_try_again.wav
│   │           │   │   ├── dir-result_match.wav
│   │           │   │   ├── dir-result_number.wav
│   │           │   │   ├── dir-specify_mininum.wav
│   │           │   │   ├── dir-start_new_search.wav
│   │           │   │   ├── dir-too_many_result.wav
│   │           │   │   ├── dir-to_search_by.wav
│   │           │   │   └── dir-to_select_entry.wav
│   │           │   ├── 48000
│   │           │   │   ├── dir-at_extension.wav
│   │           │   │   ├── dir-enter_person_first_or_last.wav
│   │           │   │   ├── dir-enter_person.wav
│   │           │   │   ├── dir-first_name.wav
│   │           │   │   ├── dir-for_next.wav
│   │           │   │   ├── dir-for_prev.wav
│   │           │   │   ├── dir-last_name.wav
│   │           │   │   ├── dir-letters_of_person_name.wav
│   │           │   │   ├── dir-no_matching_results.wav
│   │           │   │   ├── dir-no_more_results.wav
│   │           │   │   ├── dir-please_try_again.wav
│   │           │   │   ├── dir-result_match.wav
│   │           │   │   ├── dir-result_number.wav
│   │           │   │   ├── dir-specify_mininum.wav
│   │           │   │   ├── dir-start_new_search.wav
│   │           │   │   ├── dir-too_many_result.wav
│   │           │   │   ├── dir-to_search_by.wav
│   │           │   │   └── dir-to_select_entry.wav
│   │           │   └── 8000
│   │           │       ├── dir-at_extension.wav
│   │           │       ├── dir-enter_person_first_or_last.wav
│   │           │       ├── dir-enter_person.wav
│   │           │       ├── dir-first_name.wav
│   │           │       ├── dir-for_next.wav
│   │           │       ├── dir-for_prev.wav
│   │           │       ├── dir-last_name.wav
│   │           │       ├── dir-letters_of_person_name.wav
│   │           │       ├── dir-no_matching_results.wav
│   │           │       ├── dir-no_more_results.wav
│   │           │       ├── dir-please_try_again.wav
│   │           │       ├── dir-result_match.wav
│   │           │       ├── dir-result_number.wav
│   │           │       ├── dir-specify_mininum.wav
│   │           │       ├── dir-start_new_search.wav
│   │           │       ├── dir-too_many_result.wav
│   │           │       ├── dir-to_search_by.wav
│   │           │       └── dir-to_select_entry.wav
│   │           ├── ivr
│   │           │   ├── 16000
│   │           │   │   ├── ivr-accept_reject_voicemail.wav
│   │           │   │   ├── ivr-accept_reject.wav
│   │           │   │   ├── ivr-access_denied.wav
│   │           │   │   ├── ivr-account_balance_is.wav
│   │           │   │   ├── ivr-account_number.wav
│   │           │   │   ├── ivr-aint_nobody_got_time_for_that.wav
│   │           │   │   ├── ivr-all_your_call_are_belong_to_us.wav
│   │           │   │   ├── ivr-already_contains_a_recording.wav
│   │           │   │   ├── ivr-anonymous_caller.wav
│   │           │   │   ├── ivr-any_other_digit.wav
│   │           │   │   ├── ivr-appointment_schedule_for.wav
│   │           │   │   ├── ivr-asterisk_like_syphilis.wav
│   │           │   │   ├── ivr-at_the_tone.wav
│   │           │   │   ├── ivr-automated_attendants.wav
│   │           │   │   ├── ivr-automated_attendant.wav
│   │           │   │   ├── ivr-barbecuing.wav
│   │           │   │   ├── ivr-barracuda_networks.wav
│   │           │   │   ├── ivr-beacuase.wav
│   │           │   │   ├── ivr-begin_recording.wav
│   │           │   │   ├── ivr-by_dialing.wav
│   │           │   │   ├── ivr-call_answered_order_received.wav
│   │           │   │   ├── ivr-call_attempt_aborted.wav
│   │           │   │   ├── ivr-call_being_transferred.wav
│   │           │   │   ├── ivr-call_cannot_be_completed_as_dialed.wav
│   │           │   │   ├── ivr-call_forwarding_has_been_cancelled.wav
│   │           │   │   ├── ivr-call_forwarding_has_been_set.wav
│   │           │   │   ├── ivr-call_from.wav
│   │           │   │   ├── ivr-call_rejected.wav
│   │           │   │   ├── ivr-call_screening_disabled.wav
│   │           │   │   ├── ivr-call_screening_enabled.wav
│   │           │   │   ├── ivr-call.wav
│   │           │   │   ├── ivr-cancel_wakeup_call.wav
│   │           │   │   ├── ivr-cold_foolish.wav
│   │           │   │   ├── ivr-cold_pop.wav
│   │           │   │   ├── ivr-concentrate.wav
│   │           │   │   ├── ivr-congratulations_you_pressed_star.wav
│   │           │   │   ├── ivr-connect_actual_human_being.wav
│   │           │   │   ├── ivr_connect_live_operator.wav
│   │           │   │   ├── ivr-connect_to_caller.wav
│   │           │   │   ├── ivr-contact_system_administrator.wav
│   │           │   │   ├── ivr-credit_card_could_not_be_charged.wav
│   │           │   │   ├── ivr-cudatel_communication_server.wav
│   │           │   │   ├── ivr-customer_service.wav
│   │           │   │   ├── ivr-custom_mode_number.wav
│   │           │   │   ├── ivr-daily_wakeup_call.wav
│   │           │   │   ├── ivr-day_mode.wav
│   │           │   │   ├── ivr-delayed_echo_your_audio_back.wav
│   │           │   │   ├── ivr-did_you_mean_to_press_key.wav
│   │           │   │   ├── ivr-disabled.wav
│   │           │   │   ├── ivr-dnd_activated.wav
│   │           │   │   ├── ivr-dnd_cancelled.wav
│   │           │   │   ├── ivr-does_not_contain_a_recording.wav
│   │           │   │   ├── ivr-do_not_call_list.wav
│   │           │   │   ├── ivr-douche_telecom.wav
│   │           │   │   ├── ivr-dude_you_suck.wav
│   │           │   │   ├── ivr-echo_your_audio_back.wav
│   │           │   │   ├── ivr-enabled.wav
│   │           │   │   ├── ivr-engineers_busy_assisting_other_sales.wav
│   │           │   │   ├── ivr-enjoy_music_while_transfer.wav
│   │           │   │   ├── ivr-ensure_service_keeps_working.wav
│   │           │   │   ├── ivr-enter_destination_telephone_number.wav
│   │           │   │   ├── ivr-enter_ext_pound.wav
│   │           │   │   ├── ivr-enter_ext.wav
│   │           │   │   ├── ivr-enter_number_send_fax.wav
│   │           │   │   ├── ivr-enter_number_to_add_to_blacklist.wav
│   │           │   │   ├── ivr-enter_number_to_remove_from_blacklist.wav
│   │           │   │   ├── ivr-enter_queue_number.wav
│   │           │   │   ├── ivr-enter_source_telephone_number.wav
│   │           │   │   ├── ivr-estimated_hold_time.wav
│   │           │   │   ├── ivr-exit_sound_prompt.wav
│   │           │   │   ├── ivr-extension_number.wav
│   │           │   │   ├── ivr-extension_to_provision_this_phone.wav
│   │           │   │   ├── ivr-failure_reason_is.wav
│   │           │   │   ├── ivr-feature.wav
│   │           │   │   ├── ivr-file_a_jira.wav
│   │           │   │   ├── ivr-files.wav
│   │           │   │   ├── ivr-file.wav
│   │           │   │   ├── ivr-finished_pound_hash_key.wav
│   │           │   │   ├── ivr-first_name_first.wav
│   │           │   │   ├── ivr-followed_by_pound.wav
│   │           │   │   ├── ivr-for_a_wakeup_call.wav
│   │           │   │   ├── ivr-for_daily_wakeup_calls.wav
│   │           │   │   ├── ivr-for_daily_wakeup_call.wav
│   │           │   │   ├── ivr-for_directory_press.wav
│   │           │   │   ├── ivr-for_english_press.wav
│   │           │   │   ├── ivr-for_one_time_wakeup_call.wav
│   │           │   │   ├── ivr-for_other_options.wav
│   │           │   │   ├── ivr-for_this_person.wav
│   │           │   │   ├── ivr-for.wav
│   │           │   │   ├── ivr-founder_of_freesource.wav
│   │           │   │   ├── ivr-freeguipy.wav
│   │           │   │   ├── ivr-gateway_down.wav
│   │           │   │   ├── ivr-generic_greeting.wav
│   │           │   │   ├── ivr-good_afternoon.wav
│   │           │   │   ├── ivr-good_evening.wav
│   │           │   │   ├── ivr-good_morning.wav
│   │           │   │   ├── ivr-got_bronchitis.wav
│   │           │   │   ├── ivr-hangup_to_discard.wav
│   │           │   │   ├── ivr-hangup_to_end_test.wav
│   │           │   │   ├── ivr-hang_up.wav
│   │           │   │   ├── ivr-has_been_added_to_the_blacklist.wav
│   │           │   │   ├── ivr-has_been_answered.wav
│   │           │   │   ├── ivr-has_been_removed_from_blacklist.wav
│   │           │   │   ├── ivr-has_been_removed.wav
│   │           │   │   ├── ivr-has_called_emergency_services.wav
│   │           │   │   ├── ivr-has_had.wav
│   │           │   │   ├── ivr-has_left_the_building.wav
│   │           │   │   ├── ivr-hear_usage_stats.wav
│   │           │   │   ├── ivr-hello.wav
│   │           │   │   ├── ivr-hold_connect_call.wav
│   │           │   │   ├── ivr-hotseat_intro.wav
│   │           │   │   ├── ivr-hotseat_options.wav
│   │           │   │   ├── ivr-hotseat_pin.wav
│   │           │   │   ├── ivr-id_number.wav
│   │           │   │   ├── ivr-if_correct_one_if_not_two.wav
│   │           │   │   ├── ivr-if_correct_press.wav
│   │           │   │   ├── ivr-if_not_press.wav
│   │           │   │   ├── ivr-if_you_would_like_us_to_call_back.wav
│   │           │   │   ├── ivr-im_sorry.wav
│   │           │   │   ├── ivr-incoming_call.wav
│   │           │   │   ├── ivr-incompatible_destination.wav
│   │           │   │   ├── ivr-in_line.wav
│   │           │   │   ├── ivr-invalid_extension_try_again.wav
│   │           │   │   ├── ivr-invalid_number_format.wav
│   │           │   │   ├── ivr-invalid_sound_prompt.wav
│   │           │   │   ├── ivr-is_already_on_the_blacklist.wav
│   │           │   │   ├── ivr-is_not_on_the_blacklist.wav
│   │           │   │   ├── ivr-is_now_off.wav
│   │           │   │   ├── ivr-is_now_on.wav
│   │           │   │   ├── ivr-it_appears_that_your_phone_number_is.wav
│   │           │   │   ├── ivr-it_was_that_bug.wav
│   │           │   │   ├── ivr-key.wav
│   │           │   │   ├── ivr-last_name_first.wav
│   │           │   │   ├── ivr-learn_more_freeguipydotorg.wav
│   │           │   │   ├── ivr-less_than.wav
│   │           │   │   ├── ivr-longer_than_usual_hold_times.wav
│   │           │   │   ├── ivr-love_those_touch_tones.wav
│   │           │   │   ├── ivr-lunch_mode.wav
│   │           │   │   ├── ivr-message_self_destruct.wav
│   │           │   │   ├── ivr-modify_main_prompts.wav
│   │           │   │   ├── ivr-modify_main_prompt.wav
│   │           │   │   ├── ivr-modify_option_prompts.wav
│   │           │   │   ├── ivr-more_than.wav
│   │           │   │   ├── ivr-next_billing_cycle.wav
│   │           │   │   ├── ivr-night_mode.wav
│   │           │   │   ├── ivr-nobody_got_time_for_that.wav
│   │           │   │   ├── ivr-no_calls_waiting_in_queue.wav
│   │           │   │   ├── ivr-no_longer_in_queue.wav
│   │           │   │   ├── ivr-no_menu_items.wav
│   │           │   │   ├── ivr-no_no_no.wav
│   │           │   │   ├── ivr-no_questions_in_queue.wav
│   │           │   │   ├── ivr-normal_clearing.wav
│   │           │   │   ├── ivr-normal_unspecified.wav
│   │           │   │   ├── ivr-no_route_destination.wav
│   │           │   │   ├── ivr-no_shoes.wav
│   │           │   │   ├── ivr-not_accept_anonymous_calls.wav
│   │           │   │   ├── ivr-not_have_permission_to_edit.wav
│   │           │   │   ├── ivr-not_have_permission.wav
│   │           │   │   ├── ivr-not_requested_wakeup_call.wav
│   │           │   │   ├── ivr-not.wav
│   │           │   │   ├── ivr-no_user_response.wav
│   │           │   │   ├── ivr-number.wav
│   │           │   │   ├── ivr-oh_whatever.wav
│   │           │   │   ├── ivr-one_moment_please.wav
│   │           │   │   ├── ivr-one_more_mistake.wav
│   │           │   │   ├── ivr-one_time_wakeup_call.wav
│   │           │   │   ├── ivr-one_yes_two_no.wav
│   │           │   │   ├── ivr-on_hold_indefinitely.wav
│   │           │   │   ├── ivr-operator.wav
│   │           │   │   ├── ivr-option.wav
│   │           │   │   ├── ivr-or_press.wav
│   │           │   │   ├── ivr-or.wav
│   │           │   │   ├── ivr-out_of.wav
│   │           │   │   ├── ivr-perform_delayed_echo_test.wav
│   │           │   │   ├── ivr-perform_dtmf_test.wav
│   │           │   │   ├── ivr-perform_echo_test.wav
│   │           │   │   ├── ivr-per_minute.wav
│   │           │   │   ├── ivr-phone_is_configured_properly.wav
│   │           │   │   ├── ivr-phone_is_unassigned.wav
│   │           │   │   ├── ivr-phone_not_configured.wav
│   │           │   │   ├── ivr-phone_not_make_external_calls.wav
│   │           │   │   ├── ivr-pin_or_extension_is-invalid.wav
│   │           │   │   ├── ivr-please_check_number_try_again.wav
│   │           │   │   ├── ivr-please_contact.wav
│   │           │   │   ├── ivr-please_enjoy_music_while_party_reached.wav
│   │           │   │   ├── ivr-please_enter_extension_followed_by_pound.wav
│   │           │   │   ├── ivr-please_enter_extension_number_of.wav
│   │           │   │   ├── ivr-please_enter_pin_followed_by_pound.wav
│   │           │   │   ├── ivr-please_enter_the_number_where_we_can_reach_you.wav
│   │           │   │   ├── ivr-please_enter_the_phone_number.wav
│   │           │   │   ├── ivr-please_enter_the.wav
│   │           │   │   ├── ivr-please_hold_while_party_contacted.wav
│   │           │   │   ├── ivr-please_reenter_your_pin.wav
│   │           │   │   ├── ivr-please_return_our_call_at.wav
│   │           │   │   ├── ivr-please_state_your_name_and_reason_for_calling.wav
│   │           │   │   ├── ivr-please_try_again.wav
│   │           │   │   ├── ivr-please.wav
│   │           │   │   ├── ivr-press_key_of_prompt_to_modify.wav
│   │           │   │   ├── ivr-press_one_q_or_z.wav
│   │           │   │   ├── ivr-prompt.wav
│   │           │   │   ├── ivr-provision_phone_permanently_to_extension.wav
│   │           │   │   ├── ivr-questions.wav
│   │           │   │   ├── ivr-question.wav
│   │           │   │   ├── ivr-read_each_key_press_back.wav
│   │           │   │   ├── ivr-record_exit_sound.wav
│   │           │   │   ├── ivr-recording_deleted.wav
│   │           │   │   ├── ivr-recording_paused.wav
│   │           │   │   ├── ivr-recording_saved.wav
│   │           │   │   ├── ivr-recording_started.wav
│   │           │   │   ├── ivr-recording_stopped.wav
│   │           │   │   ├── ivr-record_invalid_sound.wav
│   │           │   │   ├── ivr-record_prompt.wav
│   │           │   │   ├── ivr-record_short_greeting.wav
│   │           │   │   ├── ivr-regarding_reference_number.wav
│   │           │   │   ├── ivr-register_for_cluecon.wav
│   │           │   │   ├── ivr-reminder_for.wav
│   │           │   │   ├── ivr-repeat_this_information.wav
│   │           │   │   ├── ivr-requested_wakeup_call_for.wav
│   │           │   │   ├── ivr-request_or_use_pin.wav
│   │           │   │   ├── ivr-request_wakeup_call.wav
│   │           │   │   ├── ivr-reset_usage_totals_confirm.wav
│   │           │   │   ├── ivr-reset_usage_totals.wav
│   │           │   │   ├── ivr-sales.wav
│   │           │   │   ├── ivr-sample_submenu.wav
│   │           │   │   ├── ivr-save_review_record.wav
│   │           │   │   ├── ivr-say_name.wav
│   │           │   │   ├── ivr-send_fax_now.wav
│   │           │   │   ├── ivr-send_fax.wav
│   │           │   │   ├── ivr-send_to_voicemail.wav
│   │           │   │   ├── ivr-seriously_mean_to_press_key.wav
│   │           │   │   ├── ivr-short_greeting.wav
│   │           │   │   ├── ivr-skip_instructions.wav
│   │           │   │   ├── ivr-smoke_got_you.wav
│   │           │   │   ├── ivr-speak_to_a_customer_service_representative.wav
│   │           │   │   ├── ivr-spell_name.wav
│   │           │   │   ├── ivr-stay_on_line_call_answered_momentarily.wav
│   │           │   │   ├── ivr-sucks.wav
│   │           │   │   ├── ivr-suck.wav
│   │           │   │   ├── ivr-system_back_up_in_approximately.wav
│   │           │   │   ├── ivr-system_down_for_maintenance.wav
│   │           │   │   ├── ivr-take_a_message.wav
│   │           │   │   ├── ivr-technical_support.wav
│   │           │   │   ├── ivr-terribly_wrong_awkward.wav
│   │           │   │   ├── ivr-thank_you_for_calling.wav
│   │           │   │   ├── ivr-thank_you_for_holding.wav
│   │           │   │   ├── ivr-thank_you.wav
│   │           │   │   ├── ivr-that_was_an_invalid_entry.wav
│   │           │   │   ├── ivr-that_you_would_like_to_modify.wav
│   │           │   │   ├── ivr-the_billing_department.wav
│   │           │   │   ├── ivr-there_are.wav
│   │           │   │   ├── ivr-there_is.wav
│   │           │   │   ├── ivr-this_feature.wav
│   │           │   │   ├── ivr-this_is_a_call_from.wav
│   │           │   │   ├── ivr-this_is_your_wakeup_call.wav
│   │           │   │   ├── ivr-this_ivr_will_let_you_test_features.wav
│   │           │   │   ├── ivr-this_phone_will_now_reboot.wav
│   │           │   │   ├── ivr-to_accept_press_one.wav
│   │           │   │   ├── ivr-to_accept_press.wav
│   │           │   │   ├── ivr-to_call_the_freeswitch_conference.wav
│   │           │   │   ├── ivr-to_confirm.wav
│   │           │   │   ├── ivr-to_do_a_freeswitch_echo_test.wav
│   │           │   │   ├── ivr-to_do_a_fwd_echo_test.wav
│   │           │   │   ├── ivr-to_hear_sample_submenu.wav
│   │           │   │   ├── ivr-to_hear_screaming_monkeys.wav
│   │           │   │   ├── ivr-to_learn_more_about_freeswitch.wav
│   │           │   │   ├── ivr-to_listen_to_moh.wav
│   │           │   │   ├── ivr-to_log_in.wav
│   │           │   │   ├── ivr-to_log_out.wav
│   │           │   │   ├── ivr-to_modify.wav
│   │           │   │   ├── ivr-to_redial_last_call.wav
│   │           │   │   ├── ivr-to_reject_hangup.wav
│   │           │   │   ├── ivr-to_reject.wav
│   │           │   │   ├── ivr-to_repeat_these_options.wav
│   │           │   │   ├── ivr-to_return_to_previous_menu.wav
│   │           │   │   ├── ivr-to_skip.wav
│   │           │   │   ├── ivr-to_speak_with_an_operator.wav
│   │           │   │   ├── ivr-to_wait_stay_on_the_line.wav
│   │           │   │   ├── ivr-trollover_minutes.wav
│   │           │   │   ├── ivr-unable_save.wav
│   │           │   │   ├── ivr-unallocated_number.wav
│   │           │   │   ├── ivr-unblock_caller_id.wav
│   │           │   │   ├── ivr-units.wav
│   │           │   │   ├── ivr-usage_totals_have_been_reset.wav
│   │           │   │   ├── ivr-user_busy.wav
│   │           │   │   ├── ivr-use_telephone_keypad.wav
│   │           │   │   ├── ivr-using_telephone_keypad.wav
│   │           │   │   ├── ivr-visitors.wav
│   │           │   │   ├── ivr-visitor.wav
│   │           │   │   ├── ivr-wakeup_call_cancelled.wav
│   │           │   │   ├── ivr-wakeup_call.wav
│   │           │   │   ├── ivr-wakey_wakey_sunshine.wav
│   │           │   │   ├── ivr-welcome_to_freeswitch.wav
│   │           │   │   ├── ivr-welcome_to.wav
│   │           │   │   ├── ivr-welcome.wav
│   │           │   │   ├── ivr-were_asterisk_free.wav
│   │           │   │   ├── ivr-we_will_return_your_call_at_this_number.wav
│   │           │   │   ├── ivr-we_would_support.wav
│   │           │   │   ├── ivr-when_finished_press_any_key.wav
│   │           │   │   ├── ivr-withdrawn.wav
│   │           │   │   ├── ivr-would_you_like_to_receive_a_call_at_this_number.wav
│   │           │   │   ├── ivr-yes_we_have_no_bananas.wav
│   │           │   │   ├── ivr-you_are_about_to_provision_this_phone.wav
│   │           │   │   ├── ivr-you_are_now_logged_in.wav
│   │           │   │   ├── ivr-you_are_now_logged_out.wav
│   │           │   │   ├── ivr-you_are_number_one.wav
│   │           │   │   ├── ivr-you_are_number.wav
│   │           │   │   ├── ivr-you_are_the.wav
│   │           │   │   ├── ivr-you_entered.wav
│   │           │   │   ├── ivr-you_have_dialed_an_invalid_extension.wav
│   │           │   │   ├── ivr-you_have_used.wav
│   │           │   │   ├── ivr-you_lose.wav
│   │           │   │   ├── ivr-you_may_exit_by_hanging_up.wav
│   │           │   │   ├── ivr-you_may.wav
│   │           │   │   ├── ivr-your_caller_id_information_is.wav
│   │           │   │   ├── ivr-your_caller_id_number_is_blocked.wav
│   │           │   │   ├── ivr-youre_doing_it_wrong.wav
│   │           │   │   └── ivr-yuno_silent_drill.wav
│   │           │   ├── 32000
│   │           │   │   ├── ivr-accept_reject_voicemail.wav
│   │           │   │   ├── ivr-accept_reject.wav
│   │           │   │   ├── ivr-access_denied.wav
│   │           │   │   ├── ivr-account_balance_is.wav
│   │           │   │   ├── ivr-account_number.wav
│   │           │   │   ├── ivr-aint_nobody_got_time_for_that.wav
│   │           │   │   ├── ivr-all_your_call_are_belong_to_us.wav
│   │           │   │   ├── ivr-already_contains_a_recording.wav
│   │           │   │   ├── ivr-anonymous_caller.wav
│   │           │   │   ├── ivr-any_other_digit.wav
│   │           │   │   ├── ivr-appointment_schedule_for.wav
│   │           │   │   ├── ivr-asterisk_like_syphilis.wav
│   │           │   │   ├── ivr-at_the_tone.wav
│   │           │   │   ├── ivr-automated_attendants.wav
│   │           │   │   ├── ivr-automated_attendant.wav
│   │           │   │   ├── ivr-barbecuing.wav
│   │           │   │   ├── ivr-barracuda_networks.wav
│   │           │   │   ├── ivr-beacuase.wav
│   │           │   │   ├── ivr-begin_recording.wav
│   │           │   │   ├── ivr-by_dialing.wav
│   │           │   │   ├── ivr-call_answered_order_received.wav
│   │           │   │   ├── ivr-call_attempt_aborted.wav
│   │           │   │   ├── ivr-call_being_transferred.wav
│   │           │   │   ├── ivr-call_cannot_be_completed_as_dialed.wav
│   │           │   │   ├── ivr-call_forwarding_has_been_cancelled.wav
│   │           │   │   ├── ivr-call_forwarding_has_been_set.wav
│   │           │   │   ├── ivr-call_from.wav
│   │           │   │   ├── ivr-call_rejected.wav
│   │           │   │   ├── ivr-call_screening_disabled.wav
│   │           │   │   ├── ivr-call_screening_enabled.wav
│   │           │   │   ├── ivr-call.wav
│   │           │   │   ├── ivr-cancel_wakeup_call.wav
│   │           │   │   ├── ivr-cold_foolish.wav
│   │           │   │   ├── ivr-cold_pop.wav
│   │           │   │   ├── ivr-concentrate.wav
│   │           │   │   ├── ivr-congratulations_you_pressed_star.wav
│   │           │   │   ├── ivr-connect_actual_human_being.wav
│   │           │   │   ├── ivr_connect_live_operator.wav
│   │           │   │   ├── ivr-connect_to_caller.wav
│   │           │   │   ├── ivr-contact_system_administrator.wav
│   │           │   │   ├── ivr-credit_card_could_not_be_charged.wav
│   │           │   │   ├── ivr-cudatel_communication_server.wav
│   │           │   │   ├── ivr-customer_service.wav
│   │           │   │   ├── ivr-custom_mode_number.wav
│   │           │   │   ├── ivr-daily_wakeup_call.wav
│   │           │   │   ├── ivr-day_mode.wav
│   │           │   │   ├── ivr-delayed_echo_your_audio_back.wav
│   │           │   │   ├── ivr-did_you_mean_to_press_key.wav
│   │           │   │   ├── ivr-disabled.wav
│   │           │   │   ├── ivr-dnd_activated.wav
│   │           │   │   ├── ivr-dnd_cancelled.wav
│   │           │   │   ├── ivr-does_not_contain_a_recording.wav
│   │           │   │   ├── ivr-do_not_call_list.wav
│   │           │   │   ├── ivr-douche_telecom.wav
│   │           │   │   ├── ivr-dude_you_suck.wav
│   │           │   │   ├── ivr-echo_your_audio_back.wav
│   │           │   │   ├── ivr-enabled.wav
│   │           │   │   ├── ivr-engineers_busy_assisting_other_sales.wav
│   │           │   │   ├── ivr-enjoy_music_while_transfer.wav
│   │           │   │   ├── ivr-ensure_service_keeps_working.wav
│   │           │   │   ├── ivr-enter_destination_telephone_number.wav
│   │           │   │   ├── ivr-enter_ext_pound.wav
│   │           │   │   ├── ivr-enter_ext.wav
│   │           │   │   ├── ivr-enter_number_send_fax.wav
│   │           │   │   ├── ivr-enter_number_to_add_to_blacklist.wav
│   │           │   │   ├── ivr-enter_number_to_remove_from_blacklist.wav
│   │           │   │   ├── ivr-enter_queue_number.wav
│   │           │   │   ├── ivr-enter_source_telephone_number.wav
│   │           │   │   ├── ivr-estimated_hold_time.wav
│   │           │   │   ├── ivr-exit_sound_prompt.wav
│   │           │   │   ├── ivr-extension_number.wav
│   │           │   │   ├── ivr-extension_to_provision_this_phone.wav
│   │           │   │   ├── ivr-failure_reason_is.wav
│   │           │   │   ├── ivr-feature.wav
│   │           │   │   ├── ivr-file_a_jira.wav
│   │           │   │   ├── ivr-files.wav
│   │           │   │   ├── ivr-file.wav
│   │           │   │   ├── ivr-finished_pound_hash_key.wav
│   │           │   │   ├── ivr-first_name_first.wav
│   │           │   │   ├── ivr-followed_by_pound.wav
│   │           │   │   ├── ivr-for_a_wakeup_call.wav
│   │           │   │   ├── ivr-for_daily_wakeup_calls.wav
│   │           │   │   ├── ivr-for_daily_wakeup_call.wav
│   │           │   │   ├── ivr-for_directory_press.wav
│   │           │   │   ├── ivr-for_english_press.wav
│   │           │   │   ├── ivr-for_one_time_wakeup_call.wav
│   │           │   │   ├── ivr-for_other_options.wav
│   │           │   │   ├── ivr-for_this_person.wav
│   │           │   │   ├── ivr-for.wav
│   │           │   │   ├── ivr-founder_of_freesource.wav
│   │           │   │   ├── ivr-freeguipy.wav
│   │           │   │   ├── ivr-gateway_down.wav
│   │           │   │   ├── ivr-generic_greeting.wav
│   │           │   │   ├── ivr-good_afternoon.wav
│   │           │   │   ├── ivr-good_evening.wav
│   │           │   │   ├── ivr-good_morning.wav
│   │           │   │   ├── ivr-got_bronchitis.wav
│   │           │   │   ├── ivr-hangup_to_discard.wav
│   │           │   │   ├── ivr-hangup_to_end_test.wav
│   │           │   │   ├── ivr-hang_up.wav
│   │           │   │   ├── ivr-has_been_added_to_the_blacklist.wav
│   │           │   │   ├── ivr-has_been_answered.wav
│   │           │   │   ├── ivr-has_been_removed_from_blacklist.wav
│   │           │   │   ├── ivr-has_been_removed.wav
│   │           │   │   ├── ivr-has_called_emergency_services.wav
│   │           │   │   ├── ivr-has_had.wav
│   │           │   │   ├── ivr-has_left_the_building.wav
│   │           │   │   ├── ivr-hear_usage_stats.wav
│   │           │   │   ├── ivr-hello.wav
│   │           │   │   ├── ivr-hold_connect_call.wav
│   │           │   │   ├── ivr-hotseat_intro.wav
│   │           │   │   ├── ivr-hotseat_options.wav
│   │           │   │   ├── ivr-hotseat_pin.wav
│   │           │   │   ├── ivr-id_number.wav
│   │           │   │   ├── ivr-if_correct_one_if_not_two.wav
│   │           │   │   ├── ivr-if_correct_press.wav
│   │           │   │   ├── ivr-if_not_press.wav
│   │           │   │   ├── ivr-if_you_would_like_us_to_call_back.wav
│   │           │   │   ├── ivr-im_sorry.wav
│   │           │   │   ├── ivr-incoming_call.wav
│   │           │   │   ├── ivr-incompatible_destination.wav
│   │           │   │   ├── ivr-in_line.wav
│   │           │   │   ├── ivr-invalid_extension_try_again.wav
│   │           │   │   ├── ivr-invalid_number_format.wav
│   │           │   │   ├── ivr-invalid_sound_prompt.wav
│   │           │   │   ├── ivr-is_already_on_the_blacklist.wav
│   │           │   │   ├── ivr-is_not_on_the_blacklist.wav
│   │           │   │   ├── ivr-is_now_off.wav
│   │           │   │   ├── ivr-is_now_on.wav
│   │           │   │   ├── ivr-it_appears_that_your_phone_number_is.wav
│   │           │   │   ├── ivr-it_was_that_bug.wav
│   │           │   │   ├── ivr-key.wav
│   │           │   │   ├── ivr-last_name_first.wav
│   │           │   │   ├── ivr-learn_more_freeguipydotorg.wav
│   │           │   │   ├── ivr-less_than.wav
│   │           │   │   ├── ivr-longer_than_usual_hold_times.wav
│   │           │   │   ├── ivr-love_those_touch_tones.wav
│   │           │   │   ├── ivr-lunch_mode.wav
│   │           │   │   ├── ivr-message_self_destruct.wav
│   │           │   │   ├── ivr-modify_main_prompts.wav
│   │           │   │   ├── ivr-modify_main_prompt.wav
│   │           │   │   ├── ivr-modify_option_prompts.wav
│   │           │   │   ├── ivr-more_than.wav
│   │           │   │   ├── ivr-next_billing_cycle.wav
│   │           │   │   ├── ivr-night_mode.wav
│   │           │   │   ├── ivr-nobody_got_time_for_that.wav
│   │           │   │   ├── ivr-no_calls_waiting_in_queue.wav
│   │           │   │   ├── ivr-no_longer_in_queue.wav
│   │           │   │   ├── ivr-no_menu_items.wav
│   │           │   │   ├── ivr-no_no_no.wav
│   │           │   │   ├── ivr-no_questions_in_queue.wav
│   │           │   │   ├── ivr-normal_clearing.wav
│   │           │   │   ├── ivr-normal_unspecified.wav
│   │           │   │   ├── ivr-no_route_destination.wav
│   │           │   │   ├── ivr-no_shoes.wav
│   │           │   │   ├── ivr-not_accept_anonymous_calls.wav
│   │           │   │   ├── ivr-not_have_permission_to_edit.wav
│   │           │   │   ├── ivr-not_have_permission.wav
│   │           │   │   ├── ivr-not_requested_wakeup_call.wav
│   │           │   │   ├── ivr-not.wav
│   │           │   │   ├── ivr-no_user_response.wav
│   │           │   │   ├── ivr-number.wav
│   │           │   │   ├── ivr-oh_whatever.wav
│   │           │   │   ├── ivr-one_moment_please.wav
│   │           │   │   ├── ivr-one_more_mistake.wav
│   │           │   │   ├── ivr-one_time_wakeup_call.wav
│   │           │   │   ├── ivr-one_yes_two_no.wav
│   │           │   │   ├── ivr-on_hold_indefinitely.wav
│   │           │   │   ├── ivr-operator.wav
│   │           │   │   ├── ivr-option.wav
│   │           │   │   ├── ivr-or_press.wav
│   │           │   │   ├── ivr-or.wav
│   │           │   │   ├── ivr-out_of.wav
│   │           │   │   ├── ivr-perform_delayed_echo_test.wav
│   │           │   │   ├── ivr-perform_dtmf_test.wav
│   │           │   │   ├── ivr-perform_echo_test.wav
│   │           │   │   ├── ivr-per_minute.wav
│   │           │   │   ├── ivr-phone_is_configured_properly.wav
│   │           │   │   ├── ivr-phone_is_unassigned.wav
│   │           │   │   ├── ivr-phone_not_configured.wav
│   │           │   │   ├── ivr-phone_not_make_external_calls.wav
│   │           │   │   ├── ivr-pin_or_extension_is-invalid.wav
│   │           │   │   ├── ivr-please_check_number_try_again.wav
│   │           │   │   ├── ivr-please_contact.wav
│   │           │   │   ├── ivr-please_enjoy_music_while_party_reached.wav
│   │           │   │   ├── ivr-please_enter_extension_followed_by_pound.wav
│   │           │   │   ├── ivr-please_enter_extension_number_of.wav
│   │           │   │   ├── ivr-please_enter_pin_followed_by_pound.wav
│   │           │   │   ├── ivr-please_enter_the_number_where_we_can_reach_you.wav
│   │           │   │   ├── ivr-please_enter_the_phone_number.wav
│   │           │   │   ├── ivr-please_enter_the.wav
│   │           │   │   ├── ivr-please_hold_while_party_contacted.wav
│   │           │   │   ├── ivr-please_reenter_your_pin.wav
│   │           │   │   ├── ivr-please_return_our_call_at.wav
│   │           │   │   ├── ivr-please_state_your_name_and_reason_for_calling.wav
│   │           │   │   ├── ivr-please_try_again.wav
│   │           │   │   ├── ivr-please.wav
│   │           │   │   ├── ivr-press_key_of_prompt_to_modify.wav
│   │           │   │   ├── ivr-press_one_q_or_z.wav
│   │           │   │   ├── ivr-prompt.wav
│   │           │   │   ├── ivr-provision_phone_permanently_to_extension.wav
│   │           │   │   ├── ivr-questions.wav
│   │           │   │   ├── ivr-question.wav
│   │           │   │   ├── ivr-read_each_key_press_back.wav
│   │           │   │   ├── ivr-record_exit_sound.wav
│   │           │   │   ├── ivr-recording_deleted.wav
│   │           │   │   ├── ivr-recording_paused.wav
│   │           │   │   ├── ivr-recording_saved.wav
│   │           │   │   ├── ivr-recording_started.wav
│   │           │   │   ├── ivr-recording_stopped.wav
│   │           │   │   ├── ivr-record_invalid_sound.wav
│   │           │   │   ├── ivr-record_prompt.wav
│   │           │   │   ├── ivr-record_short_greeting.wav
│   │           │   │   ├── ivr-regarding_reference_number.wav
│   │           │   │   ├── ivr-register_for_cluecon.wav
│   │           │   │   ├── ivr-reminder_for.wav
│   │           │   │   ├── ivr-repeat_this_information.wav
│   │           │   │   ├── ivr-requested_wakeup_call_for.wav
│   │           │   │   ├── ivr-request_or_use_pin.wav
│   │           │   │   ├── ivr-request_wakeup_call.wav
│   │           │   │   ├── ivr-reset_usage_totals_confirm.wav
│   │           │   │   ├── ivr-reset_usage_totals.wav
│   │           │   │   ├── ivr-sales.wav
│   │           │   │   ├── ivr-sample_submenu.wav
│   │           │   │   ├── ivr-save_review_record.wav
│   │           │   │   ├── ivr-say_name.wav
│   │           │   │   ├── ivr-send_fax_now.wav
│   │           │   │   ├── ivr-send_fax.wav
│   │           │   │   ├── ivr-send_to_voicemail.wav
│   │           │   │   ├── ivr-seriously_mean_to_press_key.wav
│   │           │   │   ├── ivr-short_greeting.wav
│   │           │   │   ├── ivr-skip_instructions.wav
│   │           │   │   ├── ivr-smoke_got_you.wav
│   │           │   │   ├── ivr-speak_to_a_customer_service_representative.wav
│   │           │   │   ├── ivr-spell_name.wav
│   │           │   │   ├── ivr-stay_on_line_call_answered_momentarily.wav
│   │           │   │   ├── ivr-sucks.wav
│   │           │   │   ├── ivr-suck.wav
│   │           │   │   ├── ivr-system_back_up_in_approximately.wav
│   │           │   │   ├── ivr-system_down_for_maintenance.wav
│   │           │   │   ├── ivr-take_a_message.wav
│   │           │   │   ├── ivr-technical_support.wav
│   │           │   │   ├── ivr-terribly_wrong_awkward.wav
│   │           │   │   ├── ivr-thank_you_for_calling.wav
│   │           │   │   ├── ivr-thank_you_for_holding.wav
│   │           │   │   ├── ivr-thank_you.wav
│   │           │   │   ├── ivr-that_was_an_invalid_entry.wav
│   │           │   │   ├── ivr-that_you_would_like_to_modify.wav
│   │           │   │   ├── ivr-the_billing_department.wav
│   │           │   │   ├── ivr-there_are.wav
│   │           │   │   ├── ivr-there_is.wav
│   │           │   │   ├── ivr-this_feature.wav
│   │           │   │   ├── ivr-this_is_a_call_from.wav
│   │           │   │   ├── ivr-this_is_your_wakeup_call.wav
│   │           │   │   ├── ivr-this_ivr_will_let_you_test_features.wav
│   │           │   │   ├── ivr-this_phone_will_now_reboot.wav
│   │           │   │   ├── ivr-to_accept_press_one.wav
│   │           │   │   ├── ivr-to_accept_press.wav
│   │           │   │   ├── ivr-to_call_the_freeswitch_conference.wav
│   │           │   │   ├── ivr-to_confirm.wav
│   │           │   │   ├── ivr-to_do_a_freeswitch_echo_test.wav
│   │           │   │   ├── ivr-to_do_a_fwd_echo_test.wav
│   │           │   │   ├── ivr-to_hear_sample_submenu.wav
│   │           │   │   ├── ivr-to_hear_screaming_monkeys.wav
│   │           │   │   ├── ivr-to_learn_more_about_freeswitch.wav
│   │           │   │   ├── ivr-to_listen_to_moh.wav
│   │           │   │   ├── ivr-to_log_in.wav
│   │           │   │   ├── ivr-to_log_out.wav
│   │           │   │   ├── ivr-to_modify.wav
│   │           │   │   ├── ivr-to_redial_last_call.wav
│   │           │   │   ├── ivr-to_reject_hangup.wav
│   │           │   │   ├── ivr-to_reject.wav
│   │           │   │   ├── ivr-to_repeat_these_options.wav
│   │           │   │   ├── ivr-to_return_to_previous_menu.wav
│   │           │   │   ├── ivr-to_skip.wav
│   │           │   │   ├── ivr-to_speak_with_an_operator.wav
│   │           │   │   ├── ivr-to_wait_stay_on_the_line.wav
│   │           │   │   ├── ivr-trollover_minutes.wav
│   │           │   │   ├── ivr-unable_save.wav
│   │           │   │   ├── ivr-unallocated_number.wav
│   │           │   │   ├── ivr-unblock_caller_id.wav
│   │           │   │   ├── ivr-units.wav
│   │           │   │   ├── ivr-usage_totals_have_been_reset.wav
│   │           │   │   ├── ivr-user_busy.wav
│   │           │   │   ├── ivr-use_telephone_keypad.wav
│   │           │   │   ├── ivr-using_telephone_keypad.wav
│   │           │   │   ├── ivr-visitors.wav
│   │           │   │   ├── ivr-visitor.wav
│   │           │   │   ├── ivr-wakeup_call_cancelled.wav
│   │           │   │   ├── ivr-wakeup_call.wav
│   │           │   │   ├── ivr-wakey_wakey_sunshine.wav
│   │           │   │   ├── ivr-welcome_to_freeswitch.wav
│   │           │   │   ├── ivr-welcome_to.wav
│   │           │   │   ├── ivr-welcome.wav
│   │           │   │   ├── ivr-were_asterisk_free.wav
│   │           │   │   ├── ivr-we_will_return_your_call_at_this_number.wav
│   │           │   │   ├── ivr-we_would_support.wav
│   │           │   │   ├── ivr-when_finished_press_any_key.wav
│   │           │   │   ├── ivr-withdrawn.wav
│   │           │   │   ├── ivr-would_you_like_to_receive_a_call_at_this_number.wav
│   │           │   │   ├── ivr-yes_we_have_no_bananas.wav
│   │           │   │   ├── ivr-you_are_about_to_provision_this_phone.wav
│   │           │   │   ├── ivr-you_are_now_logged_in.wav
│   │           │   │   ├── ivr-you_are_now_logged_out.wav
│   │           │   │   ├── ivr-you_are_number_one.wav
│   │           │   │   ├── ivr-you_are_number.wav
│   │           │   │   ├── ivr-you_are_the.wav
│   │           │   │   ├── ivr-you_entered.wav
│   │           │   │   ├── ivr-you_have_dialed_an_invalid_extension.wav
│   │           │   │   ├── ivr-you_have_used.wav
│   │           │   │   ├── ivr-you_lose.wav
│   │           │   │   ├── ivr-you_may_exit_by_hanging_up.wav
│   │           │   │   ├── ivr-you_may.wav
│   │           │   │   ├── ivr-your_caller_id_information_is.wav
│   │           │   │   ├── ivr-your_caller_id_number_is_blocked.wav
│   │           │   │   ├── ivr-youre_doing_it_wrong.wav
│   │           │   │   └── ivr-yuno_silent_drill.wav
│   │           │   ├── 48000
│   │           │   │   ├── ivr-accept_reject_voicemail.wav
│   │           │   │   ├── ivr-accept_reject.wav
│   │           │   │   ├── ivr-access_denied.wav
│   │           │   │   ├── ivr-account_balance_is.wav
│   │           │   │   ├── ivr-account_number.wav
│   │           │   │   ├── ivr-aint_nobody_got_time_for_that.wav
│   │           │   │   ├── ivr-all_your_call_are_belong_to_us.wav
│   │           │   │   ├── ivr-already_contains_a_recording.wav
│   │           │   │   ├── ivr-anonymous_caller.wav
│   │           │   │   ├── ivr-any_other_digit.wav
│   │           │   │   ├── ivr-appointment_schedule_for.wav
│   │           │   │   ├── ivr-asterisk_like_syphilis.wav
│   │           │   │   ├── ivr-at_the_tone.wav
│   │           │   │   ├── ivr-automated_attendants.wav
│   │           │   │   ├── ivr-automated_attendant.wav
│   │           │   │   ├── ivr-barbecuing.wav
│   │           │   │   ├── ivr-barracuda_networks.wav
│   │           │   │   ├── ivr-beacuase.wav
│   │           │   │   ├── ivr-begin_recording.wav
│   │           │   │   ├── ivr-by_dialing.wav
│   │           │   │   ├── ivr-call_answered_order_received.wav
│   │           │   │   ├── ivr-call_attempt_aborted.wav
│   │           │   │   ├── ivr-call_being_transferred.wav
│   │           │   │   ├── ivr-call_cannot_be_completed_as_dialed.wav
│   │           │   │   ├── ivr-call_forwarding_has_been_cancelled.wav
│   │           │   │   ├── ivr-call_forwarding_has_been_set.wav
│   │           │   │   ├── ivr-call_from.wav
│   │           │   │   ├── ivr-call_rejected.wav
│   │           │   │   ├── ivr-call_screening_disabled.wav
│   │           │   │   ├── ivr-call_screening_enabled.wav
│   │           │   │   ├── ivr-call.wav
│   │           │   │   ├── ivr-cancel_wakeup_call.wav
│   │           │   │   ├── ivr-cold_foolish.wav
│   │           │   │   ├── ivr-cold_pop.wav
│   │           │   │   ├── ivr-concentrate.wav
│   │           │   │   ├── ivr-congratulations_you_pressed_star.wav
│   │           │   │   ├── ivr-connect_actual_human_being.wav
│   │           │   │   ├── ivr_connect_live_operator.wav
│   │           │   │   ├── ivr-connect_to_caller.wav
│   │           │   │   ├── ivr-contact_system_administrator.wav
│   │           │   │   ├── ivr-credit_card_could_not_be_charged.wav
│   │           │   │   ├── ivr-cudatel_communication_server.wav
│   │           │   │   ├── ivr-customer_service.wav
│   │           │   │   ├── ivr-custom_mode_number.wav
│   │           │   │   ├── ivr-daily_wakeup_call.wav
│   │           │   │   ├── ivr-day_mode.wav
│   │           │   │   ├── ivr-delayed_echo_your_audio_back.wav
│   │           │   │   ├── ivr-did_you_mean_to_press_key.wav
│   │           │   │   ├── ivr-disabled.wav
│   │           │   │   ├── ivr-dnd_activated.wav
│   │           │   │   ├── ivr-dnd_cancelled.wav
│   │           │   │   ├── ivr-does_not_contain_a_recording.wav
│   │           │   │   ├── ivr-do_not_call_list.wav
│   │           │   │   ├── ivr-douche_telecom.wav
│   │           │   │   ├── ivr-dude_you_suck.wav
│   │           │   │   ├── ivr-echo_your_audio_back.wav
│   │           │   │   ├── ivr-enabled.wav
│   │           │   │   ├── ivr-engineers_busy_assisting_other_sales.wav
│   │           │   │   ├── ivr-enjoy_music_while_transfer.wav
│   │           │   │   ├── ivr-ensure_service_keeps_working.wav
│   │           │   │   ├── ivr-enter_destination_telephone_number.wav
│   │           │   │   ├── ivr-enter_ext_pound.wav
│   │           │   │   ├── ivr-enter_ext.wav
│   │           │   │   ├── ivr-enter_number_send_fax.wav
│   │           │   │   ├── ivr-enter_number_to_add_to_blacklist.wav
│   │           │   │   ├── ivr-enter_number_to_remove_from_blacklist.wav
│   │           │   │   ├── ivr-enter_queue_number.wav
│   │           │   │   ├── ivr-enter_source_telephone_number.wav
│   │           │   │   ├── ivr-estimated_hold_time.wav
│   │           │   │   ├── ivr-exit_sound_prompt.wav
│   │           │   │   ├── ivr-extension_number.wav
│   │           │   │   ├── ivr-extension_to_provision_this_phone.wav
│   │           │   │   ├── ivr-failure_reason_is.wav
│   │           │   │   ├── ivr-feature.wav
│   │           │   │   ├── ivr-file_a_jira.wav
│   │           │   │   ├── ivr-files.wav
│   │           │   │   ├── ivr-file.wav
│   │           │   │   ├── ivr-finished_pound_hash_key.wav
│   │           │   │   ├── ivr-first_name_first.wav
│   │           │   │   ├── ivr-followed_by_pound.wav
│   │           │   │   ├── ivr-for_a_wakeup_call.wav
│   │           │   │   ├── ivr-for_daily_wakeup_calls.wav
│   │           │   │   ├── ivr-for_daily_wakeup_call.wav
│   │           │   │   ├── ivr-for_directory_press.wav
│   │           │   │   ├── ivr-for_english_press.wav
│   │           │   │   ├── ivr-for_one_time_wakeup_call.wav
│   │           │   │   ├── ivr-for_other_options.wav
│   │           │   │   ├── ivr-for_this_person.wav
│   │           │   │   ├── ivr-for.wav
│   │           │   │   ├── ivr-founder_of_freesource.wav
│   │           │   │   ├── ivr-freeguipy.wav
│   │           │   │   ├── ivr-gateway_down.wav
│   │           │   │   ├── ivr-generic_greeting.wav
│   │           │   │   ├── ivr-good_afternoon.wav
│   │           │   │   ├── ivr-good_evening.wav
│   │           │   │   ├── ivr-good_morning.wav
│   │           │   │   ├── ivr-got_bronchitis.wav
│   │           │   │   ├── ivr-hangup_to_discard.wav
│   │           │   │   ├── ivr-hangup_to_end_test.wav
│   │           │   │   ├── ivr-hang_up.wav
│   │           │   │   ├── ivr-has_been_added_to_the_blacklist.wav
│   │           │   │   ├── ivr-has_been_answered.wav
│   │           │   │   ├── ivr-has_been_removed_from_blacklist.wav
│   │           │   │   ├── ivr-has_been_removed.wav
│   │           │   │   ├── ivr-has_called_emergency_services.wav
│   │           │   │   ├── ivr-has_had.wav
│   │           │   │   ├── ivr-has_left_the_building.wav
│   │           │   │   ├── ivr-hear_usage_stats.wav
│   │           │   │   ├── ivr-hello.wav
│   │           │   │   ├── ivr-hold_connect_call.wav
│   │           │   │   ├── ivr-hotseat_intro.wav
│   │           │   │   ├── ivr-hotseat_options.wav
│   │           │   │   ├── ivr-hotseat_pin.wav
│   │           │   │   ├── ivr-id_number.wav
│   │           │   │   ├── ivr-if_correct_one_if_not_two.wav
│   │           │   │   ├── ivr-if_correct_press.wav
│   │           │   │   ├── ivr-if_not_press.wav
│   │           │   │   ├── ivr-if_you_would_like_us_to_call_back.wav
│   │           │   │   ├── ivr-im_sorry.wav
│   │           │   │   ├── ivr-incoming_call.wav
│   │           │   │   ├── ivr-incompatible_destination.wav
│   │           │   │   ├── ivr-in_line.wav
│   │           │   │   ├── ivr-invalid_extension_try_again.wav
│   │           │   │   ├── ivr-invalid_number_format.wav
│   │           │   │   ├── ivr-invalid_sound_prompt.wav
│   │           │   │   ├── ivr-is_already_on_the_blacklist.wav
│   │           │   │   ├── ivr-is_not_on_the_blacklist.wav
│   │           │   │   ├── ivr-is_now_off.wav
│   │           │   │   ├── ivr-is_now_on.wav
│   │           │   │   ├── ivr-it_appears_that_your_phone_number_is.wav
│   │           │   │   ├── ivr-it_was_that_bug.wav
│   │           │   │   ├── ivr-key.wav
│   │           │   │   ├── ivr-last_name_first.wav
│   │           │   │   ├── ivr-learn_more_freeguipydotorg.wav
│   │           │   │   ├── ivr-less_than.wav
│   │           │   │   ├── ivr-longer_than_usual_hold_times.wav
│   │           │   │   ├── ivr-love_those_touch_tones.wav
│   │           │   │   ├── ivr-lunch_mode.wav
│   │           │   │   ├── ivr-message_self_destruct.wav
│   │           │   │   ├── ivr-modify_main_prompts.wav
│   │           │   │   ├── ivr-modify_main_prompt.wav
│   │           │   │   ├── ivr-modify_option_prompts.wav
│   │           │   │   ├── ivr-more_than.wav
│   │           │   │   ├── ivr-next_billing_cycle.wav
│   │           │   │   ├── ivr-night_mode.wav
│   │           │   │   ├── ivr-nobody_got_time_for_that.wav
│   │           │   │   ├── ivr-no_calls_waiting_in_queue.wav
│   │           │   │   ├── ivr-no_longer_in_queue.wav
│   │           │   │   ├── ivr-no_menu_items.wav
│   │           │   │   ├── ivr-no_no_no.wav
│   │           │   │   ├── ivr-no_questions_in_queue.wav
│   │           │   │   ├── ivr-normal_clearing.wav
│   │           │   │   ├── ivr-normal_unspecified.wav
│   │           │   │   ├── ivr-no_route_destination.wav
│   │           │   │   ├── ivr-no_shoes.wav
│   │           │   │   ├── ivr-not_accept_anonymous_calls.wav
│   │           │   │   ├── ivr-not_have_permission_to_edit.wav
│   │           │   │   ├── ivr-not_have_permission.wav
│   │           │   │   ├── ivr-not_requested_wakeup_call.wav
│   │           │   │   ├── ivr-not.wav
│   │           │   │   ├── ivr-no_user_response.wav
│   │           │   │   ├── ivr-number.wav
│   │           │   │   ├── ivr-oh_whatever.wav
│   │           │   │   ├── ivr-one_moment_please.wav
│   │           │   │   ├── ivr-one_more_mistake.wav
│   │           │   │   ├── ivr-one_time_wakeup_call.wav
│   │           │   │   ├── ivr-one_yes_two_no.wav
│   │           │   │   ├── ivr-on_hold_indefinitely.wav
│   │           │   │   ├── ivr-operator.wav
│   │           │   │   ├── ivr-option.wav
│   │           │   │   ├── ivr-or_press.wav
│   │           │   │   ├── ivr-or.wav
│   │           │   │   ├── ivr-out_of.wav
│   │           │   │   ├── ivr-perform_delayed_echo_test.wav
│   │           │   │   ├── ivr-perform_dtmf_test.wav
│   │           │   │   ├── ivr-perform_echo_test.wav
│   │           │   │   ├── ivr-per_minute.wav
│   │           │   │   ├── ivr-phone_is_configured_properly.wav
│   │           │   │   ├── ivr-phone_is_unassigned.wav
│   │           │   │   ├── ivr-phone_not_configured.wav
│   │           │   │   ├── ivr-phone_not_make_external_calls.wav
│   │           │   │   ├── ivr-pin_or_extension_is-invalid.wav
│   │           │   │   ├── ivr-please_check_number_try_again.wav
│   │           │   │   ├── ivr-please_contact.wav
│   │           │   │   ├── ivr-please_enjoy_music_while_party_reached.wav
│   │           │   │   ├── ivr-please_enter_extension_followed_by_pound.wav
│   │           │   │   ├── ivr-please_enter_extension_number_of.wav
│   │           │   │   ├── ivr-please_enter_pin_followed_by_pound.wav
│   │           │   │   ├── ivr-please_enter_the_number_where_we_can_reach_you.wav
│   │           │   │   ├── ivr-please_enter_the_phone_number.wav
│   │           │   │   ├── ivr-please_enter_the.wav
│   │           │   │   ├── ivr-please_hold_while_party_contacted.wav
│   │           │   │   ├── ivr-please_reenter_your_pin.wav
│   │           │   │   ├── ivr-please_return_our_call_at.wav
│   │           │   │   ├── ivr-please_state_your_name_and_reason_for_calling.wav
│   │           │   │   ├── ivr-please_try_again.wav
│   │           │   │   ├── ivr-please.wav
│   │           │   │   ├── ivr-press_key_of_prompt_to_modify.wav
│   │           │   │   ├── ivr-press_one_q_or_z.wav
│   │           │   │   ├── ivr-prompt.wav
│   │           │   │   ├── ivr-provision_phone_permanently_to_extension.wav
│   │           │   │   ├── ivr-questions.wav
│   │           │   │   ├── ivr-question.wav
│   │           │   │   ├── ivr-read_each_key_press_back.wav
│   │           │   │   ├── ivr-record_exit_sound.wav
│   │           │   │   ├── ivr-recording_deleted.wav
│   │           │   │   ├── ivr-recording_paused.wav
│   │           │   │   ├── ivr-recording_saved.wav
│   │           │   │   ├── ivr-recording_started.wav
│   │           │   │   ├── ivr-recording_stopped.wav
│   │           │   │   ├── ivr-record_invalid_sound.wav
│   │           │   │   ├── ivr-record_prompt.wav
│   │           │   │   ├── ivr-record_short_greeting.wav
│   │           │   │   ├── ivr-regarding_reference_number.wav
│   │           │   │   ├── ivr-register_for_cluecon.wav
│   │           │   │   ├── ivr-reminder_for.wav
│   │           │   │   ├── ivr-repeat_this_information.wav
│   │           │   │   ├── ivr-requested_wakeup_call_for.wav
│   │           │   │   ├── ivr-request_or_use_pin.wav
│   │           │   │   ├── ivr-request_wakeup_call.wav
│   │           │   │   ├── ivr-reset_usage_totals_confirm.wav
│   │           │   │   ├── ivr-reset_usage_totals.wav
│   │           │   │   ├── ivr-sales.wav
│   │           │   │   ├── ivr-sample_submenu.wav
│   │           │   │   ├── ivr-save_review_record.wav
│   │           │   │   ├── ivr-say_name.wav
│   │           │   │   ├── ivr-send_fax_now.wav
│   │           │   │   ├── ivr-send_fax.wav
│   │           │   │   ├── ivr-send_to_voicemail.wav
│   │           │   │   ├── ivr-seriously_mean_to_press_key.wav
│   │           │   │   ├── ivr-short_greeting.wav
│   │           │   │   ├── ivr-skip_instructions.wav
│   │           │   │   ├── ivr-smoke_got_you.wav
│   │           │   │   ├── ivr-speak_to_a_customer_service_representative.wav
│   │           │   │   ├── ivr-spell_name.wav
│   │           │   │   ├── ivr-stay_on_line_call_answered_momentarily.wav
│   │           │   │   ├── ivr-sucks.wav
│   │           │   │   ├── ivr-suck.wav
│   │           │   │   ├── ivr-system_back_up_in_approximately.wav
│   │           │   │   ├── ivr-system_down_for_maintenance.wav
│   │           │   │   ├── ivr-take_a_message.wav
│   │           │   │   ├── ivr-technical_support.wav
│   │           │   │   ├── ivr-terribly_wrong_awkward.wav
│   │           │   │   ├── ivr-thank_you_for_calling.wav
│   │           │   │   ├── ivr-thank_you_for_holding.wav
│   │           │   │   ├── ivr-thank_you.wav
│   │           │   │   ├── ivr-that_was_an_invalid_entry.wav
│   │           │   │   ├── ivr-that_you_would_like_to_modify.wav
│   │           │   │   ├── ivr-the_billing_department.wav
│   │           │   │   ├── ivr-there_are.wav
│   │           │   │   ├── ivr-there_is.wav
│   │           │   │   ├── ivr-this_feature.wav
│   │           │   │   ├── ivr-this_is_a_call_from.wav
│   │           │   │   ├── ivr-this_is_your_wakeup_call.wav
│   │           │   │   ├── ivr-this_ivr_will_let_you_test_features.wav
│   │           │   │   ├── ivr-this_phone_will_now_reboot.wav
│   │           │   │   ├── ivr-to_accept_press_one.wav
│   │           │   │   ├── ivr-to_accept_press.wav
│   │           │   │   ├── ivr-to_call_the_freeswitch_conference.wav
│   │           │   │   ├── ivr-to_confirm.wav
│   │           │   │   ├── ivr-to_do_a_freeswitch_echo_test.wav
│   │           │   │   ├── ivr-to_do_a_fwd_echo_test.wav
│   │           │   │   ├── ivr-to_hear_sample_submenu.wav
│   │           │   │   ├── ivr-to_hear_screaming_monkeys.wav
│   │           │   │   ├── ivr-to_learn_more_about_freeswitch.wav
│   │           │   │   ├── ivr-to_listen_to_moh.wav
│   │           │   │   ├── ivr-to_log_in.wav
│   │           │   │   ├── ivr-to_log_out.wav
│   │           │   │   ├── ivr-to_modify.wav
│   │           │   │   ├── ivr-to_redial_last_call.wav
│   │           │   │   ├── ivr-to_reject_hangup.wav
│   │           │   │   ├── ivr-to_reject.wav
│   │           │   │   ├── ivr-to_repeat_these_options.wav
│   │           │   │   ├── ivr-to_return_to_previous_menu.wav
│   │           │   │   ├── ivr-to_skip.wav
│   │           │   │   ├── ivr-to_speak_with_an_operator.wav
│   │           │   │   ├── ivr-to_wait_stay_on_the_line.wav
│   │           │   │   ├── ivr-trollover_minutes.wav
│   │           │   │   ├── ivr-unable_save.wav
│   │           │   │   ├── ivr-unallocated_number.wav
│   │           │   │   ├── ivr-unblock_caller_id.wav
│   │           │   │   ├── ivr-units.wav
│   │           │   │   ├── ivr-usage_totals_have_been_reset.wav
│   │           │   │   ├── ivr-user_busy.wav
│   │           │   │   ├── ivr-use_telephone_keypad.wav
│   │           │   │   ├── ivr-using_telephone_keypad.wav
│   │           │   │   ├── ivr-visitors.wav
│   │           │   │   ├── ivr-visitor.wav
│   │           │   │   ├── ivr-wakeup_call_cancelled.wav
│   │           │   │   ├── ivr-wakeup_call.wav
│   │           │   │   ├── ivr-wakey_wakey_sunshine.wav
│   │           │   │   ├── ivr-welcome_to_freeswitch.wav
│   │           │   │   ├── ivr-welcome_to.wav
│   │           │   │   ├── ivr-welcome.wav
│   │           │   │   ├── ivr-were_asterisk_free.wav
│   │           │   │   ├── ivr-we_will_return_your_call_at_this_number.wav
│   │           │   │   ├── ivr-we_would_support.wav
│   │           │   │   ├── ivr-when_finished_press_any_key.wav
│   │           │   │   ├── ivr-withdrawn.wav
│   │           │   │   ├── ivr-would_you_like_to_receive_a_call_at_this_number.wav
│   │           │   │   ├── ivr-yes_we_have_no_bananas.wav
│   │           │   │   ├── ivr-you_are_about_to_provision_this_phone.wav
│   │           │   │   ├── ivr-you_are_now_logged_in.wav
│   │           │   │   ├── ivr-you_are_now_logged_out.wav
│   │           │   │   ├── ivr-you_are_number_one.wav
│   │           │   │   ├── ivr-you_are_number.wav
│   │           │   │   ├── ivr-you_are_the.wav
│   │           │   │   ├── ivr-you_entered.wav
│   │           │   │   ├── ivr-you_have_dialed_an_invalid_extension.wav
│   │           │   │   ├── ivr-you_have_used.wav
│   │           │   │   ├── ivr-you_lose.wav
│   │           │   │   ├── ivr-you_may_exit_by_hanging_up.wav
│   │           │   │   ├── ivr-you_may.wav
│   │           │   │   ├── ivr-your_caller_id_information_is.wav
│   │           │   │   ├── ivr-your_caller_id_number_is_blocked.wav
│   │           │   │   ├── ivr-youre_doing_it_wrong.wav
│   │           │   │   └── ivr-yuno_silent_drill.wav
│   │           │   └── 8000
│   │           │       ├── ivr-accept_reject_voicemail.wav
│   │           │       ├── ivr-accept_reject.wav
│   │           │       ├── ivr-access_denied.wav
│   │           │       ├── ivr-account_balance_is.wav
│   │           │       ├── ivr-account_number.wav
│   │           │       ├── ivr-aint_nobody_got_time_for_that.wav
│   │           │       ├── ivr-all_your_call_are_belong_to_us.wav
│   │           │       ├── ivr-already_contains_a_recording.wav
│   │           │       ├── ivr-anonymous_caller.wav
│   │           │       ├── ivr-any_other_digit.wav
│   │           │       ├── ivr-appointment_schedule_for.wav
│   │           │       ├── ivr-asterisk_like_syphilis.wav
│   │           │       ├── ivr-at_the_tone.wav
│   │           │       ├── ivr-automated_attendants.wav
│   │           │       ├── ivr-automated_attendant.wav
│   │           │       ├── ivr-barbecuing.wav
│   │           │       ├── ivr-barracuda_networks.wav
│   │           │       ├── ivr-beacuase.wav
│   │           │       ├── ivr-begin_recording.wav
│   │           │       ├── ivr-by_dialing.wav
│   │           │       ├── ivr-call_answered_order_received.wav
│   │           │       ├── ivr-call_attempt_aborted.wav
│   │           │       ├── ivr-call_being_transferred.wav
│   │           │       ├── ivr-call_cannot_be_completed_as_dialed.wav
│   │           │       ├── ivr-call_forwarding_has_been_cancelled.wav
│   │           │       ├── ivr-call_forwarding_has_been_set.wav
│   │           │       ├── ivr-call_from.wav
│   │           │       ├── ivr-call_rejected.wav
│   │           │       ├── ivr-call_screening_disabled.wav
│   │           │       ├── ivr-call_screening_enabled.wav
│   │           │       ├── ivr-call.wav
│   │           │       ├── ivr-cancel_wakeup_call.wav
│   │           │       ├── ivr-cold_foolish.wav
│   │           │       ├── ivr-cold_pop.wav
│   │           │       ├── ivr-concentrate.wav
│   │           │       ├── ivr-congratulations_you_pressed_star.wav
│   │           │       ├── ivr-connect_actual_human_being.wav
│   │           │       ├── ivr_connect_live_operator.wav
│   │           │       ├── ivr-connect_to_caller.wav
│   │           │       ├── ivr-contact_system_administrator.wav
│   │           │       ├── ivr-credit_card_could_not_be_charged.wav
│   │           │       ├── ivr-cudatel_communication_server.wav
│   │           │       ├── ivr-customer_service.wav
│   │           │       ├── ivr-custom_mode_number.wav
│   │           │       ├── ivr-daily_wakeup_call.wav
│   │           │       ├── ivr-day_mode.wav
│   │           │       ├── ivr-delayed_echo_your_audio_back.wav
│   │           │       ├── ivr-did_you_mean_to_press_key.wav
│   │           │       ├── ivr-disabled.wav
│   │           │       ├── ivr-dnd_activated.wav
│   │           │       ├── ivr-dnd_cancelled.wav
│   │           │       ├── ivr-does_not_contain_a_recording.wav
│   │           │       ├── ivr-do_not_call_list.wav
│   │           │       ├── ivr-douche_telecom.wav
│   │           │       ├── ivr-dude_you_suck.wav
│   │           │       ├── ivr-echo_your_audio_back.wav
│   │           │       ├── ivr-enabled.wav
│   │           │       ├── ivr-engineers_busy_assisting_other_sales.wav
│   │           │       ├── ivr-enjoy_music_while_transfer.wav
│   │           │       ├── ivr-ensure_service_keeps_working.wav
│   │           │       ├── ivr-enter_destination_telephone_number.wav
│   │           │       ├── ivr-enter_ext_pound.wav
│   │           │       ├── ivr-enter_ext.wav
│   │           │       ├── ivr-enter_number_send_fax.wav
│   │           │       ├── ivr-enter_number_to_add_to_blacklist.wav
│   │           │       ├── ivr-enter_number_to_remove_from_blacklist.wav
│   │           │       ├── ivr-enter_queue_number.wav
│   │           │       ├── ivr-enter_source_telephone_number.wav
│   │           │       ├── ivr-estimated_hold_time.wav
│   │           │       ├── ivr-exit_sound_prompt.wav
│   │           │       ├── ivr-extension_number.wav
│   │           │       ├── ivr-extension_to_provision_this_phone.wav
│   │           │       ├── ivr-failure_reason_is.wav
│   │           │       ├── ivr-feature.wav
│   │           │       ├── ivr-file_a_jira.wav
│   │           │       ├── ivr-files.wav
│   │           │       ├── ivr-file.wav
│   │           │       ├── ivr-finished_pound_hash_key.wav
│   │           │       ├── ivr-first_name_first.wav
│   │           │       ├── ivr-followed_by_pound.wav
│   │           │       ├── ivr-for_a_wakeup_call.wav
│   │           │       ├── ivr-for_daily_wakeup_calls.wav
│   │           │       ├── ivr-for_daily_wakeup_call.wav
│   │           │       ├── ivr-for_directory_press.wav
│   │           │       ├── ivr-for_english_press.wav
│   │           │       ├── ivr-for_one_time_wakeup_call.wav
│   │           │       ├── ivr-for_other_options.wav
│   │           │       ├── ivr-for_this_person.wav
│   │           │       ├── ivr-for.wav
│   │           │       ├── ivr-founder_of_freesource.wav
│   │           │       ├── ivr-freeguipy.wav
│   │           │       ├── ivr-gateway_down.wav
│   │           │       ├── ivr-generic_greeting.wav
│   │           │       ├── ivr-good_afternoon.wav
│   │           │       ├── ivr-good_evening.wav
│   │           │       ├── ivr-good_morning.wav
│   │           │       ├── ivr-got_bronchitis.wav
│   │           │       ├── ivr-hangup_to_discard.wav
│   │           │       ├── ivr-hangup_to_end_test.wav
│   │           │       ├── ivr-hang_up.wav
│   │           │       ├── ivr-has_been_added_to_the_blacklist.wav
│   │           │       ├── ivr-has_been_answered.wav
│   │           │       ├── ivr-has_been_removed_from_blacklist.wav
│   │           │       ├── ivr-has_been_removed.wav
│   │           │       ├── ivr-has_called_emergency_services.wav
│   │           │       ├── ivr-has_had.wav
│   │           │       ├── ivr-has_left_the_building.wav
│   │           │       ├── ivr-hear_usage_stats.wav
│   │           │       ├── ivr-hello.wav
│   │           │       ├── ivr-hold_connect_call.wav
│   │           │       ├── ivr-hotseat_intro.wav
│   │           │       ├── ivr-hotseat_options.wav
│   │           │       ├── ivr-hotseat_pin.wav
│   │           │       ├── ivr-id_number.wav
│   │           │       ├── ivr-if_correct_one_if_not_two.wav
│   │           │       ├── ivr-if_correct_press.wav
│   │           │       ├── ivr-if_not_press.wav
│   │           │       ├── ivr-if_you_would_like_us_to_call_back.wav
│   │           │       ├── ivr-im_sorry.wav
│   │           │       ├── ivr-incoming_call.wav
│   │           │       ├── ivr-incompatible_destination.wav
│   │           │       ├── ivr-in_line.wav
│   │           │       ├── ivr-invalid_extension_try_again.wav
│   │           │       ├── ivr-invalid_number_format.wav
│   │           │       ├── ivr-invalid_sound_prompt.wav
│   │           │       ├── ivr-is_already_on_the_blacklist.wav
│   │           │       ├── ivr-is_not_on_the_blacklist.wav
│   │           │       ├── ivr-is_now_off.wav
│   │           │       ├── ivr-is_now_on.wav
│   │           │       ├── ivr-it_appears_that_your_phone_number_is.wav
│   │           │       ├── ivr-it_was_that_bug.wav
│   │           │       ├── ivr-key.wav
│   │           │       ├── ivr-last_name_first.wav
│   │           │       ├── ivr-learn_more_freeguipydotorg.wav
│   │           │       ├── ivr-less_than.wav
│   │           │       ├── ivr-longer_than_usual_hold_times.wav
│   │           │       ├── ivr-love_those_touch_tones.wav
│   │           │       ├── ivr-lunch_mode.wav
│   │           │       ├── ivr-message_self_destruct.wav
│   │           │       ├── ivr-modify_main_prompts.wav
│   │           │       ├── ivr-modify_main_prompt.wav
│   │           │       ├── ivr-modify_option_prompts.wav
│   │           │       ├── ivr-more_than.wav
│   │           │       ├── ivr-next_billing_cycle.wav
│   │           │       ├── ivr-night_mode.wav
│   │           │       ├── ivr-nobody_got_time_for_that.wav
│   │           │       ├── ivr-no_calls_waiting_in_queue.wav
│   │           │       ├── ivr-no_longer_in_queue.wav
│   │           │       ├── ivr-no_menu_items.wav
│   │           │       ├── ivr-no_no_no.wav
│   │           │       ├── ivr-no_questions_in_queue.wav
│   │           │       ├── ivr-normal_clearing.wav
│   │           │       ├── ivr-normal_unspecified.wav
│   │           │       ├── ivr-no_route_destination.wav
│   │           │       ├── ivr-no_shoes.wav
│   │           │       ├── ivr-not_accept_anonymous_calls.wav
│   │           │       ├── ivr-not_have_permission_to_edit.wav
│   │           │       ├── ivr-not_have_permission.wav
│   │           │       ├── ivr-not_requested_wakeup_call.wav
│   │           │       ├── ivr-not.wav
│   │           │       ├── ivr-no_user_response.wav
│   │           │       ├── ivr-number.wav
│   │           │       ├── ivr-oh_whatever.wav
│   │           │       ├── ivr-one_moment_please.wav
│   │           │       ├── ivr-one_more_mistake.wav
│   │           │       ├── ivr-one_time_wakeup_call.wav
│   │           │       ├── ivr-one_yes_two_no.wav
│   │           │       ├── ivr-on_hold_indefinitely.wav
│   │           │       ├── ivr-operator.wav
│   │           │       ├── ivr-option.wav
│   │           │       ├── ivr-or_press.wav
│   │           │       ├── ivr-or.wav
│   │           │       ├── ivr-out_of.wav
│   │           │       ├── ivr-perform_delayed_echo_test.wav
│   │           │       ├── ivr-perform_dtmf_test.wav
│   │           │       ├── ivr-perform_echo_test.wav
│   │           │       ├── ivr-per_minute.wav
│   │           │       ├── ivr-phone_is_configured_properly.wav
│   │           │       ├── ivr-phone_is_unassigned.wav
│   │           │       ├── ivr-phone_not_configured.wav
│   │           │       ├── ivr-phone_not_make_external_calls.wav
│   │           │       ├── ivr-pin_or_extension_is-invalid.wav
│   │           │       ├── ivr-please_check_number_try_again.wav
│   │           │       ├── ivr-please_contact.wav
│   │           │       ├── ivr-please_enjoy_music_while_party_reached.wav
│   │           │       ├── ivr-please_enter_extension_followed_by_pound.wav
│   │           │       ├── ivr-please_enter_extension_number_of.wav
│   │           │       ├── ivr-please_enter_pin_followed_by_pound.wav
│   │           │       ├── ivr-please_enter_the_number_where_we_can_reach_you.wav
│   │           │       ├── ivr-please_enter_the_phone_number.wav
│   │           │       ├── ivr-please_enter_the.wav
│   │           │       ├── ivr-please_hold_while_party_contacted.wav
│   │           │       ├── ivr-please_reenter_your_pin.wav
│   │           │       ├── ivr-please_return_our_call_at.wav
│   │           │       ├── ivr-please_state_your_name_and_reason_for_calling.wav
│   │           │       ├── ivr-please_try_again.wav
│   │           │       ├── ivr-please.wav
│   │           │       ├── ivr-press_key_of_prompt_to_modify.wav
│   │           │       ├── ivr-press_one_q_or_z.wav
│   │           │       ├── ivr-prompt.wav
│   │           │       ├── ivr-provision_phone_permanently_to_extension.wav
│   │           │       ├── ivr-questions.wav
│   │           │       ├── ivr-question.wav
│   │           │       ├── ivr-read_each_key_press_back.wav
│   │           │       ├── ivr-record_exit_sound.wav
│   │           │       ├── ivr-recording_deleted.wav
│   │           │       ├── ivr-recording_paused.wav
│   │           │       ├── ivr-recording_saved.wav
│   │           │       ├── ivr-recording_started.wav
│   │           │       ├── ivr-recording_stopped.wav
│   │           │       ├── ivr-record_invalid_sound.wav
│   │           │       ├── ivr-record_prompt.wav
│   │           │       ├── ivr-record_short_greeting.wav
│   │           │       ├── ivr-regarding_reference_number.wav
│   │           │       ├── ivr-register_for_cluecon.wav
│   │           │       ├── ivr-reminder_for.wav
│   │           │       ├── ivr-repeat_this_information.wav
│   │           │       ├── ivr-requested_wakeup_call_for.wav
│   │           │       ├── ivr-request_or_use_pin.wav
│   │           │       ├── ivr-request_wakeup_call.wav
│   │           │       ├── ivr-reset_usage_totals_confirm.wav
│   │           │       ├── ivr-reset_usage_totals.wav
│   │           │       ├── ivr-sales.wav
│   │           │       ├── ivr-sample_submenu.wav
│   │           │       ├── ivr-save_review_record.wav
│   │           │       ├── ivr-say_name.wav
│   │           │       ├── ivr-send_fax_now.wav
│   │           │       ├── ivr-send_fax.wav
│   │           │       ├── ivr-send_to_voicemail.wav
│   │           │       ├── ivr-seriously_mean_to_press_key.wav
│   │           │       ├── ivr-short_greeting.wav
│   │           │       ├── ivr-skip_instructions.wav
│   │           │       ├── ivr-smoke_got_you.wav
│   │           │       ├── ivr-speak_to_a_customer_service_representative.wav
│   │           │       ├── ivr-spell_name.wav
│   │           │       ├── ivr-stay_on_line_call_answered_momentarily.wav
│   │           │       ├── ivr-sucks.wav
│   │           │       ├── ivr-suck.wav
│   │           │       ├── ivr-system_back_up_in_approximately.wav
│   │           │       ├── ivr-system_down_for_maintenance.wav
│   │           │       ├── ivr-take_a_message.wav
│   │           │       ├── ivr-technical_support.wav
│   │           │       ├── ivr-terribly_wrong_awkward.wav
│   │           │       ├── ivr-thank_you_for_calling.wav
│   │           │       ├── ivr-thank_you_for_holding.wav
│   │           │       ├── ivr-thank_you.wav
│   │           │       ├── ivr-that_was_an_invalid_entry.wav
│   │           │       ├── ivr-that_you_would_like_to_modify.wav
│   │           │       ├── ivr-the_billing_department.wav
│   │           │       ├── ivr-there_are.wav
│   │           │       ├── ivr-there_is.wav
│   │           │       ├── ivr-this_feature.wav
│   │           │       ├── ivr-this_is_a_call_from.wav
│   │           │       ├── ivr-this_is_your_wakeup_call.wav
│   │           │       ├── ivr-this_ivr_will_let_you_test_features.wav
│   │           │       ├── ivr-this_phone_will_now_reboot.wav
│   │           │       ├── ivr-to_accept_press_one.wav
│   │           │       ├── ivr-to_accept_press.wav
│   │           │       ├── ivr-to_call_the_freeswitch_conference.wav
│   │           │       ├── ivr-to_confirm.wav
│   │           │       ├── ivr-to_do_a_freeswitch_echo_test.wav
│   │           │       ├── ivr-to_do_a_fwd_echo_test.wav
│   │           │       ├── ivr-to_hear_sample_submenu.wav
│   │           │       ├── ivr-to_hear_screaming_monkeys.wav
│   │           │       ├── ivr-to_learn_more_about_freeswitch.wav
│   │           │       ├── ivr-to_listen_to_moh.wav
│   │           │       ├── ivr-to_log_in.wav
│   │           │       ├── ivr-to_log_out.wav
│   │           │       ├── ivr-to_modify.wav
│   │           │       ├── ivr-to_redial_last_call.wav
│   │           │       ├── ivr-to_reject_hangup.wav
│   │           │       ├── ivr-to_reject.wav
│   │           │       ├── ivr-to_repeat_these_options.wav
│   │           │       ├── ivr-to_return_to_previous_menu.wav
│   │           │       ├── ivr-to_skip.wav
│   │           │       ├── ivr-to_speak_with_an_operator.wav
│   │           │       ├── ivr-to_wait_stay_on_the_line.wav
│   │           │       ├── ivr-trollover_minutes.wav
│   │           │       ├── ivr-unable_save.wav
│   │           │       ├── ivr-unallocated_number.wav
│   │           │       ├── ivr-unblock_caller_id.wav
│   │           │       ├── ivr-units.wav
│   │           │       ├── ivr-usage_totals_have_been_reset.wav
│   │           │       ├── ivr-user_busy.wav
│   │           │       ├── ivr-use_telephone_keypad.wav
│   │           │       ├── ivr-using_telephone_keypad.wav
│   │           │       ├── ivr-visitors.wav
│   │           │       ├── ivr-visitor.wav
│   │           │       ├── ivr-wakeup_call_cancelled.wav
│   │           │       ├── ivr-wakeup_call.wav
│   │           │       ├── ivr-wakey_wakey_sunshine.wav
│   │           │       ├── ivr-welcome_to_freeswitch.wav
│   │           │       ├── ivr-welcome_to.wav
│   │           │       ├── ivr-welcome.wav
│   │           │       ├── ivr-were_asterisk_free.wav
│   │           │       ├── ivr-we_will_return_your_call_at_this_number.wav
│   │           │       ├── ivr-we_would_support.wav
│   │           │       ├── ivr-when_finished_press_any_key.wav
│   │           │       ├── ivr-withdrawn.wav
│   │           │       ├── ivr-would_you_like_to_receive_a_call_at_this_number.wav
│   │           │       ├── ivr-yes_we_have_no_bananas.wav
│   │           │       ├── ivr-you_are_about_to_provision_this_phone.wav
│   │           │       ├── ivr-you_are_now_logged_in.wav
│   │           │       ├── ivr-you_are_now_logged_out.wav
│   │           │       ├── ivr-you_are_number_one.wav
│   │           │       ├── ivr-you_are_number.wav
│   │           │       ├── ivr-you_are_the.wav
│   │           │       ├── ivr-you_entered.wav
│   │           │       ├── ivr-you_have_dialed_an_invalid_extension.wav
│   │           │       ├── ivr-you_have_used.wav
│   │           │       ├── ivr-you_lose.wav
│   │           │       ├── ivr-you_may_exit_by_hanging_up.wav
│   │           │       ├── ivr-you_may.wav
│   │           │       ├── ivr-your_caller_id_information_is.wav
│   │           │       ├── ivr-your_caller_id_number_is_blocked.wav
│   │           │       ├── ivr-youre_doing_it_wrong.wav
│   │           │       └── ivr-yuno_silent_drill.wav
│   │           ├── misc
│   │           │   ├── 16000
│   │           │   │   ├── call_monitoring_blurb.wav
│   │           │   │   ├── call_secured.wav
│   │           │   │   ├── en.wav
│   │           │   │   ├── error.wav
│   │           │   │   ├── es.wav
│   │           │   │   ├── followed.wav
│   │           │   │   ├── if_you_are_this_person.wav
│   │           │   │   ├── if_you_would_like_to.wav
│   │           │   │   ├── invalid_extension.wav
│   │           │   │   ├── misc-chicago_each_summer.wav
│   │           │   │   ├── misc-cluecon_is_premier_conference.wav
│   │           │   │   ├── misc-cudatel_automagicatronical.wav
│   │           │   │   ├── misc-cudatel_by_it.wav
│   │           │   │   ├── misc-cudatel_communication_server_from_barracuda.wav
│   │           │   │   ├── misc-cudatel_you_know_you_want_one.wav
│   │           │   │   ├── misc-freeswitch_dot_org_more.wav
│   │           │   │   ├── misc-freeswitch_is_state_of_the_art.wav
│   │           │   │   ├── misc-freeswitch_sponsored_by_ostag.wav
│   │           │   │   ├── misc-free_to_download.wav
│   │           │   │   ├── misc-fss_best_consulting.wav
│   │           │   │   ├── misc-fss_contact_us.wav
│   │           │   │   ├── misc-fss_network_of_experts.wav
│   │           │   │   ├── misc-information_about_freeswitch.wav
│   │           │   │   ├── misc-it_is_stable_scalable_extensible.wav
│   │           │   │   ├── misc-join_us_each_wed.wav
│   │           │   │   ├── misc-koo_koo_for_cudatel.wav
│   │           │   │   ├── misc-learn_more_about_cudatel.wav
│   │           │   │   ├── misc-learn_more_about_freeswitch_solutions.wav
│   │           │   │   ├── misc-more_info_wiki.wav
│   │           │   │   ├── misc-ostag_learn_more.wav
│   │           │   │   ├── misc-Sangoma.wav
│   │           │   │   ├── misc-soccer_mom.wav
│   │           │   │   ├── misc-speak_live_with_community.wav
│   │           │   │   ├── misc-speak_to_cudatel_rep.wav
│   │           │   │   ├── misc-support_open_source_by_attending.wav
│   │           │   │   ├── misc-to_hear_about_cluecon.wav
│   │           │   │   ├── misc-visit_cudatel_dot_com.wav
│   │           │   │   ├── misc-welcome_freeswitch_conf_call.wav
│   │           │   │   ├── misc-wide_range_of_persons.wav
│   │           │   │   ├── misc-your_call_has_been_terminated.wav
│   │           │   │   ├── misc-your_call_will_be_terminated_in.wav
│   │           │   │   ├── phone_not_auth.wav
│   │           │   │   ├── provide_reference_number.wav
│   │           │   │   ├── sorry.wav
│   │           │   │   ├── transfer1.wav
│   │           │   │   ├── transfer2.wav
│   │           │   │   └── we_are_trying_to_reach.wav
│   │           │   ├── 32000
│   │           │   │   ├── call_monitoring_blurb.wav
│   │           │   │   ├── call_secured.wav
│   │           │   │   ├── en.wav
│   │           │   │   ├── error.wav
│   │           │   │   ├── es.wav
│   │           │   │   ├── followed.wav
│   │           │   │   ├── if_you_are_this_person.wav
│   │           │   │   ├── if_you_would_like_to.wav
│   │           │   │   ├── invalid_extension.wav
│   │           │   │   ├── misc-chicago_each_summer.wav
│   │           │   │   ├── misc-cluecon_is_premier_conference.wav
│   │           │   │   ├── misc-cudatel_automagicatronical.wav
│   │           │   │   ├── misc-cudatel_by_it.wav
│   │           │   │   ├── misc-cudatel_communication_server_from_barracuda.wav
│   │           │   │   ├── misc-cudatel_you_know_you_want_one.wav
│   │           │   │   ├── misc-freeswitch_dot_org_more.wav
│   │           │   │   ├── misc-freeswitch_is_state_of_the_art.wav
│   │           │   │   ├── misc-freeswitch_sponsored_by_ostag.wav
│   │           │   │   ├── misc-free_to_download.wav
│   │           │   │   ├── misc-fss_best_consulting.wav
│   │           │   │   ├── misc-fss_contact_us.wav
│   │           │   │   ├── misc-fss_network_of_experts.wav
│   │           │   │   ├── misc-information_about_freeswitch.wav
│   │           │   │   ├── misc-it_is_stable_scalable_extensible.wav
│   │           │   │   ├── misc-join_us_each_wed.wav
│   │           │   │   ├── misc-koo_koo_for_cudatel.wav
│   │           │   │   ├── misc-learn_more_about_cudatel.wav
│   │           │   │   ├── misc-learn_more_about_freeswitch_solutions.wav
│   │           │   │   ├── misc-more_info_wiki.wav
│   │           │   │   ├── misc-ostag_learn_more.wav
│   │           │   │   ├── misc-Sangoma.wav
│   │           │   │   ├── misc-soccer_mom.wav
│   │           │   │   ├── misc-speak_live_with_community.wav
│   │           │   │   ├── misc-speak_to_cudatel_rep.wav
│   │           │   │   ├── misc-support_open_source_by_attending.wav
│   │           │   │   ├── misc-to_hear_about_cluecon.wav
│   │           │   │   ├── misc-visit_cudatel_dot_com.wav
│   │           │   │   ├── misc-welcome_freeswitch_conf_call.wav
│   │           │   │   ├── misc-wide_range_of_persons.wav
│   │           │   │   ├── misc-your_call_has_been_terminated.wav
│   │           │   │   ├── misc-your_call_will_be_terminated_in.wav
│   │           │   │   ├── phone_not_auth.wav
│   │           │   │   ├── provide_reference_number.wav
│   │           │   │   ├── sorry.wav
│   │           │   │   ├── transfer1.wav
│   │           │   │   ├── transfer2.wav
│   │           │   │   └── we_are_trying_to_reach.wav
│   │           │   ├── 48000
│   │           │   │   ├── call_monitoring_blurb.wav
│   │           │   │   ├── call_secured.wav
│   │           │   │   ├── en.wav
│   │           │   │   ├── error.wav
│   │           │   │   ├── es.wav
│   │           │   │   ├── followed.wav
│   │           │   │   ├── if_you_are_this_person.wav
│   │           │   │   ├── if_you_would_like_to.wav
│   │           │   │   ├── invalid_extension.wav
│   │           │   │   ├── misc-chicago_each_summer.wav
│   │           │   │   ├── misc-cluecon_is_premier_conference.wav
│   │           │   │   ├── misc-cudatel_automagicatronical.wav
│   │           │   │   ├── misc-cudatel_by_it.wav
│   │           │   │   ├── misc-cudatel_communication_server_from_barracuda.wav
│   │           │   │   ├── misc-cudatel_you_know_you_want_one.wav
│   │           │   │   ├── misc-freeswitch_dot_org_more.wav
│   │           │   │   ├── misc-freeswitch_is_state_of_the_art.wav
│   │           │   │   ├── misc-freeswitch_sponsored_by_ostag.wav
│   │           │   │   ├── misc-free_to_download.wav
│   │           │   │   ├── misc-fss_best_consulting.wav
│   │           │   │   ├── misc-fss_contact_us.wav
│   │           │   │   ├── misc-fss_network_of_experts.wav
│   │           │   │   ├── misc-information_about_freeswitch.wav
│   │           │   │   ├── misc-it_is_stable_scalable_extensible.wav
│   │           │   │   ├── misc-join_us_each_wed.wav
│   │           │   │   ├── misc-koo_koo_for_cudatel.wav
│   │           │   │   ├── misc-learn_more_about_cudatel.wav
│   │           │   │   ├── misc-learn_more_about_freeswitch_solutions.wav
│   │           │   │   ├── misc-more_info_wiki.wav
│   │           │   │   ├── misc-ostag_learn_more.wav
│   │           │   │   ├── misc-Sangoma.wav
│   │           │   │   ├── misc-soccer_mom.wav
│   │           │   │   ├── misc-speak_live_with_community.wav
│   │           │   │   ├── misc-speak_to_cudatel_rep.wav
│   │           │   │   ├── misc-support_open_source_by_attending.wav
│   │           │   │   ├── misc-to_hear_about_cluecon.wav
│   │           │   │   ├── misc-visit_cudatel_dot_com.wav
│   │           │   │   ├── misc-welcome_freeswitch_conf_call.wav
│   │           │   │   ├── misc-wide_range_of_persons.wav
│   │           │   │   ├── misc-your_call_has_been_terminated.wav
│   │           │   │   ├── misc-your_call_will_be_terminated_in.wav
│   │           │   │   ├── phone_not_auth.wav
│   │           │   │   ├── provide_reference_number.wav
│   │           │   │   ├── sorry.wav
│   │           │   │   ├── transfer1.wav
│   │           │   │   ├── transfer2.wav
│   │           │   │   └── we_are_trying_to_reach.wav
│   │           │   └── 8000
│   │           │       ├── call_monitoring_blurb.wav
│   │           │       ├── call_secured.wav
│   │           │       ├── en.wav
│   │           │       ├── error.wav
│   │           │       ├── es.wav
│   │           │       ├── followed.wav
│   │           │       ├── if_you_are_this_person.wav
│   │           │       ├── if_you_would_like_to.wav
│   │           │       ├── invalid_extension.wav
│   │           │       ├── misc-chicago_each_summer.wav
│   │           │       ├── misc-cluecon_is_premier_conference.wav
│   │           │       ├── misc-cudatel_automagicatronical.wav
│   │           │       ├── misc-cudatel_by_it.wav
│   │           │       ├── misc-cudatel_communication_server_from_barracuda.wav
│   │           │       ├── misc-cudatel_you_know_you_want_one.wav
│   │           │       ├── misc-freeswitch_dot_org_more.wav
│   │           │       ├── misc-freeswitch_is_state_of_the_art.wav
│   │           │       ├── misc-freeswitch_sponsored_by_ostag.wav
│   │           │       ├── misc-free_to_download.wav
│   │           │       ├── misc-fss_best_consulting.wav
│   │           │       ├── misc-fss_contact_us.wav
│   │           │       ├── misc-fss_network_of_experts.wav
│   │           │       ├── misc-information_about_freeswitch.wav
│   │           │       ├── misc-it_is_stable_scalable_extensible.wav
│   │           │       ├── misc-join_us_each_wed.wav
│   │           │       ├── misc-koo_koo_for_cudatel.wav
│   │           │       ├── misc-learn_more_about_cudatel.wav
│   │           │       ├── misc-learn_more_about_freeswitch_solutions.wav
│   │           │       ├── misc-more_info_wiki.wav
│   │           │       ├── misc-ostag_learn_more.wav
│   │           │       ├── misc-Sangoma.wav
│   │           │       ├── misc-soccer_mom.wav
│   │           │       ├── misc-speak_live_with_community.wav
│   │           │       ├── misc-speak_to_cudatel_rep.wav
│   │           │       ├── misc-support_open_source_by_attending.wav
│   │           │       ├── misc-to_hear_about_cluecon.wav
│   │           │       ├── misc-visit_cudatel_dot_com.wav
│   │           │       ├── misc-welcome_freeswitch_conf_call.wav
│   │           │       ├── misc-wide_range_of_persons.wav
│   │           │       ├── misc-your_call_has_been_terminated.wav
│   │           │       ├── misc-your_call_will_be_terminated_in.wav
│   │           │       ├── phone_not_auth.wav
│   │           │       ├── provide_reference_number.wav
│   │           │       ├── sorry.wav
│   │           │       ├── transfer1.wav
│   │           │       ├── transfer2.wav
│   │           │       └── we_are_trying_to_reach.wav
│   │           ├── phonetic-ascii
│   │           │   ├── 16000
│   │           │   │   ├── 100.wav
│   │           │   │   ├── 101.wav
│   │           │   │   ├── 102.wav
│   │           │   │   ├── 103.wav
│   │           │   │   ├── 104.wav
│   │           │   │   ├── 105.wav
│   │           │   │   ├── 106.wav
│   │           │   │   ├── 107.wav
│   │           │   │   ├── 108.wav
│   │           │   │   ├── 109.wav
│   │           │   │   ├── 110.wav
│   │           │   │   ├── 111.wav
│   │           │   │   ├── 112.wav
│   │           │   │   ├── 113.wav
│   │           │   │   ├── 114.wav
│   │           │   │   ├── 115.wav
│   │           │   │   ├── 116.wav
│   │           │   │   ├── 117.wav
│   │           │   │   ├── 118.wav
│   │           │   │   ├── 119.wav
│   │           │   │   ├── 120.wav
│   │           │   │   ├── 121.wav
│   │           │   │   ├── 122.wav
│   │           │   │   ├── 32.wav
│   │           │   │   ├── 35.wav
│   │           │   │   ├── 42.wav
│   │           │   │   ├── 46.wav
│   │           │   │   ├── 97.wav
│   │           │   │   ├── 98.wav
│   │           │   │   └── 99.wav
│   │           │   ├── 32000
│   │           │   │   ├── 100.wav
│   │           │   │   ├── 101.wav
│   │           │   │   ├── 102.wav
│   │           │   │   ├── 103.wav
│   │           │   │   ├── 104.wav
│   │           │   │   ├── 105.wav
│   │           │   │   ├── 106.wav
│   │           │   │   ├── 107.wav
│   │           │   │   ├── 108.wav
│   │           │   │   ├── 109.wav
│   │           │   │   ├── 110.wav
│   │           │   │   ├── 111.wav
│   │           │   │   ├── 112.wav
│   │           │   │   ├── 113.wav
│   │           │   │   ├── 114.wav
│   │           │   │   ├── 115.wav
│   │           │   │   ├── 116.wav
│   │           │   │   ├── 117.wav
│   │           │   │   ├── 118.wav
│   │           │   │   ├── 119.wav
│   │           │   │   ├── 120.wav
│   │           │   │   ├── 121.wav
│   │           │   │   ├── 122.wav
│   │           │   │   ├── 32.wav
│   │           │   │   ├── 35.wav
│   │           │   │   ├── 42.wav
│   │           │   │   ├── 46.wav
│   │           │   │   ├── 97.wav
│   │           │   │   ├── 98.wav
│   │           │   │   └── 99.wav
│   │           │   ├── 48000
│   │           │   │   ├── 100.wav
│   │           │   │   ├── 101.wav
│   │           │   │   ├── 102.wav
│   │           │   │   ├── 103.wav
│   │           │   │   ├── 104.wav
│   │           │   │   ├── 105.wav
│   │           │   │   ├── 106.wav
│   │           │   │   ├── 107.wav
│   │           │   │   ├── 108.wav
│   │           │   │   ├── 109.wav
│   │           │   │   ├── 110.wav
│   │           │   │   ├── 111.wav
│   │           │   │   ├── 112.wav
│   │           │   │   ├── 113.wav
│   │           │   │   ├── 114.wav
│   │           │   │   ├── 115.wav
│   │           │   │   ├── 116.wav
│   │           │   │   ├── 117.wav
│   │           │   │   ├── 118.wav
│   │           │   │   ├── 119.wav
│   │           │   │   ├── 120.wav
│   │           │   │   ├── 121.wav
│   │           │   │   ├── 122.wav
│   │           │   │   ├── 32.wav
│   │           │   │   ├── 35.wav
│   │           │   │   ├── 42.wav
│   │           │   │   ├── 46.wav
│   │           │   │   ├── 97.wav
│   │           │   │   ├── 98.wav
│   │           │   │   └── 99.wav
│   │           │   └── 8000
│   │           │       ├── 100.wav
│   │           │       ├── 101.wav
│   │           │       ├── 102.wav
│   │           │       ├── 103.wav
│   │           │       ├── 104.wav
│   │           │       ├── 105.wav
│   │           │       ├── 106.wav
│   │           │       ├── 107.wav
│   │           │       ├── 108.wav
│   │           │       ├── 109.wav
│   │           │       ├── 110.wav
│   │           │       ├── 111.wav
│   │           │       ├── 112.wav
│   │           │       ├── 113.wav
│   │           │       ├── 114.wav
│   │           │       ├── 115.wav
│   │           │       ├── 116.wav
│   │           │       ├── 117.wav
│   │           │       ├── 118.wav
│   │           │       ├── 119.wav
│   │           │       ├── 120.wav
│   │           │       ├── 121.wav
│   │           │       ├── 122.wav
│   │           │       ├── 32.wav
│   │           │       ├── 35.wav
│   │           │       ├── 42.wav
│   │           │       ├── 46.wav
│   │           │       ├── 97.wav
│   │           │       ├── 98.wav
│   │           │       └── 99.wav
│   │           ├── time
│   │           │   ├── 16000
│   │           │   │   ├── a-m.wav
│   │           │   │   ├── at.wav
│   │           │   │   ├── day-0.wav
│   │           │   │   ├── day-1.wav
│   │           │   │   ├── day-2.wav
│   │           │   │   ├── day-3.wav
│   │           │   │   ├── day-4.wav
│   │           │   │   ├── day-5.wav
│   │           │   │   ├── day-6.wav
│   │           │   │   ├── hours.wav
│   │           │   │   ├── hour.wav
│   │           │   │   ├── minutes.wav
│   │           │   │   ├── minute.wav
│   │           │   │   ├── mon-0.wav
│   │           │   │   ├── mon-10.wav
│   │           │   │   ├── mon-11.wav
│   │           │   │   ├── mon-1.wav
│   │           │   │   ├── mon-2.wav
│   │           │   │   ├── mon-3.wav
│   │           │   │   ├── mon-4.wav
│   │           │   │   ├── mon-5.wav
│   │           │   │   ├── mon-6.wav
│   │           │   │   ├── mon-7.wav
│   │           │   │   ├── mon-8.wav
│   │           │   │   ├── mon-9.wav
│   │           │   │   ├── oclock.wav
│   │           │   │   ├── oh.wav
│   │           │   │   ├── p-m.wav
│   │           │   │   ├── seconds.wav
│   │           │   │   ├── second.wav
│   │           │   │   ├── today.wav
│   │           │   │   ├── tomorrow.wav
│   │           │   │   └── yesterday.wav
│   │           │   ├── 32000
│   │           │   │   ├── a-m.wav
│   │           │   │   ├── at.wav
│   │           │   │   ├── day-0.wav
│   │           │   │   ├── day-1.wav
│   │           │   │   ├── day-2.wav
│   │           │   │   ├── day-3.wav
│   │           │   │   ├── day-4.wav
│   │           │   │   ├── day-5.wav
│   │           │   │   ├── day-6.wav
│   │           │   │   ├── hours.wav
│   │           │   │   ├── hour.wav
│   │           │   │   ├── minutes.wav
│   │           │   │   ├── minute.wav
│   │           │   │   ├── mon-0.wav
│   │           │   │   ├── mon-10.wav
│   │           │   │   ├── mon-11.wav
│   │           │   │   ├── mon-1.wav
│   │           │   │   ├── mon-2.wav
│   │           │   │   ├── mon-3.wav
│   │           │   │   ├── mon-4.wav
│   │           │   │   ├── mon-5.wav
│   │           │   │   ├── mon-6.wav
│   │           │   │   ├── mon-7.wav
│   │           │   │   ├── mon-8.wav
│   │           │   │   ├── mon-9.wav
│   │           │   │   ├── oclock.wav
│   │           │   │   ├── oh.wav
│   │           │   │   ├── p-m.wav
│   │           │   │   ├── seconds.wav
│   │           │   │   ├── second.wav
│   │           │   │   ├── today.wav
│   │           │   │   ├── tomorrow.wav
│   │           │   │   └── yesterday.wav
│   │           │   ├── 48000
│   │           │   │   ├── a-m.wav
│   │           │   │   ├── at.wav
│   │           │   │   ├── day-0.wav
│   │           │   │   ├── day-1.wav
│   │           │   │   ├── day-2.wav
│   │           │   │   ├── day-3.wav
│   │           │   │   ├── day-4.wav
│   │           │   │   ├── day-5.wav
│   │           │   │   ├── day-6.wav
│   │           │   │   ├── hours.wav
│   │           │   │   ├── hour.wav
│   │           │   │   ├── minutes.wav
│   │           │   │   ├── minute.wav
│   │           │   │   ├── mon-0.wav
│   │           │   │   ├── mon-10.wav
│   │           │   │   ├── mon-11.wav
│   │           │   │   ├── mon-1.wav
│   │           │   │   ├── mon-2.wav
│   │           │   │   ├── mon-3.wav
│   │           │   │   ├── mon-4.wav
│   │           │   │   ├── mon-5.wav
│   │           │   │   ├── mon-6.wav
│   │           │   │   ├── mon-7.wav
│   │           │   │   ├── mon-8.wav
│   │           │   │   ├── mon-9.wav
│   │           │   │   ├── oclock.wav
│   │           │   │   ├── oh.wav
│   │           │   │   ├── p-m.wav
│   │           │   │   ├── seconds.wav
│   │           │   │   ├── second.wav
│   │           │   │   ├── today.wav
│   │           │   │   ├── tomorrow.wav
│   │           │   │   └── yesterday.wav
│   │           │   └── 8000
│   │           │       ├── a-m.wav
│   │           │       ├── at.wav
│   │           │       ├── day-0.wav
│   │           │       ├── day-1.wav
│   │           │       ├── day-2.wav
│   │           │       ├── day-3.wav
│   │           │       ├── day-4.wav
│   │           │       ├── day-5.wav
│   │           │       ├── day-6.wav
│   │           │       ├── hours.wav
│   │           │       ├── hour.wav
│   │           │       ├── minutes.wav
│   │           │       ├── minute.wav
│   │           │       ├── mon-0.wav
│   │           │       ├── mon-10.wav
│   │           │       ├── mon-11.wav
│   │           │       ├── mon-1.wav
│   │           │       ├── mon-2.wav
│   │           │       ├── mon-3.wav
│   │           │       ├── mon-4.wav
│   │           │       ├── mon-5.wav
│   │           │       ├── mon-6.wav
│   │           │       ├── mon-7.wav
│   │           │       ├── mon-8.wav
│   │           │       ├── mon-9.wav
│   │           │       ├── oclock.wav
│   │           │       ├── oh.wav
│   │           │       ├── p-m.wav
│   │           │       ├── seconds.wav
│   │           │       ├── second.wav
│   │           │       ├── today.wav
│   │           │       ├── tomorrow.wav
│   │           │       └── yesterday.wav
│   │           ├── voicemail
│   │           │   ├── 16000
│   │           │   │   ├── vm-abort.wav
│   │           │   │   ├── vm-advanced_alt.wav
│   │           │   │   ├── vm-advanced.wav
│   │           │   │   ├── vm-change_password.wav
│   │           │   │   ├── vm-choose_greeting_choose.wav
│   │           │   │   ├── vm-choose_greeting_fail.wav
│   │           │   │   ├── vm-choose_greeting.wav
│   │           │   │   ├── vm-choose_password.wav
│   │           │   │   ├── vm-continue.wav
│   │           │   │   ├── vm-deleted.wav
│   │           │   │   ├── vm-delete_message.wav
│   │           │   │   ├── vm-delete_recording.wav
│   │           │   │   ├── vm-emailed.wav
│   │           │   │   ├── vm-enter_id.wav
│   │           │   │   ├── vm-enter_new_pin.wav
│   │           │   │   ├── vm-enter_pass.wav
│   │           │   │   ├── vm-fail_auth.wav
│   │           │   │   ├── vm-followed_by_pound.wav
│   │           │   │   ├── vm-followed_by.wav
│   │           │   │   ├── vm-forward_add_intro.wav
│   │           │   │   ├── vm-forward_enter_ext.wav
│   │           │   │   ├── vm-forward_to_email.wav
│   │           │   │   ├── vm-from.wav
│   │           │   │   ├── vm-goodbye.wav
│   │           │   │   ├── vm-greeting.wav
│   │           │   │   ├── vm-has_been_changed_to.wav
│   │           │   │   ├── vm-hello.wav
│   │           │   │   ├── vm-in_folder.wav
│   │           │   │   ├── vm-last.wav
│   │           │   │   ├── vm-listen_new.wav
│   │           │   │   ├── vm-listen_saved.wav
│   │           │   │   ├── vm-listen_to_recording_again.wav
│   │           │   │   ├── vm-listen_to_recording.wav
│   │           │   │   ├── vm-mailbox_full.wav
│   │           │   │   ├── vm-main_menu_alt.wav
│   │           │   │   ├── vm-main_menu.wav
│   │           │   │   ├── vm-marked_new.wav
│   │           │   │   ├── vm-marked-urgent.wav
│   │           │   │   ├── vm-mark_message_new.wav
│   │           │   │   ├── vm-mark-urgent.wav
│   │           │   │   ├── vm-message_alt.wav
│   │           │   │   ├── vm-message_envelope.wav
│   │           │   │   ├── vm-message_forwarded.wav
│   │           │   │   ├── vm-message_from.wav
│   │           │   │   ├── vm-message_number.wav
│   │           │   │   ├── vm-messages_alt.wav
│   │           │   │   ├── vm-messages.wav
│   │           │   │   ├── vm-message.wav
│   │           │   │   ├── vm-minimum_pin_length_is.wav
│   │           │   │   ├── vm-new.wav
│   │           │   │   ├── vm-next.wav
│   │           │   │   ├── vm-no_answer_no_vm.wav
│   │           │   │   ├── vm-nobody_leaving_message.wav
│   │           │   │   ├── vm-no_more_messages.wav
│   │           │   │   ├── vm-not_available_no_voicemail.wav
│   │           │   │   ├── vm-not_available.wav
│   │           │   │   ├── vm-password_has_been_changed.wav
│   │           │   │   ├── vm-password_is_not_secure.wav
│   │           │   │   ├── vm-password_not_valid.wav
│   │           │   │   ├── vm-person.wav
│   │           │   │   ├── vm-pin_below_minimum_length.wav
│   │           │   │   ├── vm-play_greeting.wav
│   │           │   │   ├── vm-play_next_message.wav
│   │           │   │   ├── vm-play_previous_message.wav
│   │           │   │   ├── vm-press.wav
│   │           │   │   ├── vm-received.wav
│   │           │   │   ├── vm-record_greeting.wav
│   │           │   │   ├── vm-record_message.wav
│   │           │   │   ├── vm-record_name1.wav
│   │           │   │   ├── vm-record_name2.wav
│   │           │   │   ├── vm-repeat_message.wav
│   │           │   │   ├── vm-rerecord.wav
│   │           │   │   ├── vm-return_call.wav
│   │           │   │   ├── vm-saved.wav
│   │           │   │   ├── vm-save_message.wav
│   │           │   │   ├── vm-save_recording.wav
│   │           │   │   ├── vm-selected.wav
│   │           │   │   ├── vm-send_message_now.wav
│   │           │   │   ├── vm-that_was_an_invalid_ext.wav
│   │           │   │   ├── vm-to_exit_alt.wav
│   │           │   │   ├── vm-to_exit.wav
│   │           │   │   ├── vm-to_forward.wav
│   │           │   │   ├── vm-too-small.wav
│   │           │   │   ├── vm-to_record_greeting.wav
│   │           │   │   ├── vm-tutorial_change_pin.wav
│   │           │   │   ├── vm-tutorial_record_name.wav
│   │           │   │   ├── vm-tutorial_yes_no.wav
│   │           │   │   ├── vm-undeleted.wav
│   │           │   │   ├── vm-undelete_message.wav
│   │           │   │   ├── vm-urgent-new.wav
│   │           │   │   ├── vm-urgent-saved.wav
│   │           │   │   ├── vm-urgent.wav
│   │           │   │   ├── vm-voicemail_password_is_web_password.wav
│   │           │   │   └── vm-you_have.wav
│   │           │   ├── 32000
│   │           │   │   ├── vm-abort.wav
│   │           │   │   ├── vm-advanced_alt.wav
│   │           │   │   ├── vm-advanced.wav
│   │           │   │   ├── vm-change_password.wav
│   │           │   │   ├── vm-choose_greeting_choose.wav
│   │           │   │   ├── vm-choose_greeting_fail.wav
│   │           │   │   ├── vm-choose_greeting.wav
│   │           │   │   ├── vm-choose_password.wav
│   │           │   │   ├── vm-continue.wav
│   │           │   │   ├── vm-deleted.wav
│   │           │   │   ├── vm-delete_message.wav
│   │           │   │   ├── vm-delete_recording.wav
│   │           │   │   ├── vm-emailed.wav
│   │           │   │   ├── vm-enter_id.wav
│   │           │   │   ├── vm-enter_new_pin.wav
│   │           │   │   ├── vm-enter_pass.wav
│   │           │   │   ├── vm-fail_auth.wav
│   │           │   │   ├── vm-followed_by_pound.wav
│   │           │   │   ├── vm-followed_by.wav
│   │           │   │   ├── vm-forward_add_intro.wav
│   │           │   │   ├── vm-forward_enter_ext.wav
│   │           │   │   ├── vm-forward_to_email.wav
│   │           │   │   ├── vm-from.wav
│   │           │   │   ├── vm-goodbye.wav
│   │           │   │   ├── vm-greeting.wav
│   │           │   │   ├── vm-has_been_changed_to.wav
│   │           │   │   ├── vm-hello.wav
│   │           │   │   ├── vm-in_folder.wav
│   │           │   │   ├── vm-last.wav
│   │           │   │   ├── vm-listen_new.wav
│   │           │   │   ├── vm-listen_saved.wav
│   │           │   │   ├── vm-listen_to_recording_again.wav
│   │           │   │   ├── vm-listen_to_recording.wav
│   │           │   │   ├── vm-mailbox_full.wav
│   │           │   │   ├── vm-main_menu_alt.wav
│   │           │   │   ├── vm-main_menu.wav
│   │           │   │   ├── vm-marked_new.wav
│   │           │   │   ├── vm-marked-urgent.wav
│   │           │   │   ├── vm-mark_message_new.wav
│   │           │   │   ├── vm-mark-urgent.wav
│   │           │   │   ├── vm-message_alt.wav
│   │           │   │   ├── vm-message_envelope.wav
│   │           │   │   ├── vm-message_forwarded.wav
│   │           │   │   ├── vm-message_from.wav
│   │           │   │   ├── vm-message_number.wav
│   │           │   │   ├── vm-messages_alt.wav
│   │           │   │   ├── vm-messages.wav
│   │           │   │   ├── vm-message.wav
│   │           │   │   ├── vm-minimum_pin_length_is.wav
│   │           │   │   ├── vm-new.wav
│   │           │   │   ├── vm-next.wav
│   │           │   │   ├── vm-no_answer_no_vm.wav
│   │           │   │   ├── vm-nobody_leaving_message.wav
│   │           │   │   ├── vm-no_more_messages.wav
│   │           │   │   ├── vm-not_available_no_voicemail.wav
│   │           │   │   ├── vm-not_available.wav
│   │           │   │   ├── vm-password_has_been_changed.wav
│   │           │   │   ├── vm-password_is_not_secure.wav
│   │           │   │   ├── vm-password_not_valid.wav
│   │           │   │   ├── vm-person.wav
│   │           │   │   ├── vm-pin_below_minimum_length.wav
│   │           │   │   ├── vm-play_greeting.wav
│   │           │   │   ├── vm-play_next_message.wav
│   │           │   │   ├── vm-play_previous_message.wav
│   │           │   │   ├── vm-press.wav
│   │           │   │   ├── vm-received.wav
│   │           │   │   ├── vm-record_greeting.wav
│   │           │   │   ├── vm-record_message.wav
│   │           │   │   ├── vm-record_name1.wav
│   │           │   │   ├── vm-record_name2.wav
│   │           │   │   ├── vm-repeat_message.wav
│   │           │   │   ├── vm-rerecord.wav
│   │           │   │   ├── vm-return_call.wav
│   │           │   │   ├── vm-saved.wav
│   │           │   │   ├── vm-save_message.wav
│   │           │   │   ├── vm-save_recording.wav
│   │           │   │   ├── vm-selected.wav
│   │           │   │   ├── vm-send_message_now.wav
│   │           │   │   ├── vm-that_was_an_invalid_ext.wav
│   │           │   │   ├── vm-to_exit_alt.wav
│   │           │   │   ├── vm-to_exit.wav
│   │           │   │   ├── vm-to_forward.wav
│   │           │   │   ├── vm-too-small.wav
│   │           │   │   ├── vm-to_record_greeting.wav
│   │           │   │   ├── vm-tutorial_change_pin.wav
│   │           │   │   ├── vm-tutorial_record_name.wav
│   │           │   │   ├── vm-tutorial_yes_no.wav
│   │           │   │   ├── vm-undeleted.wav
│   │           │   │   ├── vm-undelete_message.wav
│   │           │   │   ├── vm-urgent-new.wav
│   │           │   │   ├── vm-urgent-saved.wav
│   │           │   │   ├── vm-urgent.wav
│   │           │   │   ├── vm-voicemail_password_is_web_password.wav
│   │           │   │   └── vm-you_have.wav
│   │           │   ├── 48000
│   │           │   │   ├── vm-abort.wav
│   │           │   │   ├── vm-advanced_alt.wav
│   │           │   │   ├── vm-advanced.wav
│   │           │   │   ├── vm-change_password.wav
│   │           │   │   ├── vm-choose_greeting_choose.wav
│   │           │   │   ├── vm-choose_greeting_fail.wav
│   │           │   │   ├── vm-choose_greeting.wav
│   │           │   │   ├── vm-choose_password.wav
│   │           │   │   ├── vm-continue.wav
│   │           │   │   ├── vm-deleted.wav
│   │           │   │   ├── vm-delete_message.wav
│   │           │   │   ├── vm-delete_recording.wav
│   │           │   │   ├── vm-emailed.wav
│   │           │   │   ├── vm-enter_id.wav
│   │           │   │   ├── vm-enter_new_pin.wav
│   │           │   │   ├── vm-enter_pass.wav
│   │           │   │   ├── vm-fail_auth.wav
│   │           │   │   ├── vm-followed_by_pound.wav
│   │           │   │   ├── vm-followed_by.wav
│   │           │   │   ├── vm-forward_add_intro.wav
│   │           │   │   ├── vm-forward_enter_ext.wav
│   │           │   │   ├── vm-forward_to_email.wav
│   │           │   │   ├── vm-from.wav
│   │           │   │   ├── vm-goodbye.wav
│   │           │   │   ├── vm-greeting.wav
│   │           │   │   ├── vm-has_been_changed_to.wav
│   │           │   │   ├── vm-hello.wav
│   │           │   │   ├── vm-in_folder.wav
│   │           │   │   ├── vm-last.wav
│   │           │   │   ├── vm-listen_new.wav
│   │           │   │   ├── vm-listen_saved.wav
│   │           │   │   ├── vm-listen_to_recording_again.wav
│   │           │   │   ├── vm-listen_to_recording.wav
│   │           │   │   ├── vm-mailbox_full.wav
│   │           │   │   ├── vm-main_menu_alt.wav
│   │           │   │   ├── vm-main_menu.wav
│   │           │   │   ├── vm-marked_new.wav
│   │           │   │   ├── vm-marked-urgent.wav
│   │           │   │   ├── vm-mark_message_new.wav
│   │           │   │   ├── vm-mark-urgent.wav
│   │           │   │   ├── vm-message_alt.wav
│   │           │   │   ├── vm-message_envelope.wav
│   │           │   │   ├── vm-message_forwarded.wav
│   │           │   │   ├── vm-message_from.wav
│   │           │   │   ├── vm-message_number.wav
│   │           │   │   ├── vm-messages_alt.wav
│   │           │   │   ├── vm-messages.wav
│   │           │   │   ├── vm-message.wav
│   │           │   │   ├── vm-minimum_pin_length_is.wav
│   │           │   │   ├── vm-new.wav
│   │           │   │   ├── vm-next.wav
│   │           │   │   ├── vm-no_answer_no_vm.wav
│   │           │   │   ├── vm-nobody_leaving_message.wav
│   │           │   │   ├── vm-no_more_messages.wav
│   │           │   │   ├── vm-not_available_no_voicemail.wav
│   │           │   │   ├── vm-not_available.wav
│   │           │   │   ├── vm-password_has_been_changed.wav
│   │           │   │   ├── vm-password_is_not_secure.wav
│   │           │   │   ├── vm-password_not_valid.wav
│   │           │   │   ├── vm-person.wav
│   │           │   │   ├── vm-pin_below_minimum_length.wav
│   │           │   │   ├── vm-play_greeting.wav
│   │           │   │   ├── vm-play_next_message.wav
│   │           │   │   ├── vm-play_previous_message.wav
│   │           │   │   ├── vm-press.wav
│   │           │   │   ├── vm-received.wav
│   │           │   │   ├── vm-record_greeting.wav
│   │           │   │   ├── vm-record_message.wav
│   │           │   │   ├── vm-record_name1.wav
│   │           │   │   ├── vm-record_name2.wav
│   │           │   │   ├── vm-repeat_message.wav
│   │           │   │   ├── vm-rerecord.wav
│   │           │   │   ├── vm-return_call.wav
│   │           │   │   ├── vm-saved.wav
│   │           │   │   ├── vm-save_message.wav
│   │           │   │   ├── vm-save_recording.wav
│   │           │   │   ├── vm-selected.wav
│   │           │   │   ├── vm-send_message_now.wav
│   │           │   │   ├── vm-that_was_an_invalid_ext.wav
│   │           │   │   ├── vm-to_exit_alt.wav
│   │           │   │   ├── vm-to_exit.wav
│   │           │   │   ├── vm-to_forward.wav
│   │           │   │   ├── vm-too-small.wav
│   │           │   │   ├── vm-to_record_greeting.wav
│   │           │   │   ├── vm-tutorial_change_pin.wav
│   │           │   │   ├── vm-tutorial_record_name.wav
│   │           │   │   ├── vm-tutorial_yes_no.wav
│   │           │   │   ├── vm-undeleted.wav
│   │           │   │   ├── vm-undelete_message.wav
│   │           │   │   ├── vm-urgent-new.wav
│   │           │   │   ├── vm-urgent-saved.wav
│   │           │   │   ├── vm-urgent.wav
│   │           │   │   ├── vm-voicemail_password_is_web_password.wav
│   │           │   │   └── vm-you_have.wav
│   │           │   └── 8000
│   │           │       ├── vm-abort.wav
│   │           │       ├── vm-advanced_alt.wav
│   │           │       ├── vm-advanced.wav
│   │           │       ├── vm-change_password.wav
│   │           │       ├── vm-choose_greeting_choose.wav
│   │           │       ├── vm-choose_greeting_fail.wav
│   │           │       ├── vm-choose_greeting.wav
│   │           │       ├── vm-choose_password.wav
│   │           │       ├── vm-continue.wav
│   │           │       ├── vm-deleted.wav
│   │           │       ├── vm-delete_message.wav
│   │           │       ├── vm-delete_recording.wav
│   │           │       ├── vm-emailed.wav
│   │           │       ├── vm-enter_id.wav
│   │           │       ├── vm-enter_new_pin.wav
│   │           │       ├── vm-enter_pass.wav
│   │           │       ├── vm-fail_auth.wav
│   │           │       ├── vm-followed_by_pound.wav
│   │           │       ├── vm-followed_by.wav
│   │           │       ├── vm-forward_add_intro.wav
│   │           │       ├── vm-forward_enter_ext.wav
│   │           │       ├── vm-forward_to_email.wav
│   │           │       ├── vm-from.wav
│   │           │       ├── vm-goodbye.wav
│   │           │       ├── vm-greeting.wav
│   │           │       ├── vm-has_been_changed_to.wav
│   │           │       ├── vm-hello.wav
│   │           │       ├── vm-in_folder.wav
│   │           │       ├── vm-last.wav
│   │           │       ├── vm-listen_new.wav
│   │           │       ├── vm-listen_saved.wav
│   │           │       ├── vm-listen_to_recording_again.wav
│   │           │       ├── vm-listen_to_recording.wav
│   │           │       ├── vm-mailbox_full.wav
│   │           │       ├── vm-main_menu_alt.wav
│   │           │       ├── vm-main_menu.wav
│   │           │       ├── vm-marked_new.wav
│   │           │       ├── vm-marked-urgent.wav
│   │           │       ├── vm-mark_message_new.wav
│   │           │       ├── vm-mark-urgent.wav
│   │           │       ├── vm-message_alt.wav
│   │           │       ├── vm-message_envelope.wav
│   │           │       ├── vm-message_forwarded.wav
│   │           │       ├── vm-message_from.wav
│   │           │       ├── vm-message_number.wav
│   │           │       ├── vm-messages_alt.wav
│   │           │       ├── vm-messages.wav
│   │           │       ├── vm-message.wav
│   │           │       ├── vm-minimum_pin_length_is.wav
│   │           │       ├── vm-new.wav
│   │           │       ├── vm-next.wav
│   │           │       ├── vm-no_answer_no_vm.wav
│   │           │       ├── vm-nobody_leaving_message.wav
│   │           │       ├── vm-no_more_messages.wav
│   │           │       ├── vm-not_available_no_voicemail.wav
│   │           │       ├── vm-not_available.wav
│   │           │       ├── vm-password_has_been_changed.wav
│   │           │       ├── vm-password_is_not_secure.wav
│   │           │       ├── vm-password_not_valid.wav
│   │           │       ├── vm-person.wav
│   │           │       ├── vm-pin_below_minimum_length.wav
│   │           │       ├── vm-play_greeting.wav
│   │           │       ├── vm-play_next_message.wav
│   │           │       ├── vm-play_previous_message.wav
│   │           │       ├── vm-press.wav
│   │           │       ├── vm-received.wav
│   │           │       ├── vm-record_greeting.wav
│   │           │       ├── vm-record_message.wav
│   │           │       ├── vm-record_name1.wav
│   │           │       ├── vm-record_name2.wav
│   │           │       ├── vm-repeat_message.wav
│   │           │       ├── vm-rerecord.wav
│   │           │       ├── vm-return_call.wav
│   │           │       ├── vm-saved.wav
│   │           │       ├── vm-save_message.wav
│   │           │       ├── vm-save_recording.wav
│   │           │       ├── vm-selected.wav
│   │           │       ├── vm-send_message_now.wav
│   │           │       ├── vm-that_was_an_invalid_ext.wav
│   │           │       ├── vm-to_exit_alt.wav
│   │           │       ├── vm-to_exit.wav
│   │           │       ├── vm-to_forward.wav
│   │           │       ├── vm-too-small.wav
│   │           │       ├── vm-to_record_greeting.wav
│   │           │       ├── vm-tutorial_change_pin.wav
│   │           │       ├── vm-tutorial_record_name.wav
│   │           │       ├── vm-tutorial_yes_no.wav
│   │           │       ├── vm-undeleted.wav
│   │           │       ├── vm-undelete_message.wav
│   │           │       ├── vm-urgent-new.wav
│   │           │       ├── vm-urgent-saved.wav
│   │           │       ├── vm-urgent.wav
│   │           │       ├── vm-voicemail_password_is_web_password.wav
│   │           │       └── vm-you_have.wav
│   │           └── zrtp
│   │               ├── 16000
│   │               │   ├── zrtp-check_sas.wav
│   │               │   ├── zrtp-enroll_already_enrolled.wav
│   │               │   ├── zrtp-enroll_confirmed.wav
│   │               │   ├── zrtp-enroll_not_sip_registered.wav
│   │               │   ├── zrtp-enroll_notzrtp.wav
│   │               │   ├── zrtp-enroll_welcome.wav
│   │               │   ├── zrtp-is_secure.wav
│   │               │   ├── zrtp-is_unverified.wav
│   │               │   ├── zrtp-is_verified.wav
│   │               │   ├── zrtp-somethings_wrong.wav
│   │               │   ├── zrtp-status_error.wav
│   │               │   ├── zrtp-status_notsecure.wav
│   │               │   ├── zrtp-status_secure.wav
│   │               │   ├── zrtp-status_securing.wav
│   │               │   └── zrtp-thankyou_goodbye.wav
│   │               ├── 32000
│   │               │   ├── zrtp-check_sas.wav
│   │               │   ├── zrtp-enroll_already_enrolled.wav
│   │               │   ├── zrtp-enroll_confirmed.wav
│   │               │   ├── zrtp-enroll_not_sip_registered.wav
│   │               │   ├── zrtp-enroll_notzrtp.wav
│   │               │   ├── zrtp-enroll_welcome.wav
│   │               │   ├── zrtp-is_secure.wav
│   │               │   ├── zrtp-is_unverified.wav
│   │               │   ├── zrtp-is_verified.wav
│   │               │   ├── zrtp-somethings_wrong.wav
│   │               │   ├── zrtp-status_error.wav
│   │               │   ├── zrtp-status_notsecure.wav
│   │               │   ├── zrtp-status_secure.wav
│   │               │   ├── zrtp-status_securing.wav
│   │               │   └── zrtp-thankyou_goodbye.wav
│   │               ├── 48000
│   │               │   ├── zrtp-check_sas.wav
│   │               │   ├── zrtp-enroll_already_enrolled.wav
│   │               │   ├── zrtp-enroll_confirmed.wav
│   │               │   ├── zrtp-enroll_not_sip_registered.wav
│   │               │   ├── zrtp-enroll_notzrtp.wav
│   │               │   ├── zrtp-enroll_welcome.wav
│   │               │   ├── zrtp-is_secure.wav
│   │               │   ├── zrtp-is_unverified.wav
│   │               │   ├── zrtp-is_verified.wav
│   │               │   ├── zrtp-somethings_wrong.wav
│   │               │   ├── zrtp-status_error.wav
│   │               │   ├── zrtp-status_notsecure.wav
│   │               │   ├── zrtp-status_secure.wav
│   │               │   ├── zrtp-status_securing.wav
│   │               │   └── zrtp-thankyou_goodbye.wav
│   │               └── 8000
│   │                   ├── zrtp-check_sas.wav
│   │                   ├── zrtp-enroll_already_enrolled.wav
│   │                   ├── zrtp-enroll_confirmed.wav
│   │                   ├── zrtp-enroll_not_sip_registered.wav
│   │                   ├── zrtp-enroll_notzrtp.wav
│   │                   ├── zrtp-enroll_welcome.wav
│   │                   ├── zrtp-is_secure.wav
│   │                   ├── zrtp-is_unverified.wav
│   │                   ├── zrtp-is_verified.wav
│   │                   ├── zrtp-somethings_wrong.wav
│   │                   ├── zrtp-status_error.wav
│   │                   ├── zrtp-status_notsecure.wav
│   │                   ├── zrtp-status_secure.wav
│   │                   ├── zrtp-status_securing.wav
│   │                   └── zrtp-thankyou_goodbye.wav
│   └── music
│       ├── 16000
│       │   ├── danza-espanola-op-37-h-142-xii-arabesca.wav
│       │   ├── partita-no-3-in-e-major-bwv-1006-1-preludio.wav
│       │   ├── ponce-preludio-in-e-major.wav
│       │   └── suite-espanola-op-47-leyenda.wav
│       ├── 32000
│       │   ├── danza-espanola-op-37-h-142-xii-arabesca.wav
│       │   ├── partita-no-3-in-e-major-bwv-1006-1-preludio.wav
│       │   ├── ponce-preludio-in-e-major.wav
│       │   └── suite-espanola-op-47-leyenda.wav
│       ├── 48000
│       │   ├── danza-espanola-op-37-h-142-xii-arabesca.wav
│       │   ├── partita-no-3-in-e-major-bwv-1006-1-preludio.wav
│       │   ├── ponce-preludio-in-e-major.wav
│       │   └── suite-espanola-op-47-leyenda.wav
│       └── 8000
│           ├── danza-espanola-op-37-h-142-xii-arabesca.wav
│           ├── partita-no-3-in-e-major-bwv-1006-1-preludio.wav
│           ├── ponce-preludio-in-e-major.wav
│           └── suite-espanola-op-47-leyenda.wav
└── storage
    ├── http_file_cache
    └── voicemail
        └── default
            └── 192.168.150.145
                ├── 1000
                └── 1001

155 directories, 5363 files



```