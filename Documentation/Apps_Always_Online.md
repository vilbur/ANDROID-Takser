<TaskerData sr="" dvi="1" tv="5.9.1">
	<Project sr="proj0" ve="2">
		<cdate>1580299410218</cdate>
		<name>Apps Always Online</name>
		<tids>161,160</tids>
	</Project>
	<Task sr="task160">
		<cdate>1580299432632</cdate>
		<edate>1580320307770</edate>
		<id>160</id>
		<nme>Am.x</nme>
		<pri>100</pri>
		<Action sr="act0" ve="7">
			<code>433</code>
			<Int sr="arg0" val="1"/>
		</Action>
		<Action sr="act1" ve="7">
			<code>220</code>
		</Action>
		<Action sr="act2" ve="7">
			<code>433</code>
			<Int sr="arg0" val="0"/>
		</Action>
		<Action sr="act3" ve="7">
			<code>548</code>
			<Str sr="arg0" ve="3">%WIFII</Str>
			<Int sr="arg1" val="0"/>
		</Action>
	</Task>
	<Task sr="task161">
		<cdate>1580320357518</cdate>
		<edate>1580320434002</edate>
		<id>161</id>
		<nme>AAO.wifiTest</nme>
		<pri>100</pri>
		<Action sr="act0" ve="7">
			<code>425</code>
			<Int sr="arg0" val="1"/>
			<ConditionList sr="if">
				<Condition sr="c0" ve="3">
					<lhs>%WIFII</lhs>
					<op>3</op>
					<rhs>CONNECTION</rhs>
				</Condition>
			</ConditionList>
		</Action>
	</Task>
</TaskerData>
