new Vue({
  el: '#app',
  data: () => ({
    items: [
      {
        action: 'move_to_inbox',
        title: 'Inbox'
      },
      {
        action: 'send',
        title: 'Sent'
      },
      {
        action: 'delete',
        title: 'Trash'
      },
      {
        action: 'report',
        title: 'Spam'
      },
      { divider: true },
      { header: 'Labels' },
      {
        action: 'label',
        title: 'Family'
      },
      {
        action: 'label',
        title: 'Friends'
      },
      {
        action: 'label',
        title: 'Work'
      }
    ]
  })
})