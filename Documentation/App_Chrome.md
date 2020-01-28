<TaskerData sr="" dvi="1" tv="5.9.1">
	<Project sr="proj0" ve="2">
		<cdate>1579981274747</cdate>
		<name>App Chrome</name>
		<tids>24,28,22,20</tids>
		<Img sr="icon" ve="2">
			<cls>com.google.android.apps.chrome.Main</cls>
			<pkg>com.android.chrome</pkg>
		</Img>
	</Project>
	<Task sr="task20">
		<cdate>1579981790233</cdate>
		<edate>1579985914810</edate>
		<id>20</id>
		<nme>Chrome.opeNewTab</nme>
		<pri>100</pri>
		<Action sr="act0" ve="7">
			<code>877</code>
			<Str sr="arg0" ve="3">android.intent.action.VIEW</Str>
			<Int sr="arg1" val="0"/>
			<Str sr="arg2" ve="3"/>
			<Str sr="arg3" ve="3">http://www.google.com</Str>
			<Str sr="arg4" ve="3"/>
			<Str sr="arg5" ve="3"/>
			<Str sr="arg6" ve="3"/>
			<Str sr="arg7" ve="3">com.android.chrome</Str>
			<Str sr="arg8" ve="3"/>
			<Int sr="arg9" val="1"/>
		</Action>
		<Action sr="act1" ve="7">
			<code>130</code>
			<Str sr="arg0" ve="3">Chrome.clickVoiceSearch</Str>
			<Int sr="arg1">
				<var>%priority</var>
			</Int>
			<Str sr="arg2" ve="3"/>
			<Str sr="arg3" ve="3"/>
			<Str sr="arg4" ve="3"/>
			<Int sr="arg5" val="0"/>
		</Action>
	</Task>
	<Task sr="task22">
		<cdate>1579985449770</cdate>
		<edate>1579986354531</edate>
		<id>22</id>
		<nme>Chrome.clickVoiceSearch</nme>
		<Action sr="act0" ve="7">
			<code>1732635924</code>
			<Bundle sr="arg0">
				<Vals sr="val">
					<ActionId>Start voice search</ActionId>
					<ActionId-type>java.lang.String</ActionId-type>
					<ActionType>16</ActionType>
					<ActionType-type>java.lang.String</ActionType-type>
					<EnableDisableAccessibilityService>&lt;null&gt;</EnableDisableAccessibilityService>
					<EnableDisableAccessibilityService-type>java.lang.String</EnableDisableAccessibilityService-type>
					<FieldSelectionType>0</FieldSelectionType>
					<FieldSelectionType-type>java.lang.String</FieldSelectionType-type>
					<IsFirstAction>false</IsFirstAction>
					<IsFirstAction-type>java.lang.Boolean</IsFirstAction-type>
					<IsTaskerAction>true</IsTaskerAction>
					<IsTaskerAction-type>java.lang.Boolean</IsTaskerAction-type>
					<NearbyText>&lt;null&gt;</NearbyText>
					<NearbyText-type>java.lang.String</NearbyText-type>
					<Password>&lt;null&gt;</Password>
					<Password-type>java.lang.String</Password-type>
					<RepeatInterval>&lt;null&gt;</RepeatInterval>
					<RepeatInterval-type>java.lang.String</RepeatInterval-type>
					<RepeatTimes>&lt;null&gt;</RepeatTimes>
					<RepeatTimes-type>java.lang.String</RepeatTimes-type>
					<StoredAction>&lt;null&gt;</StoredAction>
					<StoredAction-type>java.lang.String</StoredAction-type>
					<TextToWrite>&lt;null&gt;</TextToWrite>
					<TextToWrite-type>java.lang.String</TextToWrite-type>
					<com.twofortyfouram.locale.intent.extra.BLURB>Type: Text
Value: Start voice search
Action : Click
Is Tasker Action: true</com.twofortyfouram.locale.intent.extra.BLURB>
					<com.twofortyfouram.locale.intent.extra.BLURB-type>java.lang.String</com.twofortyfouram.locale.intent.extra.BLURB-type>
					<net.dinglisch.android.tasker.RELEVANT_VARIABLES>&lt;StringArray sr=""&gt;&lt;_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES0&gt;%err
Error Code
Only available if you select &amp;lt;b&amp;gt;Continue Task After Error&amp;lt;/b&amp;gt; and the action ends in error&lt;/_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES0&gt;&lt;_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES1&gt;%errmsg
Error Message
Only available if you select &amp;lt;b&amp;gt;Continue Task After Error&amp;lt;/b&amp;gt; and the action ends in error&lt;/_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES1&gt;&lt;/StringArray&gt;</net.dinglisch.android.tasker.RELEVANT_VARIABLES>
					<net.dinglisch.android.tasker.RELEVANT_VARIABLES-type>[Ljava.lang.String;</net.dinglisch.android.tasker.RELEVANT_VARIABLES-type>
					<net.dinglisch.android.tasker.extras.VARIABLE_REPLACE_KEYS>ActionId FieldSelectionType ActionType plugininstanceid plugintypeid </net.dinglisch.android.tasker.extras.VARIABLE_REPLACE_KEYS>
					<net.dinglisch.android.tasker.extras.VARIABLE_REPLACE_KEYS-type>java.lang.String</net.dinglisch.android.tasker.extras.VARIABLE_REPLACE_KEYS-type>
					<net.dinglisch.android.tasker.subbundled>true</net.dinglisch.android.tasker.subbundled>
					<net.dinglisch.android.tasker.subbundled-type>java.lang.Boolean</net.dinglisch.android.tasker.subbundled-type>
					<plugininstanceid>8d297a07-b57b-4b8a-b8c1-625ec71aaf8a</plugininstanceid>
					<plugininstanceid-type>java.lang.String</plugininstanceid-type>
					<plugintypeid>com.joaomgcd.autoinput.intent.IntentPerformAction</plugintypeid>
					<plugintypeid-type>java.lang.String</plugintypeid-type>
				</Vals>
			</Bundle>
			<Str sr="arg1" ve="3">com.joaomgcd.autoinput</Str>
			<Str sr="arg2" ve="3">com.joaomgcd.autoinput.activity.ActivityConfigPerformAction</Str>
			<Int sr="arg3" val="23"/>
		</Action>
	</Task>
	<Task sr="task24">
		<cdate>1579985618283</cdate>
		<edate>1579986795304</edate>
		<id>24</id>
		<nme>Chrome.closeAllTabs</nme>
		<pri>100</pri>
		<Action sr="act0" ve="7">
			<code>20</code>
			<App sr="arg0">
				<appClass>com.google.android.apps.chrome.Main</appClass>
				<appPkg>com.android.chrome</appPkg>
				<label>Chrome</label>
			</App>
			<Str sr="arg1" ve="3"/>
			<Int sr="arg2" val="0"/>
			<Int sr="arg3" val="0"/>
		</Action>
		<Action sr="act1" ve="7">
			<code>130</code>
			<Str sr="arg0" ve="3">Chrome.wait</Str>
			<Int sr="arg1">
				<var>%priority</var>
			</Int>
			<Str sr="arg2" ve="3"/>
			<Str sr="arg3" ve="3"/>
			<Str sr="arg4" ve="3"/>
			<Int sr="arg5" val="0"/>
		</Action>
		<Action sr="act2" ve="7">
			<code>1732635924</code>
			<Bundle sr="arg0">
				<Vals sr="val">
					<ActionId>com.android.chrome:id/tab_switcher_button</ActionId>
					<ActionId-type>java.lang.String</ActionId-type>
					<ActionType>16</ActionType>
					<ActionType-type>java.lang.String</ActionType-type>
					<EnableDisableAccessibilityService>&lt;null&gt;</EnableDisableAccessibilityService>
					<EnableDisableAccessibilityService-type>java.lang.String</EnableDisableAccessibilityService-type>
					<FieldSelectionType>1</FieldSelectionType>
					<FieldSelectionType-type>java.lang.String</FieldSelectionType-type>
					<IsFirstAction>false</IsFirstAction>
					<IsFirstAction-type>java.lang.Boolean</IsFirstAction-type>
					<IsTaskerAction>true</IsTaskerAction>
					<IsTaskerAction-type>java.lang.Boolean</IsTaskerAction-type>
					<NearbyText>&lt;null&gt;</NearbyText>
					<NearbyText-type>java.lang.String</NearbyText-type>
					<Password>&lt;null&gt;</Password>
					<Password-type>java.lang.String</Password-type>
					<RepeatInterval>&lt;null&gt;</RepeatInterval>
					<RepeatInterval-type>java.lang.String</RepeatInterval-type>
					<RepeatTimes>&lt;null&gt;</RepeatTimes>
					<RepeatTimes-type>java.lang.String</RepeatTimes-type>
					<StoredAction>&lt;null&gt;</StoredAction>
					<StoredAction-type>java.lang.String</StoredAction-type>
					<TextToWrite>&lt;null&gt;</TextToWrite>
					<TextToWrite-type>java.lang.String</TextToWrite-type>
					<com.twofortyfouram.locale.intent.extra.BLURB>Type: Id
Value: com.android.chrome:id/tab_switcher_button
Action : Click
Is Tasker Action: true</com.twofortyfouram.locale.intent.extra.BLURB>
					<com.twofortyfouram.locale.intent.extra.BLURB-type>java.lang.String</com.twofortyfouram.locale.intent.extra.BLURB-type>
					<net.dinglisch.android.tasker.RELEVANT_VARIABLES>&lt;StringArray sr=""&gt;&lt;_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES0&gt;%err
Error Code
Only available if you select &amp;lt;b&amp;gt;Continue Task After Error&amp;lt;/b&amp;gt; and the action ends in error&lt;/_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES0&gt;&lt;_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES1&gt;%errmsg
Error Message
Only available if you select &amp;lt;b&amp;gt;Continue Task After Error&amp;lt;/b&amp;gt; and the action ends in error&lt;/_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES1&gt;&lt;/StringArray&gt;</net.dinglisch.android.tasker.RELEVANT_VARIABLES>
					<net.dinglisch.android.tasker.RELEVANT_VARIABLES-type>[Ljava.lang.String;</net.dinglisch.android.tasker.RELEVANT_VARIABLES-type>
					<net.dinglisch.android.tasker.extras.VARIABLE_REPLACE_KEYS>ActionId FieldSelectionType ActionType plugininstanceid plugintypeid </net.dinglisch.android.tasker.extras.VARIABLE_REPLACE_KEYS>
					<net.dinglisch.android.tasker.extras.VARIABLE_REPLACE_KEYS-type>java.lang.String</net.dinglisch.android.tasker.extras.VARIABLE_REPLACE_KEYS-type>
					<net.dinglisch.android.tasker.subbundled>true</net.dinglisch.android.tasker.subbundled>
					<net.dinglisch.android.tasker.subbundled-type>java.lang.Boolean</net.dinglisch.android.tasker.subbundled-type>
					<plugininstanceid>6ba6c944-373c-45fd-8301-471c50687403</plugininstanceid>
					<plugininstanceid-type>java.lang.String</plugininstanceid-type>
					<plugintypeid>com.joaomgcd.autoinput.intent.IntentPerformAction</plugintypeid>
					<plugintypeid-type>java.lang.String</plugintypeid-type>
				</Vals>
			</Bundle>
			<Str sr="arg1" ve="3">com.joaomgcd.autoinput</Str>
			<Str sr="arg2" ve="3">com.joaomgcd.autoinput.activity.ActivityConfigPerformAction</Str>
			<Int sr="arg3" val="23"/>
		</Action>
		<Action sr="act3" ve="7">
			<code>130</code>
			<Str sr="arg0" ve="3">Chrome.wait</Str>
			<Int sr="arg1">
				<var>%priority</var>
			</Int>
			<Str sr="arg2" ve="3"/>
			<Str sr="arg3" ve="3"/>
			<Str sr="arg4" ve="3"/>
			<Int sr="arg5" val="0"/>
		</Action>
		<Action sr="act4" ve="7">
			<code>1732635924</code>
			<Bundle sr="arg0">
				<Vals sr="val">
					<ActionId>com.android.chrome:id/menu_button</ActionId>
					<ActionId-type>java.lang.String</ActionId-type>
					<ActionType>16</ActionType>
					<ActionType-type>java.lang.String</ActionType-type>
					<EnableDisableAccessibilityService>&lt;null&gt;</EnableDisableAccessibilityService>
					<EnableDisableAccessibilityService-type>java.lang.String</EnableDisableAccessibilityService-type>
					<FieldSelectionType>1</FieldSelectionType>
					<FieldSelectionType-type>java.lang.String</FieldSelectionType-type>
					<IsFirstAction>false</IsFirstAction>
					<IsFirstAction-type>java.lang.Boolean</IsFirstAction-type>
					<IsTaskerAction>true</IsTaskerAction>
					<IsTaskerAction-type>java.lang.Boolean</IsTaskerAction-type>
					<NearbyText>&lt;null&gt;</NearbyText>
					<NearbyText-type>java.lang.String</NearbyText-type>
					<Password>&lt;null&gt;</Password>
					<Password-type>java.lang.String</Password-type>
					<RepeatInterval>&lt;null&gt;</RepeatInterval>
					<RepeatInterval-type>java.lang.String</RepeatInterval-type>
					<RepeatTimes>&lt;null&gt;</RepeatTimes>
					<RepeatTimes-type>java.lang.String</RepeatTimes-type>
					<StoredAction>&lt;null&gt;</StoredAction>
					<StoredAction-type>java.lang.String</StoredAction-type>
					<TextToWrite>&lt;null&gt;</TextToWrite>
					<TextToWrite-type>java.lang.String</TextToWrite-type>
					<com.twofortyfouram.locale.intent.extra.BLURB>Type: Id
Value: com.android.chrome:id/menu_button
Action : Click
Is Tasker Action: true</com.twofortyfouram.locale.intent.extra.BLURB>
					<com.twofortyfouram.locale.intent.extra.BLURB-type>java.lang.String</com.twofortyfouram.locale.intent.extra.BLURB-type>
					<net.dinglisch.android.tasker.RELEVANT_VARIABLES>&lt;StringArray sr=""&gt;&lt;_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES0&gt;%err
Error Code
Only available if you select &amp;lt;b&amp;gt;Continue Task After Error&amp;lt;/b&amp;gt; and the action ends in error&lt;/_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES0&gt;&lt;_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES1&gt;%errmsg
Error Message
Only available if you select &amp;lt;b&amp;gt;Continue Task After Error&amp;lt;/b&amp;gt; and the action ends in error&lt;/_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES1&gt;&lt;/StringArray&gt;</net.dinglisch.android.tasker.RELEVANT_VARIABLES>
					<net.dinglisch.android.tasker.RELEVANT_VARIABLES-type>[Ljava.lang.String;</net.dinglisch.android.tasker.RELEVANT_VARIABLES-type>
					<net.dinglisch.android.tasker.extras.VARIABLE_REPLACE_KEYS>ActionId FieldSelectionType ActionType plugininstanceid plugintypeid </net.dinglisch.android.tasker.extras.VARIABLE_REPLACE_KEYS>
					<net.dinglisch.android.tasker.extras.VARIABLE_REPLACE_KEYS-type>java.lang.String</net.dinglisch.android.tasker.extras.VARIABLE_REPLACE_KEYS-type>
					<net.dinglisch.android.tasker.subbundled>true</net.dinglisch.android.tasker.subbundled>
					<net.dinglisch.android.tasker.subbundled-type>java.lang.Boolean</net.dinglisch.android.tasker.subbundled-type>
					<plugininstanceid>6ba6c944-373c-45fd-8301-471c50687403</plugininstanceid>
					<plugininstanceid-type>java.lang.String</plugininstanceid-type>
					<plugintypeid>com.joaomgcd.autoinput.intent.IntentPerformAction</plugintypeid>
					<plugintypeid-type>java.lang.String</plugintypeid-type>
				</Vals>
			</Bundle>
			<Str sr="arg1" ve="3">com.joaomgcd.autoinput</Str>
			<Str sr="arg2" ve="3">com.joaomgcd.autoinput.activity.ActivityConfigPerformAction</Str>
			<Int sr="arg3" val="23"/>
		</Action>
		<Action sr="act5" ve="7">
			<code>130</code>
			<Str sr="arg0" ve="3">Chrome.wait</Str>
			<Int sr="arg1">
				<var>%priority</var>
			</Int>
			<Str sr="arg2" ve="3"/>
			<Str sr="arg3" ve="3"/>
			<Str sr="arg4" ve="3"/>
			<Int sr="arg5" val="0"/>
		</Action>
		<Action sr="act6" ve="7">
			<code>1732635924</code>
			<Bundle sr="arg0">
				<Vals sr="val">
					<ActionId>Close all tabs</ActionId>
					<ActionId-type>java.lang.String</ActionId-type>
					<ActionType>16</ActionType>
					<ActionType-type>java.lang.String</ActionType-type>
					<EnableDisableAccessibilityService>&lt;null&gt;</EnableDisableAccessibilityService>
					<EnableDisableAccessibilityService-type>java.lang.String</EnableDisableAccessibilityService-type>
					<FieldSelectionType>0</FieldSelectionType>
					<FieldSelectionType-type>java.lang.String</FieldSelectionType-type>
					<IsFirstAction>false</IsFirstAction>
					<IsFirstAction-type>java.lang.Boolean</IsFirstAction-type>
					<IsTaskerAction>true</IsTaskerAction>
					<IsTaskerAction-type>java.lang.Boolean</IsTaskerAction-type>
					<NearbyText>&lt;null&gt;</NearbyText>
					<NearbyText-type>java.lang.String</NearbyText-type>
					<Password>&lt;null&gt;</Password>
					<Password-type>java.lang.String</Password-type>
					<RepeatInterval>&lt;null&gt;</RepeatInterval>
					<RepeatInterval-type>java.lang.String</RepeatInterval-type>
					<RepeatTimes>&lt;null&gt;</RepeatTimes>
					<RepeatTimes-type>java.lang.String</RepeatTimes-type>
					<StoredAction>&lt;null&gt;</StoredAction>
					<StoredAction-type>java.lang.String</StoredAction-type>
					<TextToWrite>&lt;null&gt;</TextToWrite>
					<TextToWrite-type>java.lang.String</TextToWrite-type>
					<com.twofortyfouram.locale.intent.extra.BLURB>Type: Text
Value: Close all tabs
Action : Click
Is Tasker Action: true</com.twofortyfouram.locale.intent.extra.BLURB>
					<com.twofortyfouram.locale.intent.extra.BLURB-type>java.lang.String</com.twofortyfouram.locale.intent.extra.BLURB-type>
					<net.dinglisch.android.tasker.RELEVANT_VARIABLES>&lt;StringArray sr=""&gt;&lt;_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES0&gt;%err
Error Code
Only available if you select &amp;lt;b&amp;gt;Continue Task After Error&amp;lt;/b&amp;gt; and the action ends in error&lt;/_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES0&gt;&lt;_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES1&gt;%errmsg
Error Message
Only available if you select &amp;lt;b&amp;gt;Continue Task After Error&amp;lt;/b&amp;gt; and the action ends in error&lt;/_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES1&gt;&lt;/StringArray&gt;</net.dinglisch.android.tasker.RELEVANT_VARIABLES>
					<net.dinglisch.android.tasker.RELEVANT_VARIABLES-type>[Ljava.lang.String;</net.dinglisch.android.tasker.RELEVANT_VARIABLES-type>
					<net.dinglisch.android.tasker.extras.VARIABLE_REPLACE_KEYS>ActionId FieldSelectionType ActionType plugininstanceid plugintypeid </net.dinglisch.android.tasker.extras.VARIABLE_REPLACE_KEYS>
					<net.dinglisch.android.tasker.extras.VARIABLE_REPLACE_KEYS-type>java.lang.String</net.dinglisch.android.tasker.extras.VARIABLE_REPLACE_KEYS-type>
					<net.dinglisch.android.tasker.subbundled>true</net.dinglisch.android.tasker.subbundled>
					<net.dinglisch.android.tasker.subbundled-type>java.lang.Boolean</net.dinglisch.android.tasker.subbundled-type>
					<plugininstanceid>6ba6c944-373c-45fd-8301-471c50687403</plugininstanceid>
					<plugininstanceid-type>java.lang.String</plugininstanceid-type>
					<plugintypeid>com.joaomgcd.autoinput.intent.IntentPerformAction</plugintypeid>
					<plugintypeid-type>java.lang.String</plugintypeid-type>
				</Vals>
			</Bundle>
			<Str sr="arg1" ve="3">com.joaomgcd.autoinput</Str>
			<Str sr="arg2" ve="3">com.joaomgcd.autoinput.activity.ActivityConfigPerformAction</Str>
			<Int sr="arg3" val="23"/>
		</Action>
		<Action sr="act7" ve="7">
			<code>130</code>
			<Str sr="arg0" ve="3">Chrome.wait</Str>
			<Int sr="arg1">
				<var>%priority</var>
			</Int>
			<Str sr="arg2" ve="3"/>
			<Str sr="arg3" ve="3"/>
			<Str sr="arg4" ve="3"/>
			<Int sr="arg5" val="0"/>
		</Action>
		<Action sr="act8" ve="7">
			<code>1732635924</code>
			<Bundle sr="arg0">
				<Vals sr="val">
					<ActionId>New tab</ActionId>
					<ActionId-type>java.lang.String</ActionId-type>
					<ActionType>16</ActionType>
					<ActionType-type>java.lang.String</ActionType-type>
					<EnableDisableAccessibilityService>&lt;null&gt;</EnableDisableAccessibilityService>
					<EnableDisableAccessibilityService-type>java.lang.String</EnableDisableAccessibilityService-type>
					<FieldSelectionType>0</FieldSelectionType>
					<FieldSelectionType-type>java.lang.String</FieldSelectionType-type>
					<IsFirstAction>false</IsFirstAction>
					<IsFirstAction-type>java.lang.Boolean</IsFirstAction-type>
					<IsTaskerAction>true</IsTaskerAction>
					<IsTaskerAction-type>java.lang.Boolean</IsTaskerAction-type>
					<NearbyText>&lt;null&gt;</NearbyText>
					<NearbyText-type>java.lang.String</NearbyText-type>
					<Password>&lt;null&gt;</Password>
					<Password-type>java.lang.String</Password-type>
					<RepeatInterval>&lt;null&gt;</RepeatInterval>
					<RepeatInterval-type>java.lang.String</RepeatInterval-type>
					<RepeatTimes>&lt;null&gt;</RepeatTimes>
					<RepeatTimes-type>java.lang.String</RepeatTimes-type>
					<StoredAction>&lt;null&gt;</StoredAction>
					<StoredAction-type>java.lang.String</StoredAction-type>
					<TextToWrite>&lt;null&gt;</TextToWrite>
					<TextToWrite-type>java.lang.String</TextToWrite-type>
					<com.twofortyfouram.locale.intent.extra.BLURB>Type: Text
Value: New tab
Action : Click
Is Tasker Action: true</com.twofortyfouram.locale.intent.extra.BLURB>
					<com.twofortyfouram.locale.intent.extra.BLURB-type>java.lang.String</com.twofortyfouram.locale.intent.extra.BLURB-type>
					<net.dinglisch.android.tasker.RELEVANT_VARIABLES>&lt;StringArray sr=""&gt;&lt;_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES0&gt;%err
Error Code
Only available if you select &amp;lt;b&amp;gt;Continue Task After Error&amp;lt;/b&amp;gt; and the action ends in error&lt;/_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES0&gt;&lt;_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES1&gt;%errmsg
Error Message
Only available if you select &amp;lt;b&amp;gt;Continue Task After Error&amp;lt;/b&amp;gt; and the action ends in error&lt;/_array_net.dinglisch.android.tasker.RELEVANT_VARIABLES1&gt;&lt;/StringArray&gt;</net.dinglisch.android.tasker.RELEVANT_VARIABLES>
					<net.dinglisch.android.tasker.RELEVANT_VARIABLES-type>[Ljava.lang.String;</net.dinglisch.android.tasker.RELEVANT_VARIABLES-type>
					<net.dinglisch.android.tasker.extras.VARIABLE_REPLACE_KEYS>ActionId FieldSelectionType ActionType plugininstanceid plugintypeid </net.dinglisch.android.tasker.extras.VARIABLE_REPLACE_KEYS>
					<net.dinglisch.android.tasker.extras.VARIABLE_REPLACE_KEYS-type>java.lang.String</net.dinglisch.android.tasker.extras.VARIABLE_REPLACE_KEYS-type>
					<net.dinglisch.android.tasker.subbundled>true</net.dinglisch.android.tasker.subbundled>
					<net.dinglisch.android.tasker.subbundled-type>java.lang.Boolean</net.dinglisch.android.tasker.subbundled-type>
					<plugininstanceid>6ba6c944-373c-45fd-8301-471c50687403</plugininstanceid>
					<plugininstanceid-type>java.lang.String</plugininstanceid-type>
					<plugintypeid>com.joaomgcd.autoinput.intent.IntentPerformAction</plugintypeid>
					<plugintypeid-type>java.lang.String</plugintypeid-type>
				</Vals>
			</Bundle>
			<Str sr="arg1" ve="3">com.joaomgcd.autoinput</Str>
			<Str sr="arg2" ve="3">com.joaomgcd.autoinput.activity.ActivityConfigPerformAction</Str>
			<Int sr="arg3" val="23"/>
		</Action>
		<Action sr="act9" ve="7">
			<code>130</code>
			<Str sr="arg0" ve="3">Chrome.clickVoiceSearch</Str>
			<Int sr="arg1">
				<var>%priority</var>
			</Int>
			<Str sr="arg2" ve="3"/>
			<Str sr="arg3" ve="3"/>
			<Str sr="arg4" ve="3"/>
			<Int sr="arg5" val="0"/>
		</Action>
	</Task>
	<Task sr="task28">
		<cdate>1579986042399</cdate>
		<edate>1579986176700</edate>
		<id>28</id>
		<nme>Chrome.wait</nme>
		<Action sr="act0" ve="7">
			<code>30</code>
			<Int sr="arg0" val="253"/>
			<Int sr="arg1" val="0"/>
			<Int sr="arg2" val="0"/>
			<Int sr="arg3" val="0"/>
			<Int sr="arg4" val="0"/>
		</Action>
	</Task>
</TaskerData>
