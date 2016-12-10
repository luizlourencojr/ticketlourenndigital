# ticketlourenndigital
Ticket Lourenn Digital
<?xml version="1.0" encoding="UTF-8" ?>
<!--
By modifying this file, you can customize your context menu popuped as right clicking on the edit zone.
It may be more convinient to access to your frequent used commands via context menu than via the top menu.

Please check "How to Customize the Context Menu" on:
http://sourceforge.net/apps/mediawiki/notepad-plus/index.php?title=Context_Menu
-->
<NotepadPlus>
    <ScintillaContextMenu>
		<!-- 
		Use MenuEntryName and MenuItemName to localize your commands to add. 
		The values should be in English but not in translated language.
		(You can set Notepad++ language back to English from Preferences dialog via menu "Settings->Preferences...")
		-->
        <Item MenuEntryName="Edit" MenuItemName="Cut"/>
        <Item MenuEntryName="Edit" MenuItemName="Copy"/>
        <Item MenuEntryName="Edit" MenuItemName="Paste"/>
        <Item MenuEntryName="Edit" MenuItemName="Delete"/>
        <Item MenuEntryName="Edit" MenuItemName="Select all"/>
        <Item MenuEntryName="Edit" MenuItemName="Begin/End Select"/>
		
		<!-- id="0" is the separator -->
        <Item id="0"/>
		
		<!-- You can use command id to add the commands you want. 
		Check english.xml to get commands id:
		http://notepad-plus.svn.sourceforge.net/viewvc/notepad-plus/trunk/PowerEditor/installer/nativeLang/english.xml
		
		Use FolderName (optional) to create sub-menu. FolderName can be used in any type of item.
		FolderName value can be in any language.
		-->
        <Item FolderName="Style token" id="43022"/>
        <Item FolderName="Style token" id="43024"/>
        <Item FolderName="Style token" id="43026"/>
        <Item FolderName="Style token" id="43028"/>
        <Item FolderName="Style token" id="43030"/>
		
        <Item FolderName="Remove style" id="43023"/>
        <Item FolderName="Remove style" id="43025"/>
        <Item FolderName="Remove style" id="43027"/>
        <Item FolderName="Remove style" id="43029"/>
        <Item FolderName="Remove style" id="43031"/>
        <Item FolderName="Remove style" id="43032"/>
        <Item id="0"/>
		
		<!--
		To add plugin commands, you have to use PluginEntryName and PluginCommandItemName to localize the plugin commands
		-->
		<Item FolderName="Plugin commands" PluginEntryName="MIME Tools" PluginCommandItemName="Base64 Encode" />
        <Item FolderName="Plugin commands" PluginEntryName="MIME Tools" PluginCommandItemName="Base64 Decode" />
		
		<!--
		Use ItemNameAs (optional) to rename the menu item name in the context menu 
		ItemNameAs can be used in any type of item. ItemNameAs value can be in any language.
		-->
        <Item FolderName="Plugin commands" PluginEntryName="NppExport" PluginCommandItemName="Copy all formats to clipboard" ItemNameAs="Copy Text with Syntax Highlighting" />
		<Item id="0"/>
        <Item MenuEntryName="Run" MenuItemName="Google Search"/>
        <Item id="0"/>
        <Item MenuEntryName="Edit" MenuItemName="UPPERCASE"/>
        <Item MenuEntryName="Edit" MenuItemName="lowercase"/>
        <Item id="0"/>
        <Item MenuEntryName="Edit" MenuItemName="Toggle Single Line Comment"/>
        <Item MenuEntryName="Edit" MenuItemName="Block Comment"/>
        <Item MenuEntryName="Edit" MenuItemName="Block Uncomment"/>
        <Item id="0"/>
        <Item MenuEntryName="View" MenuItemName="Hide lines"/>
    </ScintillaContextMenu>
</NotepadPlus>
