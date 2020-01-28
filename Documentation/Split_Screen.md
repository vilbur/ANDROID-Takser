<TaskerData sr="" dvi="1" tv="5.9.1">
	<Project sr="proj0" ve="2">
		<cdate>1579807560182</cdate>
		<name>Split Screen</name>
		<tids>9,10</tids>
	</Project>
	<Task sr="task10">
		<cdate>1579962899132</cdate>
		<edate>1579962904430</edate>
		<id>10</id>
		<nme>v</nme>
		<Action sr="act0" ve="7">
			<code>30</code>
			<Int sr="arg0" val="0"/>
			<Int sr="arg1" val="1"/>
			<Int sr="arg2" val="0"/>
			<Int sr="arg3" val="0"/>
			<Int sr="arg4" val="0"/>
		</Action>
		<Action sr="act1" ve="7">
			<code>244</code>
		</Action>
		<Action sr="act2" ve="7">
			<code>30</code>
			<Int sr="arg0" val="0"/>
			<Int sr="arg1" val="1"/>
			<Int sr="arg2" val="0"/>
			<Int sr="arg3" val="0"/>
			<Int sr="arg4" val="0"/>
		</Action>
		<Action sr="act3" ve="7">
			<code>20</code>
			<App sr="arg0">
				<appClass>com.ghisler.android.TotalCommander.TotalCommander</appClass>
				<appPkg>com.ghisler.android.TotalCommander</appPkg>
				<label>Total Commander</label>
			</App>
			<Str sr="arg1" ve="3"/>
			<Int sr="arg2" val="0"/>
			<Int sr="arg3" val="0"/>
		</Action>
	</Task>
	<Task sr="task9">
		<cdate>1579860571819</cdate>
		<edate>1579979033053</edate>
		<id>9</id>
		<nme>Split.currentAppAndTotalCommander</nme>
		<pri>100</pri>
		<Action sr="act0" ve="7">
			<code>547</code>
			<Str sr="arg0" ve="3">%last_package</Str>
			<Str sr="arg1" ve="3">%LAST_APP_PACKAGE</Str>
			<Int sr="arg2" val="0"/>
			<Int sr="arg3" val="0"/>
			<Int sr="arg4" val="0"/>
			<Int sr="arg5" val="3"/>
		</Action>
		<Action sr="act1" ve="7">
			<code>547</code>
			<Str sr="arg0" ve="3">%last_app</Str>
			<Str sr="arg1" ve="3">%LAST_APP_NAME</Str>
			<Int sr="arg2" val="0"/>
			<Int sr="arg3" val="0"/>
			<Int sr="arg4" val="0"/>
			<Int sr="arg5" val="3"/>
		</Action>
		<Action sr="act2" ve="7">
			<code>548</code>
			<Str sr="arg0" ve="3">%last_package</Str>
			<Int sr="arg1" val="0"/>
		</Action>
		<Action sr="act3" ve="7">
			<code>1795842217</code>
			<Bundle sr="arg0">
				<Vals sr="val">
					<AppLabel>&lt;null&gt;</AppLabel>
					<AppLabel-type>java.lang.String</AppLabel-type>
					<AppNickname>%last_app</AppNickname>
					<AppNickname-type>java.lang.String</AppNickname-type>
					<ContainsAllAppLabel>false</ContainsAllAppLabel>
					<ContainsAllAppLabel-type>java.lang.Boolean</ContainsAllAppLabel-type>
					<ContainsAllAppNickname>false</ContainsAllAppNickname>
					<ContainsAllAppNickname-type>java.lang.Boolean</ContainsAllAppNickname-type>
					<ContainsAllPackageName>false</ContainsAllPackageName>
					<ContainsAllPackageName-type>java.lang.Boolean</ContainsAllPackageName-type>
					<ExactAppLabel>false</ExactAppLabel>
					<ExactAppLabel-type>java.lang.Boolean</ExactAppLabel-type>
					<ExactAppNickname>true</ExactAppNickname>
					<ExactAppNickname-type>java.lang.Boolean</ExactAppNickname-type>
					<ExactPackageName>false</ExactPackageName>
					<ExactPackageName-type>java.lang.Boolean</ExactPackageName-type>
					<OptionAlwaysStartNewCopy>false</OptionAlwaysStartNewCopy>
					<OptionAlwaysStartNewCopy-type>java.lang.Boolean</OptionAlwaysStartNewCopy-type>
					<OptionExcludeFromRecents>false</OptionExcludeFromRecents>
					<OptionExcludeFromRecents-type>java.lang.Boolean</OptionExcludeFromRecents-type>
					<PackageName>&lt;null&gt;</PackageName>
					<PackageName-type>java.lang.String</PackageName-type>
					<RegexAppLabel>false</RegexAppLabel>
					<RegexAppLabel-type>java.lang.Boolean</RegexAppLabel-type>
					<RegexAppNickname>false</RegexAppNickname>
					<RegexAppNickname-type>java.lang.Boolean</RegexAppNickname-type>
					<RegexPackageName>false</RegexPackageName>
					<RegexPackageName-type>java.lang.Boolean</RegexPackageName-type>
					<com.twofortyfouram.locale.intent.extra.BLURB>Name or Nickname: "%last_app"
Exact Name or Nickname: true</com.twofortyfouram.locale.intent.extra.BLURB>
					<com.twofortyfouram.locale.intent.extra.BLURB-type>java.lang.String</com.twofortyfouram.locale.intent.extra.BLURB-type>
					<net.dinglisch.android.tasker.RELEVANT_VARIABLES>&lt;StringArray sr=""&gt;&lt;_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES0&gt;%alactivity
Launcher Activity Name
&lt;/_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES0&gt;&lt;_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES1&gt;%allabel
Label
&lt;/_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES1&gt;&lt;_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES2&gt;%alnicklabel
Nickname or Label
&lt;/_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES2&gt;&lt;_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES3&gt;%alnickname
Nickname
&lt;/_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES3&gt;&lt;_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES4&gt;%alpackage
Package Name
&lt;/_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES4&gt;&lt;_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES5&gt;%err
Error Code
Only available if you select &amp;lt;b&amp;gt;Continue Task After Error&amp;lt;/b&amp;gt; and the action ends in error&lt;/_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES5&gt;&lt;_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES6&gt;%errmsg
Error Message
Only available if you select &amp;lt;b&amp;gt;Continue Task After Error&amp;lt;/b&amp;gt; and the action ends in error&lt;/_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES6&gt;&lt;/StringArray&gt;</net.dinglisch.android.tasker.RELEVANT_VARIABLES>
					<net.dinglisch.android.tasker.RELEVANT_VARIABLES-type>[Ljava.lang.String;</net.dinglisch.android.tasker.RELEVANT_VARIABLES-type>
					<net.dinglisch.android.tasker.extras.VARIABLE_REPLACE_KEYS>AppNickname plugininstanceid plugintypeid </net.dinglisch.android.tasker.extras.VARIABLE_REPLACE_KEYS>
					<net.dinglisch.android.tasker.extras.VARIABLE_REPLACE_KEYS-type>java.lang.String</net.dinglisch.android.tasker.extras.VARIABLE_REPLACE_KEYS-type>
					<net.dinglisch.android.tasker.subbundled>true</net.dinglisch.android.tasker.subbundled>
					<net.dinglisch.android.tasker.subbundled-type>java.lang.Boolean</net.dinglisch.android.tasker.subbundled-type>
					<plugininstanceid>d348caf4-ad35-48a0-ad53-46fd38d62ddb</plugininstanceid>
					<plugininstanceid-type>java.lang.String</plugininstanceid-type>
					<plugintypeid>com.joaomgcd.autoapps.intent.IntentLaunchApp</plugintypeid>
					<plugintypeid-type>java.lang.String</plugintypeid-type>
				</Vals>
			</Bundle>
			<Str sr="arg1" ve="3">com.joaomgcd.autoapps</Str>
			<Str sr="arg2" ve="3">com.joaomgcd.autoapps.activity.ActivityConfigLaunchApp</Str>
			<Int sr="arg3" val="60"/>
		</Action>
		<Action sr="act4" ve="7">
			<code>30</code>
			<Int sr="arg0" val="537"/>
			<Int sr="arg1" val="0"/>
			<Int sr="arg2" val="0"/>
			<Int sr="arg3" val="0"/>
			<Int sr="arg4" val="0"/>
		</Action>
		<Action sr="act5" ve="7">
			<code>244</code>
		</Action>
		<Action sr="act6" ve="7">
			<code>30</code>
			<Int sr="arg0" val="0"/>
			<Int sr="arg1" val="1"/>
			<Int sr="arg2" val="0"/>
			<Int sr="arg3" val="0"/>
			<Int sr="arg4" val="0"/>
		</Action>
		<Action sr="act7" ve="7">
			<code>20</code>
			<App sr="arg0">
				<appClass>com.ghisler.android.TotalCommander.TotalCommander</appClass>
				<appPkg>com.ghisler.android.TotalCommander</appPkg>
				<label>Total Commander</label>
			</App>
			<Str sr="arg1" ve="3"/>
			<Int sr="arg2" val="0"/>
			<Int sr="arg3" val="0"/>
		</Action>
		<Img sr="icn" ve="2">
			<nme>mw_communication_stop_screen_share</nme>
		</Img>
	</Task>
</TaskerData>
