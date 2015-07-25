<?xml version="1.0" encoding="UTF-8" standalone="yes"?>
<addons>
<addon id="plugin.video.roggerstream" name="Rogger Stream" version="1.1.9" provider-name="Master, Pirates ">
  <requires>
    <import addon="xbmc.python" version="2.1.0"/>
  </requires>
  <extension point="xbmc.python.pluginsource" library="defaut.py">
    <provides>video</provides>
  </extension>
  <extension point="xbmc.addon.metadata">
    <language>en</language>
    <platform>all</platform>
    <summary lang="en">Lista de Filmes e Canais Master Pirate</summary>
    <description lang="en">Assista a varios filmes e canais transmitidos pela internet diretamente no Kodi</description>
	<platform>all</platform>
  </extension>
</addon>

<addon id="rogger.repository" name="rogger repository" version="0.0.2" provider-name="rogger2">
	<extension point="xbmc.addon.repository" name="rogger Add-on Repository">
		<info compressed="false">masterpirates/filmes
</info>
		<checksum>masterpirates/filmes
</checksum>
		<datadir zip="true">masterpirates/filmes
</datadir>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary>rogger Addon</summary>
		<description>Addon Description</description>
		<disclaimer></disclaimer>
		<platform>all</platform>
	</extension>
</addon>
</addons>
