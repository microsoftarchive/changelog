# What's New in Wunderlist
Changelog for the Web, Chrome, and Windows 7 applications.

## 3.17.1

  - Only show email change settings if user has an email address
  - Fix unhandled error in localization on app reload 
  - Always use localStorage wrapper to capture exceptions 
  - Capture exceptions when connecting to websocket
  - Fix unhandled error from Firefox not giving access to dataTransfer.types
  - Capture invalid state errors when requesting write transaction for IndexedDB 
  - Poperly redirect to unsupported page for Safari 6
  - Fix typo in context menu item attributes
  - Fix safari having wrong add file UI 
  - Fix deleting list from context menu freezing app if add task input was last in focus
  - Fix animation when completing tasks from the from context menu 

## 3.17.0

  - Add support for double-byte numbers in smart dates
  - Don't crash the Windows 7 app on encryption failures 
  - Move webapp assets to CDN with custom domain (static.wunderlist.com)
  - Fix realtime updates not applying in detail view title
  - Update translations

## 3.16.0

  - We fixed a few bugs in our recently released certificate pinning and user token encryption for Windows 7.

## 3.15.0

  - Right click on a To-do or List. What's that you see? That's right, we've brought Context menus to the webapp. Now you can move, change due dates, copy your to-dos and much more, just at the (right) click of a button.
  - On Windows 7 we added user token encryption and https certificate pinning to keep your account and data super secure.
  - We updated a few translations.

## 3.14.0
  - As a Windows 7 user you might have thought that, like Pi, we were being a little irrational with our never-ending updates and intrusive dialog screen. We will now only bug you about restarting Wunderlist when there is an important change.
  - If you have an infinite number of to-dos then you'll have noticed that the scrollbars were sometimes impossible to see depending on your chosen background. The color of the scrollbars now change to contrast with your background in Chrome and Safari.
  - We fixed some random bugs in the Due Date and Reminder pickers.

## 3.13.1

  - If you like keeping your Wunderlist in minified view, then you'll be happy to know that we fixed a small issue that was causing problems when using the keyboard shortcut to search. The Sidebar will now open and let you search through your lists.
  - We've fixed the issue that was making Automatic Reminders break in the Detail View.
  - Your Smart List names should now show up in the title bar of the browser.
  - Were your Folder arrows looking a little funny when you expanded them to see your lists? We've fixed the chevrons doubling up.
  - Right click on a Folder and you'll now be able to open and delete it straight from the context menu in Windows 7.
  - You can now copy text in comments for Windows 7.
  - If you have a long name you may have encountered an unsightly visual bug in Windows 7. It will now work for you.
  - The Windows 7 update spinner was a little off-centre, we've realigned it.
  - The star lost a bit of its shine when you starred a to-do from the Windows 7 context menu. It will now fully animate and move to the top of your list.  
  - We've now disabled middle-click on Windows 7 as it was causing small implosions in your Wunderlist.

## 3.13.0

  - Head to your Account Settings. Notice anything different? That's right, the navigation has changed from the topbar to the sidebar. 
  - Want quick and easy access to the changelog to see what exciting new features and fixes are in store? We've added a link in your Settings that takes you straight to this page. 
  - Want to see your emojis in full technicolor when you print out your to-dos? Ok! When you print your lists you'll now see all your emojis too.
  - We've made it easy for you to get back to business once you've finished searching for a to-do—the looking glass will transform itself into an X and a quick click on that will take you back to your lists.
  - We're giving our delete icons a little rest and only rolling them out when there's a job to-do—you'll now only see the delete icons when there's content in the Detail View. 
  - If you have friends with very long names then you'll have seen that something strange went on with the 'Not Sent' label when you wanted to share a list with them. We fixed that one.
  - Talking of long names, we've also fixed a bug where long user names were causing havoc with the toolbar on Firefox.
  - We fixed a little issue when pasting a to-do so it should now work seamlessly every time.
  - We fixed a couple of UI regression including bringing back the upload progress bar for Files.
  - We fixed a few avatar regressions to make sure your Wunderlist picture was looking as good as it should. 
  - Were new subtasks occasionally showing up in wrong to-dos when you synced? Yeah, that was a pesky bug. We've squished it now.
  - Last but not least, we fixed the Sharing List labels in Safari.

## 3.12.10

  - We've updated our translations.
  - We were getting a little postmodern on our settings dialog on IE11. We've fixed the glitch art now. 
  - Love Wunderlist so much that you want to tell all your friends about it on Facebook, Twitter or Google+? Why, thank you. We've made the sharing buttons look a little prettier just for you.
  - We fixed the flex layout for Firefox in the searchbar.
  - We hope you love Smart Due Dates as much as we do. You might have noticed though, that occasionally we were seeing dates in your to-dos when there weren't any. If you keep typing after we've recognized a date then we'll reset the date—so 'sunscreen' will no longer become 'screen' with a due date of Sunday.  

## 3.12.9

  - We've stopped patching task positions unnecessarily when you tick off a to-do. What does this mean for you? Just that your Wunderlist will be running more smoothly when you tick off recurring to-dos.

## 3.12.8

  - We've disabled the option to Duplicate your List while searching because, if we're honest, it didn't make much sense.
  - Were visual glitches causing you to wonder if you were in the Matrix? We've now fixed the glitches, and can assure you that you weren't. Would you mind just taking this blue pill?
  - We've updated our translations.
  - Click on the 3 dots within a list and you'll find our Delete Selected To-do option. You might have noticed that it was showing up when no to-dos were selected though. We've fixed that bug.
  - If you were having issues switching between Search and add a to-do you'll be pleased to hear that we've fixed that pesky little bug.
  - Talking of switching—if you like to switch between languages on your Wunderlist you may have noticed that the Title bar was expressing a little reluctance about changing to the new language. We've given it a talking to and it will now change as soon as you switch languages.
  - If you had an extra long title for your to-do something went a little funny when you tried to use @ to assign a to-do. We've fixed that little quirk.

## 3.12.7

  - If your Wunderlist was kicking up a fuss and freezing when you tried to delegate your to-dos to someone else you'll be happy to hear that this is now fixed. You can now delegate to your heart's content.
  - In Safari we fixed the position of the Close Note icon.
  - We also fixed a couple of UI issues for both Safari and Edge.
  - Prefer checking off your to-dos with a pen? We've fixed issues with printing in Firefox and Edge.
  - Wunderlist really, really liked files with long names so it stopped letting you delete them for a while. We've worked on its attachment issues and you can now delete all your files.

## 3.12.6

  - A simple update this time—we've fixed the issue where some popovers where getting stuck open.

## 3.12.5

  - Some of the formating of printing went a little funny with the last update. We've fixed it so it looks just as it should.

## 3.12.4

  - We updated some design elements to keep Wunderlist looking ever so stylish.
  - We fixed an issue that caused your to-do to break when you tried to delegate by typing @.
  - The click targets for expanding a Folder were fixed.
  - If you logged out there were occasionally issues with not being redirected properly. We took care of that bug.
  - You might have noticed that you had problems renaming or ungrouping your Folders in Safari. We've made the 3 dots clickable now.
  - Our search icon was getting a little too cosy with the hamburger icon. We've had to separate them.
  - The layout of Reminders was fixed.

## 3.12.3

  - Everyone loves emojis, right? We love them too so we were aghast to see that they weren't rendering correctly in the Detail View footer on a shared list. We fixed it pronto. 👏
  - We optimized how task counts are rendered.
  - A number of miscellaneous bugs were fixed.
  - There was an issue with dragging and dropping your to-dos between Lists in Smart Lists. We fixed that one.
  - We fixed realtime to-do updates not always rendering in Smart Lists.
  - You can now print your search results without anything weird happening.

## 3.12.1

  - We now support Welsh! Just change the language in your Account Settings.
  - We polished up some of the design.
  - If you're resizing your browser window you'll notice that the sidebar now auto collapses.
  - We fixed a bunch of Smart Due Date issues including adding more support for different date formats, and fixing bugs for Chinese and Japanese users.
  - If you had a long file name you might have noticed it colliding with the delete icon. They shall crash together no longer.
  - We fixed right-to-left section border and List emoji positions to make it look more sleek.

## 3.12.0

  - If you like to use a lot of tags but also like to keep your Wunderlist in a small browser window then this update will help you make more sense of your to-dos. Tags will now auto collapse when in a small browser window and you can see the detail of the tags when you hover over them.
  - When you change your password we'll now let you know straight away if we don't approve of your password.
  - We've increased the print font size so you can see your to-dos more easily.
  - If you change your language settings the date picker will now update too.
  - With autocomplete for tags or assigning, you'll now find it easier to navigate through the list with your keyboard.
  - We know that forgetting your password can be pretty frustrating and being faced with a blank screen when you hit 'Forgot Password' is doubly frustrating which is why we fixed that issue quick smart!
  - We fixed search results not always rendering their list headings when updates were received from the sync.
  - Your Completed Smart List should now be sorted by completion date.
  - Unwanted escaping when you duplicated a list was fixed.
  - Emojis on your to-dos might have been looking a bit funny but we've fixed it so that they'll no longer get cut off.
  - We've fixed keyboard navigation for right-to-left languages.
  - Imagine a country where the time format starts with minutes instead of hours. Can't? That's because it doesn't exist. We fixed our reminder picer so that it no longer shows this imaginary time format.
  - Our AM/PM dropdown inside the reminder calendar was a little too narrow for Hebrew, so we widened it.
  - The detail view icons were a little misplaced for right-to-left languages, we did a little rearranging.
  - We fixed the issue of not being able to view or download invoices.
  - If you have an emoji in your name then it might not have been showing up correctly in the Detail View... until now.
  - When there's a sync error you should see a small (yet dramatic) red lightning bolt. We fixed a bug that was making it less dramatic than we wanted.
  - We fixed subtasks not always rendering links in text.
