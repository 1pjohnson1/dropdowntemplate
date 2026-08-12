<style>
.box {
    display: inline-block;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 15px;
    background-color: #217097;
	display: flex;
    border-radius: 10px;
}

.box select {
    background-color: #D4D8Da;
}
</style>

<center>
@lab.title
</center>

<br>

<div class=box>
    <b>Select Lab:</b>&nbsp;&nbsp;&nbsp;&nbsp;
    @lab.DropDownList(module)[Intro,Environment,Scripts,Lab0,Lab1,Lab2,Lab3,Lab4,Lab5,Lab6,Lab7,Lab8,Lab9,Lab10,Lab11,Lab12,Lab13,Lab14,Lab15,Outro]

</div>
---


:::module(module=Intro)

## Scenario

[Provide a brief scenario describing the purpose of the lab and the business or technical context.]

<div class="mission-box">

<h2>🎯 YOUR MISSION</h2>

<ol>
<li>[Mission Task 1]</li>
<li>[Mission Task 2]</li>
<li>[Mission Task 3]</li>
<li>[Mission Task 4]</li>
<li>[Mission Task 5]</li>
<li>[Mission Task 6]</li>
</ol>

### Exam Objectives

This activity is designed to test your understanding of and ability to apply concepts from the following CompTIA objective(s):

- 1.1

### Lab Environment

Describe the systems, tools, and resources available to complete this activity.

Example:

- **Endpoint:** WIN-PC1
- **Server:** SRV-OT1
- **SIEM:** Wazuh
- **PLC:** OpenPLC
- **HMI:** Node-RED
- **Utilities:** Wireshark, Sysmon

</div>

:::


:::module(module=Scripts)

# Scripts

## Enable Hints

@lab.DropDownList(ShowHints)[Yes,No]

:::hint-toggle

<span class="label slider-heading">Hints Enabled</span>

<span class="label">No</span>

<label class="switch">
    <input type="checkbox"
           class="checkMode"
           title="Toggle Hints"
           checked>
    <span class="slider round"></span>
</label>

<span class="label">Yes</span>



## Sample Hint

<details>
  <summary><b>💡 Hint</b> - Click here if you need assistance.</summary>

  <br>

  <code>su - student1</code>

</details>

## Sample Investigation Tip

<details>
  <summary><b>🔍 Investigation Tip</b></summary>

  Review the authentication logs for any failed login attempts before proceeding.

</details>

##AI
<iframe
  src="https://ai-server:3001/embed/chat?embedId=bf6e4b29-b4e4-451a-aefb-4c90bfb6f578"
  width="100%"
  height="650"
  frameborder="0"
  allow="microphone">
	<script>
    data-embed-id="bf6e4b29-b4e4-451a-aefb-4c90bfb6f578"
    data-base-api-url="https://ai-server:3001/api/embed"
    src="https://ai-server:3001/embed/anythingllm-chat-widget.min.js"> 
    data-assistant-name="${EMBED_ASSISTANT_NAME}"
    data-greeting="${EMBED_GREETING}"
    data-default-messages="${EMBED_SUGGESTIONS}"
    data-button-color="${EMBED_BUTTON_COLOR}"
    data-assistant-bg-color="#f0f4f8"
    data-user-bg-color="${EMBED_BUTTON_COLOR}"
    data-chat-icon="${EMBED_ICON}"
    data-position="bottom-right"
    data-window-height="550px"
    data-window-width="380px"
    data-text-size="14"
    data-open-on-load="on"
	</script>
</iframe>

:::

:::module(module=Outro)

## Grade Lab

>You have completed the following tasks:

- [Task 1]
- [Task 2]
- [Task 3]

That concludes this lab. To submit this lab for grading:

1. Select check boxes to mark all tasks complete.
2. Submit responses to all questions and activities.

>[!alert] Select:
>
>- **Submit** in the bottom-right corner, then **Yes** to submit your lab for grading. You may relaunch the lab and attempt it again at any time.
>- **Save & Exit** in the top-right corner to save your progress and return later. Your progress will be retained for seven (7) days.

:::
