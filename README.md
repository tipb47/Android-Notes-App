# Notes App

Note App where users can create notes, edit notes, delete notes, and have them saved whenever the app is terminated.

## Functionality 

The following **required** functionality is completed:

* [ ] User can add a note with their own title and message.
* [ ] Note will be saved in a database, still available even when app is reset.
* [ ] User can edit note's title, message and also delete notes.

The following **extensions** are implemented:

* Room Library
* ListAdapter
* DiffUtil
* RecyclerView

* SafeArgs
* Fragment
* NavController

## Video Walkthrough

Here's a walkthrough of the program:

<img src='Walkthrough.gif' title='Video Walkthrough' width='50%' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Working with RecyclerView was challenging at first, but once we figured out how it interacted with the other things we were trying to implement, we were able to complete the project. The only thing we had trouble with was adding/editing a note as we couldn't figure out how to distinguish from a note that had just been created versus an old one, but after that everything came together nicely!

## License

    Copyright [2023] [Tip Browne, Ethan Deporter]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
