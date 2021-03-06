---
title: (dependencies within SeLite)
layout: default
---
{% include links %}
* TOC
{:toc}

Following shows direct dependencies between Firefox [Components](Components) that form SeLite. You don't need to read this if you use all SeLite components.

If you disable some components, do it at {{chromeUrl}} _about:addons_. Don't disable them in Selenium menu Options > Options... > Plugins.<!-- because that doesn't disable chrome overloads/overlays -->

<!-- Keep the following table sorted alphabetically.-->
<table class="table">
<thead>
<tr><td><strong>Providers</strong> &gt;<hr/>Dependents \/</td><td>&#160;</td><td>&#160;</td><td> <a href="Bootstrap">Bootstrap</a></td><td> Clipboard And Indent</td><td><a href="Commands">Commands</a></td><td>DB Objects</td><td><a href="ExtensionSequencer">ExtensionSequencer</a></td><td>Miscellaneous</td><td><a href="SelBlocksGlobal">SelBlocksGlobal</a></td><td><a href="Settings">Settings</a></td><td>TestCase<br>Debug<br>Context</td>
</tr>
</thead>
<tbody>
<tr><td colspan="12">VISUAL</td>
</tr>
<tr><td> Clipboard And Indent     </td><td> <a href='https://addons.mozilla.org/en-US/firefox/addon/selite-clipboard-and-indent/'>info</a> </td><td> <a href='https://addons.mozilla.org/en-US/firefox/addon/selite-clipboard-and-indent/versions'>download</a> </td><td>           </td><td>            </td><td>            </td><td>            </td><td> X                      </td><td>               </td><td>                  </td><td>     X (1)           </td><td>                               </td>
</tr>
<tr><td> Hands-on GUI       </td><td> <a href='https://addons.mozilla.org/en-US/firefox/addon/selite-hands-on-gui/'>info</a>         </td><td> <a href='https://addons.mozilla.org/en-US/firefox/addon/selite-hands-on-gui/versions/'>download</a>                           </td><td>           </td><td> X         </td><td>            </td><td>            </td><td> X                      </td><td> X             </td><td>                  </td><td>                 </td><td>                               </td>
</tr>
<tr><td> <a href="Preview">Preview</a> </td><td> <a href='https://addons.mozilla.org/en-US/firefox/addon/selite-preview/'>info</a> </td><td> <a href='https://addons.mozilla.org/en-US/firefox/addon/selite-preview/versions/'>download</a>                  </td><td>            </td><td>           </td><td>            </td><td>            </td><td> X                      </td><td> X             </td><td>         X         </td><td>                 </td><td>                                 </td>
</tr>
<tr><td> <a href='Settings'>Settings</a> </td><td> <a href='https://addons.mozilla.org/en-US/firefox/addon/selite-settings/'>info</a> </td><td> <a href='https://addons.mozilla.org/en-US/firefox/addon/selite-settings/versions/'>download</a>                      </td><td>           </td><td>            </td><td>            </td><td> X (5)     </td><td> X (5)                 </td><td> X             </td><td>                  </td><td>                 </td><td>                                 </td>
</tr>
<tr><td colspan="12">ACTIONS (COMMANDS)</td>
</tr>
<tr><td> <a href='Commands'>Commands</a> </td><td> <a href='https://addons.mozilla.org/en-US/firefox/addon/selite-commands/'>info</a> </td><td> <a href='https://addons.mozilla.org/en-US/firefox/addon/selite-commands/versions/'>download</a>                       </td><td>           </td><td>            </td><td>            </td><td>            </td><td> X                      </td><td> X             </td><td>                  </td><td> X               </td><td>                               </td>
</tr>
<tr><td> DB Objects </td><td> <a href='https://addons.mozilla.org/en-US/firefox/addon/selite-db-objects/'>info</a> </td><td> <a href='https://addons.mozilla.org/en-US/firefox/addon/selite-db-objects/versions/'>download</a>                       </td><td>            </td><td>           </td><td> X          </td><td>            </td><td> X                      </td><td> X             </td><td>                  </td><td>       X         </td><td>                               </td>
</tr>
<tr><td> <a href="SelBlocksGlobal">SelBlocksGlobal</a> </td><td> <a href='https://addons.mozilla.org/en-US/firefox/addon/selite-selblocks-global/'>info</a> </td><td> <a href='https://addons.mozilla.org/en-US/firefox/addon/SeLite-SelBlocks-Global/versions/'>download</a>                  </td><td>            </td><td>           </td><td>            </td><td>            </td><td> X                      </td><td> X             </td><td>                  </td><td>                 </td><td>     X                         </td>
</tr>
<tr><td colspan="12">API</td>
</tr>
<tr><td> <a href="ExtensionSequencer">ExtensionSequencer</a> </td><td> <a href='https://addons.mozilla.org/en-US/firefox/addon/selite-extension-sequencer/'>info</a> </td><td> <a href='https://addons.mozilla.org/en-US/firefox/addon/selite-extension-sequencer/versions/'>download</a>               </td><td>            </td><td>           </td><td>            </td><td>            </td><td>                        </td><td>               </td><td>                  </td><td>                 </td><td>                               </td>
</tr>
<tr><td> Miscellaneous </td><td> <a href='https://addons.mozilla.org/en-US/firefox/addon/selite-miscellaneous/'>info</a> </td><td> <a href='https://addons.mozilla.org/en-US/firefox/addon/selite-miscellaneous/versions/'>download</a>                    </td><td>            </td><td>           </td><td>            </td><td>            </td><td> X (3)                 </td><td>               </td><td>                  </td><td>                 </td><td>                                 </td>
</tr>
<tr><td> TestCase Debug Context </td><td> <a href='https://addons.mozilla.org/en-US/firefox/addon/selite-testcase-debug-conte/'>info</a> </td><td> <a href='https://addons.mozilla.org/en-US/firefox/addon/SeLite-TestCase-Debug-Conte/versions/'>download</a>          </td><td>           </td><td>            </td><td>            </td><td>            </td><td> X                      </td><td>               </td><td>                  </td><td>                 </td><td>                                 </td>
</tr>
<tr><td colspan="12">PRODUCTIVITY</td>
</tr>
<tr><td> <a href="AutoCheck">AutoCheck</a> </td><td> <a href='https://addons.mozilla.org/en-US/firefox/addon/selite-auto-check/'>info</a> </td><td> <a href='https://addons.mozilla.org/en-US/firefox/addon/selite-auto-check/versions/'>download</a>                        </td><td>  X        </td><td>            </td><td>            </td><td>            </td><td> X                      </td><td> X             </td><td>                  </td><td> X               </td><td> X                             </td>
</tr>
<tr><td> <a href="Bootstrap">Bootstrap</a> </td><td> <a href='https://addons.mozilla.org/en-US/firefox/addon/selite-bootstrap/'>info</a> </td><td> <a href='https://addons.mozilla.org/en-US/firefox/addon/SeLite-Bootstrap/versions/'>download</a>                      </td><td>           </td><td>            </td><td>            </td><td>            </td><td> X                      </td><td> X             </td><td>  X               </td><td> X               </td><td>                               </td>
</tr>
<tr><td> <a href="ExitConfirmationChecker">ExitConfirmationChecker</a> </td><td> <a href='https://addons.mozilla.org/en-US/firefox/addon/selite-exit-confirmation-check/'>info</a> </td><td> <a href='https://addons.mozilla.org/en-US/firefox/addon/selite-exit-confirmation-check/versions'>download</a>          </td><td>            </td><td>           </td><td> X (2)     </td><td>            </td><td> X                      </td><td> X             </td><td>                  </td><td> X               </td><td>     X                         </td>
</tr>
<tr><td> Run All Favorites (4) </td><td> <a href='https://addons.mozilla.org/en-US/firefox/addon/selite-run-all-favorites/'>info</a> </td><td> <a href='https://addons.mozilla.org/en-US/firefox/addon/selite-run-all-favorites/versions/'>download</a>           </td><td>            </td><td>           </td><td>            </td><td>            </td><td> X                      </td><td>               </td><td>                  </td><td>                 </td><td>                                 </td>
</tr>
</tbody></table>

Notes

1. Clipboard And Indent can work without [Settings](Settings). Then the default indentation step is 4 spaces.
2. [Exit Confirmation Checker] can be used either with or without [Commands](Commands). If used together, then it applies to Selenese defined in [Commands](Commands).
3. Miscellaneous and [Settings](Settings) can be used without Selenium IDE (as Javascript code modules). Then they don't require [Extension Sequencer]. However, if you want to use them within Selenium IDE, you need [Extension Sequencer], too.
4. Run All Favorites also requires [Favorites (Selenium IDE)](https://addons.mozilla.org/en-US/firefox/addon/favorites-selenium-ide/).
5. [Settings](Settings) can be used without DB Objects, but then you can't reload [script][script db]/vanilla[vanilla db]/[app DB] through GUI (as per {{navReloadingDatabases}}).
