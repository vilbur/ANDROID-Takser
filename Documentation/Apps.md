<TaskerData sr="" dvi="1" tv="5.9.1">
	<Profile sr="prof12" ve="2">
		<cdate>1579965973923</cdate>
		<edate>1579965973923</edate>
		<flags>8</flags>
		<id>12</id>
		<mid0>11</mid0>
		<Event sr="con0" ve="2">
			<code>2078</code>
			<pri>0</pri>
			<Bundle sr="arg0">
				<Vals sr="val">
					<net.dinglisch.android.tasker.RELEVANT_VARIABLES>&lt;StringArray sr=""&gt;&lt;_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES0&gt;%app_icon
Icon
Icon for the app&lt;/_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES0&gt;&lt;_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES1&gt;%app_name
Name
Name of the App&lt;/_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES1&gt;&lt;_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES2&gt;%app_package
Package
Unique package name for the app&lt;/_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES2&gt;&lt;/StringArray&gt;</net.dinglisch.android.tasker.RELEVANT_VARIABLES>
					<net.dinglisch.android.tasker.RELEVANT_VARIABLES-type>[Ljava.lang.String;</net.dinglisch.android.tasker.RELEVANT_VARIABLES-type>
				</Vals>
			</Bundle>
			<Str sr="arg1" ve="3"/>
		</Event>
	</Profile>
	<Project sr="proj0" ve="2">
		<cdate>1579965656119</cdate>
		<name>Apps</name>
		<pids>12</pids>
		<tids>15,11</tids>
	</Project>
	<Task sr="task11">
		<cdate>1579965688664</cdate>
		<edate>1580025503997</edate>
		<id>11</id>
		<nme>Apps.getAppInfo</nme>
		<pri>6</pri>
		<Action sr="act0" ve="7">
			<code>335</code>
			<Bundle sr="arg0">
				<Vals sr="val">
					<net.dinglisch.android.tasker.RELEVANT_VARIABLES>&lt;StringArray sr=""&gt;&lt;_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES0&gt;%app_icon
Icon
Icon for the app&lt;/_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES0&gt;&lt;_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES1&gt;%app_name
Name
Name of the App&lt;/_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES1&gt;&lt;_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES2&gt;%app_package
Package
Unique package name for the app&lt;/_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES2&gt;&lt;/StringArray&gt;</net.dinglisch.android.tasker.RELEVANT_VARIABLES>
					<net.dinglisch.android.tasker.RELEVANT_VARIABLES-type>[Ljava.lang.String;</net.dinglisch.android.tasker.RELEVANT_VARIABLES-type>
				</Vals>
			</Bundle>
			<Str sr="arg1" ve="3">last(1)</Str>
			<Str sr="arg2" ve="3"/>
			<Int sr="arg3" val="0"/>
			<Int sr="arg4" val="0"/>
		</Action>
		<Action sr="act1" ve="7">
			<code>137</code>
			<Int sr="arg0" val="0"/>
			<Str sr="arg1" ve="3"/>
			<ConditionList sr="if">
				<bool0>Or</bool0>
				<bool1>Or</bool1>
				<Condition sr="c0" ve="3">
					<lhs>%app_name</lhs>
					<op>2</op>
					<rhs>One UI Home</rhs>
				</Condition>
				<Condition sr="c1" ve="3">
					<lhs>%app_name</lhs>
					<op>2</op>
					<rhs>Nova Launcher</rhs>
				</Condition>
				<Condition sr="c2" ve="3">
					<lhs>%app_name</lhs>
					<op>2</op>
					<rhs>AutoLaunch</rhs>
				</Condition>
			</ConditionList>
		</Action>
		<Action sr="act2" ve="7">
			<code>547</code>
			<Str sr="arg0" ve="3">%LAST_APP_PACKAGE</Str>
			<Str sr="arg1" ve="3">%app_package </Str>
			<Int sr="arg2" val="0"/>
			<Int sr="arg3" val="0"/>
			<Int sr="arg4" val="0"/>
			<Int sr="arg5" val="3"/>
		</Action>
		<Action sr="act3" ve="7">
			<code>547</code>
			<Str sr="arg0" ve="3">%LAST_APP_NAME</Str>
			<Str sr="arg1" ve="3">%app_name</Str>
			<Int sr="arg2" val="0"/>
			<Int sr="arg3" val="0"/>
			<Int sr="arg4" val="0"/>
			<Int sr="arg5" val="3"/>
		</Action>
	</Task>
	<Task sr="task15">
		<cdate>1579967251294</cdate>
		<edate>1579973292000</edate>
		<id>15</id>
		<nme>Apps.getLastApp</nme>
		<pri>100</pri>
		<Action sr="act0" ve="7">
			<code>548</code>
			<Str sr="arg0" ve="3">%LAST_APP_PACKAGE/%LAST_APP_NAME</Str>
			<Int sr="arg1" val="0"/>
		</Action>
		<Img sr="icn" ve="2">
			<nme>hl_ab_navigation_back</nme>
		</Img>
	</Task>
</TaskerData>
