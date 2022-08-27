# OC-SSDT-Battery-Patch-HP-Pavilion-14-AL132TX

* Put the `SSDT-BAT.aml` inside `EFI>OC>ACPI` folder

* And add these rename patches below to your `Root>ACPI>Patch` inside of your `config.plist`

* Use `ProperTree` and save the `config.plist`

```swift

<key>Patch</key>
		<array>
			<dict>
				<key>Comment</key>
				<string>ADJT to XDJT</string>
				<key>Count</key>
				<integer>1</integer>
				<key>Enabled</key>
				<true/>
				<key>Find</key>
				<data>QURKVAg=</data>
				<key>Limit</key>
				<integer>0</integer>
				<key>Mask</key>
				<data></data>
				<key>OemTableId</key>
				<data></data>
				<key>Replace</key>
				<data>WERKVAg=</data>
				<key>ReplaceMask</key>
				<data></data>
				<key>Skip</key>
				<integer>0</integer>
				<key>TableLength</key>
				<integer>0</integer>
				<key>TableSignature</key>
				<data></data>
			</dict>
			<dict>
				<key>Comment</key>
				<string>CLRI to XLRI</string>
				<key>Count</key>
				<integer>1</integer>
				<key>Enabled</key>
				<true/>
				<key>Find</key>
				<data>Q0xSSQg=</data>
				<key>Limit</key>
				<integer>0</integer>
				<key>Mask</key>
				<data></data>
				<key>OemTableId</key>
				<data></data>
				<key>Replace</key>
				<data>WExSSQg=</data>
				<key>ReplaceMask</key>
				<data></data>
				<key>Skip</key>
				<integer>0</integer>
				<key>TableLength</key>
				<integer>0</integer>
				<key>TableSignature</key>
				<data></data>
			</dict>
			<dict>
				<key>Comment</key>
				<string>_BST to XBST</string>
				<key>Count</key>
				<integer>1</integer>
				<key>Enabled</key>
				<true/>
				<key>Find</key>
				<data>X0JTVAA=</data>
				<key>Limit</key>
				<integer>0</integer>
				<key>Mask</key>
				<data></data>
				<key>OemTableId</key>
				<data></data>
				<key>Replace</key>
				<data>WEJTVAA=</data>
				<key>ReplaceMask</key>
				<data></data>
				<key>Skip</key>
				<integer>0</integer>
				<key>TableLength</key>
				<integer>0</integer>
				<key>TableSignature</key>
				<data></data>
			</dict>
			<dict>
				<key>Comment</key>
				<string>UPBI to XPBI</string>
				<key>Count</key>
				<integer>1</integer>
				<key>Enabled</key>
				<true/>
				<key>Find</key>
				<data>VVBCSQA=</data>
				<key>Limit</key>
				<integer>0</integer>
				<key>Mask</key>
				<data></data>
				<key>OemTableId</key>
				<data></data>
				<key>Replace</key>
				<data>WFBCSQA=</data>
				<key>ReplaceMask</key>
				<data></data>
				<key>Skip</key>
				<integer>0</integer>
				<key>TableLength</key>
				<integer>0</integer>
				<key>TableSignature</key>
				<data></data>
			</dict>
			<dict>
				<key>Comment</key>
				<string>UPBS to XPBS</string>
				<key>Count</key>
				<integer>1</integer>
				<key>Enabled</key>
				<true/>
				<key>Find</key>
				<data>VVBCUwA=</data>
				<key>Limit</key>
				<integer>0</integer>
				<key>Mask</key>
				<data></data>
				<key>OemTableId</key>
				<data></data>
				<key>Replace</key>
				<data>WFBCUwA=</data>
				<key>ReplaceMask</key>
				<data></data>
				<key>Skip</key>
				<integer>0</integer>
				<key>TableLength</key>
				<integer>0</integer>
				<key>TableSignature</key>
				<data></data>
			</dict>
			<dict>
				<key>Comment</key>
				<string>SMRD to XMRD</string>
				<key>Count</key>
				<integer>1</integer>
				<key>Enabled</key>
				<true/>
				<key>Find</key>
				<data>U01SRAQ=</data>
				<key>Limit</key>
				<integer>0</integer>
				<key>Mask</key>
				<data></data>
				<key>OemTableId</key>
				<data></data>
				<key>Replace</key>
				<data>WE1SRAQ=</data>
				<key>ReplaceMask</key>
				<data></data>
				<key>Skip</key>
				<integer>0</integer>
				<key>TableLength</key>
				<integer>0</integer>
				<key>TableSignature</key>
				<data></data>
			</dict>
			<dict>
				<key>Comment</key>
				<string>SMWR to XMWR</string>
				<key>Count</key>
				<integer>1</integer>
				<key>Enabled</key>
				<true/>
				<key>Find</key>
				<data>U01XUgQ=</data>
				<key>Limit</key>
				<integer>0</integer>
				<key>Mask</key>
				<data></data>
				<key>OemTableId</key>
				<data></data>
				<key>Replace</key>
				<data>WE1XUgQ=</data>
				<key>ReplaceMask</key>
				<data></data>
				<key>Skip</key>
				<integer>0</integer>
				<key>TableLength</key>
				<integer>0</integer>
				<key>TableSignature</key>
				<data></data>
			</dict>
			<dict>
				<key>Comment</key>
				<string>Rename _STA to XSTA(BAT0)</string>
				<key>Count</key>
				<integer>1</integer>
				<key>Enabled</key>
				<false/>
				<key>Find</key>
				<data>X1NUQQCg</data>
				<key>Limit</key>
				<integer>0</integer>
				<key>Mask</key>
				<data></data>
				<key>OemTableId</key>
				<data></data>
				<key>Replace</key>
				<data>WFNUQQCg</data>
				<key>ReplaceMask</key>
				<data></data>
				<key>Skip</key>
				<integer>2</integer>
				<key>TableLength</key>
				<integer>0</integer>
				<key>TableSignature</key>
				<data>RFNEVA==</data>
			</dict>
		</array>

```
