# calender-project-tools
calender/project tools addon for Thunderbird

	1. The addon creates a new calendar with the name "Ganttview calendar". All events created in that calendar	will be shown in the Gantt
				View and in the calendar Year View. Both views are automatically updated when you create/modify or remove events.

			  Open Ganttview by clicking the Ganttview button. Open year calendar view by Shift + clicking the Ganttview button.
				
				In Calendar View, click the event to edit. In Gantt view, click the table entry to edit the event.
				For recurring events, they may only be shown if the start event is inside the time window, due to a
				current limitation for "fetching" events from the database.
			
   2. ctrl+Gantview button opens the task/project planning page. The gantt view will show	all tasks that have a start and end date set. !! On task creation in TB, both dates are set to inactive!!
					If you set status, "in Arbeit (under work)", you can set a completion status (percent-complete), which is shown in an inlaid bar inside the task bar.
		
					If you drag a task onto another task, it will be converted to a child task. If you drag it to the empty
					field above the top task name, it will go back to top level.
					<br>If you doubleclick a task name, the edit dialog will open. If you adapt percent-complete, it will
					be shown in the gantt chart accordingly.
			
		3. You can open the Planner page by clicking Alt + Gantt View button.<br/><br/>
				On the left, you will see your current tasks. You can drag them into the day view to plan
				at which time today to work on them. 
			 If you click into the task on the calendar, it will convert to green background - e.g. to indicate you
				finished your work on this for today.
				 If you doubleclick a task in the list on the left, its edit dialog will open. If you set it to 100% complete,
				 it will be removed from the list.
				Please note: this calendar view is not saved yet. It will be shown with its entries as long
				 as the tab is open.
				 
				Slowly, there will come more features:
				
					<li> choose which calendars to include in the views </li>
					<li> interactively change events in the views </li>
					<li> include tasks </li>
					<li> "quick enter" for sets of events and tasks. </li>
					<li> add parent child relationships to task, aka "project management" </li>
					<li> show % complete in the Gantt bars </li>
					<li> add links, notes etc. to events and tasks </li>
					<li> resources for tasks and events* etc. </li>
					<li> sync events and tasks to others, maybe even with ACL (access control) </li>
				
			
				If you want to support some of this, I am thankful for donations:<br><br>
				<h3 style="color: rgb(166, 77, 121);text-align:center"><span
						style="color: rgb(166, 77, 121);text-align:center"><strong>Donations are very much welcome. <br>
							Paypal:&nbsp;<a
								data-external-href="https://www.paypal.com/donate/?hosted_button_id=BRNZYE8JC47QU"
								rel="nofollow"
								style="box-sizing: border-box; color: red;background-color: rgb(255, 255, 255); color: var(--color-accent-fg); text-decoration: underline; font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, &quot;Noto Sans&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;; font-size: 18px; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; white-space: normal;">
								I want to support the addon Calendar Tools</a></strong></span></h2>

					<br><br>
					If you need specific features for your business, please contact me at buecher (at) optosolar.com. I
					have been
					personally involved in coding for an open source project management software before supporting
					Thunderbird addons.<br>
			</div>
		</div>
		<p>Icon from here: <a href="https://www.flaticon.com/de/kostenlose-icons/gantt-diagramm"
				title="gantt-diagramm Icons">Gantt-diagramm Icons erstellt von iconading - Flaticon</a></p>
